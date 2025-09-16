[index.html.html](https://github.com/user-attachments/files/22360682/index.html.html)
<!doctype html>
<html lang="ko">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>CANTOKKI — 캔토끼 공식 페이지</title>
  <meta name="description" content="재활용에서 태어난 긍정의 아이콘, CANTOKKI(캔토끼) — 세계관, 캐릭터, 굿즈와 제안/문의 안내." />
  <meta property="og:title" content="CANTOKKI — 캔토끼" />
  <meta property="og:description" content="재활용에서 태어난 긍정의 아이콘, CANTOKKI(캔토끼)." />
  <meta property="og:type" content="website" />
  <meta name="theme-color" content="#111111" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Pretendard:wght@400;600;800&family=Rubik:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#ffffff; --fg:#0e0e0e; --muted:#6a6a6a; --accent:#ff4b4b; --card:#f7f7f7;
    }
    [data-theme="dark"]{ --bg:#0c0c0c; --fg:#f2f2f2; --muted:#b5b5b5; --accent:#ff554d; --card:#151515; }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{margin:0; font-family: 'Pretendard', 'Rubik', system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif; color:var(--fg); background:var(--bg); line-height:1.5}
    a{color:inherit; text-decoration:none}
    .container{max-width:1100px; margin:0 auto; padding:0 20px}
    .nav{position:sticky; top:0; backdrop-filter:saturate(180%) blur(8px); background:color-mix(in oklab, var(--bg) 85%, transparent); z-index:50; border-bottom:1px solid color-mix(in oklab, var(--fg) 10%, transparent)}
    .nav-inner{display:flex; align-items:center; justify-content:space-between; padding:14px 0}
    .brand{display:flex; align-items:center; gap:12px; font-weight:800; letter-spacing:0.4px}
    .brand svg{width:36px; height:36px}
    .menu{display:flex; gap:18px; font-weight:600}
    .btn{display:inline-flex; align-items:center; gap:10px; padding:12px 18px; border-radius:14px; border:1px solid color-mix(in oklab, var(--fg) 12%, transparent); background:var(--bg); transition:.2s; cursor:pointer; font-weight:700}
    .btn:hover{transform:translateY(-1px); box-shadow:0 6px 18px color-mix(in oklab, var(--fg) 12%, transparent)}
    .btn.accent{background:var(--accent); color:#fff; border-color:transparent}
    .hero{padding:88px 0 56px; text-align:center}
    .tag{display:inline-block; font-size:13px; padding:8px 12px; border-radius:999px; background:var(--card); color:var(--muted); border:1px solid color-mix(in oklab, var(--fg) 10%, transparent)}
    h1{font-size: clamp(32px, 5vw, 56px); margin:16px 0 10px; letter-spacing:-0.5px}
    .lead{max-width:820px; margin:0 auto 28px; font-size: clamp(16px, 2.5vw, 20px); color:var(--muted)}
    .hero-actions{display:flex; gap:12px; justify-content:center; flex-wrap:wrap}
    .logo-wrap{display:grid; place-items:center; margin:28px auto 8px}
    .logo{width:min(420px, 80vw); height:auto}
    section{padding:72px 0; border-top:1px dashed color-mix(in oklab, var(--fg) 10%, transparent)}
    h2{font-size: clamp(24px, 3.5vw, 36px); margin:0 0 16px}
    .grid{display:grid; grid-template-columns:repeat(12,1fr); gap:18px}
    .card{background:var(--card); border:1px solid color-mix(in oklab, var(--fg) 10%, transparent); border-radius:18px; padding:20px}
    .col-6{grid-column: span 6}
    .col-4{grid-column: span 4}
    .col-12{grid-column: span 12}
    .pill{display:inline-flex; align-items:center; gap:8px; padding:8px 12px; border-radius:999px; background:var(--bg); border:1px solid color-mix(in oklab, var(--fg) 10%, transparent); font-size:13px}
    .swatch{width:18px; height:18px; border-radius:6px; border:1px solid color-mix(in oklab, var(--fg) 15%, transparent)}
    .gallery{display:grid; grid-template-columns: repeat(auto-fill, minmax(160px, 1fr)); gap:14px}
    .gallery .frame{aspect-ratio:1/1; border-radius:16px; background:var(--card); border:1px solid color-mix(in oklab, var(--fg) 10%, transparent); display:grid; place-items:center; font-weight:600; color:var(--muted)}
    .footer{padding:32px 0 60px; color:var(--muted); text-align:center}
    .small{font-size:13px}
    @media (max-width:900px){ .col-6{grid-column: span 12} .col-4{grid-column: span 6} }
  </style>
</head>
<body>
  <header class="nav">
    <div class="container nav-inner">
      <a href="#top" class="brand" aria-label="CANTOKKI 홈">
        <!-- Minimal inline SVG logo (brand colors) -->
        <svg viewBox="0 0 120 100" role="img" aria-label="CANTOKKI logo">
          <defs>
            <style>
              .ear{fill:#ff4b4b}
              .face{fill:#111}
              .eye{fill:#fff}
              .whisk{stroke:#ff4b4b; stroke-width:6; stroke-linecap:round}
            </style>
          </defs>
          <g transform="translate(0,6)">
            <g transform="translate(10,0)">
              <ellipse cx="25" cy="10" rx="10" ry="18" class="ear"/>
              <rect x="5" y="20" width="40" height="46" rx="12" class="face"/>
            </g>
            <g transform="translate(60,0)">
              <ellipse cx="25" cy="10" rx="10" ry="18" class="ear"/>
              <rect x="5" y="20" width="40" height="46" rx="12" class="face"/>
            </g>
            <circle cx="45" cy="48" r="4" class="eye"/>
            <circle cx="75" cy="48" r="4" class="eye"/>
            <path d="M15 52 L35 58" class="whisk"/>
            <path d="M15 64 L35 58" class="whisk"/>
            <path d="M105 52 L85 58" class="whisk"/>
            <path d="M105 64 L85 58" class="whisk"/>
          </g>
        </svg>
        <span>CANTOKKI</span>
      </a>
      <nav class="menu" aria-label="주 메뉴">
        <a href="#about">소개</a>
        <a href="#world">세계관</a>
        <a href="#brand">브랜드</a>
        <a href="#contact">문의</a>
        <button class="btn" id="themeBtn" aria-label="다크모드 전환">🌓</button>
      </nav>
    </div>
  </header>

  <main id="top">
    <section class="hero container">
      <div class="tag">Design • Upcycle • Future</div>
      <h1>CANTOKKI(캔토끼) — 재활용에서 태어난 희망의 캐릭터</h1>
      <p class="lead">두 개의 캔이 만나 귀여운 토끼가 되었어요. CANTOKKI는 환경과 우정을 이야기하며, 굿즈·애니메이션·이벤트로 확장됩니다.</p>
      <div class="hero-actions">
        <a class="btn accent" href="#contact">제안/문의</a>
        <a class="btn" href="#brand">브랜드 가이드</a>
      </div>
      <div class="logo-wrap">
        <!-- Large showcase logo replicating the header SVG -->
        <img class="logo" alt="CANTOKKI 로고" src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 120 100'><style>.e{fill:%23ff4b4b}.f{fill:%23111}.i{fill:%23fff}.w{stroke:%23ff4b4b;stroke-width:6;stroke-linecap:round}</style><g transform='translate(0,6)'><g transform='translate(10,0)'><ellipse cx='25' cy='10' rx='10' ry='18' class='e'/><rect x='5' y='20' width='40' height='46' rx='12' class='f'/></g><g transform='translate(60,0)'><ellipse cx='25' cy='10' rx='10' ry='18' class='e'/><rect x='5' y='20' width='40' height='46' rx='12' class='f'/></g><circle cx='45' cy='48' r='4' class='i'/><circle cx='75' cy='48' r='4' class='i'/><path d='M15 52 L35 58' class='w'/><path d='M15 64 L35 58' class='w'/><path d='M105 52 L85 58' class='w'/><path d='M105 64 L85 58' class='w'/></g></svg>"/>
      </div>
    </section>

    <section id="about">
      <div class="container grid">
        <div class="col-6 card">
          <h2>왜 CANTOKKI인가요?</h2>
          <p>CAN(깡통) + TOKKI(토끼). 버려진 캔에 새로운 생명을 부여한다는 상징과 
            <strong>can‑do spirit</strong>의 메시지를 함께 담았습니다. 누구나 쉽게 기억하고, 다양한 굿즈와 콘텐츠로 확장 가능한 구조입니다.</p>
          <ul>
            <li>환경/ESG 키워드와 높은 친화성</li>
            <li>단순한 형태 — 생산/인쇄/애니메이션에 최적</li>
            <li>패밀리 캐릭터(CANDLEZ WORLD)로 확장</li>
          </ul>
        </div>
        <div class="col-6 card">
          <h2>주요 활용</h2>
          <ul>
            <li>굿즈: 티셔츠, 에코백, 머그, 스티커</li>
            <li>디지털: 이모티콘, 배경화면, SNS 스티커</li>
            <li>콘텐츠: 숏폼/애니메이션 파일럿, 행사 마스코트</li>
          </ul>
          <div class="pill" style="margin-top:10px">문의: <a href="#contact" style="color:var(--accent); font-weight:700">제안하기</a></div>
        </div>
      </div>
    </section>

    <section id="world">
      <div class="container">
        <h2>세계관 — CANDLEZ WORLD</h2>
        <p class="lead">파괴된 지구를 다시 밝히는 작은 불씨들, CANTOKKI와 친구들(캔냥이, 캔멍이, 캔봇…).
          긍정과 협력으로 세상을 수리합니다.</p>
        <div class="gallery" aria-label="샘플 아트워크">
          <div class="frame">아트워크 1</div>
          <div class="frame">아트워크 2</div>
          <div class="frame">아트워크 3</div>
          <div class="frame">아트워크 4</div>
        </div>
      </div>
    </section>

    <section id="brand">
      <div class="container grid">
        <div class="col-6 card">
          <h2>브랜드 컬러</h2>
          <div style="display:flex; gap:10px; flex-wrap:wrap">
            <div class="pill"><span class="swatch" style="background:#111"></span> Black #111111</div>
            <div class="pill"><span class="swatch" style="background:#ff4b4b"></span> Red #FF4B4B</div>
            <div class="pill"><span class="swatch" style="background:#ffffff"></span> White #FFFFFF</div>
          </div>
          <p class="small" style="margin-top:10px">* 실제 제품/인쇄용 색상은 PANTONE/CMYK 지정이 필요합니다.</p>
        </div>
        <div class="col-6 card">
          <h2>로고 사용 가이드</h2>
          <ul>
            <li>여백: 로고 높이의 20% 이상 확보</li>
            <li>최소 크기: 디지털 24px 높이, 인쇄 12mm</li>
            <li>배경: 가급적 단색(밝은색 배경 권장)</li>
          </ul>
          <div class="hero-actions" style="justify-content:flex-start">
            <a class="btn" href="#" onclick="downloadSVG();return false;">SVG 다운로드</a>
            <a class="btn" href="#" onclick="downloadPNG();return false;">PNG 다운로드</a>
          </div>
        </div>
      </div>
    </section>

    <section id="contact">
      <div class="container grid">
        <div class="col-6 card">
          <h2>제안/협업 문의</h2>
          <p>애니메이션/투자/라이선싱 제안을 환영합니다. 간단한 내용을 적어 보내주세요.</p>
          <form class="small" onsubmit="sendMail(event)">
            <label>이름<br><input required name="name" style="width:100%"></label><br><br>
            <label>이메일<br><input required type="email" name="email" style="width:100%"></label><br><br>
            <label>메시지<br><textarea required name="message" rows="5" style="width:100%"></textarea></label><br><br>
            <button class="btn accent" type="submit">메일 열기</button>
          </form>
        </div>
        <div class="col-6 card">
          <h2>SNS</h2>
          <p class="small">아래 채널은 예시입니다. 개설 후 링크를 바꿔주세요.</p>
          <p><a href="https://www.instagram.com/" target="_blank">Instagram</a> · <a href="https://www.youtube.com/" target="_blank">YouTube</a> · <a href="https://x.com/" target="_blank">X</a></p>
          <p class="small">문의 메일: <a href="mailto:hello@cantokki.com">hello@cantokki.com</a></p>
        </div>
      </div>
    </section>
  </main>

  <footer class="footer container">
    <div>© <span id="year"></span> CANTOKKI. All rights reserved.</div>
    <div class="small">이 페이지는 단일 HTML 파일로 제작되었습니다. 호스팅에 업로드하면 바로 사용 가능합니다.</div>
  </footer>

  <script>
    // Dark / Light toggle
    const themeBtn = document.getElementById('themeBtn');
    const saved = localStorage.getItem('theme');
    if(saved) document.documentElement.setAttribute('data-theme', saved);
    themeBtn.addEventListener('click', ()=>{
      const cur = document.documentElement.getAttribute('data-theme') === 'dark' ? 'light' : 'dark';
      document.documentElement.setAttribute('data-theme', cur);
      localStorage.setItem('theme', cur);
    });

    // Year
    document.getElementById('year').textContent = new Date().getFullYear();

    // Generate SVG source used above (kept minimal & identical to the inline logo)
    function logoSVG(){
      return `<?xml version="1.0" encoding="UTF-8"?>\n<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 120 100'>\n<style>.e{fill:#ff4b4b}.f{fill:#111}.i{fill:#fff}.w{stroke:#ff4b4b;stroke-width:6;stroke-linecap:round}</style>\n<g transform='translate(0,6)'><g transform='translate(10,0)'><ellipse cx='25' cy='10' rx='10' ry='18' class='e'/><rect x='5' y='20' width='40' height='46' rx='12' class='f'/></g><g transform='translate(60,0)'><ellipse cx='25' cy='10' rx='10' ry='18' class='e'/><rect x='5' y='20' width='40' height='46' rx='12' class='f'/></g><circle cx='45' cy='48' r='4' class='i'/><circle cx='75' cy='48' r='4' class='i'/><path d='M15 52 L35 58' class='w'/><path d='M15 64 L35 58' class='w'/><path d='M105 52 L85 58' class='w'/><path d='M105 64 L85 58' class='w'/></g></svg>`;
    }

    // Download helpers
    function downloadSVG(){
      const blob = new Blob([logoSVG()], {type: 'image/svg+xml'});
      const url = URL.createObjectURL(blob);
      trigger(url, 'cantokki-logo.svg');
    }
    function downloadPNG(){
      const svg = new Blob([logoSVG()], {type: 'image/svg+xml'});
      const url = URL.createObjectURL(svg);
      const img = new Image();
      img.onload = function(){
        const scale = 6; // ~720px square
        const c = document.createElement('canvas');
        c.width = 120*scale; c.height = 100*scale;
        const ctx = c.getContext('2d');
        ctx.fillStyle = 'white'; ctx.fillRect(0,0,c.width,c.height); // white background
        ctx.drawImage(img, 0, 0, c.width, c.height);
        c.toBlob(b=>{ trigger(URL.createObjectURL(b), 'cantokki-logo.png'); }, 'image/png');
      };
      img.src = url;
    }
    function trigger(url, filename){
      const a = document.createElement('a');
      a.href = url; a.download = filename; a.click();
      setTimeout(()=>URL.revokeObjectURL(url), 2000);
    }

    // Simple mailto form
    function sendMail(e){
      e.preventDefault();
      const d = new FormData(e.target);
      const subject = encodeURIComponent(`[CANTOKKI 문의] ${d.get('name')}`);
      const body = encodeURIComponent(`이름: ${d.get('name')}\n이메일: ${d.get('email')}\n\n내용:\n${d.get('message')}`);
      location.href = `mailto:hello@cantokki.com?subject=${subject}&body=${body}`;
    }
  </script>
</body>
</html>
