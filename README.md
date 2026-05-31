
<style>
@import url('https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&family=DM+Sans:wght@300;400;500&display=swap');
*{box-sizing:border-box;margin:0;padding:0}
:root{--mono:'Space Mono',monospace;--sans:'DM Sans',sans-serif}
.profile{padding:2rem 0;font-family:var(--sans)}
.top{display:flex;align-items:center;gap:2rem;margin-bottom:2rem}
.avatar{width:96px;height:96px;border-radius:50%;border:2px solid var(--color-border-secondary);overflow:hidden;flex-shrink:0;background:var(--color-background-secondary);display:flex;align-items:center;justify-content:center;font-size:2.5rem}
.name-block{}
.name{font-family:var(--mono);font-size:22px;font-weight:700;color:var(--color-text-primary);letter-spacing:-0.5px}
.handle{font-size:14px;color:var(--color-text-secondary);margin-top:2px;font-family:var(--mono)}
.bio{font-size:15px;color:var(--color-text-secondary);margin-top:6px;line-height:1.5}
.badges{display:flex;gap:8px;margin-top:10px;flex-wrap:wrap}
.badge{display:inline-flex;align-items:center;gap:5px;font-size:12px;font-family:var(--mono);padding:4px 10px;border-radius:20px;border:0.5px solid var(--color-border-secondary);color:var(--color-text-secondary)}
.badge i{font-size:13px}
.divider{height:0.5px;background:var(--color-border-tertiary);margin:1.5rem 0}
.section-label{font-family:var(--mono);font-size:11px;letter-spacing:2px;color:var(--color-text-tertiary);text-transform:uppercase;margin-bottom:1rem}
.tools-grid{display:flex;flex-wrap:wrap;gap:10px;margin-bottom:1.5rem}
.tool{display:flex;align-items:center;gap:6px;padding:6px 12px;border-radius:var(--border-radius-md);border:0.5px solid var(--color-border-tertiary);font-size:13px;color:var(--color-text-secondary);font-family:var(--sans);background:var(--color-background-primary)}
.tool img{width:18px;height:18px;object-fit:contain}
.links{display:flex;gap:10px}
.link-btn{display:inline-flex;align-items:center;gap:6px;padding:7px 16px;border-radius:var(--border-radius-md);border:0.5px solid var(--color-border-secondary);font-size:13px;font-family:var(--mono);color:var(--color-text-primary);text-decoration:none;background:var(--color-background-primary);cursor:pointer}
.link-btn:hover{background:var(--color-background-secondary)}
.link-btn i{font-size:15px}
.streak-wrap{margin-top:1.5rem}
.streak-img{width:100%;border-radius:var(--border-radius-md);border:0.5px solid var(--color-border-tertiary)}
.interests{display:grid;grid-template-columns:repeat(auto-fit,minmax(160px,1fr));gap:10px;margin-bottom:1.5rem}
.interest-card{padding:12px 14px;border-radius:var(--border-radius-lg);border:0.5px solid var(--color-border-tertiary);background:var(--color-background-primary)}
.interest-card i{font-size:20px;color:var(--color-text-secondary);margin-bottom:6px;display:block}
.interest-card p{font-size:13px;color:var(--color-text-primary);font-weight:500}
.interest-card span{font-size:12px;color:var(--color-text-secondary)}
</style>

<div class="profile">
  <div class="top">
    <div class="avatar">👨🏾‍💻</div>
    <div class="name-block">
      <div class="name">Dokun</div>
      <div class="handle">@Harwarl</div>
      <div class="bio">Backend engineer. Building in Rust & Web3.<br>EEE graduate · Privacy-first systems.</div>
      <div class="badges">
        <span class="badge"><i class="ti ti-map-pin" aria-hidden="true"></i> Nigeria</span>
        <span class="badge"><i class="ti ti-mail" aria-hidden="true"></i> harwarl87@gmail.com</span>
      </div>
    </div>
  </div>

  <div class="divider"></div>

  <div class="section-label">connect</div>
  <div class="links">
    <a class="link-btn" href="https://www.linkedin.com/in/erensama/" target="_blank">
      <i class="ti ti-brand-linkedin" aria-hidden="true"></i> LinkedIn
    </a>
    <a class="link-btn" href="https://twitter.com/_Harwarl" target="_blank">
      <i class="ti ti-brand-twitter" aria-hidden="true"></i> Twitter
    </a>
  </div>

  <div class="divider"></div>

  <div class="section-label">interests</div>
  <div class="interests">
    <div class="interest-card">
      <i class="ti ti-cube" aria-hidden="true"></i>
      <p>Web3 & DeFi</p>
      <span>Solidity · EthersJs · On-chain privacy</span>
    </div>
    <div class="interest-card">
      <i class="ti ti-server" aria-hidden="true"></i>
      <p>Backend Systems</p>
      <span>Rust · Axum · PostgreSQL</span>
    </div>
    <div class="interest-card">
      <i class="ti ti-lock" aria-hidden="true"></i>
      <p>Privacy Tech</p>
      <span>Stealth addresses · ZK · RAILGUN</span>
    </div>
    <div class="interest-card">
      <i class="ti ti-school" aria-hidden="true"></i>
      <p>Research</p>
      <span>Adaptive systems · Robotics · RL</span>
    </div>
  </div>

  <div class="divider"></div>

  <div class="section-label">tools & languages</div>
  <div class="tools-grid">
    <div class="tool"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" alt=""/>Rust</div>
    <div class="tool"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt=""/>TypeScript</div>
    <div class="tool"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt=""/>Node.js</div>
    <div class="tool"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt=""/>PostgreSQL</div>
    <div class="tool"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt=""/>MongoDB</div>
    <div class="tool"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/solidity/solidity-plain.svg" alt=""/>Solidity</div>
    <div class="tool"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/graphql/graphql-plain.svg" alt=""/>GraphQL</div>
    <div class="tool"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt=""/>Docker</div>
    <div class="tool"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt=""/>Git</div>
  </div>

  <div class="divider"></div>

  <div class="section-label">streak</div>
  <div class="streak-wrap">
    <img class="streak-img" src="https://github-readme-streak-stats.herokuapp.com?user=_harwarl&theme=transparent&hide_border=true&border_radius=3.5&date_format=M%20j%5B%2C%20Y%5D&exclude_days=Sun&card_width=680" alt="GitHub streak stats"/>
  </div>
</div>
