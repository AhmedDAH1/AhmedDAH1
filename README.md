<img width="1440" height="1684" alt="image" src="https://github.com/user-attachments/assets/fee56239-c252-4873-90f5-1bd6ba69707d" /><img width="1440" height="1684" alt="image" src="https://github.com/user-attachments/assets/b0246748-118d-49be-86ec-d3d059824843" />
<style>
  @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;600;700&family=Sora:wght@400;600;700&display=swap');
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: 'Sora', sans-serif; }
  .readme {
    border: 0.5px solid var(--color-border-tertiary);
    border-radius: var(--border-radius-lg);
    overflow: hidden;
    background: var(--color-background-primary);
  }
  .readme-bar {
    background: var(--color-background-secondary);
    border-bottom: 0.5px solid var(--color-border-tertiary);
    padding: 10px 16px;
    display: flex;
    align-items: center;
    gap: 8px;
  }
  .readme-bar .dot { width: 10px; height: 10px; border-radius: 50%; }
  .dot-r { background: #ff5f57; }
  .dot-y { background: #febc2e; }
  .dot-g { background: #28c840; }
  .readme-bar span { font-size: 12px; color: var(--color-text-secondary); margin-left: 8px; font-family: 'JetBrains Mono', monospace; }
  .readme-body { padding: 28px 32px; line-height: 1.7; }
  .greeting { font-family: 'JetBrains Mono', monospace; font-size: 22px; font-weight: 700; color: var(--color-text-primary); margin-bottom: 4px; }
  .greeting .cursor { display: inline-block; width: 2px; height: 22px; background: var(--color-text-primary); margin-left: 2px; vertical-align: middle; animation: blink 1s step-end infinite; }
  @keyframes blink { 0%,100%{opacity:1} 50%{opacity:0} }
  .subtitle { font-size: 14px; color: var(--color-text-secondary); margin-bottom: 20px; }
  .about { font-size: 14px; color: var(--color-text-primary); margin-bottom: 20px; line-height: 1.8; }
  .about p { margin-bottom: 6px; }
  .section-title { font-size: 11px; font-weight: 600; letter-spacing: 0.08em; text-transform: uppercase; color: var(--color-text-secondary); margin-bottom: 10px; margin-top: 20px; }
  .tags { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 20px; }
  .tag {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    padding: 4px 10px;
    border-radius: 20px;
    border: 0.5px solid;
    font-weight: 600;
  }
  .tag-blue { background: #E6F1FB; color: #0C447C; border-color: #85B7EB; }
  .tag-green { background: #EAF3DE; color: #27500A; border-color: #97C459; }
  .tag-amber { background: #FAEEDA; color: #633806; border-color: #EF9F27; }
  .tag-red { background: #FCEBEB; color: #791F1F; border-color: #F09595; }
  .tag-purple { background: #EEEDFE; color: #3C3489; border-color: #AFA9EC; }
  .tag-teal { background: #E1F5EE; color: #085041; border-color: #5DCAA5; }
  .projects { display: flex; flex-direction: column; gap: 10px; margin-bottom: 20px; }
  .proj-card {
    border: 0.5px solid var(--color-border-tertiary);
    border-radius: var(--border-radius-md);
    padding: 12px 14px;
    background: var(--color-background-secondary);
  }
  .proj-name { font-size: 13px; font-weight: 600; color: var(--color-text-primary); margin-bottom: 3px; font-family: 'JetBrains Mono', monospace; }
  .proj-desc { font-size: 12px; color: var(--color-text-secondary); }
  .stats-row { display: flex; gap: 10px; margin-bottom: 20px; flex-wrap: wrap; }
  .stat-pill {
    font-size: 11px;
    font-family: 'JetBrains Mono', monospace;
    padding: 5px 12px;
    border-radius: 20px;
    background: var(--color-background-secondary);
    border: 0.5px solid var(--color-border-tertiary);
    color: var(--color-text-secondary);
  }
  .divider { border: none; border-top: 0.5px solid var(--color-border-tertiary); margin: 18px 0; }
  .footer { font-size: 12px; color: var(--color-text-secondary); font-family: 'JetBrains Mono', monospace; }
  .copy-btn {
    display: inline-block;
    margin-top: 16px;
    font-size: 13px;
    padding: 8px 18px;
    border-radius: var(--border-radius-md);
    border: 0.5px solid var(--color-border-secondary);
    background: transparent;
    color: var(--color-text-primary);
    cursor: pointer;
    font-family: 'Sora', sans-serif;
  }
  .copy-btn:hover { background: var(--color-background-secondary); }
  .action-row { display: flex; gap: 10px; flex-wrap: wrap; }
</style>

<div class="readme">
  <div class="readme-bar">
    <div class="dot dot-r"></div>
    <div class="dot dot-y"></div>
    <div class="dot dot-g"></div>
    <span>README.md</span>
  </div>
  <div class="readme-body">
    <div class="greeting">Hi, I'm Ahmed Dahdouh <span class="cursor"></span></div>
    <div class="subtitle">Software Engineering @ Zhengzhou University · Cybersecurity Enthusiast</div>

    <div class="about">
      <p>🎓 Studying Software Engineering at <strong>Zhengzhou University</strong></p>
      <p>🔐 Passionate about cybersecurity — currently working toward <strong>CompTIA Network+</strong></p>
      <p>🛠️ Building security tools and CTF writeups to sharpen my skills</p>
      <p>🌱 Learning: Network protocols, penetration testing fundamentals, SIEM & log analysis</p>
    </div>

    <div class="section-title">Tech Stack & Focus Areas</div>
    <div class="tags">
      <span class="tag tag-blue">Python</span>
      <span class="tag tag-green">Networking</span>
      <span class="tag tag-amber">Linux</span>
      <span class="tag tag-red">Wireshark</span>
      <span class="tag tag-purple">Nmap</span>
      <span class="tag tag-teal">TCP/IP</span>
      <span class="tag tag-blue">Bash</span>
      <span class="tag tag-amber">CompTIA Network+</span>
    </div>

    <div class="section-title">Featured Projects</div>
    <div class="projects">
      <div class="proj-card">
        <div class="proj-name">🔍 network-scanner</div>
        <div class="proj-desc">Custom Python network scanner — host discovery, port enumeration & OS fingerprinting</div>
      </div>
      <div class="proj-card">
        <div class="proj-name">🚨 log-threat-detector</div>
        <div class="proj-desc">SIEM-style log parser that flags anomalous activity using rule-based heuristics</div>
      </div>
      <div class="proj-card">
        <div class="proj-name">🏴 ctf-writeups</div>
        <div class="proj-desc">Documented solutions from TryHackMe & PicoCTF — network forensics, web exploits, crypto</div>
      </div>
    </div>

    <div class="section-title">Currently</div>
    <div class="stats-row">
      <span class="stat-pill">📖 Studying Network+</span>
      <span class="stat-pill">🧩 Solving CTF challenges</span>
      <span class="stat-pill">📡 Practicing on TryHackMe</span>
    </div>

    <hr class="divider">
    <div class="footer">💬 Let's talk security, networking, or open source &nbsp;·&nbsp; zhengzhouuniversity.edu.cn</div>

    <div class="action-row">
      <button class="copy-btn" onclick="sendPrompt('Generate the full markdown source code for this GitHub README')">Get Markdown Source ↗</button>
      <button class="copy-btn" onclick="sendPrompt('Give me project ideas to add to this GitHub profile for cybersecurity jobs')">Project Ideas ↗</button>
    </div>
  </div>
</div>
