<div align="center" style="
  margin: 0 auto 18px;
  max-width: 880px;
  border: 4px solid #f5c2e7;
  padding: 16px 18px;
  background: #0f1115;
  box-shadow: 6px 6px 0 #f5c2e7;
  font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, 'Liberation Mono', 'Courier New', monospace;
">
  <h1 style="margin:0 0 6px 0; letter-spacing:.08em;">
    <span style="display:inline-block; border:3px solid #f5c2e7; padding:.25rem .6rem;">DVH.SH</span>
  </h1>
  <p style="margin:.25rem 0 0 0; color:#cdd6f4;">portfolio • resume • blog</p>
</div>

<!-- primary showcase -->
<div style="
  margin: 0 auto 14px;
  max-width: 880px;
  border: 2px solid #f5c2e7;
  padding: 16px 18px;
  background: #111318;
  box-shadow: 4px 4px 0 #f5c2e7;
  color:#cdd6f4;
">
  <h3 style="margin:.25rem 0 .6rem 0; color:#f5c2e7;">personal projects</h3>

  <div style="display:grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap:12px;">
    <!-- dvh.sh -->
    <div style="border:2px solid #f5c2e7; padding:12px; background:#0f1115; box-shadow:3px 3px 0 #f5c2e7;">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:6px;">
        <b style="letter-spacing:.03em;">dvh.sh</b>
        <span style="font-size:11px; color:#a6adc8; border:1px solid #2a2d36; padding:2px 6px;">TypeScript / Next.js</span>
      </div>
      <p style="margin:6px 0 10px 0; color:#cdd6f4;">Brutalist portfolio. Text/PDF resume, server‑cached data, keyword emphasis.</p>
      <a href="https://github.com/dvh-sh/dvh.sh" style="color:#f5c2e7; text-decoration:none; border-bottom:2px solid #f5c2e7;">repo</a>
    </div>

    <!-- catppuccin.dvh.sh -->
    <div style="border:2px solid #f5c2e7; padding:12px; background:#0f1115; box-shadow:3px 3px 0 #f5c2e7;">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:6px;">
        <b style="letter-spacing:.03em;">catppuccin.dvh.sh</b>
        <span style="font-size:11px; color:#a6adc8; border:1px solid #2a2d36; padding:2px 6px;">C++ API</span>
      </div>
      <p style="margin:6px 0 10px 0; color:#cdd6f4;">Simple API surface for Catppuccin interactions and palette helpers.</p>
      <a href="https://github.com/dvh-sh/catppuccin.dvh.sh" style="color:#f5c2e7; text-decoration:none; border-bottom:2px solid #f5c2e7;">repo</a>
    </div>
  </div>
</div>

<!-- repos -->
<div style="
  margin: 0 auto 14px;
  max-width: 880px;
  border: 2px solid #f5c2e7;
  padding: 16px 18px;
  background: #111318;
  box-shadow: 4px 4px 0 #f5c2e7;
  color:#cdd6f4;
">
  <h3 style="margin:.25rem 0 .6rem 0; color:#f5c2e7;">repos</h3>

  <div style="display:grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap:12px;">
    <div style="border:2px solid #f5c2e7; padding:12px; background:#0f1115; box-shadow:3px 3px 0 #f5c2e7;">
      <b>dvh.sh</b>
      <p style="margin:6px 0 8px 0; color:#a6adc8;">next.js portfolio app, generates text/pdf resume</p>
      <a href="https://github.com/dvh-sh/dvh.sh" style="color:#f5c2e7; text-decoration:none; border-bottom:2px solid #f5c2e7;">open</a>
    </div>

    <div style="border:2px solid #f5c2e7; padding:12px; background:#0f1115; box-shadow:3px 3px 0 #f5c2e7;">
      <b>.github</b>
      <p style="margin:6px 0 8px 0; color:#a6adc8;">org profile + resources</p>
      <a href="https://github.com/dvh-sh/.github" style="color:#f5c2e7; text-decoration:none; border-bottom:2px solid #f5c2e7;">open</a>
    </div>

    <div style="border:2px solid #f5c2e7; padding:12px; background:#0f1115; box-shadow:3px 3px 0 #f5c2e7;">
      <b>blog</b>
      <p style="margin:6px 0 8px 0; color:#a6adc8;">blog posts and recipe logs</p>
      <a href="https://github.com/dvh-sh/blog" style="color:#f5c2e7; text-decoration:none; border-bottom:2px solid #f5c2e7;">open</a>
    </div>
  </div>
</div>

<!-- data / api -->
<div style="
  margin: 0 auto;
  max-width: 880px;
  border: 2px solid #f5c2e7;
  padding: 16px 18px;
  background: #111318;
  box-shadow: 4px 4px 0 #f5c2e7;
  color:#cdd6f4;
">
  <h3 style="margin:.25rem 0 .6rem 0; color:#f5c2e7;">data</h3>
  <p style="margin:.25rem 0 .8rem 0;">
    <code style="background:#1a1c22; padding:.12rem .35rem; border:1px solid #2a2d36; border-radius:4px; color:#cdd6f4;">portfolio.json</code>
    in <b>.github</b> feeds the site (experience, works, projects, skills, software, etc). fetched + cached server‑side.
  </p>

  <div style="display:flex; gap:10px; flex-wrap:wrap;">
    <a href="https://raw.githubusercontent.com/dvh-sh/.github/main/portfolio.json"
       style="display:inline-block; color:#0f1115; background:#f5c2e7; border:2px solid #f5c2e7; padding:6px 10px; text-decoration:none; font-weight:700; box-shadow:2px 2px 0 #f5c2e7;">
      portfolio.json
    </a>
    <a href="https://dvh.sh/api/catppuccin" 
       style="display:inline-block; color:#0f1115; background:#f5c2e7; border:2px solid #f5c2e7; padding:6px 10px; text-decoration:none; font-weight:700; box-shadow:2px 2px 0 #f5c2e7;">
      catppuccin api
    </a>
  </div>
</div>
