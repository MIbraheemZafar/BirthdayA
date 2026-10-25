<!DOCTYPE html>
<html lang="en"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Happy Birthday 🎂</title>
<style>
:root{--bg:#fff4f7;--fg:#4a1d3a;--card:#fff;--ac:#e8407a;--ac2:#f5a623;--sh:rgba(120,30,80,.25);box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media(prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#1d1020;--fg:#ffe8f1;--card:#2b1830;--sh:rgba(0,0,0,.5)}}
:root[data-theme="dark"]{--bg:#1d1020;--fg:#ffe8f1;--card:#2b1830;--sh:rgba(0,0,0,.5)}
*{box-sizing:border-box}
html,body{height:100%;margin:0;overflow:hidden}
body{background:var(--bg);color:var(--fg);font-family:Georgia,serif;text-align:center}
.stage{position:absolute;inset:0;padding:calc(124px + env(safe-area-inset-top,0px)) 16px 16px;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:clamp(8px,2vh,18px);opacity:0;visibility:hidden;transition:opacity .7s,visibility .7s}
.stage.on{opacity:1;visibility:visible}
h1{position:fixed;top:calc(48px + env(safe-area-inset-top,0px));left:0;right:0;z-index:4;padding:0 56px;font-size:clamp(1.5rem,7vw,2.6rem);margin:0;background:linear-gradient(90deg,var(--ac),var(--ac2),var(--ac));background-size:200%;-webkit-background-clip:text;background-clip:text;color:transparent;animation:flow 4s linear infinite}
@keyframes flow{to{background-position:200%}}
.typed{font-size:clamp(1rem,4vw,1.3rem);min-height:1.6em;font-style:italic}
.typed::after{content:'|';animation:blink 1s infinite}
@keyframes blink{50%{opacity:0}}
.hint{opacity:.7;font-size:.9rem;margin:0}
.bal{position:fixed;bottom:-80px;font-size:2.2rem;animation:up linear forwards;pointer-events:none;z-index:5}
@keyframes up{to{transform:translateY(-120vh) rotate(20deg)}}
.conf{position:fixed;top:-20px;width:9px;height:14px;animation:fall linear forwards;pointer-events:none;z-index:5}
@keyframes fall{to{transform:translateY(110vh) rotate(720deg)}}
/* card */
.card{--w:min(86vw,340px,calc((100dvh - 300px)*.78));width:var(--w);height:calc(var(--w)*1.3);position:relative;perspective:1200px;cursor:pointer;-webkit-tap-highlight-color:transparent}
.inside,.cover{position:absolute;inset:0;border-radius:14px;box-shadow:0 10px 30px var(--sh)}
.inside{background:var(--card);display:flex;align-items:center;justify-content:center;padding:6%;font-size:clamp(.95rem,4.2vw,1.2rem);line-height:1.7;overflow:hidden}
.cover{background:linear-gradient(135deg,var(--ac),#ff8fb1 60%,var(--ac2));transform-origin:left center;transition:transform .9s,opacity .4s .5s;color:#fff;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:8px;font-size:clamp(1.2rem,6vw,1.7rem)}
.cover .big{font-size:clamp(3rem,16vw,4.5rem)}
.card.open .cover{transform:rotateY(-110deg);opacity:0;pointer-events:none}
button{font:inherit;background:var(--ac);color:#fff;border:0;border-radius:99px;padding:10px 22px;cursor:pointer}
.nav{display:flex;gap:14px;align-items:center}
.nav button:disabled{opacity:.4}
/* jokes */
.joke{width:min(92vw,460px);min-height:min(46dvh,320px);background:var(--card);border-left:10px solid var(--ac);border-radius:12px;box-shadow:0 12px 30px var(--sh);padding:22px 18px;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:12px;font-size:clamp(1.05rem,4.6vw,1.35rem);line-height:1.6}
.joke .e{font-size:clamp(2.6rem,14vw,4rem);animation:pop .6s}
