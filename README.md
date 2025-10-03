# managerialecon.github.io
Games for Managerial Economics, UCLA Anderson's School of Management 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Econ Games — UCLA Anderson</title>
  <style>
    :root {
      --bg: #0f172a;
      --text: #e5e7eb;
      --muted: #9ca3af;
      --accent: #22c55e;
      --card: #1f2937;
      --border: #334155;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0; font-family: system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial;
      background: radial-gradient(1000px 600px at 10% -10%, #1e293b 0%, var(--bg) 60%);
      color: var(--text);
      min-height: 100vh; display: grid; place-items: start center; padding: 40px 16px 64px;
    }
    .container { width: min(1100px, 100%); }
    header { margin-bottom: 14px; }
    h1 { margin: 0; font-size: clamp(28px, 2.8vw, 40px); letter-spacing: .3px; }
    .subtitle { color: var(--muted); margin-top: 6px; }
    .grid { display: grid; grid-template-columns: repeat(2, 1fr); gap: 16px; margin-top: 18px; }
    @media (max-width: 820px) { .grid { grid-template-columns: 1fr; } }
    .card { background: linear-gradient(180deg, rgba(255,255,255,.03), rgba(255,255,255,.01));
            border: 1px solid var(--border); border-radius: 16px;
            box-shadow: 0 10px 30px rgba(0,0,0,.25); overflow: hidden;
            display:flex; flex-direction:column; }
    .card .hd { padding: 16px 18px; border-bottom: 1px solid var(--border);
                font-weight: 800; display:flex; align-items:center; justify-content:space-between; }
    .card .bd { padding: 16px 18px; color: var(--muted); }
    a.btn { display:inline-flex; align-items:center; gap:10px; padding: 12px 14px; border-radius: 12px;
            border: 1px solid var(--border); background:#0b1220; color:var(--text); font-weight:700;
            text-decoration:none; transition: transform .03s ease, box-shadow .2s ease; }
    a.btn:hover { box-shadow: 0 6px 20px rgba(0,0,0,.35); }
    a.btn:active { transform: translateY(1px); }
    footer { margin-top: 20px; color: var(--muted); font-size: 14px; }
    .muted { color: var(--muted); }
    .pill { display:inline-flex; align-items:center; gap:8px; border:1px solid var(--border);
            padding:6px 10px; border-radius:999px; background:#0b1220; color:var(--text); font-size:12px; }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>Econ Games</h1>
      <div class="subtitle">Interactive mini‑apps for Managerial Economics at UCLA Anderson's School of Management</div>
    </header>
    <section class="grid">
      <article class="card">
        <div class="hd">
          <span>First‑Price Auction</span>
          <span class="pill">game1.htm</span>
        </div>
        <div class="bd">
          Bid against a simulated opponent in a first‑price sealed‑bid auction. Track wins and earnings.
          <div style="margin-top:12px; display:flex; gap:10px; flex-wrap:wrap;">
            <a class="btn" href="game1.htm">Open Game</a>
          </div>
        </div>
      </article>
      <article class="card">
        <div class="hd">
          <span>Pricing Experiment (Linear Demand)</span>
          <span class="pill">game2.htm</span>
        </div>
        <div class="bd">
          Use an interactive price slider under demand P = 400 − 0.25·Q with fixed cost $50k.
          <div style="margin-top:12px; display:flex; gap:10px; flex-wrap:wrap;">
            <a class="btn" href="game2.htm">Open Game</a>
          </div>
        </div>
      </article>
      <article class="card">
        <div class="hd">
          <span>Coming Soon</span>
          <span class="pill">more games</span>
        </div>
        <div class="bd">
          More games will be added here in the future.
        </div>
      </article>
    </section>
    <footer>
      <div>Questions or ideas for new games? Email your instructor and include a short description.</div>
    </footer>
  </div>
</body>
</html>
