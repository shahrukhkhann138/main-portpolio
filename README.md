
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Cybersecurity Portfolio - shah rukh khan</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-800">

  <!-- Hero Section -->
  <header class="bg-gray-900 text-white py-12 text-center">
    <h1 class="text-4xl md:text-5xl font-bold">shah rukh khan</h1>
    <p class="text-lg md:text-xl mt-2">Cybersecurity Analyst | 6 Months Experience</p>
  </header>

  <!-- Navigation -->
  <nav class="bg-gray-800 text-white text-center py-3 sticky top-0 z-50">
    <a href="#about" class="mx-4 hover:underline">About</a>
    <a href="#experience" class="mx-4 hover:underline">Experience</a>
    <a href="#skills" class="mx-4 hover:underline">Skills</a>
    <a href="#projects" class="mx-4 hover:underline">Projects</a>
    <a href="#contact" class="mx-4 hover:underline">Contact</a>
  </nav>

  <main class="max-w-5xl mx-auto p-6">

    <!-- About Section -->
    <section id="about" class="my-12">
      <h2 class="text-3xl font-semibold border-b-2 border-gray-400 pb-2 mb-4">About Me</h2>
      <p>
        I'm a passionate Cybersecurity Analyst with 6 months of hands-on experience in threat analysis, vulnerability assessments, and network security. I thrive in fast-paced environments and am committed to protecting systems and data from emerging threats.
      </p>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="my-12">
      <h2 class="text-3xl font-semibold border-b-2 border-gray-400 pb-2 mb-4">Experience</h2>
      <div class="bg-white shadow-md p-4 rounded">
        <h3 class="text-xl font-bold">Cybersecurity Analyst Intern</h3>
        <p class="text-sm text-gray-600">XYZ Tech Solutions | Mar 2025 - Aug 2025</p>
        <ul class="list-disc ml-6 mt-2 text-gray-700">
          <li>Monitored network traffic for suspicious activity using SIEM tools</li>
          <li>Performed vulnerability scans and risk assessments</li>
          <li>Created security reports and assisted in incident response</li>
        </ul>
      </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="my-12">
      <h2 class="text-3xl font-semibold border-b-2 border-gray-400 pb-2 mb-4">Skills</h2>
      <div class="grid grid-cols-2 md:grid-cols-3 gap-4">
        <span class="bg-white shadow p-2 rounded text-center">Network Security</span>
        <span class="bg-white shadow p-2 rounded text-center">Vulnerability Scanning</span>
        <span class="bg-white shadow p-2 rounded text-center">Wireshark</span>
        <span class="bg-white shadow p-2 rounded text-center">Kali Linux</span>
        <span class="bg-white shadow p-2 rounded text-center">Burp Suite</span>
        <span class="bg-white shadow p-2 rounded text-center">Python (for automation)</span>
      </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="my-12">
      <h2 class="text-3xl font-semibold border-b-2 border-gray-400 pb-2 mb-4">Projects</h2>
      <div class="space-y-6">
        <div class="bg-white p-4 shadow rounded">
          <h3 class="text-xl font-bold">Vulnerability Assessment Report</h3>
          <p>Performed scanning and created a report outlining vulnerabilities and remediation for a simulated enterprise network.</p>
        </div>
        <div class="bg-white p-4 shadow rounded">
          <h3 class="text-xl font-bold">Capture The Flag (CTF) Challenges</h3>
          <p>Participated in online CTFs, solving challenges in cryptography, web exploitation, and reverse engineering.</p>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="my-12">
      <h2 class="text-3xl font-semibold border-b-2 border-gray-400 pb-2 mb-4">Contact Me</h2>
      <form id="contactForm" class="space-y-4 bg-white p-6 shadow rounded">
        <input type="text" id="name" placeholder="Your Name" class="w-full border border-gray-300 p-2 rounded" required>
        <input type="email" id="email" placeholder="Your Email" class="w-full border border-gray-300 p-2 rounded" required>
        <textarea id="message" rows="4" placeholder="Your Message" class="w-full border border-gray-300 p-2 rounded" required></textarea>
        <button type="submit" class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">923059460077</button>
      </form>
      <p id="formMsg" class="mt-4 text-green-600 hidden">Message sent! (This is just a demo.)</p>
    </section>

  </main>

  <!-- Footer -->
  <footer class="bg-gray-900 text-white text-center py-4">
    <p>&copy; shah rukh khan.</p>
  </footer>

  <!-- JavaScript -->
  <script>
    document.getElementById("contactForm").addEventListener("submit", function(e) {
      e.preventDefault();
      document.getElementById("formMsg").classList.remove("hidden");
      this.reset();
    });
  </script>

</body>
</html>
<!-- Projects Section -->
<section id="projects" class="my-12">
  <h2 class="text-3xl font-semibold border-b-2 border-gray-400 pb-2 mb-6">Projects</h2>

  <div class="space-y-6">

    <div class="bg-white p-5 rounded shadow">
      <h3 class="text-xl font-bold text-blue-700">Internal Network Vulnerability Scan</h3>
      <p class="mt-2 text-gray-700">
        Conducted a full internal vulnerability scan using tools like Nessus and OpenVAS. Identified critical misconfigurations and outdated software across simulated enterprise systems. Documented findings in a professional report.
      </p>
      <p class="text-sm text-gray-500 mt-1">Tools: sql , Kali Linux</p>
    </div>

    <div class="bg-white p-5 rounded shadow">
      <h3 class="text-xl font-bold text-blue-700">Web Application Penetration Test, </h3>
      <p class="mt-2 text-gray-700">
        Performed black-box testing on a demo e-commerce website. Identified and exploited vulnerabilities such as SQL Injection and XSS. Provided detailed remediation guidance and logged the entire process.
      </p>
      <p class="text-sm text-gray-500 mt-1">Tools: siem tool, linux bash,python automation, sql quary </p>
    </div>

    <div class="bg-white p-5 rounded shadow">
      <h3 class="text-xl font-bold text-blue-700">CTF Challenges & Writeups</h3>
      <p class="mt-2 text-gray-700">
        Participated in cybersecurity Capture The Flag (CTF) events on platforms like TryHackMe and Hack The Box. Solved challenges in web exploitation, privilege escalation, and reverse engineering.
      </p>
      <p class="text-sm text-gray-500 mt-1">Platforms: TryHackMe, Hack The Box</p>
    </div>

    <div class="bg-white p-5 rounded shadow">
      <h3 class="text-xl font-bold text-blue-700">Security Automation Script</h3>
      <p class="mt-2 text-gray-700">
        Created a Python script to automate log parsing and anomaly detection from firewall logs. Improved incident response time and reduced manual log review by 40%.
      </p>
      <p class="text-sm text-gray-500 mt-1">Language: Python</p>
    </div>

  </div>
</section>



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Contact • shah rukh khan</title>
  <meta name="description" content="Get in touch — portfolio contact section" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #0b1020;
      --card: #0f172a; /* slate-900 */
      --muted: #94a3b8; /* slate-400 */
      --text: #e2e8f0; /* slate-200 */
      --primary: #7c3aed; /* violet-600 */
      --primary-2: #06b6d4; /* cyan-500 */
      --ring: rgba(124, 58, 237, 0.35);
      --ok: #22c55e;
      --err: #ef4444;
      --radius: 1.2rem;
    }

    * { box-sizing: border-box; }
    html, body { height: 100%; }
    body {
      margin: 0;
      font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji", "Segoe UI Emoji";
      color: var(--text);
      background: radial-gradient(1000px 600px at 10% -10%, rgba(124,58,237,.25), transparent),
                  radial-gradient(900px 600px at 120% 10%, rgba(6,182,212,.2), transparent),
                  var(--bg);
      line-height: 1.6;
    }

    .wrap {
      max-width: 1100px;
      margin: 0 auto;
      padding: 4rem 1.25rem 6rem;
    }

    header {
      text-align: center;
      margin-bottom: 2rem;
    }
    .eyebrow {
      display: inline-block;
      padding: .35rem .7rem;
      border-radius: 999px;
      font-size: .8rem;
      letter-spacing: .06em;
      text-transform: uppercase;
      background: rgba(124, 58, 237, .12);
      border: 1px solid rgba(124, 58, 237, .25);
      color: #c4b5fd;
    }
    h1 {
      margin: .9rem 0 .25rem;
      font-size: clamp(1.8rem, 3.8vw + .5rem, 3rem);
      line-height: 1.1;
      letter-spacing: -0.02em;
    }
    .subhead { color: var(--muted); max-width: 65ch; margin: 0 auto; }

    .grid {
      display: grid;
      grid-template-columns: 1.1fr 1.4fr;
      gap: 1.25rem;
      margin-top: 2rem;
    }
    @media (max-width: 900px){ .grid{ grid-template-columns: 1fr; } }

    .card {
      background: linear-gradient(180deg, rgba(255,255,255,0.04), rgba(255,255,255,0.01));
      border: 1px solid rgba(148, 163, 184, 0.18);
      box-shadow: 0 10px 50px rgba(2, 6, 23, .6), inset 0 1px 0 rgba(255,255,255,.05);
      border-radius: var(--radius);
      backdrop-filter: blur(6px);
    }

    .panel { padding: 1.35rem; }

    .panel h2 { margin: 0 0 .75rem; font-size: 1.25rem; }

    .contact-item { display:flex; gap:.8rem; align-items:flex-start; padding:.6rem 0; }
    .contact-item svg { flex:0 0 22px; opacity:.9 }
    .contact-item a { color: #c7d2fe; text-decoration: none; }
    .contact-item a:hover { text-decoration: underline; }

    .socials { display:flex; gap:.6rem; margin-top: .6rem; }
    .icon-btn { display:inline-grid; place-items:center; width:42px; height:42px; border-radius: 11px; border:1px solid rgba(148,163,184,.25); background: rgba(15,23,42,.5); text-decoration:none; }
    .icon-btn:hover { border-color: rgba(199,210,254,.8); transform: translateY(-2px); transition: .2s ease; }

    form { display:grid; grid-template-columns: 1fr 1fr; gap: .9rem; }
    form .full { grid-column: 1 / -1; }

    label { display:block; font-size:.9rem; color: var(--muted); margin-bottom:.35rem; }
    input, textarea { width:100%; padding: .85rem 1rem; border-radius: .8rem; border: 1px solid rgba(148,163,184,.35); background:#0b132b; color: var(--text); outline: none; }
    input:focus, textarea:focus { border-color: var(--primary); box-shadow: 0 0 0 4px var(--ring); }
    textarea { min-height: 150px; resize: vertical; }

    .hint { font-size: .85rem; color: var(--muted); margin-top: .4rem; }

    .row { display:flex; align-items:center; gap:.8rem; }
    .btn {
      display:inline-flex; align-items:center; justify-content:center; gap:.5rem;
      padding: .9rem 1.1rem; border-radius: .9rem; border: 1px solid transparent;
      background: linear-gradient(90deg, var(--primary), var(--primary-2));
      color:white; font-weight:600; cursor:pointer;
    }
    .btn:hover{ filter: brightness(1.05); transform: translateY(-1px); transition:.2s ease; }

    <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Contact • Your Name</title>
  <meta name="description" content="Get in touch — portfolio contact section" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #0b1020;
      --card: #0f172a; /* slate-900 */
      --muted: #94a3b8; /* slate-400 */
      --text: #e2e8f0; /* slate-200 */
      --primary: #7c3aed; /* violet-600 */
      --primary-2: #06b6d4; /* cyan-500 */
      --ring: rgba(124, 58, 237, 0.35);
      --ok: #22c55e;
      --err: #ef4444;
      --radius: 1.2rem;
    }

    * { box-sizing: border-box; }
    html, body { height: 100%; }
    body {
      margin: 0;
      font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji", "Segoe UI Emoji";
      color: var(--text);
      background: radial-gradient(1000px 600px at 10% -10%, rgba(124,58,237,.25), transparent),
                  radial-gradient(900px 600px at 120% 10%, rgba(6,182,212,.2), transparent),
                  var(--bg);
      line-height: 1.6;
    }

    .wrap {
      max-width: 1100px;
      margin: 0 auto;
      padding: 4rem 1.25rem 6rem;
    }

    header {
      text-align: center;
      margin-bottom: 2rem;
    }
    .eyebrow {
      display: inline-block;
      padding: .35rem .7rem;
      border-radius: 999px;
      font-size: .8rem;
      letter-spacing: .06em;
      text-transform: uppercase;
      background: rgba(124, 58, 237, .12);
      border: 1px solid rgba(124, 58, 237, .25);
      color: #c4b5fd;
    }
    h1 {
      margin: .9rem 0 .25rem;
      font-size: clamp(1.8rem, 3.8vw + .5rem, 3rem);
      line-height: 1.1;
      letter-spacing: -0.02em;
    }
    .subhead { color: var(--muted); max-width: 65ch; margin: 0 auto; }

    .grid {
      display: grid;
      grid-template-columns: 1.1fr 1.4fr;
      gap: 1.25rem;
      margin-top: 2rem;
    }
    @media (max-width: 900px){ .grid{ grid-template-columns: 1fr; } }

    .card {
      background: linear-gradient(180deg, rgba(255,255,255,0.04), rgba(255,255,255,0.01));
      border: 1px solid rgba(148, 163, 184, 0.18);
      box-shadow: 0 10px 50px rgba(2, 6, 23, .6), inset 0 1px 0 rgba(255,255,255,.05);
      border-radius: var(--radius);
      backdrop-filter: blur(6px);
    }

    .panel { padding: 1.35rem; }

    .panel h2 { margin: 0 0 .75rem; font-size: 1.25rem; }

    .contact-item { display:flex; gap:.8rem; align-items:flex-start; padding:.6rem 0; }
    .contact-item svg { flex:0 0 22px; opacity:.9 }
    .contact-item a { color: #c7d2fe; text-decoration: none; }
    .contact-item a:hover { text-decoration: underline; }

    .socials { display:flex; gap:.6rem; margin-top: .6rem; }
    .icon-btn { display:inline-grid; place-items:center; width:42px; height:42px; border-radius: 11px; border:1px solid rgba(148,163,184,.25); background: rgba(15,23,42,.5); text-decoration:none; }
    .icon-btn:hover { border-color: rgba(199,210,254,.8); transform: translateY(-2px); transition: .2s ease; }

    form { display:grid; grid-template-columns: 1fr 1fr; gap: .9rem; }
    form .full { grid-column: 1 / -1; }

    label { display:block; font-size:.9rem; color: var(--muted); margin-bottom:.35rem; }
    input, textarea { width:100%; padding: .85rem 1rem; border-radius: .8rem; border: 1px solid rgba(148,163,184,.35); background:#0b132b; color: var(--text); outline: none; }
    input:focus, textarea:focus { border-color: var(--primary); box-shadow: 0 0 0 4px var(--ring); }
    textarea { min-height: 150px; resize: vertical; }

    .hint { font-size: .85rem; color: var(--muted); margin-top: .4rem; }

    .row { display:flex; align-items:center; gap:.8rem; }
    .btn {
      display:inline-flex; align-items:center; justify-content:center; gap:.5rem;
      padding: .9rem 1.1rem; border-radius: .9rem; border: 1px solid transparent;
      background: linear-gradient(90deg, var(--primary), var(--primary-2));
      color:white; font-weight:600; cursor:pointer;
    }
    .btn:hover{ filter: brightness(1.05); transform: translateY(-1px); transition:.2s ease; }
    .btn.secondary{ background: transparent; border-color: rgba(148,163,184,.4); color: var(--text); }

    .status { margin-top: .9rem; padding:.85rem 1rem; border-radius:.8rem; display:none; }
    .status.ok{ display:block; background: rgba(34,197,94,.15); border:1px solid rgba(34,197,94,.35); color:#bbf7d0; }
    .status.err{ display:block; background: rgba(239,68,68,.12); border:1px solid rgba(239,68,68,.35); color:#fecaca; }

    .map { height: 260px; border: 0; width:100%; border-radius: .9rem; overflow:hidden; }
    footer { text-align:center; color: var(--muted); font-size:.9rem; margin-top:2.5rem; }
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <span class="eyebrow">Contact</span>
      <h1>Let’s build something great together</h1>
      <p class="subhead">Fill out the form or reach out directly via email or socials. I typically respond within 24–48 hours.</p>
    </header>

    <section class="grid" aria-label="Contact section">
      <!-- Info side -->
      <aside class="card panel" aria-label="Contact details">
        <h2>Contact Details</h2>
        <div class="contact-item" role="group" aria-label="Email">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M4 4h16a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2zm0 0 8 7 8-7" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/></svg>
          <div>
            <div><strong>Email</strong></div>
            <a href="mailto:you@example.com">shahrukhkhann138@gmail.com</a>
          </div>
        </div>
        <div class="contact-item" role="group" aria-label="Phone">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.8 19.8 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6A19.8 19.8 0 0 1 2.08 4.18 2 2 0 0 1 4.06 2h3a2 2 0 0 1 2 1.72c.12.9.32 1.77.6 2.61a2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.47-1.12a2 2 0 0 1 2.11-.45c.84.28 1.71.48 2.61.6A2 2 0 0 1 22 16.92z" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/></svg>
          <div>
            <div><strong>Phone</strong></div>
            <a href="tel:+1234567890">923059460077</a>
          </div>
        </div>
        <div class="contact-item" role="group" aria-label="Location">
          <svg width="22" height="22" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M21 10c0 7-9 12-9 12S3 17 3 10a9 9 0 1 1 18 0z" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/><circle cx="12" cy="10" r="3" stroke="currentColor" stroke-width="1.6"/></svg>
          <div>
            <div><strong>hazara university mansehra</strong></div>
            <div>mansehra,pakistan kpk</div>
          </div>
        </div>

        <h2 style="margin-top:1.1rem">Social</h2>
        <div class="socials" aria-label="Social links">
          <a class="icon-btn" href="#" aria-label="GitHub">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M12 .5C5.73.5.98 5.24.98 11.5c0 4.84 3.14 8.94 7.5 10.39.55.1.75-.24.75-.53 0-.26-.01-1.14-.02-2.07-3.05.66-3.7-1.3-3.7-1.3-.5-1.28-1.22-1.62-1.22-1.62-.99-.68.08-.67.08-.67 1.1.08 1.68 1.13 1.68 1.13.98 1.68 2.56 1.2 3.19.92.1-.71.38-1.2.69-1.48-2.44-.28-5.01-1.22-5.01-5.43 0-1.2.43-2.17 1.14-2.94-.12-.28-.49-1.42.11-2.96 0 0 .93-.3 3.05 1.12.88-.24 1.82-.36 2.76-.36.94 0 1.88.12 2.76.36 2.12-1.43 3.04-1.12 3.04-1.12.6 1.54.23 2.68.11 2.96.71.77 1.14 1.74 1.14 2.94 0 4.22-2.58 5.15-5.04 5.43.39.33.73.98.73 1.99 0 1.44-.01 2.6-.01 2.95 0 .29.2.64.75.53 4.36-1.46 7.5-5.55 7.5-10.39C23.02 5.24 18.27.5 12 .5Z"/></svg>
          </a>
          <a class="icon-btn" href="#" aria-label="LinkedIn">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M4.98 3.5C4.98 4.88 3.86 6 2.5 6S0 4.88 0 3.5 1.12 1 2.5 1 4.98 2.12 4.98 3.5zM.5 8.5h4V24h-4V8.5zM8.5 8.5h3.83v2.11h.05c.53-1 1.83-2.11 3.77-2.11 4.04 0 4.78 2.66 4.78 6.11V24h-4v-5.83c0-1.39-.02-3.17-1.93-3.17-1.93 0-2.23 1.51-2.23 3.07V24h-4V8.5z"/></svg>
          </a>
          <a class="icon-btn" href="#" aria-label="Twitter / X">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M18.244 2H21.5l-7.5 8.568L22.5 22h-5.828l-4.56-5.33L6.9 22H3.643l8.036-9.174L2.5 2h5.914l4.123 4.8L18.244 2Zm-1.022 18h1.532L8.86 4h-1.6l9.962 16Z"/></svg>
          </a>
        </div>

        <h2 style="margin:1.1rem 0 .6rem">Location Map</h2>
        <!-- Replace the src with your own place if you like -->
        <iframe class="map" title="Map" loading="lazy" allowfullscreen referrerpolicy="no-referrer-when-downgrade"
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d241317.11609865755!2d72.741099!3d33.6162773!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x38dfbf92f14f1a6b%3A0x36d969c7f5a0221!2sIslamabad%2C%20Pakistan!5e0!3m2!1sen!2s!4v1696170000000"></iframe>
      </aside>

      <!-- Form side -->
      <div class="card panel" aria-label="Contact form">
        <h2>Send a message</h2>
        <form id="contactForm" novalidate aria-describedby="formHint">
          <div>
            <label for="name">shah rukh khan</label>
            <input id="name" name="name" type="text" placeholder="John Doe" autocomplete="name" required />
          </div>
          <div>
            <label for="email">shahrukhkhann138</label>
            <input id="email" name="email" type="email" placeholder="you@example.com" autocomplete="email" required />
          </div>
          <div class="full">
            <label for="subject">Subject</label>
            <input id="subject" name="subject" type="text" placeholder="How can I help?" required />
          </div>
          <div class="full">
            <label for="message">Message</label>
            <textarea id="message" name="message" placeholder="Write your message..." required></textarea>
            <p id="formHint" class="hint">All fields are required. Your info is only used to reply to your message.</p>
          </div>
          <div class="full row" style="justify-content: space-between;">
            <button class="btn" type="submit" aria-label="Send message">
              <svg width="18" height="18" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M22 2 11 13" stroke="#fff" stroke-width="2" stroke-linecap="round"/><path d="M22 2 15 22l-4-9-9-4 20-7Z" stroke="#fff" stroke-width="2" stroke-linejoin="round"/></svg>
              Send Message
            </button>
            <button class="btn secondary" type="reset">Reset</button>
          </div>
        </form>
        <div id="status" role="status" aria-live="polite" class="status"></div>
      </div>
    </section>

    <footer>
      © <span id="year"></span> shah rukh khan • Built with ♥
    </footer>
  </div>

  <script>  cd d:\portpolio
    // Footer year
    document.getElementById('year').textContent = new Date().getFullYear();

    // Simple client-side validation + demo submit handler
    const form = document.getElementById('contactForm');
    const statusEl = document.getElementById('status');

    function showStatus(type, msg){
      statusEl.className = 'status ' + (type === 'ok' ? 'ok' : 'err');
      statusEl.textContent = msg;
    }

    form.addEventListener('submit', async (e) => {
      e.preventDefault();

      // Basic HTML5 validity check
      if (!form.reportValidity()) return;

      // Gather data
      const data = Object.fromEntries(new FormData(form).entries());

      // TODO: Replace with your email service / API endpoint
      // Example: Formspree
      // const resp = await fetch('https://formspree.io/f/your-id', {
      //   method: 'POST',
      //   headers: { 'Content-Type': 'application/json' },
      //   body: JSON.stringify(data)
      // });
      // if (resp.ok) { ... }

      // Demo-only success UI (since no backend is connected here)
      await new Promise(r => setTimeout(r, 600));
      showStatus('ok', 'Thanks! Your message has been queued. I\'ll get back to you soon.');
      form.reset();
    });
  </script>
</body>
</html>
