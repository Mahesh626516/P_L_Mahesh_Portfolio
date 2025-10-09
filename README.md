<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>P L Mahesh — Portfolio</title>
  <meta name="description" content="Portfolio of P L Mahesh — Graduate Engineer | Embedded & Software" />

  <style>
    :root{
      --bg:#060607;
      --card:#0b0c10;
      --muted:#9aa3b2;
      --accent: #00ffea;
      --accent-2:#799ba4;
      --glow: 0 8px 40px rgba(0,255,234,0.08);
      --glass: rgba(255,255,255,0.03);
      --radius:16px;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%;}
    body{
      margin:0;
      background: radial-gradient(1200px 600px at 10% 10%, rgba(77,217,255,0.03), transparent),
                  radial-gradient(800px 400px at 90% 90%, rgba(0,255,234,0.02), transparent),
                  var(--bg);
      color:#cfeff1;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.45;
      padding:48px 24px;
    }

    .container{max-width:980px;margin:0 auto;}

    header{
      display:flex;align-items:center;justify-content:space-between;margin-bottom:32px;
    }
    .brand{
      display:flex;gap:14px;align-items:center;
    }
    .logo{
      width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent),var(--accent-2));
      display:grid;place-items:center;color:#001f21;font-weight:700;box-shadow:var(--glow);
      font-family:monospace;font-size:20px
    }
    h1{margin:0;font-size:22px;letter-spacing:0.4px}
    p.lead{margin:0;color:var(--muted);font-size:13px}

    nav a{color:var(--muted);text-decoration:none;margin-left:18px;font-size:14px}
    nav a:hover{color:var(--accent-2)}

    main{display:grid;grid-template-columns:1fr;gap:28px}

    .hero{
      background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent);
      border-radius:var(--radius);padding:26px;border:1px solid rgba(255,255,255,0.04);
      box-shadow:var(--glow);
    }
    .hero-top{display:flex;gap:20px;align-items:center}
    .title{flex:1}
    .title h2{margin:0;font-size:28px}
    .title .role{color:var(--accent);font-weight:600;margin-top:6px}
    .subtitle{color:var(--muted);margin-top:8px}

    .chips{display:flex;gap:8px;flex-wrap:wrap;margin-top:12px}
    .chip{background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent);padding:6px 10px;border-radius:999px;font-size:13px;border:1px solid rgba(255,255,255,0.03);}

    section.card{background:var(--card);border-radius:12px;padding:18px;border:1px solid rgba(255,255,255,0.03)}
    h3{margin:0 0 12px 0;color:var(--accent-2)}

    .two-col{display:grid;grid-template-columns:1fr 1fr;gap:18px}

    .list{margin:0;padding:0;list-style:none}
    .list li{padding:10px 0;border-top:1px dashed rgba(255,255,255,0.02);}
    .muted{color:var(--muted);font-size:13px}

    .project{padding:14px;border-radius:12px;background:linear-gradient(180deg, rgba(255,255,255,0.012), transparent);border:1px solid rgba(255,255,255,0.02)}
    .project h4{margin:0 0 8px 0}
    .project .meta{font-size:13px;color:var(--muted);margin-bottom:8px}

    .skills-grid{display:flex;flex-wrap:wrap;gap:10px}

    footer{margin-top:18px;color:var(--muted);font-size:13px;display:flex;justify-content:space-between;align-items:center}

    @media (max-width:800px){
      .two-col{grid-template-columns:1fr}
      header{flex-direction:column;align-items:flex-start;gap:12px}
    }

    .accent-line{height:2px;background:linear-gradient(90deg, transparent, var(--accent-2), transparent);border-radius:2px;margin:10px 0}

    .float-cta{display:inline-flex;gap:8px;align-items:center;padding:10px 14px;border-radius:10px;border:1px solid rgba(255,255,255,0.04);background:linear-gradient(180deg, rgba(0,0,0,0.2), rgba(255,255,255,0.01));}
    .btn{display:inline-block;padding:10px 14px;border-radius:10px;background:linear-gradient(90deg,var(--accent),var(--accent-2));color:#001f21;font-weight:600;text-decoration:none}

    .glow-anim{animation:glow 2.6s ease-in-out infinite}
    @keyframes glow{0%{filter:brightness(1)}50%{filter:brightness(1.12)}100%{filter:brightness(1)}}

    .code-box{background:rgba(0,0,0,0.25);padding:10px;border-radius:8px;font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, "Roboto Mono", monospace;color:var(--accent-2);font-size:13px}
  </style>
</head>
<body>
  <div class="container">

    <header>
      <div class="brand">
        <div class="logo">PM</div>
        <div>
          <h1>P L Mahesh</h1>
          <p class="lead">Graduate Engineer — Software | ECE (2025)</p>
        </div>
      </div>

      <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <main>
      <section class="hero">
        <div class="hero-top">
          <div class="title">
            <h2>Embedded Systems & Software Solutions — Built with Precision</h2>
            <div class="role">Software Engineer (Entry Level)</div>
            <p class="subtitle">Hands-on experience with microcontrollers, sensor interfacing, Arduino, Embedded C, and foundational web development (HTML, CSS, JS, Python).</p>

            <div class="chips" style="margin-top:10px">
              <span class="chip">Embedded C</span>
              <span class="chip">Arduino</span>
              <span class="chip">Python</span>
              <span class="chip">HTML / CSS / JS</span>
              <span class="chip">MySQL / PostgreSQL</span>
            </div>
          </div>

          <div style="min-width:220px;display:flex;flex-direction:column;gap:12px;align-items:flex-end">
            <div class="float-cta">
              <div class="code-box">B.Tech — ECE (2021–2025)</div>
            </div>
            <a class="btn" href="#projects">View projects</a>
          </div>
        </div>

        <div class="accent-line"></div>

        <div style="display:flex;gap:18px;flex-wrap:wrap;justify-content:space-between;align-items:center">
          <div>
            <p class="muted">Internship: Aspire Knowledge and Skills Pvt. Ltd — Embedded Software (Dec 2024 – May 2025)</p>
            <p class="muted">Familiar with microcontrollers, GPIO, timers, UART/SPI/I2C, Keil / STM32CubeIDE, sensor interfacing.</p>
          </div>
        </div>
      </section>

      <section id="about" class="card">
        <h3>About</h3>
        <div class="two-col" style="margin-top:12px">
          <div>
            <p class="muted">Quick summary</p>
            <p>I am an aspiring software developer with a strong passion for technology and coding. My dream is to create innovative software solutions and grow my skills in programming and development.</p>

            <h4 style="margin-top:12px">Education</h4>
            <ul class="list">
              <li><strong>B.Tech — Electronics & Communication</strong>, Vemana Institute of Technology (2021–2025)</li>
              <li><strong>MPC (PU)</strong>, Narayana College — 90%</li>
              <li><strong>SSC</strong> — 83.6%</li>
            </ul>
          </div>

          <div>
            <h4>Internship experience</h4>
            <p class="muted">Aspire Knowledge and Skills Pvt. Ltd — Embedded Software (Dec 2024 – May 2025)</p>
            <ul class="list" style="margin-top:8px">
              <li>Worked with microcontrollers, ADC, sensor interfacing and communication protocols.</li>
              <li>Used Keil, Arduino IDE and STM32CubeIDE for development and debugging.</li>
              <li>Developed a stronger understanding of embedded constraints and hardware/software integration.</li>
            </ul>
          </div>
        </div>
      </section>

      <section id="skills" class="card">
        <h3>Technical skills</h3>
        <div style="margin-top:12px" class="skills-grid">
          <div class="chip">Embedded C</div>
          <div class="chip">Arduino</div>
          <div class="chip">Python</div>
          <div class="chip">HTML / CSS / JS</div>
          <div class="chip">MySQL</div>
          <div class="chip">PostgreSQL</div>
          <div class="chip">NoSQL</div>
          <div class="chip">SQL Workbench</div>
          <div class="chip">Keil / STM32CubeIDE</div>
        </div>
      </section>

      <section id="projects" class="card">
        <h3>Projects</h3>
        <div style="margin-top:12px;display:grid;gap:12px">

          <div class="project">
            <h4>Automatic Headlight Dimmer</h4>
            <div class="meta">Aug – Oct 2024 — Mentor: Dr. Sunil H</div>
            <p>Designed a vehicle headlight dimming system using an LDR to detect oncoming vehicle light and automatically switch between high and low beams. Implemented on Arduino with ADC readings and relay-based switching. Gained hands-on experience in sensor interfacing, ADC and hardware control.</p>
          </div>

          <div class="project">
            <h4>Third Eye for Blind — Ultrasonic Vibrator Glove</h4>
            <div class="meta">Jan – May 2025 — Mentor: Prof. Sharanya</div>
            <p>Built an assistive glove that uses an ultrasonic sensor to measure obstacle distance and drives a vibration motor with PWM feedback. Closer obstacles trigger stronger vibration patterns. Worked on time-of-flight distance measurement, PWM control and real-time feedback loops.</p>
          </div>

        </div>
      </section>

      <section id="contact" class="card">
        <h3>Contact</h3>
        <p class="muted">You can reach me via phone, email, or LinkedIn:</p>
        <div style="margin-top:12px;display:flex;gap:12px;flex-wrap:wrap;align-items:center">
          <div class="float-cta">
            <div class="code-box">Phone: 9391473457</div>
          </div>
          <div class="float-cta">
            <div class="code-box">Email: plmahesh93914@gmail.com</div>
          </div>
          <div class="float-cta">
            <div class="code-box">LinkedIn: linkedin.com/in/p-l-mahesh</div>
          </div>
        </div>
      </section>

    </main>

    <footer>
      <div>Made by P L Mahesh — 2025</div>
      <div class="muted">Built with HTML • CSS • JavaScript</div>
    </footer>

  </div>

  <script>
    document.querySelectorAll('nav a, a.btn[href^="#"]').forEach(a=>{
      a.addEventListener('click', e=>{
        const href = a.getAttribute('href');
        if(href.startsWith('#')){
          e.preventDefault();
          document.querySelector(href).scrollIntoView({behavior:'smooth', block:'start'});
        }
      })
    })

    (function(){
      const el = document.querySelector('.title h2');
      const text = el.textContent;
      el.textContent = '';
      let i=0;
      const t = setInterval(()=>{
        el.textContent += text[i++]||'';
        if(i>text.length) clearInterval(t);
      },18);
    })();

    document.addEventListener('mousemove', e=>{
      const x = (e.clientX/window.innerWidth - 0.5)*30;
      const y = (e.clientY/window.innerHeight - 0.5)*30;
      document.body.style.backgroundPosition = `${50-x}% ${50-y}% , ${90-x}% ${90-y}% , center`;
    });
  </script>
</body>
</html>
