# Kite-Fighter-<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Kite Fighter</title>
<meta name="theme-color" content="#0a1b4d">
<meta name="author" content="Nefyra IT">

<style>
:root{--glass:rgba(10,16,40,.58);--line:rgba(255,255,255,.16);--ink:#eef3ff;--red1:#ff4d3d;--red2:#c9102a;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
html,body{height:100%;margin:0}
body{background:#0a1b4d;color:var(--ink);font-family:"Segoe UI",system-ui,-apple-system,Roboto,"Helvetica Neue",Arial,sans-serif;overflow:hidden;touch-action:none;user-select:none;-webkit-user-select:none}
#wrap{position:relative;height:100%;max-width:520px;margin:0 auto;box-shadow:0 0 60px rgba(0,0,0,.5)}
canvas{display:block;width:100%;height:100%}
#hud{position:absolute;top:10px;left:12px;right:12px;display:flex;justify-content:space-between;gap:8px;pointer-events:none}
#hud span{background:var(--glass);-webkit-backdrop-filter:blur(10px);backdrop-filter:blur(10px);border:1px solid var(--line);border-radius:999px;padding:6px 14px;font-size:15px;font-weight:700}
#lv{color:#ff6b5e}
#ov,#acc{position:absolute;inset:0;display:flex;align-items:center;justify-content:center;padding:16px;overflow-y:auto;box-sizing:border-box}
#ov{background:linear-gradient(180deg,rgba(5,10,30,.3),rgba(5,10,30,.6))}
#acc{background:rgba(4,8,24,.72);z-index:5}
.card{margin:auto;background:var(--glass);-webkit-backdrop-filter:blur(18px);backdrop-filter:blur(18px);border:1px solid var(--line);border-radius:26px;padding:24px 22px;text-align:center;max-width:330px;width:100%;box-shadow:0 20px 60px rgba(0,0,0,.45),inset 0 1px 0 rgba(255,255,255,.12)}
.card img{width:min(240px,62vw,24vh);height:auto;border-radius:28px;display:block;margin:-4px auto 8px;box-shadow:0 0 0 2px rgba(255,255,255,.14),0 12px 40px rgba(255,70,50,.4)}
.card h1,.card h2{font-family:"Arial Black",Impact,system-ui,sans-serif;font-style:italic;font-weight:900;margin:0 0 10px}
.card h1{display:none;font-size:28px}
.card h2{font-size:24px}
.card p{margin:6px 0 16px;line-height:1.55;font-size:14.5px;opacity:.92;overflow-wrap:anywhere}
button{background:linear-gradient(135deg,var(--red1),var(--red2));color:#fff;border:0;border-radius:14px;padding:13px 34px;font:inherit;font-weight:800;font-size:18px;cursor:pointer;box-shadow:0 8px 22px rgba(220,30,40,.45);transition:transform .12s}
button:active{transform:scale(.96)}
button:disabled{opacity:.6}

