<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Susurro — vive el ASMR</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,300;9..144,500;9..144,600;9..144,700&family=Inter:wght@400;500;600;700&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root{
    --bg: #14121a;
    --bg-soft: #1b1822;
    --panel: #211d29;
    --panel-border: #322b3a;
    --plum: #2a1f2e;
    --rose: #e8a0bc;
    --rose-dim: #b97e93;
    --gold: #c9a876;
    --cream: #f4ede4;
    --cream-dim: #b7aebd;
    --mic-green: #8fb89a;
  }

  *{ margin:0; padding:0; box-sizing:border-box; }

  html{ scroll-behavior:smooth; }

  body{
    background: var(--bg);
    color: var(--cream);
    font-family: 'Inter', sans-serif;
    min-height:100vh;
    overflow-x:hidden;
  }

  ::selection{ background: var(--rose); color:#1b1822; }

  h1,h2,h3,.display{
    font-family: 'Fraunces', serif;
    font-weight:600;
    letter-spacing:-0.01em;
  }

  .mono{
    font-family:'JetBrains Mono', monospace;
    letter-spacing:0.04em;
    text-transform:uppercase;
  }

  a{ color:inherit; text-decoration:none; }
  button{ font-family:inherit; cursor:pointer; border:none; background:none; color:inherit; }
  img{ max-width:100%; display:block; }

  @media (prefers-reduced-motion: reduce){
    *{ animation-duration:0.001ms !important; animation-iteration-count:1 !important; transition-duration:0.001ms !important; scroll-behavior:auto !important; }
  }

  /* ===== background ambient waveform ===== */
  .ambient{
    position:fixed; inset:0; z-index:0; pointer-events:none;
    background:
      radial-gradient(ellipse 60% 40% at 20% 0%, rgba(232,160,188,0.10), transparent 60%),
      radial-gradient(ellipse 50% 35% at 90% 10%, rgba(201,168,118,0.08), transparent 60%),
      radial-gradient(ellipse 60% 50% at 50% 100%, rgba(143,184,154,0.06), transparent 60%);
  }

  /* ===== top nav ===== */
  header{
    position:sticky; top:0; z-index:50;
    display:flex; align-items:center; justify-content:space-between;
    padding:14px 24px;
    background:rgba(20,18,26,0.82);
    backdrop-filter: blur(14px);
    border-bottom:1px solid var(--panel-border);
  }

  @media (min-width: 901px) {
    header { padding:18px 36px; }
  }

  .logo{ display:flex; align-items:center; gap:10px; }
  .logo .mark{
    width:30px; height:30px;
    display:flex; align-items:center; justify-content:center;
    gap:2px;
  }
  .logo .mark span{
    width:3px; background:var(--rose); border-radius:2px;
    animation: bar 1.6s ease-in-out infinite;
  }
  .logo .mark span:nth-child(1){ height:10px; animation-delay:0s; }
  .logo .mark span:nth-child(2){ height:22px; animation-delay:0.2s; }
  .logo .mark span:nth-child(3){ height:14px; animation-delay:0.4s; }
  .logo .mark span:nth-child(4){ height:26px; animation-delay:0.6s; }
  .logo .mark span:nth-child(5){ height:8px; animation-delay:0.8s; }
  @keyframes bar{
    0%,100%{ transform:scaleY(0.4); }
    50%{ transform:scaleY(1); }
  }
  .logo-text{ font-family:'Fraunces',serif; font-size:1.35rem; font-weight:600; letter-spacing:-0.02em; }
  .logo-text .dot{ color: var(--rose); }

  nav.main-nav{ display:flex; gap:24px; }
  @media (min-width: 1100px) {
    nav.main-nav{ gap:34px; }
  }
  nav.main-nav a{
    font-size:0.92rem; color:var(--cream-dim); font-weight:500;
    position:relative; padding-bottom:4px;
    transition:color .2s;
  }
  nav.main-nav a:hover, nav.main-nav a.active{ color: var(--cream); }
  nav.main-nav a.active::after{
    content:''; position:absolute; left:0; right:0; bottom:-6px; height:2px;
    background: var(--rose); border-radius:2px;
  }

  .nav-right{ display:flex; align-items:center; gap:12px; }
  @media (min-width: 901px) {
    .nav-right{ gap:16px; }
  }

  .search-box{
    display:flex; align-items:center; gap:8px;
    background:var(--panel); border:1px solid var(--panel-border);
    border-radius:999px; padding:9px 16px; width:180px;
    color:var(--cream-dim); font-size:0.85rem;
    transition: width 0.2s ease;
  }
  @media (min-width: 1100px) {
    .search-box { width: 230px; }
  }
  .search-box svg{ width:15px; height:15px; opacity:0.7; flex-shrink:0; }
  .search-box input{
    background:none; border:none; color:var(--cream); font-family:inherit; font-size:0.85rem; width:100%; outline:none;
  }
  .search-box input::placeholder{ color:var(--cream-dim); }

  .icon-btn{
    width:38px; height:38px; border-radius:50%;
    display:flex; align-items:center; justify-content:center;
    background:var(--panel); border:1px solid var(--panel-border);
    position:relative; transition: border-color .2s, transform .2s;
  }
  .icon-btn:hover{ border-color: var(--rose-dim); transform:translateY(-1px); }
  .icon-btn svg{ width:17px; height:17px; }
  .badge-dot{
    position:absolute; top:-2px; right:-2px;
    width:9px; height:9px; border-radius:50%;
    background:var(--rose); border:2px solid var(--bg);
  }

  .btn{
    padding:10px 20px; border-radius:999px; font-size:0.88rem; font-weight:600;
    transition: transform .2s, box-shadow .2s, background .2s;
    white-space: nowrap;
  }
  .btn-primary{
    background: linear-gradient(135deg, var(--rose), var(--rose-dim));
    color:#1b1320;
  }
  .btn-primary:hover{ transform:translateY(-1px); box-shadow:0 8px 22px rgba(232,160,188,0.25); }
  .btn-ghost{
    background:transparent; border:1px solid var(--panel-border); color:var(--cream);
  }
  .btn-ghost:hover{ border-color: var(--cream-dim); }

  .avatar{
    width:38px; height:38px; border-radius:50%;
    background: linear-gradient(135deg, var(--gold), var(--rose));
    display:flex; align-items:center; justify-content:center;
    font-family:'Fraunces',serif; font-weight:600; font-size:0.95rem; color:#1b1320;
    flex-shrink:0;
  }

  /* ===== layout ===== */
  .app{
    position:relative; z-index:1;
    display:grid;
    grid-template-columns: 240px minmax(0,1fr) 300px;
    gap:0;
    max-width:1480px; margin:0 auto;
  }

  /* ----- sidebar ----- */
  .sidebar{
    padding:28px 16px 40px 24px;
    position:sticky; top:73px; align-self:start;
    height:calc(100vh - 73px); overflow-y:auto;
    scrollbar-width:thin;
  }
  .sidebar::-webkit-scrollbar{ width:6px; }
  .sidebar::-webkit-scrollbar-thumb{ background:var(--panel-border); border-radius:4px; }

  .side-section{ margin-bottom:30px; }
  .side-label{
    font-size:0.68rem; color:var(--cream-dim); margin-bottom:12px; opacity:0.7;
  }
  .side-link{
    display:flex; align-items:center; gap:12px;
    padding:10px 12px; border-radius:10px;
    color:var(--cream-dim); font-size:0.9rem; font-weight:500;
    margin-bottom:2px; transition:background .15s, color .15s;
  }
  .side-link svg{ width:18px; height:18px; flex-shrink:0; }
  .side-link:hover{ background:var(--panel); color:var(--cream); }
  .side-link.active{ background:var(--panel); color:var(--rose); }

  .creator-mini{
    display:flex; align-items:center; gap:10px;
    padding:8px 12px; border-radius:10px; margin-bottom:2px;
    transition:background .15s;
  }
  .creator-mini:hover{ background:var(--panel); }
  .creator-mini .avatar{ width:30px; height:30px; font-size:0.75rem; }
  .creator-mini .ava-status{
    width:30px; height:30px; border-radius:50%; position:relative; flex-shrink:0;
  }
  .creator-mini .ava-status::after{
    content:''; position:absolute; bottom:-1px; right:-1px;
    width:9px; height:9px; border-radius:50%;
    background:var(--mic-green); border:2px solid var(--bg);
  }
  .creator-mini-info{ min-width:0; }
  .creator-mini-info .name{ font-size:0.83rem; font-weight:600; white-space:nowrap; overflow:hidden; text-overflow:ellipsis; }
  .creator-mini-info .tag{ font-size:0.72rem; color:var(--cream-dim); }

  /* ----- feed center ----- */
  .feed{
    padding:28px 24px 80px;
    border-left:1px solid var(--panel-border);
    border-right:1px solid var(--panel-border);
  }

  /* hero / live ribbon */
  .hero{
    border-radius:22px;
    padding:38px 38px;
    margin-bottom:30px;
    position:relative;
    overflow:hidden;
    background:
      radial-gradient(ellipse 80% 100% at 100% 0%, rgba(232,160,188,0.22), transparent 60%),
      radial-gradient(ellipse 70% 80% at 0% 100%, rgba(143,184,154,0.14), transparent 60%),
      linear-gradient(135deg, #251f2c, #1c1822);
    border:1px solid var(--panel-border);
  }
  .hero-eyebrow{
    display:inline-flex; align-items:center; gap:8px;
    font-size:0.7rem; color:var(--rose); margin-bottom:16px;
  }
  .hero-eyebrow .live-pulse{
    width:7px; height:7px; border-radius:50%; background:#ff5d7a;
    box-shadow:0 0 0 0 rgba(255,93,122,0.6);
    animation:pulse 1.8s infinite;
  }
  @keyframes pulse{
    0%{ box-shadow:0 0 0 0 rgba(255,93,122,0.55); }
    70%{ box-shadow:0 0 0 9px rgba(255,93,122,0); }
    100%{ box-shadow:0 0 0 0 rgba(255,93,122,0); }
  }
  .hero h1{
    font-size:2.6rem; line-height:1.08; max-width:560px; margin-bottom:14px;
  }
  .hero h1 em{ color: var(--rose); font-style:normal; }
  .hero p{
    color:var(--cream-dim); max-width:460px; font-size:0.98rem; line-height:1.55; margin-bottom:26px;
  }
  .hero-actions{ display:flex; flex-wrap: wrap; gap:12px; }

  .hero-waveform{
    position:absolute; right:38px; bottom:0; top:0;
    width:200px; display:flex; align-items:flex-end; justify-content:center; gap:4px;
    opacity:0.9;
  }
  @media (min-width: 1200px) {
    .hero-waveform { width: 260px; }
  }
  .hero-waveform span{
    width:5px; border-radius:3px;
    background: linear-gradient(180deg, var(--rose), var(--gold));
    animation: wave 2.4s ease-in-out infinite;
  }

  /* feed tabs */
  .feed-tabs{
    display:flex; gap:8px; margin-bottom:22px; overflow-x:auto; padding-bottom:6px;
    scrollbar-width: none;
  }
  .feed-tabs::-webkit-scrollbar { display: none; }
  .feed-tab{
    padding:9px 18px; border-radius:999px; font-size:0.85rem; font-weight:500;
    background:var(--panel); border:1px solid var(--panel-border); color:var(--cream-dim);
    white-space:nowrap; transition:all .2s;
  }
  .feed-tab:hover{ color:var(--cream); }
  .feed-tab.active{ background:var(--rose); color:#1b1320; border-color:var(--rose); font-weight:600; }

  /* upload bar */
  .upload-bar{
    display:flex; align-items:center; gap:14px;
    background:var(--panel); border:1px solid var(--panel-border);
    border-radius:18px; padding:16px 18px; margin-bottom:26px;
    cursor: pointer;
  }
  .upload-bar .avatar{ width:42px; height:42px; }
  .upload-fake-input{
    flex:1; background:var(--bg-soft); border:1px solid var(--panel-border);
    border-radius:999px; padding:11px 18px; color:var(--cream-dim); font-size:0.88rem;
    transition:border-color .2s;
    white-space: nowrap; overflow: hidden; text-overflow: ellipsis;
  }
  .upload-fake-input:hover{ border-color:var(--rose-dim); }
  .upload-bar-actions{ display:flex; gap:8px; }
  .upload-bar-actions .icon-btn{ width:38px; height:38px; }

  /* live strip */
  .live-strip{
    display:flex; gap:16px; overflow-x:auto; margin-bottom:32px; padding-bottom:6px;
    scrollbar-width: none;
  }
  .live-strip::-webkit-scrollbar { display: none; }
  .live-card{
    flex:0 0 100px; cursor:pointer;
  }
  .live-ring{
    width:76px; height:76px; border-radius:50%; padding:3px;
    background: conic-gradient(from 0deg, var(--rose), var(--gold), var(--mic-green), var(--rose));
    margin:0 auto 8px;
  }
  .live-ring .avatar{
    width:100%; height:100%; border:3px solid var(--bg); font-size:1.4rem;
  }
  .live-card .lname{ text-align:center; font-size:0.78rem; font-weight:600; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
  .live-card .ltag{ text-align:center; font-size:0.7rem; color:var(--rose); display:flex; align-items:center; justify-content:center; gap:4px; }
  .live-card .ltag .dot{ width:5px;height:5px;border-radius:50%; background:#ff5d7a; }

  /* post card */
  .post{
    background:var(--panel); border:1px solid var(--panel-border);
    border-radius:20px; margin-bottom:22px; overflow:hidden;
  }
  .post-head{
    display:flex; align-items:center; gap:12px; padding:18px 20px 14px;
  }
  .post-head .meta{ flex:1; min-width:0; }
  .post-head .name-row{ display:flex; align-items:center; gap:6px; font-size:0.92rem; font-weight:600; }
  .verified{ width:14px; height:14px; color:var(--rose); flex-shrink:0; }
  .post-head .sub{ font-size:0.78rem; color:var(--cream-dim); white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
  .post-menu{ width:32px; height:32px; border-radius:50%; display:flex; align-items:center; justify-content:center; color:var(--cream-dim); }
  .post-menu:hover{ background:var(--bg-soft); }

  .post-text{
    padding:0 20px 14px; font-size:0.92rem; line-height:1.6; color:var(--cream);
  }
  .post-text .triggers{ color:var(--rose); font-weight:500; }

  .post-media{
    position:relative; width:100%; aspect-ratio:16/9;
    overflow:hidden;
  }
  .post-media img{ width:100%; height:100%; object-fit:cover; }
  .play-overlay{
    position:absolute; inset:0; display:flex; align-items:center; justify-content:center;
    background:linear-gradient(180deg, rgba(20,18,26,0) 50%, rgba(20,18,26,0.55) 100%);
    transition:background .2s;
  }
  .post-media:hover .play-overlay{ background:rgba(20,18,26,0.25); }
  .play-btn{
    width:62px; height:62px; border-radius:50%;
    background:rgba(244,237,228,0.92); display:flex; align-items:center; justify-content:center;
    transition:transform .2s;
  }
  .post-media:hover .play-btn{ transform:scale(1.08); }
  .play-btn svg{ width:22px; height:22px; color:#1b1320; margin-left:3px; }

  .media-duration{
    position:absolute; bottom:12px; right:12px;
    background:rgba(20,18,26,0.75); padding:4px 9px; border-radius:6px;
    font-size:0.72rem; font-family:'JetBrains Mono',monospace;
  }
  .media-tag{
    position:absolute; top:12px; left:12px;
    background:rgba(20,18,26,0.75); backdrop-filter:blur(4px);
    padding:5px 11px; border-radius:999px; font-size:0.68rem; color:var(--rose); display:flex; align-items:center; gap:5px;
  }

  .audio-card{
    margin:0 20px 14px; padding:16px 18px;
    background:var(--bg-soft); border:1px solid var(--panel-border); border-radius:14px;
    display:flex; align-items:center; gap:14px;
  }
  .audio-play{
    width:44px; height:44px; border-radius:50%; flex-shrink:0;
    background:var(--rose); display:flex; align-items:center; justify-content:center;
  }
  .audio-play svg{ width:16px; height:16px; color:#1b1320; margin-left:2px; }
  .audio-wave{ flex:1; display:flex; align-items:center; gap:2px; height:32px; overflow: hidden; }
  .audio-wave span{ width:3px; border-radius:2px; background:var(--panel-border); flex-shrink:0; }
  .audio-wave span.played{ background:var(--rose); }
  .audio-time{ font-size:0.72rem; color:var(--cream-dim); font-family:'JetBrains Mono',monospace; flex-shrink:0; }

  .post-stats{
    display:flex; align-items:center; gap:4px;
    padding:8px 20px; font-size:0.76rem; color:var(--cream-dim);
  }
  .post-stats .stack-icons{ display:flex; }
  .post-stats .stack-icons span{
    width:18px; height:18px; border-radius:50%; background:var(--rose); border:2px solid var(--panel);
    margin-left:-6px; display:inline-flex; align-items:center; justify-content:center; font-size:9px;
  }
  .post-stats .stack-icons span:first-child{ margin-left:0; }

  .post-actions{
    display:flex; align-items:center; justify-content:space-between; gap:12px;
    padding:10px 14px 16px; border-top:1px solid var(--panel-border); margin-top:8px;
    overflow-x: auto; scrollbar-width: none;
  }
  .post-actions::-webkit-scrollbar { display: none; }
  .action-group{ display:flex; gap:2px; }
  .action-btn{
    display:flex; align-items:center; gap:7px;
    padding:9px 12px; border-radius:10px; font-size:0.82rem; font-weight:500; color:var(--cream-dim);
    transition:background .15s, color .15s; white-space: nowrap;
  }
  .action-btn:hover{ background:var(--bg-soft); color:var(--cream); }
  .action-btn svg{ width:18px; height:18px; flex-shrink: 0; }
  .action-btn.liked{ color:var(--rose); }
  .action-btn.liked svg{ fill:var(--rose); stroke:var(--rose); }
  .action-btn.saved svg{ fill:var(--gold); stroke:var(--gold); }
  .action-btn.saved{ color:var(--gold); }

  .tip-btn{
    display:flex; align-items:center; gap:7px;
    padding:9px 14px; border-radius:10px; font-size:0.82rem; font-weight:600;
    background:linear-gradient(135deg, rgba(201,168,118,0.18), rgba(201,168,118,0.08));
    border:1px solid rgba(201,168,118,0.35); color:var(--gold); white-space: nowrap;
  }
  .tip-btn:hover{ background:rgba(201,168,118,0.25); }
  .tip-btn svg{ width:16px; height:16px; flex-shrink: 0; }

  /* ----- right rail ----- */
  .rail{
    padding:28px 24px 28px 16px;
    position:sticky; top:73px; align-self:start;
    height:calc(100vh - 73px); overflow-y:auto;
    scrollbar-width:thin;
  }
  .rail::-webkit-scrollbar{ width:6px; }
  .rail::-webkit-scrollbar-thumb{ background:var(--panel-border); border-radius:4px; }

  .rail-card{
    background:var(--panel); border:1px solid var(--panel-border); border-radius:18px;
    padding:20px; margin-bottom:22px;
  }
  .rail-title{ font-size:0.95rem; font-weight:600; margin-bottom:16px; display:flex; align-items:center; justify-content:space-between; }
  .rail-title .see-all{ font-size:0.74rem; color:var(--rose-dim); font-weight:500; }

  .stat-self{
    display:flex; align-items:center; gap:12px; margin-bottom:18px;
  }
  .stat-self .info .name{ font-weight:600; font-size:0.92rem; }
  .stat-self .info .handle{ font-size:0.76rem; color:var(--cream-dim); }
  .stat-grid{
    display:grid; grid-template-columns:1fr 1fr 1fr; gap:8px; text-align:center;
  }
  .stat-grid .stat-box{
    background:var(--bg-soft); border-radius:10px; padding:10px 4px;
  }
  .stat-grid .num{ font-family:'Fraunces',serif; font-weight:600; font-size:1.05rem; color:var(--rose); }
  .stat-grid .lbl{ font-size:0.62rem; color:var(--cream-dim); margin-top:2px; }

  .suggest-row{
    display:flex; align-items:center; gap:10px; margin-bottom:14px;
  }
  .suggest-row:last-child{ margin-bottom:0; }
  .suggest-row .info{ flex:1; min-width:0; }
  .suggest-row .info .name{ font-size:0.85rem; font-weight:600; white-space:nowrap; overflow:hidden; text-overflow:ellipsis; }
  .suggest-row .info .desc{ font-size:0.72rem; color:var(--cream-dim); white-space:nowrap; overflow:hidden; text-overflow:ellipsis; }
  .follow-pill{
    font-size:0.72rem; font-weight:600; padding:7px 14px; border-radius:999px;
    border:1px solid var(--rose-dim); color:var(--rose);
    flex-shrink:0; transition:all .2s;
  }
  .follow-pill:hover{ background:var(--rose); color:#1b1320; }
  .follow-pill.following{ background:var(--panel-border); border-color:var(--panel-border); color:var(--cream-dim); }

  .trend-row{
    display:flex; align-items:baseline; justify-content:space-between; padding:8px 0;
    border-bottom:1px solid var(--panel-border); font-size:0.84rem; gap: 8px;
  }
  .trend-row:last-child{ border-bottom:none; }
  .trend-row .tag{ color:var(--cream); font-weight:500; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
  .trend-row .count{ color:var(--cream-dim); font-size:0.74rem; flex-shrink: 0; }

  footer.rail-foot{
    font-size:0.7rem; color:var(--cream-dim); line-height:1.8; padding:0 4px;
  }
  footer.rail-foot a{ color:var(--cream-dim); }
  footer.rail-foot a:hover{ color:var(--rose); }

  @keyframes wave{
    0%,100%{ height:18%; }
    50%{ height:90%; }
  }

  /* ===== floating upload button (mobile) ===== */
  .fab-upload{
    position:fixed; bottom:26px; right:26px; z-index:60;
    width:58px; height:58px; border-radius:50%;
    background:linear-gradient(135deg, var(--rose), var(--gold));
    display:none; align-items:center; justify-content:center;
    box-shadow:0 10px 28px rgba(232,160,188,0.35);
  }
  .fab-upload svg{ width:24px; height:24px; color:#1b1320; }

  /* ===== modal: upload ===== */
  .modal-backdrop{
    position:fixed; inset:0; background:rgba(10,9,13,0.7); backdrop-filter:blur(6px);
    display:none; align-items:center; justify-content:center; z-index:100; padding:16px;
  }
  .modal-backdrop.open{ display:flex; }
  .modal{
    background:var(--bg-soft); border:1px solid var(--panel-border); border-radius:22px;
    width:100%; max-width:560px; max-height:85vh; display: flex; flex-direction: column; overflow: hidden;
  }
  .modal-header{
    display:flex; align-items:center; justify-content:space-between;
    padding:20px 24px; border-bottom:1px solid var(--panel-border);
  }
  .modal-header h3{ font-size:1.2rem; }
  .modal-close{ width:32px; height:32px; border-radius:50%; display:flex; align-items:center; justify-content:center; color:var(--cream-dim); }
  .modal-close:hover{ background:var(--panel); color:var(--cream); }
  
  .modal-body{ padding:24px; overflow-y: auto; flex: 1; }

  .upload-tabs{ display:flex; gap:8px; margin-bottom:22px; }
  .upload-tab{
    flex:1; padding:11px 6px; border-radius:12px; font-size:0.84rem; font-weight:600;
    background:var(--panel); border:1px solid var(--panel-border); color:var(--cream-dim);
    display:flex; align-items:center; justify-content:center; gap:6px;
  }
  .upload-tab svg{ width:16px; height:16px; flex-shrink: 0; }
  .upload-tab.active{ background:var(--rose); border-color:var(--rose); color:#1b1320; }

  .dropzone{
    border:1.5px dashed var(--panel-border); border-radius:16px;
    padding:32px 16px; text-align:center; margin-bottom:18px;
    transition:border-color .2s, background .2s;
  }
  .dropzone:hover{ border-color:var(--rose-dim); background:rgba(232,160,188,0.04); }
  .dropzone svg{ width:34px; height:34px; color:var(--cream-dim); margin:0 auto 12px; }
  .dropzone .dz-title{ font-weight:600; font-size:0.92rem; margin-bottom:4px; }
  .dropzone .dz-sub{ font-size:0.76rem; color:var(--cream-dim); }

  .field{ margin-bottom:16px; }
  .field label{ display:block; font-size:0.78rem; color:var(--cream-dim); margin-bottom:7px; font-weight:500; }
  .field textarea, .field input[type=text]{
    width:100%; background:var(--panel); border:1px solid var(--panel-border); border-radius:12px;
    padding:12px 14px; color:var(--cream); font-family:inherit; font-size:0.88rem; resize:none; outline:none;
    transition:border-color .2s;
  }
  .field textarea:focus, .field input[type=text]:focus{ border-color:var(--rose-dim); }

  .chip-row{ display:flex; flex-wrap:wrap; gap:8px; }
  .chip{
    padding:7px 14px; border-radius:999px; font-size:0.78rem; cursor: pointer;
    background:var(--panel); border:1px solid var(--panel-border); color:var(--cream-dim);
  }
  .chip.sel{ background:var(--rose); border-color:var(--rose); color:#1b1320; font-weight:600; }

  .modal-footer{
    display:flex; align-items:center; justify-content:space-between; gap: 16px;
    padding:18px 24px; border-top:1px solid var(--panel-border); background: var(--bg-soft);
  }
  .visibility-toggle{ display:flex; align-items:center; gap:8px; font-size:0.8rem; color:var(--cream-dim); cursor: pointer; }

  /* ===== RESPONSIVE MEDIA QUERIES ===== */
  @media (max-width: 1200px){
    .app{ grid-template-columns: 80px minmax(0,1fr) 280px; }
    .sidebar .side-link span.lbl, .sidebar .side-label, .creator-mini-info{ display:none; }
    .sidebar .side-link, .creator-mini{ justify-content:center; padding: 12px; }
    .sidebar{ padding: 28px 10px; }
  }

  @media (max-width: 990px){
    .app{ grid-template-columns: 80px minmax(0,1fr); }
    .rail{ display:none; }
  }

  @media (max-width: 768px){
    .app{ grid-template-columns: 1fr; }
    .sidebar{ display:none; }
    nav.main-nav{ display:none; }
    .search-box{ display:none; }
    .fab-upload{ display:flex; }
    header{ padding:14px 18px; }
    .feed{ border:none; padding:18px 14px 90px; }
    .hero{ padding:28px 22px; }
    .hero h1{ font-size:1.9rem; }
    .hero-waveform{ display:none; }
    .upload-bar { display: none; }
  }
</style>
</head>
<body>

<div class="ambient"></div>

<header>
  <div class="logo">
    <div class="mark"><span></span><span></span><span></span><span></span><span></span></div>
    <div class="logo-text">Susurro<span class="dot">.</span></div>
  </div>

  <nav class="main-nav">
    <a href="#" class="active">Para ti</a>
    <a href="#">Siguiendo</a>
    <a href="#">En vivo</a>
    <a href="#">Explorar triggers</a>
  </nav>

  <div class="nav-right">
    <div class="search-box">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="11" cy="11" r="7"/><line x1="21" y1="21" x2="16.65" y2="16.65"/></svg>
      <input type="text" placeholder="Buscar creadores, triggers...">
    </div>
    <button class="icon-btn" title="Mensajes">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg>
      <span class="badge-dot"></span>
    </button>
    <button class="icon-btn" title="Notificaciones">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 8a6 6 0 0 0-12 0c0 7-3 9-3 9h18s-3-2-3-9"/><path d="M13.73 21a2 2 0 0 1-3.46 0"/></svg>
      <span class="badge-dot"></span>
    </button>
    <button class="btn btn-primary" onclick="openUpload()">+ Subir</button>
    <div class="avatar">MJ</div>
  </div>
</header>

<div class="app">

  <aside class="sidebar">
    <div class="side-section">
      <a href="#" class="side-link active">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M3 12l9-9 9 9"/><path d="M5 10v10h14V10"/></svg>
        <span class="lbl">Inicio</span>
      </a>
      <a href="#" class="side-link">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="9"/><path d="M12 7v5l3 3"/></svg>
        <span class="lbl">En vivo ahora</span>
      </a>
      <a href="#" class="side-link">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="3" width="7" height="7" rx="1"/><rect x="14" y="3" width="7" height="7" rx="1"/><rect x="3" y="14" width="7" height="7" rx="1"/><rect x="14" y="14" width="7" height="7" rx="1"/></svg>
        <span class="lbl">Explorar</span>
      </a>
      <a href="#" class="side-link">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"/></svg>
        <span class="lbl">Guardados</span>
      </a>
      <a href="#" class="side-link">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 2v20M2 12h20"/></svg>
        <span class="lbl">Mis suscripciones</span>
      </a>
    </div>

    <div class="side-section">
      <div class="side-label mono">Siguiendo en vivo</div>
      <div class="creator-mini">
        <div class="ava-status"><div class="avatar" style="width:100%;height:100%;font-size:0.75rem;">LR</div></div>
        <div class="creator-mini-info"><div class="name">Luna Rivers</div><div class="tag">Susurros + mic</div></div>
      </div>
      <div class="creator-mini">
        <div class="ava-status"><div class="avatar" style="width:100%;height:100%;font-size:0.75rem;">KT</div></div>
        <div class="creator-mini-info"><div class="name">Kenji Tanabe</div><div class="tag">Roleplay relax</div></div>
      </div>
      <div class="creator-mini">
        <div class="avatar" style="width:30px;height:30px;font-size:0.75rem;">SO</div>
        <div class="creator-mini-info"><div class="name">Sofía Oaks</div><div class="tag">Tapping · offline</div></div>
      </div>
    </div>

    <div class="side-section">
      <div class="side-label mono">Tu canal</div>
      <a href="#" class="side-link">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22 12h-4l-3 9L9 3l-3 9H2"/></svg>
        <span class="lbl">Panel de creador</span>
      </a>
      <a href="#" class="side-link">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="3"/><path d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 1 1-2.83 2.83l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 0 1-4 0v-.09A1.65 1.65 0 0 0 9 19.4a1.65 1.65 0 0 0-1.82.33l-.06.06a2 2 0 1 1-2.83-2.83l.06-.06a1.65 1.65 0 0 0 .33-1.82 1.65 1.65 0 0 0-1.51-1H3a2 2 0 0 1 0-4h.09A1.65 1.65 0 0 0 4.6 9a1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 1 1 2.83-2.83l.06.06a1.65 1.65 0 0 0 1.82.33H9a1.65 1.65 0 0 0 1-1.51V3a2 2 0 0 1 4 0v.09a1.65 1.65 0 0 0 1 1.51 1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 1 1 2.83 2.83l-.06.06a1.65 1.65 0 0 0-.33 1.82V9a1.65 1.65 0 0 0 1.51 1H21a2 2 0 0 1 0 4h-.09a1.65 1.65 0 0 0-1.51 1z"/></svg>
        <span class="lbl">Configuración</span>
      </a>
    </div>
  </aside>

  <main class="feed">

    <section class="hero">
      <div class="hero-eyebrow mono"><span class="live-pulse"></span> 12 creadores en vivo ahora mismo</div>
      <h1>Cierra los ojos.<br>Escucha <em>algo nuevo</em>.</h1>
      <p>El feed con vida de las personas que sigues: directos, susurros recién subidos y los triggers que más se están escuchando hoy.</p>
      <div class="hero-actions">
        <button class="btn btn-primary" onclick="openUpload()">Subir mi primer susurro</button>
        <button class="btn btn-ghost">Ver en vivo</button>
      </div>
      <div class="hero-waveform" aria-hidden="true">
        <span style="animation-delay:0.0s"></span><span style="animation-delay:0.1s"></span><span style="animation-delay:0.2s"></span>
        <span style="animation-delay:0.3s"></span><span style="animation-delay:0.15s"></span><span style="animation-delay:0.25s"></span>
        <span style="animation-delay:0.05s"></span><span style="animation-delay:0.35s"></span><span style="animation-delay:0.2s"></span>
        <span style="animation-delay:0.4s"></span><span style="animation-delay:0.1s"></span><span style="animation-delay:0.3s"></span>
        <span style="animation-delay:0.0s"></span><span style="animation-delay:0.2s"></span><span style="animation-delay:0.15s"></span>
      </div>
    </section>

    <div class="live-strip">
      <div class="live-card">
        <div class="live-ring"><div class="avatar">LR</div></div>
        <div class="lname">Luna Rivers</div>
        <div class="ltag"><span class="dot"></span> en vivo</div>
      </div>
      <div class="live-card">
        <div class="live-ring"><div class="avatar">KT</div></div>
        <div class="lname">Kenji T.</div>
        <div class="ltag"><span class="dot"></span> en vivo</div>
      </div>
      <div class="live-card">
        <div class="live-ring"><div class="avatar">NM</div></div>
        <div class="lname">Nadia M.</div>
        <div class="ltag"><span class="dot"></span> en vivo</div>
      </div>
      <div class="live-card">
        <div class="live-ring" style="background:var(--panel-border);"><div class="avatar">EP</div></div>
        <div class="lname">Elia Park</div>
        <div class="ltag" style="color:var(--cream-dim);">hace 2h</div>
      </div>
      <div class="live-card">
        <div class="live-ring" style="background:var(--panel-border);"><div class="avatar">RS</div></div>
        <div class="lname">Rio Santos</div>
        <div class="ltag" style="color:var(--cream-dim);">hace 5h</div>
      </div>
    </div>

    <div class="upload-bar" onclick="openUpload()">
      <div class="avatar">MJ</div>
      <div class="upload-fake-input">¿Qué susurro vas a compartir hoy?</div>
      <div class="upload-bar-actions">
        <button class="icon-btn" title="Subir audio">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9 18V5l12-2v13"/><circle cx="6" cy="18" r="3"/><circle cx="18" cy="16" r="3"/></svg>
        </button>
        <button class="icon-btn" title="Subir video">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polygon points="23 7 16 12 23 17 23 7"/><rect x="1" y="5" width="15" height="14" rx="2"/></svg>
        </button>
      </div>
    </div>

    <div class="feed-tabs">
      <button class="feed-tab active">Para ti</button>
      <button class="feed-tab">Siguiendo</button>
      <button class="feed-tab">Susurros (audio)</button>
      <button class="feed-tab">Video ASMR</button>
      <button class="feed-tab">Tapping</button>
      <button class="feed-tab">Roleplay</button>
      <button class="feed-tab">Sin palabras</button>
    </div>

    <article class="post">
      <div class="post-head">
        <div class="avatar">LR</div>
        <div class="meta">
          <div class="name-row">Luna Rivers
            <svg class="verified" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2l2.4 2.2 3.2-.5 1 3.1 3.1 1-.5 3.2L23 12l-2.2 2.4.5 3.2-3.1 1-1 3.1-3.2-.5L12 23l-2.4-2.2-3.2.5-1-3.1-3.1-1 .5-3.2L1 12l2.2-2.4-.5-3.2 3.1-1 1-3.1 3.2.5z"/></svg>
          </div>
          <div class="sub">@lunarivers_asmr · hace 38 min</div>
        </div>
        <button class="post-menu">
          <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="5" cy="12" r="1"/><circle cx="12" cy="12" r="1"/><circle cx="19" cy="12" r="1"/></svg>
        </button>
      </div>
      <div class="post-text">Sesión nocturna de hoy: tapping en madera + susurros en español 🌙 <span class="triggers">#tapping #susurros #relax</span></div>
      <div class="post-media">
        <img src="https://images.unsplash.com/photo-1518457607834-6e8d80c183c5?q=80&w=1200&auto=format&fit=crop" alt="Sesión ASMR nocturna">
        <div class="media-tag">🎥 Video ASMR</div>
        <div class="media-duration">24:18</div>
        <div class="play-overlay">
          <div class="play-btn"><svg viewBox="0 0 24 24" fill="currentColor"><polygon points="5 3 19 12 5 21 5 3"/></svg></div>
        </div>
      </div>
      <div class="post-stats">
        <div class="stack-icons"><span>♥</span><span>♥</span><span>♥</span></div>
        <span>2,847 personas relajándose con esto</span>
      </div>
      <div class="post-actions">
        <div class="action-group">
          <button class="action-btn liked">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"/></svg>
            2.8K
          </button>
          <button class="action-btn">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"/></svg>
            312
          </button>
          <button class="action-btn">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 12v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-8M16 6l-4-4-4 4M12 2v13"/></svg>
            Compartir
          </button>
          <button class="action-btn saved">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M19 21l-7-5-7 5V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2z"/></svg>
          </button>
        </div>
        <button class="tip-btn">
          <svg viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5A2.5 2.5 0 1 1 12 6a2.5 2.5 0 0 1 0 5.5z" opacity="0"/><circle cx="12" cy="9" r="2.4"/></svg>
          Enviar propina
        </button>
      </div>
    </article>

    <article class="post">
      <div class="post-head">
        <div class="avatar">KT</div>
        <div class="meta">
          <div class="name-row">Kenji Tanabe
            <svg class="verified" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2l2.4 2.2 3.2-.5 1 3.1 3.1 1-.5 3.2L23 12l-2.2 2.4.5 3.2-3.1 1-1 3.1-3.2-.5L12 23l-2.4-2.2-3.2.5-1-3.1-3.1-1 .5-3.2L1 12l2.2-2.4-.5-3.2 3.1-1 1-3.1 3.2.5z"/></svg>
          </div>
          <div class="sub">@kenji.whispers · hace 2 h</div>
        </div>
        <button class="post-menu">
          <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="5" cy="12" r="1"/><circle cx="12" cy="12" r="1"/><circle cx="19" cy="12" r="1"/></svg>
        </button>
      </div>
      <div class="post-text">Episodio 14 del podcast susurrado: "Lluvia en la ventana del tren" — solo audio, ideal para dormir. <span class="triggers">#audio #lluvia #dormir</span></div>
      <div class="audio-card">
        <button class="audio-play"><svg viewBox="0 0 24 24" fill="currentColor"><polygon points="5 3 19 12 5 21 5 3"/></svg></button>
        <div class="audio-wave" id="wave2"></div>
        <div class="audio-time">06:42</div>
      </div>
      <div class="post-stats">
        <div class="stack-icons"><span>♥</span><span>♥</span><span>♥</span></div>
        <span>1,204 escuchas hoy</span>
      </div>
      <div class="post-actions">
        <div class="action-group">
          <button class="action-btn">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"/></svg>
            1.2K
          </button>
          <button class="action-btn">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"/></svg>
            89
          </button>
          <button class="action-btn">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 12v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-8M16 6l-4-4-4 4M12 2v13"/></svg>
            Compartir
          </button>
          <button class="action-btn">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M19 21l-7-5-7 5V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2z"/></svg>
          </button>
        </div>
        <button class="tip-btn">
          <svg viewBox="0 0 24 24" fill="currentColor"><circle cx="12" cy="9" r="2.4"/></svg>
          Enviar propina
        </button>
      </div>
    </article>

    <article class="post">
      <div class="post-head">
        <div class="avatar">NM</div>
        <div class="meta">
          <div class="name-row">Nadia Moss</div>
          <div class="sub">@nadia.softly · hace 4 h</div>
        </div>
        <button class="post-menu">
          <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="5" cy="12" r="1"/><circle cx="12" cy="12" r="1"/><circle cx="19" cy="12" r="1"/></svg>
        </button>
      </div>
      <div class="post-text">Roleplay: "tu primera visita al spa de susurros" — con sonidos de agua y mic brushing al final ✨</div>
      <div class="post-media">
        <img src="https://images.unsplash.com/photo-1540555700478-4be289fbecef?q=80&w=1200&auto=format&fit=crop" alt="Roleplay ASMR spa">
        <div class="media-tag">🎥 Video ASMR</div>
        <div class="media-duration">18:05</div>
        <div class="play-overlay">
          <div class="play-btn"><svg viewBox="0 0 24 24" fill="currentColor"><polygon points="5 3 19 12 5 21 5 3"/></svg></div>
        </div>
      </div>
      <div class="post-stats">
        <div class="stack-icons"><span>♥</span><span>♥</span><span>♥</span></div>
        <span>956 personas relajándose con esto</span>
      </div>
      <div class="post-actions">
        <div class="action-group">
          <button class="action-btn">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"/></svg>
            956
          </button>
          <button class="action-btn">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"/></svg>
            41
          </button>
          <button class="action-btn">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 12v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-8M16 6l-4-4-4 4M12 2v13"/></svg>
            Compartir
          </button>
          <button class="action-btn">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M19 21l-7-5-7 5V5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2z"/></svg>
          </button>
        </div>
        <button class="tip-btn">
          <svg viewBox="0 0 24 24" fill="currentColor"><circle cx="12" cy="9" r="2.4"/></svg>
          Enviar propina
        </button>
      </div>
    </article>

  </main>

  <aside class="rail">

    <div class="rail-card">
      <div class="stat-self">
        <div class="avatar" style="width:48px;height:48px;font-size:1.1rem;">MJ</div>
        <div class="info">
          <div class="name">Mariana J.</div>
          <div class="handle">@mariana.creates</div>
        </div>
      </div>
      <div class="stat-grid">
        <div class="stat-box"><div class="num">312</div><div class="lbl mono">Susurros</div></div>
        <div class="stat-box"><div class="num">8.4K</div><div class="lbl mono">Seguidores</div></div>
        <div class="stat-box"><div class="num">96</div><div class="lbl mono">Suscriptores</div></div>
      </div>
    </div>

    <div class="rail-card">
      <div class="rail-title">Creadores sugeridos <span class="see-all">ver todos</span></div>
      <div class="suggest-row">
        <div class="avatar">EP</div>
        <div class="info"><div class="name">Elia Park</div><div class="desc">Mic brushing · 14K seguidores</div></div>
        <button class="follow-pill">Seguir</button>
      </div>
      <div class="suggest-row">
        <div class="avatar">RS</div>
        <div class="info"><div class="name">Rio Santos</div><div class="desc">Roleplay · 9.1K seguidores</div></div>
        <button class="follow-pill following">Siguiendo</button>
      </div>
      <div class="suggest-row">
        <div class="avatar">AV</div>
        <div class="info"><div class="name">Ana Vergara</div><div class="desc">Sin palabras · 22K seguidores</div></div>
        <button class="follow-pill">Seguir</button>
      </div>
      <div class="suggest-row">
        <div class="avatar">DC</div>
        <div class="info"><div class="name">Diego Cano</div><div class="desc">Tapping · 5.3K seguidores</div></div>
        <button class="follow-pill">Seguir</button>
      </div>
    </div>

    <div class="rail-card">
      <div class="rail-title">Triggers en tendencia</div>
      <div class="trend-row"><span class="tag">#susurrosensueño</span><span class="count">3.2K posts</span></div>
      <div class="trend-row"><span class="tag">#tappingmadera</span><span class="count">2.7K posts</span></div>
      <div class="trend-row"><span class="tag">#roleplayrelax</span><span class="count">1.9K posts</span></div>
      <div class="trend-row"><span class="tag">#lluviaparadormir</span><span class="count">1.4K posts</span></div>
      <div class="trend-row"><span class="tag">#micbrushing</span><span class="count">980 posts</span></div>
    </div>

    <footer class="rail-foot">
      <div>Sobre · Privacidad · Términos · Comunidad · Ayuda</div>
      <div style="margin-top:6px;">© 2026 Susurro. Hecho para quienes escuchan con cuidado.</div>
    </footer>
  </aside>

</div>

<button class="fab-upload" onclick="openUpload()" title="Subir">
  <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4"><line x1="12" y1="5" x2="12" y2="19"/><line x1="5" y1="12" x2="19" y2="12"/></svg>
</button>

<div class="modal-backdrop" id="uploadModal">
  <div class="modal">
    <div class="modal-header">
      <h3>Subir un nuevo susurro</h3>
      <button class="modal-close" onclick="closeUpload()">
        <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="18" y1="6" x2="6" y2="18"/><line x1="6" y1="6" x2="18" y2="18"/></svg>
      </button>
    </div>
    <div class="modal-body">
      <div class="upload-tabs">
        <button class="upload-tab active" onclick="setUploadTab(this,'audio')">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9 18V5l12-2v13"/><circle cx="6" cy="18" r="3"/><circle cx="18" cy="16" r="3"/></svg>
          Audio
        </button>
        <button class="upload-tab" onclick="setUploadTab(this,'video')">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polygon points="23 7 16 12 23 17 23 7"/><rect x="1" y="5" width="15" height="14" rx="2"/></svg>
          Video
        </button>
        <button class="upload-tab" onclick="setUploadTab(this,'live')">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="9"/><path d="M12 7v5l3 3"/></svg>
          Ir en vivo
        </button>
      </div>

      <div class="dropzone">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="17 8 12 3 7 8"/><line x1="12" y1="3" x2="12" y2="15"/></svg>
        <div class="dz-title">Arrastra tu archivo aquí</div>
        <div class="dz-sub">o haz clic para seleccionar — MP3, WAV, MP4, MOV (máx. 2 GB)</div>
      </div>

      <div class="field">
        <label>Título</label>
        <input type="text" placeholder="Ej: Susurros para dormir profundo">
      </div>
      <div class="field">
        <label>Descripción</label>
        <textarea rows="3" placeholder="Cuéntale a tus oyentes qué van a escuchar..."></textarea>
      </div>
      <div class="field">
        <label>Triggers</label>
        <div class="chip-row">
          <span class="chip sel">Susurros</span>
          <span class="chip">Tapping</span>
          <span class="chip">Roleplay</span>
          <span class="chip">Mic brushing</span>
          <span class="chip">Lluvia</span>
          <span class="chip">Sin palabras</span>
          <span class="chip">+ Añadir</span>
        </div>
      </div>
    </div>
    <div class="modal-footer">
      <label class="visibility-toggle">
        <input type="checkbox" id="subOnly"> Solo para suscriptores
      </label>
      <button class="btn btn-primary" onclick="closeUpload()">Publicar susurro</button>
    </div>
  </div>
</div>

<script>
  // --- build audio waveform bars ---
  function buildWave(id, playedRatio){
    const el = document.getElementById(id);
    if(!el) return;
    const bars = 46;
    for(let i=0;i<bars;i++){
      const h = 20 + Math.random()*80;
      const span = document.createElement('span');
      span.style.height = h + '%';
      if(i/bars < playedRatio) span.classList.add('played');
      el.appendChild(span);
    }
  }
  buildWave('wave2', 0.35);

  // --- feed tab switching ---
  document.querySelectorAll('.feed-tab').forEach(tab=>{
    tab.addEventListener('click', ()=>{
      document.querySelectorAll('.feed-tab').forEach(t=>t.classList.remove('active'));
      tab.classList.add('active');
    });
  });

  // --- like / save toggles ---
  document.querySelectorAll('.action-btn').forEach(btn=>{
    const svg = btn.querySelector('svg');
    if(!svg) return;
    const isHeart = svg.innerHTML.includes('20.84 4.61');
    const isBookmark = svg.innerHTML.includes('19 21l-7-5');
    if(isHeart){
      btn.addEventListener('click', ()=>{
        btn.classList.toggle('liked');
      });
    }
    if(isBookmark){
      btn.addEventListener('click', ()=> btn.classList.toggle('saved'));
    }
  });

  // --- follow pill toggles ---
  document.querySelectorAll('.follow-pill').forEach(btn=>{
    btn.addEventListener('click', ()=>{
      btn.classList.toggle('following');
      btn.textContent = btn.classList.contains('following') ? 'Siguiendo' : 'Seguir';
    });
  });

  // --- chip select (triggers) ---
  document.querySelectorAll('.chip').forEach(chip=>{
    chip.addEventListener('click', ()=> chip.classList.toggle('sel'));
  });

  // --- upload tabs inside modal ---
  function setUploadTab(el, type){
    document.querySelectorAll('.upload-tab').forEach(t=>t.classList.remove('active'));
    el.classList.add('active');
  }

  // --- modal open/close ---
  function openUpload(){ document.getElementById('uploadModal').classList.add('open'); }
  function closeUpload(){ document.getElementById('uploadModal').classList.remove('open'); }
  document.getElementById('uploadModal').addEventListener('click', (e)=>{
    if(e.target.id === 'uploadModal') closeUpload();
  });
  document.addEventListener('keydown', (e)=>{
    if(e.key === 'Escape') closeUpload();
  });
</script>

</body>
</html>
