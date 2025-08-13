<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>YOUR NAME — Digital IC Design & Verification</title>
  <meta name="description" content="Portfolio of a Digital IC Design & Verification engineer: RTL, verification, FPGA/ASIC flow, and projects." />
  <style>
    :root {
      --bg: #0b0e14;
      --text: #e6e9ef;
      --subtext: #b6beca;
      --card: #131720;
      --accent: #6ee7b7;
      --link: #8ab4f8;
      --chip: #1d2330;
      --chip-border: #2a3245;
    }
    [data-theme="light"] {
      --bg: #f7f7fb;
      --text: #0b0e14;
      --subtext: #4b5563;
      --card: #ffffff;
      --accent: #047857;
      --link: #1d4ed8;
      --chip: #f3f4f6;
      --chip-border: #e5e7eb;
    }
    html, body { height: 100%; }
    body {
      margin: 0; font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, Noto Sans, Helvetica, Arial, "Apple Color Emoji", "Segoe UI Emoji";
      background: var(--bg); color: var(--text);
    }
    .container { max-width: 1050px; margin: 0 auto; padding: 24px; }
    header { display: flex; gap: 16px; align-items: center; justify-content: space-between; }
    nav a { color: var(--subtext); text-decoration: none; margin-left: 16px; font-weight: 600; }
    nav a:hover { color: var(--text); }
    .btn { display: inline-block; padding: 10px 14px; border-radius: 12px; border: 1px solid var(--chip-border); background: var(--chip); color: var(--text); text-decoration: none; font-weight: 600; }
    .btn.primary { background: var(--accent); color: #0b0e14; border-color: transparent; }
    .btn + .btn { margin-left: 10px; }
    .hero { display: grid; grid-template-columns: 1.3fr 1fr; gap: 24px; margin-top: 32px; }
    .card { background: var(--card); border: 1px solid var(--chip-border); border-radius: 18px; padding: 20px; }
    h1 { font-size: 34px; margin: 0 0 12px; }
    h2 { font-size: 24px; margin: 0 0 10px; }
    p.lead { color: var(--subtext); margin-top: 0; }
    .chips { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 12px; }
    .chip { background: var(--chip); border: 1px solid var(--chip-border); color: var(--text); padding: 6px 10px; border-radius: 999px; font-size: 13px; }
    .grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 16px; }
    .project h3 { margin: 6px 0 8px; font-size: 18px; }
    .taglist { display: flex; flex-wrap: wrap; gap: 6px; margin: 8px 0 10px; }
    .tag { border: 1px dashed var(--chip-border); border-radius: 999px; padding: 3px 8px; font-size: 12px; color: var(--subtext); }
    .links a { color: var(--link); text-decoration: none; font-weight: 600; margin-right: 10px; }
    .kpi { display: grid; grid-template-columns: repeat(3, 1fr); gap: 12px; }
    .kpi .item { background: var(--chip); border: 1px solid var(--chip-border); padding: 14px; border-radius: 16px; text-align: center; }
    footer { color: var(--subtext); text-align: center; margin: 28px 0 8px; }
    .muted { color: var(--subtext); font-size: 14px; }
    .row { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }
    .toggle { border: 1px solid var(--chip-border); background: var(--chip); color: var(--text); padding: 8px 12px; border-radius: 12px; cursor: pointer; }
    @media (max-width: 900px) {
      .hero { grid-template-columns: 1fr; }
      .grid { grid-template-columns: 1fr; }
      .row { grid-template-columns: 1fr; }
    }
    /* Simple focus style for accessibility */
    a:focus, button:focus { outline: 2px dashed var(--accent); outline-offset: 2px; }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div style="display:flex;align-items:center;gap:12px">
        <div style="width:40px;height:40px;border-radius:12px;background:var(--chip);border:1px solid var(--chip-border);"></div>
        <strong>YOUR NAME</strong>
      </div>
      <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
        <button class="toggle" id="themeToggle" aria-label="Toggle theme">🌗</button>
      </nav>
    </header>

    <section class="hero">
      <div class="card">
        <h1>Digital IC Design & Verification Engineer</h1>
        <p class="lead">RTL (Verilog/VHDL/SystemVerilog), constrained‑random verification, FPGA bring‑up, and ASIC/FPGA design flow. I build clean, testable hardware and document measurable results.</p>
        <div class="chips">
          <span class="chip">FPGA: Xilinx / Intel</span>
          <span class="chip">Sim: Questa / ModelSim / Verilator</span>
          <span class="chip">Scripting: Python, TCL</span>
          <span class="chip">Buses: AMBA (APB/AXI‑Lite)</span>
          <span class="chip">Methodology: UVM‑lite</span>
        </div>
        <div style="margin-top:14px">
          <!-- Replace links below -->
          <a class="btn primary" href="cv/YOUR_NAME_CV.pdf" target="_blank" rel="noopener">Download CV</a>
          <a class="btn" href="mailto:your.email@example.com">Email</a>
          <a class="btn" href="https://github.com/YOUR-USERNAME" target="_blank" rel="noopener">GitHub</a>
          <a class="btn" href="https://www.linkedin.com/in/YOUR-LINKEDIN" target="_blank" rel="noopener">LinkedIn</a>
        </div>
      </div>
      <div class="card">
        <h2>Highlights</h2>
        <div class="kpi">
          <div class="item">
            <div class="muted">Projects</div>
            <div style="font-size:24px;font-weight:800">6+</div>
          </div>
          <div class="item">
            <div class="muted">Test Benches</div>
            <div style="font-size:24px;font-weight:800">10+</div>
          </div>
          <div class="item">
            <div class="muted">Boards Used</div>
            <div style="font-size:24px;font-weight:800">Basys‑3 / Nexys A7</div>
          </div>
        </div>
        <p class="muted" style="margin-top:12px">Set these numbers to match your real work.</p>
      </div>
    </section>

    <section id="about" class="card" style="margin-top:16px">
      <h2>About</h2>
      <p>Short bio: 2–4 sentences about who you are, what you’re learning, and what you want to work on. Mention coursework (Digital Design Flow, Numerical Methods), labs, and any competitions or internships (e.g., CIB Egypt training—finance exposure helpful for disciplined engineering).</p>
    </section>

    <section id="skills" class="card" style="margin-top:16px">
      <h2>Skills</h2>
      <div class="row">
        <div>
          <strong>RTL & Languages</strong>
          <div class="chips">
            <span class="chip">Verilog</span>
            <span class="chip">SystemVerilog</span>
            <span class="chip">VHDL</span>
            <span class="chip">SVA</span>
            <span class="chip">Python</span>
            <span class="chip">TCL</span>
          </div>
        </div>
        <div>
          <strong>Verification</strong>
          <div class="chips">
            <span class="chip">Constrained‑random</span>
            <span class="chip">Scoreboards & Coverage</span>
            <span class="chip">UVM‑lite</span>
            <span class="chip">cocotb (optional)</span>
          </div>
        </div>
        <div>
          <strong>EDA & Tools</strong>
          <div class="chips">
            <span class="chip">Vivado / Quartus</span>
            <span class="chip">ModelSim / Questa / Verilator</span>
            <span class="chip">GTKWave</span>
            <span class="chip">Git & GitHub</span>
          </div>
        </div>
        <div>
          <strong>Protocols & IP</strong>
          <div class="chips">
            <span class="chip">AMBA APB / AXI‑Lite</span>
            <span class="chip">SPI / I2C / UART</span>
            <span class="chip">ALU / FIFO / FSM</span>
          </div>
        </div>
      </div>
    </section>

    <section id="projects" class="card" style="margin-top:16px">
      <h2>Featured Projects</h2>
      <div class="grid">
        <div class="project card">
          <h3>ALU (VHDL) + Testbench</h3>
          <p class="muted">Arithmetic‑logic unit with add/sub/logic/shift; verified with self‑checking testbench and waveform captures.</p>
          <div class="taglist">
            <span class="tag">VHDL</span>
            <span class="tag">Testbench</span>
            <span class="tag">FPGA‑ready</span>
          </div>
          <div class="links">
            <a href="https://github.com/YOUR-USERNAME/alu-vhdl" target="_blank" rel="noopener">Repo</a>
            <a href="projects/alu/report.pdf" target="_blank" rel="noopener">Report</a>
          </div>
        </div>
        <div class="project card">
          <h3>SPI Slave (Verilog)</h3>
          <p class="muted">Implements SPI mode 0/3 with RX/TX FIFOs and formal checks; includes behavioral testbench and timing diagrams.</p>
          <div class="taglist">
            <span class="tag">Verilog</span>
            <span class="tag">SPI</span>
            <span class="tag">Coverage</span>
          </div>
          <div class="links">
            <a href="https://github.com/YOUR-USERNAME/spi-slave" target="_blank" rel="noopener">Repo</a>
            <a href="projects/spi/waves.png" target="_blank" rel="noopener">Waves</a>
          </div>
        </div>
        <div class="project card">
          <h3>APB Peripheral + UVM‑lite TB</h3>
          <p class="muted">APB‑mapped timer peripheral with register map, assertions, and randomized sequences; scoreboard + functional coverage.</p>
          <div class="taglist">
            <span class="tag">SystemVerilog</span>
            <span class="tag">UVM‑lite</span>
            <span class="tag">AMBA APB</span>
          </div>
          <div class="links">
            <a href="https://github.com/YOUR-USERNAME/apb-timer" target="_blank" rel="noopener">Repo</a>
            <a href="projects/apb/coverage.html" target="_blank" rel="noopener">Coverage</a>
          </div>
        </div>
      </div>
      <p class="muted" style="margin-top:10px">Duplicate a card block above to add more projects. Keep titles, a 1‑line description, 2–4 tags, and links to repo/docs.</p>
    </section>

    <section class="row" style="margin-top:16px">
      <div class="card">
        <h2>Education</h2>
        <p><strong>B.Sc., Communications & Electronics</strong><br/>College of Engineering — <span class="muted">Expected YYYY</span></p>
        <ul>
          <li>Relevant: Digital Design Flow, Numerical Methods, Computer Architecture, VLSI basics.</li>
          <li>Training: CIB Bank (1 month) — discipline, reporting, teamwork.</li>
        </ul>
      </div>
      <div class="card">
        <h2>Contact</h2>
        <p class="muted">I’m open to internships, junior RTL/verification roles, and FPGA projects.</p>
        <p id="contact">
          <a class="btn" href="mailto:your.email@example.com">your.email@example.com</a>
          <a class="btn" href="https://t.me/YOUR-TELEGRAM" target="_blank" rel="noopener">Telegram</a>
        </p>
        <p class="muted">Cairo, Egypt · <span id="updated"></span></p>
      </div>
    </section>

    <footer>
      <p>© <span id="year"></span> YOUR NAME • Built with vanilla HTML/CSS • <a href="#top" class="muted" style="text-decoration:none">Back to top ↑</a></p>
    </footer>
  </div>

  <script>
    // Theme toggle with localStorage
    const root = document.documentElement;
    const toggle = document.getElementById('themeToggle');
    const saved = localStorage.getItem('theme');
    if (saved) document.documentElement.setAttribute('data-theme', saved);
    toggle.addEventListener('click', () => {
      const next = root.getAttribute('data-theme') === 'light' ? '' : 'light';
      if (next) root.setAttribute('data-theme', next); else root.removeAttribute('data-theme');
      localStorage.setItem('theme', next);
    });

    // Footer year + last updated
    document.getElementById('year').textContent = new Date().getFullYear();
    document.getElementById('updated').textContent = 'Last updated ' + new Date().toLocaleDateString();
  </script>
</body>
</html>
