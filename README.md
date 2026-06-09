[index.html](https://github.com/user-attachments/files/28763355/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Enrico Maria Dal Compare — Salesforce Engagement Lead</title>
<meta name="description" content="Enrico Maria Dal Compare — Salesforce Engagement Lead in Copenhagen. I detect and remove conversion bottlenecks in the commercial engine.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&family=Inter:wght@400;500;600&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root{
    --purple:#5D3FD3;
    --purple-bright:#6E4FE8;
    --aubergine:#2D1B4D;
    --cream:#F8F4EC;
    --cream-2:#EFE9DC;
    --ink:#1C1B22;
    --muted:#6B6478;
    --lilac:#8A7BC8;
    --line:rgba(45,27,77,.14);
    --maxw:1080px;
  }
  *{box-sizing:border-box;margin:0;padding:0}
  html{scroll-behavior:smooth}
  body{
    background:var(--cream);
    color:var(--ink);
    font-family:'Inter',system-ui,sans-serif;
    font-size:17px;
    line-height:1.6;
    -webkit-font-smoothing:antialiased;
    overflow-x:hidden;
  }
  a{color:inherit;text-decoration:none}
  img{max-width:100%;display:block}
  .wrap{max-width:var(--maxw);margin:0 auto;padding:0 28px}

  /* ---------- type ---------- */
  h1,h2,h3{font-family:'Space Grotesk',sans-serif;line-height:1.05;letter-spacing:-.02em}
  .mono{font-family:'JetBrains Mono',monospace;font-weight:500;letter-spacing:.04em}
  .eyebrow{
    font-family:'JetBrains Mono',monospace;font-size:12.5px;font-weight:500;
    letter-spacing:.18em;text-transform:uppercase;color:var(--purple);
  }

  /* ---------- nav ---------- */
  nav{
    position:sticky;top:0;z-index:50;
    background:rgba(248,244,236,.82);
    backdrop-filter:saturate(180%) blur(14px);
    border-bottom:1px solid var(--line);
  }
  .nav-inner{display:flex;align-items:center;justify-content:space-between;height:64px}
  .brand{display:flex;align-items:center;gap:11px;font-family:'Space Grotesk';font-weight:700;font-size:16px}
  .brand img{height:24px;width:auto}
  .brand .sep{width:1px;height:18px;background:var(--line)}
  .brand .nm{letter-spacing:-.01em}
  .nav-links{display:flex;align-items:center;gap:30px}
  .nav-links a{font-size:14px;font-weight:500;color:var(--muted);transition:color .18s}
  .nav-links a:hover{color:var(--purple)}
  .nav-cta{
    font-family:'JetBrains Mono',monospace;font-size:13px;font-weight:500;
    background:var(--purple);color:#fff;padding:9px 16px;border-radius:8px;
    transition:background .18s,transform .18s;
  }
  .nav-cta:hover{background:var(--purple-bright);transform:translateY(-1px)}
  .menu-btn{display:none}

  /* ---------- hero ---------- */
  header.hero{padding:74px 0 64px;position:relative}
  .hero-grid{display:grid;grid-template-columns:1.45fr .9fr;gap:56px;align-items:center}
  .hero-eyebrow{margin-bottom:22px}
  h1{
    font-size:clamp(42px,6.4vw,76px);font-weight:700;
    letter-spacing:-.035em;margin-bottom:0;
  }
  h1 em{font-style:normal;color:var(--purple);font-weight:700}
  .hero-role{
    font-family:'JetBrains Mono',monospace;font-size:14px;color:var(--muted);
    margin:20px 0 26px;letter-spacing:.02em;
  }
  .hero-role b{color:var(--ink);font-weight:500}
  .hero-thesis{
    font-size:20px;line-height:1.5;max-width:30ch;color:#3a3545;
    border-left:3px solid var(--purple);padding-left:18px;
  }
  .hero-thesis b{color:var(--ink);font-weight:600}
  .hero-meta{display:flex;gap:26px;margin-top:32px;flex-wrap:wrap}
  .hero-meta div{display:flex;flex-direction:column;gap:3px}
  .hero-meta .k{font-family:'JetBrains Mono',monospace;font-size:11px;letter-spacing:.12em;text-transform:uppercase;color:var(--lilac)}
  .hero-meta .v{font-size:15px;font-weight:500}
  .portrait-col{display:flex;flex-direction:column;align-items:center}
  .portrait{
    width:248px;height:248px;border-radius:50%;overflow:hidden;
    border:5px solid #fff;
    box-shadow:0 0 0 1px var(--line), 0 24px 50px -22px rgba(45,27,77,.45);
    background:var(--cream-2);
  }
  .portrait img{width:100%;height:100%;object-fit:cover;object-position:center 12%}
  .portrait-tag{
    font-family:'JetBrains Mono',monospace;font-size:12px;color:var(--muted);
    margin-top:18px;letter-spacing:.04em;text-align:center;
  }
  .portrait-tag b{color:var(--purple);font-weight:500}

  /* ---------- section frame ---------- */
  section{padding:78px 0;border-top:1px solid var(--line)}
  .sec-head{display:flex;align-items:baseline;gap:18px;margin-bottom:44px}
  .sec-num{font-family:'JetBrains Mono',monospace;font-size:13px;color:var(--purple);font-weight:500}
  .sec-head h2{font-size:clamp(28px,3.8vw,40px);font-weight:600}
  .sec-sub{color:var(--muted);font-size:15px;margin-top:8px;max-width:60ch}

  /* ---------- about ---------- */
  .about-grid{display:grid;grid-template-columns:1.3fr .9fr;gap:54px}
  .about-grid p{font-size:17px;color:#3a3545;margin-bottom:18px}
  .about-grid p:last-child{margin-bottom:0}
  .about-grid strong{color:var(--ink);font-weight:600}
  .edu{display:flex;flex-direction:column;gap:0}
  .edu .eyebrow{margin-bottom:20px}
  .edu-item{padding:16px 0;border-top:1px solid var(--line)}
  .edu-item:first-of-type{border-top:none;padding-top:0}
  .edu-item .deg{font-family:'Space Grotesk';font-weight:600;font-size:16px}
  .edu-item .meta{font-size:13.5px;color:var(--muted);margin-top:3px}
  .edu-item .meta .mono{color:var(--lilac);font-size:12px}

  /* ---------- experience timeline ---------- */
  .xp{position:relative}
  .xp-item{
    display:grid;grid-template-columns:188px 1fr;gap:34px;
    padding:30px 0;border-top:1px solid var(--line);
  }
  .xp-item:first-child{border-top:none}
  .xp-when{padding-top:3px}
  .xp-when .yr{font-family:'JetBrains Mono',monospace;font-weight:500;font-size:14px;color:var(--purple)}
  .xp-when .loc{font-size:13px;color:var(--muted);margin-top:4px}
  .xp-role{font-family:'Space Grotesk';font-weight:600;font-size:21px;letter-spacing:-.01em}
  .xp-co{font-size:14px;color:var(--muted);margin:4px 0 14px;font-weight:500}
  .xp-co b{color:var(--ink)}
  .xp-list{list-style:none;display:flex;flex-direction:column;gap:9px}
  .xp-list li{position:relative;padding-left:20px;font-size:15px;color:#3a3545;line-height:1.5}
  .xp-list li::before{
    content:"";position:absolute;left:0;top:9px;width:7px;height:7px;
    border-radius:2px;background:var(--purple);transform:rotate(45deg);
  }
  .xp-list li b{color:var(--ink);font-weight:600}

  /* ---------- selected work cards ---------- */
  .work-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:18px}
  .work-card{
    background:#fff;border:1px solid var(--line);border-radius:14px;
    padding:24px 24px 26px;transition:transform .2s,box-shadow .2s,border-color .2s;
  }
  .work-card:hover{transform:translateY(-3px);box-shadow:0 18px 40px -26px rgba(45,27,77,.4);border-color:rgba(93,63,211,.3)}
  .work-card .turn{
    font-family:'JetBrains Mono',monospace;font-size:11.5px;font-weight:500;
    letter-spacing:.06em;color:var(--purple);background:rgba(93,63,211,.08);
    display:inline-block;padding:4px 9px;border-radius:6px;margin-bottom:14px;
  }
  .work-card h3{font-size:18px;font-weight:600;letter-spacing:-.01em;margin-bottom:9px}
  .work-card p{font-size:14.5px;color:#4a4556;line-height:1.5}
  .work-card p b{color:var(--ink);font-weight:600}

  /* ---------- certifications (dark band) ---------- */
  .certs{background:var(--aubergine);border-top:none;color:var(--cream)}
  .certs .sec-num{color:var(--lilac)}
  .certs .sec-head h2{color:#fff}
  .certs .sec-sub{color:#b9aede}
  .cert-img{
    background:#1b1233;border:1px solid rgba(255,255,255,.07);
    border-radius:16px;padding:26px;margin-top:8px;
  }
  .cert-img img{margin:0 auto;border-radius:6px}
  .cert-extra{
    display:flex;gap:14px;flex-wrap:wrap;margin-top:26px;
  }
  .cert-pill{
    font-family:'JetBrains Mono',monospace;font-size:12.5px;color:#cfc6ee;
    border:1px solid rgba(255,255,255,.16);border-radius:999px;padding:8px 15px;
  }

  /* ---------- skills ---------- */
  .skill-cols{display:grid;grid-template-columns:repeat(4,1fr);gap:30px}
  .skill-col .eyebrow{display:block;margin-bottom:16px}
  .skill-col ul{list-style:none;display:flex;flex-direction:column;gap:8px}
  .skill-col li{font-size:15px;color:#3a3545}
  .skill-col li::before{content:"› ";color:var(--purple);font-family:'JetBrains Mono'}

  /* ---------- contact ---------- */
  .contact{text-align:left}
  .contact-grid{display:grid;grid-template-columns:1.1fr .9fr;gap:54px;align-items:end}
  .contact h2{font-size:clamp(34px,5vw,56px);font-weight:700;letter-spacing:-.03em;line-height:1.02}
  .contact h2 em{font-style:normal;color:var(--purple)}
  .contact-sub{color:var(--muted);margin-top:18px;font-size:17px;max-width:34ch}
  .contact-links{display:flex;flex-direction:column;gap:0}
  .clink{
    display:flex;align-items:center;justify-content:space-between;
    padding:16px 0;border-top:1px solid var(--line);font-size:16px;
    transition:padding .2s,color .2s;
  }
  .clink:first-child{border-top:none}
  .clink:hover{color:var(--purple);padding-left:6px}
  .clink .lbl{font-family:'JetBrains Mono',monospace;font-size:12px;letter-spacing:.1em;text-transform:uppercase;color:var(--lilac)}
  .clink .val{font-weight:500}
  .clink .arr{color:var(--purple);font-family:'JetBrains Mono'}

  /* ---------- footer ---------- */
  footer{background:var(--aubergine);color:#b9aede;padding:34px 0}
  .foot-inner{display:flex;align-items:center;justify-content:space-between;gap:20px;flex-wrap:wrap}
  .foot-inner img{height:22px}
  .foot-inner .fmono{font-family:'JetBrains Mono',monospace;font-size:12.5px;letter-spacing:.04em}

  /* ---------- reveal ---------- */
  .reveal{opacity:0;transform:translateY(18px);transition:opacity .7s ease,transform .7s ease}
  .reveal.in{opacity:1;transform:none}

  /* ---------- responsive ---------- */
  @media (max-width:860px){
    .hero-grid{grid-template-columns:1fr;gap:40px}
    .portrait-col{order:-1;align-items:flex-start}
    .about-grid,.contact-grid{grid-template-columns:1fr;gap:36px}
    .work-grid{grid-template-columns:1fr}
    .skill-cols{grid-template-columns:repeat(2,1fr);gap:26px}
    .xp-item{grid-template-columns:1fr;gap:12px}
    .xp-when{display:flex;gap:14px;align-items:baseline;padding-top:0}
    .xp-when .loc{margin-top:0}
    .nav-links{display:none}
  }
  @media (max-width:480px){
    .wrap{padding:0 20px}
    .skill-cols{grid-template-columns:1fr}
    .hero-meta{gap:18px}
  }
  @media (prefers-reduced-motion:reduce){
    html{scroll-behavior:auto}
    .reveal{opacity:1;transform:none;transition:none}
    .work-card,.nav-cta,.clink{transition:none}
  }
</style>
</head>
<body>

<nav>
  <div class="wrap nav-inner">
    <a class="brand" href="#top">
      <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEMAAAAxCAYAAACBIBS5AAABgklEQVR4nO2a2xGCQAxFA2M71mAlVkcl1mBB+oVz1QU3j02Ck/PpCBvOJldBp+vl/qBOltt56n0vB04NrTq4x7fOQUQ0c04gWdSaURtCRDRzT24tRNuZlvXMW4t4oL0Q641hjYllERE58YuXjOhx2cOrc986w0tIppxAvsZk9C5kywlElBkIp7iMOYE0ZWTIj4hPuM3OsBaSNSeQ3TGx2h3PnNDUrM4MpFW0Z05oN++nDM/8iBRB1NkZ0oUy3BFz6B6TkR2iDUwrkazM6Fl0uZ2nowTmJ6YBKiE6JxC2jL0CuF2RIScQUWe0LsJCRLRI8ZhgMUfOCUSdGRIRmXICUcmQFOZ9J8rB9RZeu6ujAzf0ozXLeKy4yfAcD6k4FxlaEdJs2jpu6/UTd5GjwRF5CBm9nYQXLhnD8HsTS1YB0jz6KxlaSgZQMoCSAZQMoGQAId8zMjzhUv+n698pGUDJAEoGUDKAkgGUDKBkACUDKBlAyRjF52O36+X+iPzFbF2/t54nAJr9+G0xEZoAAAAASUVORK5CYII=" alt="Y4">
      <span class="sep"></span>
      <span class="nm">Enrico Dal Compare</span>
    </a>
    <div class="nav-links">
      <a href="#about">About</a>
      <a href="#experience">Experience</a>
      <a href="#work">Selected work</a>
      <a href="#certs">Certifications</a>
      <a href="#contact">Contact</a>
    </div>
    <a class="nav-cta" href="mailto:enrico@y4now.com">Get in touch</a>
  </div>
</nav>

<header class="hero" id="top">
  <div class="wrap hero-grid">
    <div>
      <div class="eyebrow hero-eyebrow">Salesforce Engagement Lead · Copenhagen</div>
      <h1>Enrico Maria<br><em>Dal Compare</em></h1>
      <div class="hero-role">Solutions architect · <b>8+ years</b> · Salesforce since <b>2017</b></div>
      <p class="hero-thesis">I detect and remove <b>conversion bottlenecks</b> in the commercial engine.</p>
      <div class="hero-meta">
        <div><span class="k">Based in</span><span class="v">Copenhagen, DK</span></div>
        <div><span class="k">Now at</span><span class="v">Y4</span></div>
        <div><span class="k">Focus</span><span class="v">Data &amp; Marketing automation</span></div>
      </div>
    </div>
    <div class="portrait-col">
      <div class="portrait"><img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAYEBAUEBAYFBQUGBgYHCQ4JCQgICRINDQoOFRIWFhUSFBQXGiEcFxgfGRQUHScdHyIjJSUlFhwpLCgkKyEkJST/2wBDAQYGBgkICREJCREkGBQYJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCQkJCT/wAARCAFKAUoDASIAAhEBAxEB/8QAHAAAAQQDAQAAAAAAAAAAAAAAAAIEBQYBAwcI/8QASxAAAQMDAgMFBAUIBwYGAwAAAQACAwQFERIhBjFBEyJRYXEHFIGRMkKhscEIFSNSYpLR8BYXJDNyc+ElNENTVIJEY5OywvEmg+L/xAAaAQADAQEBAQAAAAAAAAAAAAAAAQIDBAUG/8QAJhEAAgICAwEAAgIDAQEAAAAAAAECEQMhBDFBEiJRE2EFFDIzcf/aAAwDAQACEQMRAD8A4whCFucYIQhAAhCEACEIQAIQhAAhCEACEIQAIQhAAhCEACEIQAIQhAAhCEACEIQAIQhAAhCEACEIQAIQhAAhCEACEIQAIQhAAhCEACEIQAIQhAAhCEACEIQAIQhAAhCEACEIQAIQhAAhCEACEIQAIQhAAhCEACEIQAIQhAAhCEACEIQAIQhAAhCEACEIQAIQhAAhCEACEIQAIQhAAhCEACEIQAIQhAAhCEACEJ7arLcr5Ue72u31ddKBksp4jIQPE4zt5nCAGSF1/hv8m/iC4hkt7rqe0xuAOho7aYb8iBho/eOPBdP4f9hPBVi0vkoJLnMAe9Wv1jf9gAN8eYPPmVLki1jbPLVDba26TCC30dTVzO2DIIjI7O/IAeAPyVztfsP46ujm/wCxvco3D+8q5Wxgeo3d9i9XUdBSW+IRUVLBTRDYMhjaxvPPIeZW5S5M0WJenny2/kw3J5abnxDSQDIyKeB0u3UZcW/crLQ/k08MQtaay53apeBuGPjjaTv00k+HXouvIS+mUoRXhz2l9gfAFO1oktc1SQMF0tVIM+fdcB9ik4vZDwLDnTw1R7/rlzvvJVvQlbH8r9Fab7NOC2tDRwvacAY3p2k/PCTL7MOCpm6XcMWoD9mAN+0YVnQi2P5RT5/Y/wACVDcScN0gGCP0bnsO4x9UhRVV7AOA6gkx2+ppdj/dVTzjb9ou9V0VCLYfK/Rxu4/ky2CYO/N16udK4g4E7WTAH0AaftVYuf5Mt8gY91uvVBVkHutlY+IuGD4au8dh8ea9FoT+mS8cWeRLr7HOObSX9pYZ6iNoLu0pHCYEeQaSfhjPkqdUU89JM6GohkgmbjMcjdLh1GQvdiaXOz229Qe73Ogpa2IgjRPE14AJB2yNtwOXgE1Mh4v0zw0heob/APk88H3USPoG1Vond3h7u/XGCf2HZ28gW+gXLuJ/yfOK7K50ltEN6p84/QYZLjPMsJ9ORP2FUpJkPG0cvQt1ZSVVBUyU1XTy01TEdL4pWaXtPPvNK0qiAQhCABCEIAEIQgAQhCABCEIAEIQgAQhCABCEIAEITu12qvvdbHQWyknrKqXIZFCzU4+e3QdSUANFMcN8I3zi6q91s1umqnAjVIBiOPzc87D5rtPAf5OsFNpruL5WVD+baCB5DG/43jc+gGOuTyXaKC30dqpI6SgpYaSnj+jFCwNa30A/FQ5fo1jjvs49wZ+Tlb6DRV8UVXv8w390gcWwg/tO2c74YHquuWyzW2yU/u1st9JQw9Y6eFsYJ8SGgZPmU8R474Chts2UUugQoq48T262u0PlMsozlkXeLfU8h96rddxzWzZbSQx07f1j33fgPsUNpBaLyXBoJJDQOZOwUXX8T2e2M1VNdGMfVjy8n4AfeuaVN1rK6ozVVMsuMkanbD4cgoO+XNrInGNwLgMNP6qwlnd6RcI/RdOIvbZarMC2loKislA+i97Yh+P3Kk1P5SF4mk0Ulioac8v0r3S53GcYLei5zXulqKpwwX5Oc4W+g4WMk+vRqJ3wenyUPM12zrhgT0kW6q9s/GtUdQr6WgG3dhgY4n94OKjR7UeM5GPjm4jmaPGNsYIxvj6I9fh54W+l4MnnAa5rYIz0a3BPxT1nANJENOkl3UrCXJd9nZDgprZWKjjjjYymRnFVykjfjDmTkBvy5JuPaHx3TszFxPcySeT5NWccwMjn/PgrNV8CU3ON7ozzBBUNPwZVQveY5O0a7mD49Elyf7B8Kukav62ePooGy0/EtQ4NGsB8cTsYPXLTsndu9v8Ax/SaBNWUFdzIdUUrRq8jo0/coCt4Zq6WYOGWNcdx9UqJdY6mnecBxAdyIWkeR/ZlLiNeHUab8qe7UrWG5cNUU5DcP93nfDk56ag/Hp9qv3Cn5QHDfErnMmpqy3yBur9IA5v2HP2LzBXwF8Wl8eCM7YTChqZKWq0s1ActQ23yuiOVtHHkwuJ7roeIrTcWh1JXwyHGcOOl3yO6kfReeeBriK2giD52veImkjr/ADzVrpLtXWx5dR1UsY/VBy0+oO3NX/J+0Y/J1tCpNBx/O3u1tKyQfrxHB+R5qyW7iK23TS2GoDZD/wAJ/dd8virU0+hUJv3C9k4npnU15tlNWxuGMyM77cZ+i8Yc3mdwQdzuuN8Xfk16Q+o4Wr3OOou91q3AHBIGGvHgC7c74A5ndd4QrUmiXFPs8Q3zh278NVhpLxb56KYbhsg2dsPou5HmNxyUbyXt++cOWjiaidRXihgq4HDlIDlvLdrhu07cxg+a4Zx5+TrU0DH13CMstawOy6gmLRIwczpfsHehAPm5WppmEsddHE0LbU0tRRTvp6mCWnnjIDo5Wlrmnnu07rUrMwQhCABCEIAEIQgAQhCABCEIAEJTWl7mta0ucTgNbzPTGP4LuPss9gxqGMvHGNPI1hw6G2uyxx6h0nUde5z8fAptIpJt6KT7OfZFeeO52VL2uoLQ1w11Ujd5B+rGCO8fPkPE8j6Y4T4LsnBdvFFZqNsTTvJK7vSTHxc7mfTkpmONkUbY42tYxgDWtaMAAdAPBKWTk2bxgkHxygkAbkAcznYJncbtT21o7Q6pCO6xu5/0VTul6q7kCwu7KL/ltOx9T1UOaRok2Sl845orU7sadhq5/wBl2ljfV3X0wqpXcS3C7kiWYxxnlFHsPj1SncNvrIzMH6cb4wt1t4Tmqs/pcfBZOd9kO7IjdYIcQVN3Xh2S2QGR0gcGjJ2UHTzsqc6Ci9E1uiOrIpGB0gyG433VUuc4lyGA93Y5Ct/EBkio3A7Do4dFSo6OaqqOziY5xJ7/AHtIA9QueW3Z24I+ILVZW1kokcBjOd9lerLZ4oO8GAfBNrNaG0rGkga+paFZ44dETSxjsZHrzXLktnq4UoqjS6BoI2+xZdSg4IOPJO5YC7B/BaX6mb9OSwo6osi6qnPQbJhPFo3xlTM4aegGfJR9S0YLcKGjRPRDVUDKmMtc0beShquhYGadIy3yVgkboJxzKj6sBzT0QmwoqNwt0DiQY29eiqdztkcZcYxpPNXur0jUMKsXWLDs+K6cU2jkz4010PvZhXkXYwyYaBhjhk7DfljbwXWphvtj4LhvDFY22cUU8j3lkUxMb8dc/wA4XcNYLWuJztz8V33as8TJH5k0xTOSwTh2c4+wrLXBYeQTsUkySbtvGFytgDHPFTC36kp3Ho7mrhZeLKG8YiJNPU5DeykI7x/ZPVczJGEjI8cfHBCqOSg+bO0oXNLJxrW2vENTmqph0c7vt9D4eWMK/Wm80d5pxNSyZx9KN2zmeoW8Zp9ENUQHHHsysHHkH9vg93rG4La6na1swxyBcR3m+R+GOa8x8c+zq98A1jIrnEySmmJEFVFvHLjp5H9k7+Gea9keqb3C30l2opqKvpoqmlmbpkilbqa4eY5dM58VpGVGcoJ9Hhf5/FC6v7VfYlPwjG+8WH3istIy6aNw1SUo55yPpM5742655rlC1TswaadMEIQmSCEIQAIQhAAt1LSz1tRHTUsEtRPK4MZFC0ufIfAAbknpjmk09PLVzxU8EbpZpXCONjAC5zidgM9ScY9V6k9kvskpuBqVtxuTI575M3vOHebTNPNjDyJxzd8BtnMt0XGLZH+yH2NR8KNivl+Yya8Obqjh2LaPbp0c/wA+nTxXWEJMsrII3SyOa1jRkuPILJv1nRGNaQrYAk7ADJ6BQV14hEYMVGQ53WTmB6Dqom9cTSVhdFTamQefN/qqsb8ffWwEc1zvNb+YmqSSuROSvfK8ve4ue7m4nJK0uwE5p4O2ja49U/htkbhkgfFRL8exxkpaRmnqhHbnjAyG80+4Wqu0h1EBMayOOCkkaMck3sdwbSUx3wMZWUratEuoy2OuPqp0dql0jfSd1zvhBpfDk779VJ8a8WtqKaWJmT0UfwT36Rp9U8TbjszbTehfF8/Z0whAGJOZ6gZH8fsUfYaFrGl8re/Icu8h4Kb4ihLxESGEa+R5/wA7LTTsbp8M4Awok6VHfxo+kjTw5/u2YbnoFLUsREeCHcuq12+h1sBJI09FI6Q0d3ZYs9KK9NL4g1hGExkiJBxlPpNRduchNJqsQv0uwPipas0jIi6qOSMclETTlj8kfNTtTVxzAhr2knoCoOraHuyPNYSi0zog00R1TOC8Fp7ybyO1QuJ8EiqjdFKXA89lu0A0ZPh4KTStFcrXAvIO3gq9cGEsJcOSslW0Fx2ztzUBdcBnJa4znypJFdeGsraSRwyGzMP2rtL6zSGtacDAwuKVGXSwgf8ANbsPVdarY3MkABwAOS9HHheVUnR8v/k8rxvSH4rjjGpArCMnUoeMPz9JO4Yy5pznZPLwZRi2mebh5knJWh0a156pPvr8c1GzVYifpKQKvWcDO68hcTPJ3Z78c1xtIeyXSSN2Eqj4lrrbUsqqOYwys5OGPkQVGzuOcrQHhxX0/HwKMEpdny/L5WT+V1o7Twf7SaO+tbR3EspK0Nxqc4COY+R6HyV2XC+A+H2Xu5aZN2MGSBtldbqLlDwyIaeukPuxwxsp3LfIjqP59MsmSMZ/J6fDlPJi+pE16fh+K4P7Y/YoD2vEXCtJ+1VUETDv+3G0fa34jdd2a4PaHNcHBwyCDkFZx5Z+0FUnRu0mjwehegfbP7GPfe34m4ap/wC0byVlFGP73qZGD9fqR15jfId5+WiZzSi4sEIQqJBZ2HM4H8/NYXbvYN7LW1728V3yld2ETg63wv5SOG/alvUDbT4nJ6DKukVFNui0exj2QjheGPiC9xNN4lZ+hge3/c2u/wDmevgCR1K60hYe9sbS95w0BYt+s6YxrSMTTMgjdJI7S1o3JVTulwluUha7LYRyZ+PmnN2u/bP05xC3kM8/NQc10ijfvhfI/wCc5PLnL+PjpqPp7XBxYYr6ydmZKYZOyqFzYIb1GRtkqzvvcR5Kl8S173XGOeMHunosP8LDmRzXm6/sOfLC8dQ7OjW8E08ZKlotJackZXNKbjUwwNYQ7IHghvHs4cdnY9F9bkpniYVJOy73dxbC/fomFgiFQxwcc9FTblxtJPA8AOzjqmfD/HT6ZzmyNdn0ThSVMibbdln40skUVHJIAAQM8kx4EjBpWNO3XJ5AKOvvFUl0hLG6hnnkJ9w1UNis9QGnvNjwduWTj8VlmkoRconRw8P8mSMJekveqOavgZPRuEkbHkHu8/RM4h7q0GVhbI4fRP1Va7YY22uNp5kDG3NNbhbWTgOdGMg4G64YTb7Pop4Iw/GKo22eTXSknYk5Th0gyGnY81roqbsItIAHotVyldFEXA7EdRz+1DlSslRfQVUxkJZC4+eFXbv3WvE0oa0jkSAUVUtfXQ+70k7aMHZ0unU4/PkqlxHwrWsoZT201VOWkNn94LSHb76cEEAdNvxSg/v0cvxWlZqqGtbN/ZrkWPz9HUDlSVO2pcG659bTyKolVRx0tI3XDOKofSy7Y/arzwPG+ela6eR0jjza7fAUTj/ZtCTq2jdVwObE+VwOBuo6O4xG2yEuGzj1Vn4jMYtZYGgYB3+C4HV3WuFzloWSubE6TIA6/aEseNyCeVRVss904jhp2uDBrdk+qhJLwKqHU6F7QeWpbqe8w2pzGOoZJXkuALmtIcRzGQU4uF+pK1r6aSLsJ2/8NzV0qDjqjkeVTvZGWim9+vdBDpLw6oYXAfq6sn7AurXRuJ9jlcy4QcW32mfqDS3URk46EfiugzQTznLpMH/Eu3BNRezwubjc3oGDfdSFC1r3aTgKt1bqinnDA8b/ALSkKaOYAP7UZP7S6smeLi0cEOPJNNmL1Shk+Wb5W61cM3Cvb2kUQ0+ZSKindI0vfICR+0FK2PjSK2YppYy4jkWkLmhkSWj1ozfzSRK2j2fT121QNJG2xTu6ey1tNAZYnuB8zlbKTjdzH9pG1oYf2gs3z2gvfQuEeAcbZcFf+w/DzcnEhOTckTXs64VltE76h8gJcE69qRBoGjOe8FUeHPaJURQ6ZA0v/wAQTfiLip15IbJIxrRvu4Lkl9TnbOvHGOLH8xJTg7jee0SR0Fa7tKFzsNcd3Q+nUjy/Dn1Nj2Ssa+N7XscMtc05BHiF5795g/50f7wVx4J4+gtJZbq+qjNGTiOTUMwkn/2/dzXXCXjIOq/z/PiqtUey7guqnkqJuG6J8sri97uwd3nE5JVoaQ4AtIIO4I5I+f7q2THSZ4PQhbqOknr6uCkpY3TVFRI2KKNm7nuccBo5bknAWxxlv9lXs/l4/wCIm08jXNtdLh9bIDyac6WDzeQR5DJ9fW1JSQUFJDSUsTYqeCNsUUbeTGtGAB6AKv8As94KpeBOGqe2RBklRgyVM7WgGWQnr5Ad0eQVlWUnbOmEaQfL49Pw815q9rP5Q1YOIH2nhYxijoXvilqH4cKiQHBLf2RjbxyTywuqe2CtvlVYJrDw28Q1lYA2apLy0wxnchpH1nYxno0nry85j2F8RnnNSj/uKyk10zRJjeo9t3F1QMOqYQP8CYye1niiT6VUz9wKX/qL4g61FL8yj+ou/wDWppftUVAdyIM+1Tib/q2furVJ7TuIpDl9TG71YFYf6ir51q6YfArI9hN5J3rqYfAp/gLZWj7S+IOk0P8A6YWqT2jX9x/3hg9GBWo+wm7D/wAfT/ulY/qIunW4QfuFKo/oLZT5OPL9I0h1ZsfBoTdnGV6jJLaxwPoFeD7Cbl1uMP7hWP6irgBvcof3CquIqZS/6b38kZr37+QXQvY9xRcLle6221tW+Rs9I5zGn9ZpymP9RlaDvco//TP8VYeB/ZhW8McTUNy9+a9sbyC0NIyHAj+fRZ5UpQaR0cSThljI7TU1T20wt1J3ZWNDHvHMbJ6XPhpNMpLi0AZPUqPEFVSXCe4xRtmpnDLmg95rhz2W243GOW0snAczXv3hgtIyvIhrs+lytNKvSSid2jR6brVWQCRvLJWq0yGWma8jnsnr29MLak1Rg7TKvW0L4++2TQ7psq7cZa0Fwc9pHoR+Ku9xjG+eSp93cyHLjhYyXydONWQDLFHXygzBxJ6Aq32q1C307GQxljAqxbKuSoqh2IwwOxqPir9S0FY2NrnPz5EqY2yska7Im/U5moHMP6pXA71QGO8Sl+xLtsjYr0bcYnvpniSMh2N9vJcJ41oXsr5HA4IOoLbHaZzZEpRGkNIwxN7ak3byewc/kmVbbW1U7ZItbn5GXP6hWKwSPqqNpc3onVypG9kXDYq/5HdMl4V82ijXx0tFS9pE7Q5rTgtznfA5qp/n66Eb3Cpz/mFdIo+G/wClMk1G+R0cUbcvc3ocjH2ZW7+pijB3qp/TZd+Br52eFymvvRy593uEhBdWVDj46ys/nm5DlXVGP8xy6iPY1Q9aqf5hZ/qaof8AqZz8Qtbicxy03m44x79UH/8AYVr/ADjWE6veps+Osrq/9TlvHOon+YWD7Hbd/wA6f5ouIbOWC73Ef+OqP/UcsOu1e8YdW1B9XuK6ofY/bhj9NP8ANZ/qht2P76b5ouKEcobc65n0aucejyg3Otdzq5z/AN5XVv6orb1lm/eR/VFbB/xJv3kfUQqzlBuFX/1U375WPf6v/qZv3yusH2SWwfXm/eWP6prX+vL+8i4hRePyZ/a+ajs+Br7UPdLu63VMr8gtG5hJJ6bluPMeGfRq8eR+y23U8jZYpamOSNwex7H6XNcNwQeh6hdqpPapeYKWGKWjpp5I2Na6VxwZCBguI8+aamh0eaF278nPgZtZVT8WVseYqZ/Y0bS0Ye/HffuOmWgEHmSOi47aLTVX26UlroY+0qauVsMTeQyT1I6b5JPL4L2lw3YKThiw0NmowRBSRCMOIwXHfU71c4ucfVbyfhz4427JJaaypbR08kzvqjbPit2f4kqvXmrFVOI2k6IiQPM9VjOVI6VG2RE+aiZ0sgy95JJ9VpMTR9VPdI8AkFo8FzWbUNDG39VazE39UJ6WjwSCB4IE0xoYh4BIdEP1U7cB4JBA8ExUNDGPAJBib4D5J4QEhwCYhmYm790JHZN8E7cB4JJA8ECoaGIHoEnswD9uU6OPBIPogF3aJy1zCaidI0fpchsg8ccj9qjruBVNjhwdnYIHJNoKiameXRPLdt06oIhP2rnu1OJyckbrjy4qdro9fjcpSSi+x7SyBlPG1uAcdNk6fJ1ymUjpIZmMa0GPBLj9Zanz/pBzO+dlndHalezXdZ9MbnEgADnlc9ucz7rVdjEe5nvO6eitHF08jqAsiJBe7TnyVPpa6miqHRyztiDcAasAfDzXPkbbo6cf4qydo6GClpWx+AyOhB8U4N6NG46p5JBy+kdkz0008QdHUa9ty3Oyj7jTtY0lr3uGDzBHUI2lpD+lLskb17QoIqJ0LS50zhgNXIuI7nU3OvD2xlkTdjk7n/RTt2o43ubK+Zvd5knluoW6SUjWfoZmPLHnBPotoPZhmVddDywXBsDBE7AHgpmvkaYXYIIxsqZEe/qid16bqehqHzWouce8xxZlEl+QQncWic9n+A64bYcXN5fFW8tCpXAD+zqa1p+kdLgPEb5+3Cu5GNl6GP8A5R83yP8A0YnSPBY0hKz5LGfJWYiS3ySHNC2ZykuQI1loCwQMJR5JD/ooGtvZrJGUbJOfNJ+KRq4IWQEkjPRAxhHomZtUJc1Jwf1h8kolJ2SaHRs/Jr4Tjqq+u4nqG6vdP7LSgtyBI5vfdnxDSG+j3Z6L0Eq97PuGf6I8H2y0ObGJ4YtU5ZuDK7vPOd87kjn05KxLqbtmcFSG1xqvdKR8gPe5Nz1P8/cqw45JOc+af3qqM1V2IPdi2I8SVHErmyStm8VSApJ5JR5JBKzoswUgpTikEpoQlyQUtyQU6JbEOKQUpxSCdkxCXJBSiUg8kUAlyQUolIPLZMRgp9amObG+QDOX4yfRR5KnrKwG3uyAcuPNZ5V+J0cb/s2yhojJBOojB+ChLhI5rC9hw0FSE82uZ8bMhrcglo5eij5qcvjIJOHOyAvPme3id9kTeoHVlI7OTsCNlGx8LW+5U4jqqaOTLg9riBlrs5BB6bhWOCDU0sduCMLVTM7B/ZkDY7LFOmdDeqE0kFws8LY2GKeJrXBrns72D+tgrU/iaopWxe9W+KQRwmNz2O3Pngj16qejnb2WDg4UFczC/WNIzzyVupKiIxi+0Uy8Xq21NNVRTWgvlkc5zXGNuRtsPmuYcYmC5MEdPRdk90mokjGBsBy+K6XW+6yF+sBpHgqje6SmikLm4JPJXjkrsyz4oLpsZcKUA7IiUBzy3APgpK5MjtbBTlwc4kyOx0z0Wuzyika6V2GhgycqLu1c6skfLj6W/NSk5Tsn7UIUWj2cObPWV85BGAMHpkkq+HmqzwFbPzfZ2vcMPlOpx8D4fJWVelBUj57LL6m2YHNYKUUhxTM7MFYcUFJcUgEknKw5DhncJDsoHE1ELBHJKc1IIIKDb6F8gsZWDyRkIMmzBGVjAWScLGUC+mehvl8EiombTwSSuOzGl2yWojiSp7OmjgB3ldv6Df8AgtpOk2OKtkJrc97nu+k45Pqsla2FLJXKjYwSkkrLikEqgsSSsEoJSSUUSYJykk+SCVgkJ0IQ8+S1kpTytZKYGCdkgkhZJSXIEJcSkEpRKQd/4IFZmOJ0z9DfM56DG+VOcK1tPX2oT0ztUYlewO5g4PNZt9lcbHVzuGJaiJzYx1a3H4qM9mVGaDg2lpZMiaNz2yg9Hazn7FHIi1A6uHTk2TVbA0ansYC47bfNQRuUMr3xOGhzTzI6qxz98czkjxULWUwijcY+853IeC4GrPUTrYx97ETyQQ7Ttk4KXJNGSHkN1dSoWrNRFM3QcgjJAWqS5SQR7t7QOHe5LJxNlMmo6pkrtLXYKjrnECD8e8VCw3gMnGJBnVu3PJLqrvqD9TslrhsfDb/VFaNYTRBXO3Ze5zZH6sdD/FU24GWOUxzHLQe65Xipqm97JBOcYG+FSOJbhE2R5achpDBkdeqvHF3RPIlGrGVbXtZTCFrue+R9yecLWOa+VDZJGEQjfvBR3D9om4krtsCKPBdldatdBHb6RkLBu1u58V6GPGuzw+RyG9Id08LKaBkTO61gwAl52WMpJK2OAUSkrBKxlMRkpJKCUlxSoGwKweSCUlzgigsw/ktRcFsO61bcki4sycHdYKxkIJCKE27MEnHJY1FYLkZSBnolVTiGpE1zMYcNMTQw48TufwVsXNLfcvzw11w+rUudIM9ATkD7VeV6SNca3ZKMJ680onZamHKWDsskU2BKQSslJcqJMEpBO6ySknmigMOKQT5rJSHeKAEuOUjGUopOcIEJd5JGMpTjvhIzp2ToBLs55pxa6T36ujhP0CdTvQc1owXnAByTsArTw/bhSU5nmGJZdgPBq0xQbkZylSJYuBgDcYA2042GyqVbIeHK19SBiiqDmTTyif8ArY8PFWYu0RkeGxTOsp462nfA4AskGDnqu3NgWSDXpnhzvHP68GbqlkrQ+MtIIyMck3keyaLvD1x/oqtPPUcHVvus2p9tef0b+fY+R8vBSzK6Kdocxwcw7g+C+eyQcH8s+hxzU4poTV07pGlulj+e7iqzcIOz1B8UvLYNJ0+XXxVrhDXkHOR4oqaaKQYczn0KiirpnNa2hY7U5pMTs5yDz8lEVk9TGwukkOvwB36Y3/nkum1lppntJDQD6KmX+0whr8uLW56JUrL+nRQay91DXOy85JwMc1A1ZluEmXknLs5CmbhTwwzFseX45ZWmSDsoHzPGDjOF0wpPRxzlJt2XrgS3MorJE/ALpiXE46clZwVUfZ9WPmszY3knHfYf2SVbGldi0eTN/kzYSsE5WCUnKZNmSsZ3WC5YygLMuO6SSgnfmkuKAMFywSsE7oJKBBk4ScIysEoGnQFJI2WSUnJwgLMcwsIJWNSVBZ3fiu4NtPC93rz/AOGoppeYydMbiMZ88D1XN+DXZsND/lNVj9t1cLf7ML5JgOdIyOBoOeb5GNPyBJ+Cq/Bbj/R+h/y2oy+G+P0szCMc0v4rSxxwtgOylAzKSSgu80glMAckHZZLikuO2UCsweS1k7JROpIcUAJJSClOPRboKGSaMyOIjjBwHnxVRi5aRDaXY2ILiABk+S3QUM07wCNDRzLlN2+g9xGvs2yvJ+lnp5Ku3+4OttQZYxp1Hdo5FdMeP7Iz/kvomoYoKFmYhrJO7jzP+ilKSviniHZvaTGdDvI8wVUbdczcpKZjstErslmdyB5/YtUFydauK6iJ7j2FXg46aui64KMVSMpW+y7PkB2HLqVpJ0uyVqjqGhwjOPIrZM8a8cx0Wy2ZtV2M7nQU9yhfFPGHteCDkdP5yucXe13Hg+Y1NIH1Nr+swbmH/RdPxqyHYB8gm00MczSxzdTDgEY5rm5PFjlX9nRx+VLE9dFFs/E0FW0Oje3fzU4Lg2Zgwd1U+K+A6illdc7EdB3c+nH0T4lvmq/a+MHRu7Cq1RyNOCHc14GTBLG6Z72LNHKrR0l7mmJxLuQXPOJawySvY1w08lLm8+8xaWS4yN1DVNG2Quc52SfJY0rNb1RVRQmeqLtOQN9SjuKX+6W2XoSMbK6ClbA0uACoHHs2qERs3LnAY+K2xq5I58uosuvBUJpbZa9Q/voS0n7fwVvG+FVLtHJbOH7TocY5Wxg7HlsEcPcWOq6r3Ks+n9V56r0ZRPGZbEklBKxlRQgKQeazlYyigMHnzQ4+awTusEooAcklBKDyRQGEHksZWCUAYJSSUOPmk5QAEpOUFYygDof5RT3M9mVUGnAfUwNcPLUD94CheCHZ4cof8pqd/lNz9j7PqRunPa3OJmc/R/RyO/D7VHcCO1cO0P8AlBGXw3h2y2MOUvK0xnktqlIGBSSUOOyQTkc06ACsEpJKzHHJO9scYJJO3gE0m+hNiT4LZBRS1D2gjSwnd58PJTUFtpaOMPmkBkxzJ2Ch7rPPA10lDEZQNyS7Bx5bLohh9ZlKb6RLR0dDT/3bJHPB+m4KIutRNSQysiIkjd3iH90j0UNBxbO3YxO1tO7C7cJ7TXenvRcypaGAbBh+8rrj8pUjOpeirRxPH2PZuflwGkNzuSei2cV0fvlrZNHh7ogNWOvmqnd6N9qre0Y7uk/TxlWOy3ZtTAIpTqBBa4Eq07VMjpkFw5W/7RBO2huACnXF7S2eGrZuWkZwoe4RPsV8c3kwnLfMZU9cHtuFqyO84DmVmnTouiSobi6ppYKhpOW4B8lOwVsdQxpAGT57hUbhWtDWOp5DnfGDzUyZX0FSW5xG7dpVqVCkrLJnJwOeN/uSH40kjmAeQ8iU0pK5k7emfPmnXdcS4gfxWqnaMnGhvLhuru+W+3RUjjX2e019BqaQCCtAyXNGzvIq+uYHOJxtzKS/GNLPpPPVZZMamqZpiyODuJ5xnkunDVaaW4RPa5p2PQ+eVN0V8hqGAueMq3e0gUbqmktLIGT1NQ7WW4+i0cz8VWKjhygt8kMbqQtdKcBzJCeW+D/PRePk4lSpM9bHzaX5IbXC6RNiOl4OxVMioZeJ+JqGhhbqHaBzvANByVdrrwjRsljfJVS0tPglzHOBeT0xtsoB1dTcGMlntjTLX1ILO0e7VoHkMD59VWHjShK2Rm5UZxpFr49la50FK3fQ3Tkeio89JKJGVVOf0sfPf6QT6jv0vFNI6pqAG1dK7E7W8nA8nY6DoU5hhy8ZXS+zhN1t4jqWNY7tXFvJzHFWGDiKlmaNYc1x6DdQNTZ9cRmhaNX1mfreajIJ3wPLXklpOCCpcQL+2sgcNQkAz4pQlY7cPafiqzSvaWgtcdKmKJzS3plL5AekoJ2UE+uqaa4vpy46Tgt26KQkrhBLGyUHEg2cPFS4sB5lYcUjVss5GFIgJWCUklYJ2QFgSEklYJWCUgsMoWM7LGUDL5+UrD2vs5a/SHCKvhfqOO7s5uftx8VC8Auzw3Q/5QVn/KGja/2XV7nDJZNTubvyPatH3Eqqez0//jVCP/LCMnhvHsuER7q2ArREegW4HZCQNg4+CQSPBK5rZSUklbUNhj5nmTyaE0rdIm6VsxSUclbKGMGANy79UKdbDFQQ4hjDnAYyOZKcxUcdHC2KMEAfMrDjp2GBt4LvxYUu+znlNsrVwq5IqkPfpJzgsz+CzHX08o0PAadjgdOXRTFXTx1TSJGRv6YIxhVi4Wa4UdT2tKWzU/WMHvM9D4LRqvCUx1X8P0V6YTG4RzDdr2qj3CGtsFYKerbj/lyN2D1YW3N0E7RvA9v1SMKSmlouJaE0daGlx+i/G7D4hS4fStdlKVdlZdWNulE6N577RkFRduuD6SfS4nGeaTPS1FhuRpKk4aD3Hj6w6FM6oaasODvpcyojKnspqyzcRwi7WhtXHh01PvnxCZ8OXL3inMJJO2MndZ98/N0dLJj+ySnsp89A4Y1fA/coYNdZb0+EbMLtiPDKJvdhFeDyFz6O6SsaTs7IB9VbI6iO4UYH1xg+hVVvBDZYatvXuuT6z1JjcWuPceN904uwaJqklkhwH7P64UzTVgIAIUTRPbWRPDj+kiJa7HUdCllksLw5uSB1VJ1olosLHtI25FN6+4U1noai41j2xQQMc9ziegTSKow3D3AM8dhgLk3tV43N7qqaw0DnC2skzPKP+K/oM+A5+o8k3KkSo7ISXiKsvN9qLzIx0bpHnRnmxg5D5KajuNQxra+olHajPZDoP2lDUtC6Noa1oLgQ0fgnVaRK8QjGluzceHRZ/MW/p9jbfSNNZXVE5Mk5L3Z2JChG2+aoqaapny8TOIA8B0VglpQ6EtP1hpJI5fzlTlxsoZQUxa3+6cMYCGv0OP8AZzq3h1i4pqG6e44DLMbOaeYVqbEA8OjJfC49x3PPkfAqM4qphTcQ007RgSM0kpxbJpo6xzWHVE895jtwf4KHGyrosVKAMDJ+KYX+wFzXVdK0+L2N3x5hPJrrSW4s7WOZpd1bhymbbe7fM0dx0mcAgNI6euFKg+gckUS2zPicBnU09ArFSvMbmvaNj0WjiKotbqt0cNDLT1RcCX5Gl3wHVLtw1MDS7ZCVaHYcQxOjNPWs2w7DvRIml7QQuyckjkpG5U3vNqli54bsSoC2SmYx6zlsQy71RWxXon6mV0co27mAClh4eMg5CU2LWzS4ZcfFNntNDO2JxwJM49cf6KJw9F9Jm7I6hBI0rBKwSdKxGYJWM7LBKSSgDOrZYysZWNKVAdo9rdvbc/ZrxFA4bMonz4wP+HiT/wCK5r7PHZ4aov8ALC7fdKFlyttXQybsqYXwu36OaQd/iuHezxj4uHaSOQYewaXDOcEFOfhvDtlyjOy2tITeJOGjZIGD9+StNjovdaUSPAEkm5Pkq/baf3quhjIyM5Vzdpxp+qOS6uPC9sxyS8GcucudgjBATKSSLJDzjzKkX4ORseu6ZVdK2pa5h2yOnRdm/DKhp2TZGl8cmU3kbVRHLCHDc4+CamjrLVl0WKiLP0c95ZjvFNLKGzaopMHIfkdR80doKpjO4e43AGGuhETztkjr4gqp3Wkq7BO2aOV0tPnZx3wr3PFHWsLSGyjx6hVK6xVFqY6J7HVNC7ZzXc2//SzlcdlUmhtPLFxVRe6uA98ibqheebupaVU5pDhodqEjDhwI65Tiqc+2TMraGXXC1weDndh8CnPEVPHU+73mkGIatoLgDyf1HzUzqW0OLa0x7VQCr4flY4kAsxlQclQbrY6K5kjtox2E3m5u2fkFYqd/a2Kobuf0Rxtz2VS4LYZrbcbe7cyDtWZ/WCjwr0moJBW20tcdwDjKRbqoxS6HnOk8yU1s0xje6JxAA25LfUsEVSdJIDkoyoGWGlr/AHWvikLgI5f0bz9x+atbS0w9mWNPe3PlpOy5+P7TROY4jXjGfMZwnlZxe/8Ao/FTRvb78/VC4dWeL/ly81r2Sive0XjCSSpfYrTIWxh2meVpwSerR+JTCn4Xfd7G8xxjWwDDx0d0+8LTXWX3WMSkZOckkc1Z+Fbk6ngNNG9ojfzyNx6fBTT6QNorNp7Spc2OQaKiBwbI07bjknfuBdL2jgdOwB+9O+KLe61XCG807MwPIE7QPjlPYoS6NpkadG/PcZJH8UNV2TaGb6IGNsfPUCM+qn7e9tyt/ZPwHsPZv8chRstL2coa5jmE8gRuntgAhuNRTvy3tWtkHrjSfuCI0+mMr/tPttBAy3z0jy5/aYO/1cKNs9MBpdpGR4Kb9o9MWU0T8HTrHwTWwRgtY7J3AO6iKp9ldjbiSnzDG7SchFk/QvZkd04CkeI2a2NA8RueqRTQEQNJbpyOgVp0yPDdxHZ/faIVcQPaQb5H1goez1YdgOwCDgq62nTV0vZkZcO47byVMu9sdba19RCMsD++0dPNPJHdoIPxlngYyaMgd7UAFS6eF1DdKimf3dU4cAf1cZH4qzWKtbK1ozz235lRXGNN7rXQ1bMAbE/d+KTSasLd0TdOGkhzjgN3+W6j+IatlLbIrq+PJ7Zuhg6tIIwtclxENAws7xnwwb8sqN41qsMoaBp1BrA5yJL8Q9Jpj2yMa9py0jIPiFkqMsVY2ekbET3otiPLopEriaopGDsUlZOyxkJDEnZJyVkrCAPTOfL4dFyaW1izXq40bW4YKl8rB0DXnUB8A5dZVK42pBHc4KoDaWPQ7Hi0/wACPknNas2iyJhzhbgVoidlbhkhSgkTfDEYfWvefqs+/ZWNw1qC4TGTUOxvgfep09SvRwL8DmyPY1myCTjbSm8kgHkPBPJfo5OMck0lijeSNOOowtaaFY1kna1xJH0vFM62iprjE4SMb5EbELF2ZPTxdpBHrIO++SFEsvYwGuaRJ1BKL/YUNqihuVqd2tDKZ4x/w3nfHkVqjvVHe4n0NaDBNnTpeMEfyVIC75bgj4cwmN2oKC+UxD2iOoG7HsOHA+qT6Gn6US60ktkrX09S3uv+hIfoTN8Ceh6IsEwqqOrs7jnA7an1cx0cPgnb6+SkkdZOIo+2idtFK5p7w9VXK2ObhW709cx5mpWuAEn7J6Hz54WKVf8Awpuy42LvW2eJ57zGkFVvg9nZ3JmjONZZ94/FWhpEFWZ4SDDUt1ZG/gq5w+zRdZ48d5kx+3dFBdiNPul2mjP0Q9w3+xP65uvS8DGCtN4pnOu9foHejeHjA6Ef/ac9oJ6IHJOfLkVHRRqpJiDvsCd0xucXYVzagNG53PJb26oiCB65Sax3awEnmPRCYmSdRCLhactG+OSgbLrjmMbdpIz1UhZ6/sz2TydBGMfyU2nb+b7w2VoPZvPe2Wl9NEV4WVs8V2t81DMNE2knSRzwE2jiPuYJcMxuDiPHO+PtTS/zG3OorvDns4Xgyjllh2P2ZUyxge7EJa6ORutpPUE5+4BXKpC6Zitq23OSKUM7MMOTv1CZROMd3pZDs05i1Z8eX2gfNPIxGyXQAD54Wi4QNNJK9g78feHqDkLKMFHopyvZq9pFMXWRs4GQHjdRPDjcxMwOg5qa4jnNdwTJI86sBuPmonhhgNPHtjbqUS1IaYX8apmR7ZPUJ3DTEUjT1TSvBmuTQcYHgFLaC2HSRsmSIs0xgrtB2Y8YSL7E2lvMZlaOxqWaHZ5ZWjWYZ2vHRw5p/wAYxdtbKerb9Jjgcq7tbF0yry00lguYaMimlOY3eHkpTiClbcLI6YN1GMah5jr9ic+6x8QWbsnEds0ZY7qHc1rsM5qKaWjqMh4Ba4H0UtVod7KXSufM2ClLiDHKAPT+Sm/EshqLy7Du6wBvyS3Mdb7y0u5QSOjePh3fsTStc6Wrc4kF73dPBQ3+NAux5a5Pc3Ml5NzgqzahjIPPdVyaPsqMYHNSVmrBUUYa76Uex9FhOJS6JAlJykl26wXbrIDJKMrWXBGrzQUenlEcU0RrLRIWjL4SJRjqBsfsJ+SlmuDmhzSHAjII5FDmNkaWOGQQQfPK0a1RqtHM4nLcHJvcpIrXcaikkkYwxuIALhy5tPyWj860rec8I/7gskNouHCR/wB5/wC38VOyDryVa4IrYar3vspo3hunVpOcc1Z3YIyvS4+4nNk7GzmlwO/nsm0mNORz5J1JnpyTWTS2TBPPvLZ9kIbvfuWuBwouutUFXktGH77hSVUzI54Ua+V0Ds5IZ4pNWOypXS2VNETIxzy0dMKNjuskWC8OGd+fgugdrFXsLCMnzCqfEHDD2a5qUAZ3x5dVO0NpMYVc9Deab3O5NGMd2Y82eG6rlzop6JklruH6aneMRy9MdMFbZXysc6OduMA5HnhPLfUCth/NFxGoEf2aU9P2CVMqe0EX4xfCkrprKKWZ2uWkd2Woncjm37E0scAHFVVGT+rJj4YUXQV01h41ZbJwRFWxHQ48i9p/gfsUpEXUnHlORkNnhew9OW6nsfo9lweKqhrh3ZWDZJbTCjqJad28bjqZlFdqj4jEmcFwwSSpO5wCSNkgxnA3ScbGmQMsRGcAYTOQYyMYHL7lKPjGggDPX0TGeMMGrHPzUNUOxg0OicdPQp5USirpRqxramkmc6gM42S6Z7hKA4DmkmJosMDBXWR1PO3JLSPVRvBNxLqGWgnce1oXmAebAMt+whSEUojY3kNW2+3RVqF35t4le4DEdS1uoZ+sM/h9y0boTLkzvvzgbrNRAXRyDfLgcDPl/qm1LLrc047qlnEY3Yd8g+SszIatAk4CLC0amNDT8CmPDY00TX5IDW8ipKsYRwjXxtIJY45281HWx/Y2cc8loxsoyLZcXoxSR+8XNxIOxU5URta1pwT+CjrJS63dq7O5UtXN0Ql2N/FNLQEHN3pgQc4PgpW6t944akaQdm5UbCO3k68+eFJ17mi1TxbjLDshdAQHDFb2bgxxyDkKUutGaOuZcqcdx5HaN8/FVS3SGLvAgaXfiugUcjKyj0EA629fROKtUQ3TOY8VRB17mazYVMYeD+0FEWhrZqkmTvOaMZPRWHiqlNPcqd/QPICg5JYLXWyukcGNO4AG5ysXpmg8uTCWBjDnx8k0t1YKOpdlwLNHeK1VNfNXjTC3soz+8VmhodUcgduMEbqZKwT8JF/E1tbk+9RfNaXcW2xvOrj+a45c4XUtyqIMkBshbz6Z2TXU4jmsaNPk7O7jK1DnVsSP6bWn/q2rjSzk+fySpBR7m9hvFLeJOBKWnlm7SstuaWbPPSM9mceGnAz4tK6CvK3sG4rZw3xwymqZCylujPdHZdhokJBjcR693/uK9Uq5KmEJWjgH5TvCVTFHR8XW90rGjFLWtjJA/wDLefjlv7i88GtqXc6mU+ryve9/slHxJZa20V8faUtZC6KQYycHqPAg4I9F5LrvZ/RWe71VrrWvFRTSFj8Hnj6wPgQiKso6d+SxSS/mO910jy8S1EcQyc6S1pJ/9wXaS/S9zHnGeRK597CLPT2bh+uip8hjqjUcnrpXRKiNr/IjqF3YlSMJ9mt/7W4TKoYZBscOadit7+1izjEg8zgrS6YD6THD4Z+0LajNaGkge7fJAPgo+thMoDNwBg5PxUhUzBwIBx8UzkDXbl4cfDKXhSImVwhziXDsch1TiiuMcw7OQeW6zWUUcn6RpGfJQlSZIZNLOY+kVG0PQriHh2OrYZof7zmCuZ3ShuEUhZLK+JzTlhHQ+S6lTXM0+GTEnPJaL1Z6a70wdG0GQjbA3USj6hnLrpdG3K2srpmf7Rtzg8+OQQdQ9Qp+81Dae82a4ADS54YSPBwKqvEVBcbXUyMfF32jGnkXsPMfJPvzky7cJUj2nMtM+NwPXun+AUxexstd8jMd3Y847ymGjtoBsD3ThQ15f2tRTP3OQFL0pJhaDz0nmrrYuyOli0vIPLH4KOq2EvOwwp+ZoDu8B9H5qIqm/SdpPL+KmUQTIeY7kgDfyTaPVqAPx2TyVmd8dSm+2ojO/Pmsq2XZIduTSbEbbqJvcTn00dYwgujIdn0Tnt8DGditBd2tNLDnIxt9yp9Ek9aJXTwsl1DJCsEe7cE/Lkqjwu8Ooi0jvM7vphWmF2pjdvids7qovRLNL2h9FdaUbnT2g88j+KrNDUSOpm07wQWjGFayWi5y5G0tI7n+y7/+lV44xUVpEXNp5jknNPsIsslrhLYGhvJb64u7Mg9M5yUWqnqJoMaAMnDSDssV9JUtlbF+jBd4uKajoPoi6Bv6RzdPTott0mAp5o9iNJ+C3st01FONUjDqG2x2Ufc6Spkm0GZjS/f6J/iitBZVaVxa1+x5q58NVQkpWaj9E4VVuNhqLWwE1TXat9mY/FSXDUE8bdHvAwd86T/FPHp0yZCePqcF0cgb9FwKpd/pGzVFNM5ozjAVt4xr3wkNkAkzt4KnVVQ6qlp4xnY6vkssiplReh7S29rY2uc4geAC1VtU+CN0dO3SMYLjzU3SU4kiBcNgFD3RoEzmsxgLNrRSZze70TBcJnPbqcTnPwTMUsIP0QrBxBTFsrJdiHbHHkofSFgy/oxHTQEbxtysGlh/5bUrOCtoLSECbJNrnNcHMdpc0gtcOh/+17B9lvGbONuEKSudI010I7CrbnJEjR9I+ow744Xj1X32N8df0K4rjFXN2Vrr8QVZd9FnPRIfDSSfgStpK0Z45U6PWa5R7beETJBHxRQxEywYjq2tH02fVf8AA7HyP7K6s1we0OaQQRkEHOfikzQxVEMkMzGvikaWPa7kWkYIPkRlZp0zpKZ7IWxf0KppmbvmfI55/aDsD7AFcThQPBfDbuEbZNahMZYm1Ej4SRv2bsEA+Y3U84A56Lvx7ic0uxtJEAC7w8E1dEW43O/inpHIdAm0ozlxWlkIZPYdWDuPMbJpJTxPe5sjBraRjon7n8jj4la6xjOzFS7njQ7HLyStIoiJqUxuDIHyNyOhyAPioyWjqYnOc1zJc+OxU1PFNG3W3L874PIKPdXCQFpGk43CTZSK7cZJIwWzRPiH6+Mj5ptDcjQuHYvMjD9LJyVYKiraQRKwOHLHNQ1dZaeuaZKV5il3PdPNQ78Ab3uhpOK7eXR4bOAS1/UH+SuaRdpa5amilboMmQ4ftEcwrZLPXWCrPbscG9XDkVG8VxQXOmbcINIkA72nqFm+7Q0vCSfWtqIKKQYw9jXbeSsNFITAN9y0hc44brXS2yBj36jHM9vPpqJA+Cv1smBYxp3wFcXYqJGbvvG+chRlSzJ9c8/ipJx7jSAAQSmFTse9nwVVYiGqI8tceqjntc07uPzUvOxvexkhRc4ydunPdZNUxp6NLn4acuz5ZSYJA2o3wA4YWt5A1DbosucO6fPkEA2SNiPYXCpj+pkP2Vxhp3sZEXDd41AndU23v7O5xkYPax6R5kFX6SsbV0rOyjI1nfUB3MYWcpSi1S0NJNWM6pp0ic844pGnyBG/2tCrnDrdTXSEZJPNWetf/YqnBIzE8b/4Sq/w5HqpGHbd2RldL2ZostvGju7jfmD/AD4rbcdL6qEgnPLda436CHaW95xwfUYWyZwc9riAS3PJPdB0NK0FxyGjY8jvlR1e1rp4XZ58/NP55tOrPI/zso6tlAbrDRlnLfxSdgRF6k94eAOg5LZYHgRuBG7R480zuE7YyMAZOyVb5DHBIWgAEb7qV3YENxZOJ5Q7O2r4KCskb6msklAy0HSMJ5xHVaHPfgYYDunHCMEbKNjhzILnZWT3IvpEpWyihpNLQS92ygpmdow6ziTGcFWTQK5+ns9QHVNLxb4IImPe/DnbABNxdEp7Kbcbeyqpnxu7jycglVF7HNcWuwCDghXuqp54JCSO0iP1lVL3TdhWuc0ANk7w9VzTVGlkWWEFKDdvouSjvuk7ftfvFQmKrJRH8c+BQhdJkemfYH7Qf6RWP+j9wna6421oEJOxmg5N9S3lt0056rq68c+yqWSL2jWF0cj2E1kbMtODpdkEehBIPiCvYoOZMHcYCykjpg7QFuVqdtz5LcNwtcvNbceb6IyxNDgeq0vG4ytx5pH1iuwwQymGl2Bv5LTVRmoxTk90jp4p04fpfmmp/wB5KlrZqMu3Jj5Eubs4KMuUDZmuezDXDfKfy/71U/4lHybxvzvsfvRWhEJPI5p0vOc7bhQzq2SkqSwOLTnPwU7cQNTtuYVWum9THn+dllJ1suKt0StZWUlwpy2cMDyOuN1SbtQy26R0tG8PhIOqLO3wVoujGtZBpaBlg5DyVSriY6ibQS3bpsuP/YbdNHbk4ihG7K5ZqsUlZPFghjpTI0HpnddJs9c17NiDjz6LlNf3boNO2QM49VdOHnERs3PJbwdnG/0Xgzgg4OxGRglNZ3anZDdiEmAktZv9X8EhxO+/1l0x6MpIa1Lz8D5qKqMtyTkYKk6vdo9FGVPX4KJLYIZVTRjUE17YAgHPzT6pHcKh5fpj1S6Bk5bZ/wDaNIC4AYft8ArjBOPot69eQXPreT+cKTf9b7wrlCTjmU0BJzvMlNPyJLHYAPLZR1hY8UkbG41AnBPgnUJJifk57rvuWq0bUwI2PaEfatCCabg5BcCNWcgJZdrYCNj6dFrfy9HJce8JJ3KaGMapuqQ7gM8hyURcpWNh0gnnyUxVf3o9Cq5cyd/VJ9AQsh7acknIBxuns9V2cHZsOB8kwHVbZ/7s/wCELEfpUuJn9s9lM0ZdPIG898dVarRROFPHTQ9xu3aO8PJVOs34kps9Gux5bK/WIfoGfBKPZT6HzzFbKNwYwasfMqvTUc1bMJ6kd0fRHgrBcQO1bsmlcMRHHktJEogJMMf2YAc1QV+tUdXE3QND2nIU/KN3JhWgFoOOpWE9oqJDcK+zq5cW3yntNHhjpcl8rh3YmDJLjgdOmeZwM7henqD2LcB0dDT00nD1DVPhibG6eaIGSUgAFzsdTzPmVW/ye4mGz3CfQ3tS4NL8d7GnOM+q64ea5qN0j//Z" alt="Portrait of Enrico Maria Dal Compare"></div>
      <div class="portrait-tag">From <b>Italy</b> · living in <b>Denmark</b><br>Computer nerd with project management skills</div>
    </div>
  </div>
</header>

<section id="about">
  <div class="wrap">
    <div class="sec-head">
      <span class="sec-num mono">01</span>
      <div><h2>About</h2></div>
    </div>
    <div class="about-grid">
      <div>
        <p>I'm a solutions architect with a Materials Science background who found a second home in the Salesforce platform. I work across global organizations and scale-ups, and I love agile projects where I can plan and ship predictable, valuable deliverables with a focus on user adoption.</p>
        <p>I treat <strong>planning and discovery phases</strong> as the levers that drive real change management. I'm most at home solving complex business and integration challenges — where inventiveness and cross-discipline thinking are what get you past cloud governor limits, adoption hurdles, and the technical debt that quietly blocks scale.</p>
        <p>Lately that means treating context as infrastructure: building structured, persistent knowledge so the work compounds instead of resetting every session.</p>
      </div>
      <div class="edu">
        <span class="eyebrow">Education</span>
        <div class="edu-item">
          <div class="deg">MSc Materials Science &amp; Engineering</div>
          <div class="meta">Università degli Studi di Padova · <span class="mono">2013–2016</span></div>
        </div>
        <div class="edu-item">
          <div class="deg">BSc Materials Science</div>
          <div class="meta">Università degli Studi di Padova · <span class="mono">2010–2013</span></div>
        </div>
        <div class="edu-item">
          <div class="deg">Project Management (specialized course)</div>
          <div class="meta">24 Ore Business School, Milan · <span class="mono">2021</span></div>
        </div>
        <div class="edu-item">
          <div class="deg">Languages</div>
          <div class="meta">Italian (native) · English (fluent) · French (scholastic) · Danish (A1)</div>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="experience">
  <div class="wrap">
    <div class="sec-head">
      <span class="sec-num mono">02</span>
      <div>
        <h2>Experience</h2>
        <p class="sec-sub">A decade of Salesforce delivery, from business analysis to engagement leadership.</p>
      </div>
    </div>
    <div class="xp">
      <div class="xp-item">
        <div class="xp-when"><div class="yr">2026 — Present</div><div class="loc">Copenhagen</div></div>
        <div>
          <div class="xp-role">Engagement Lead</div>
          <div class="xp-co"><b>Y4</b></div>
          <ul class="xp-list">
            <li>Lead client engagements end to end — detecting and removing <b>conversion bottlenecks</b> across the commercial engine.</li>
            <li>Focus on data and marketing automation, turning platform capability into measurable business outcomes.</li>
          </ul>
        </div>
      </div>
      <div class="xp-item">
        <div class="xp-when"><div class="yr">2021 — 2026</div><div class="loc">Copenhagen</div></div>
        <div>
          <div class="xp-role">Principal Consultant · Pre-Sales Lead</div>
          <div class="xp-co">One Nine <b>(form. Arpedio Consulting)</b></div>
          <ul class="xp-list">
            <li>Led the Marketing Cloud Account Engagement (Pardot) implementation in a multi-cloud global Salesforce project, leading two automation specialists.</li>
            <li>Led a <b>two-business-unit merge</b> into the main global Salesforce org.</li>
            <li>Designed a Sales Cloud solution for a $1B wholesale brokerage, mapping vendor-to-customer touchpoints.</li>
            <li>Led design of a business-process roster for a top Italian energy &amp; utility provider — a three-year program.</li>
            <li>Led an invoice-billing build on Sales Cloud + MuleSoft under a contractual go-live clause.</li>
          </ul>
        </div>
      </div>
      <div class="xp-item">
        <div class="xp-when"><div class="yr">2020 — 2021</div><div class="loc">Milan</div></div>
        <div>
          <div class="xp-role">Senior Consultant</div>
          <div class="xp-co">Engineering <b>(form. Be Consulting)</b></div>
          <ul class="xp-list">
            <li>Authored the full release-management process for an international banking group's Salesforce stack (Sales, Service, Marketing, Tableau CRM — multi-org), reviewed and approved by internal audit.</li>
            <li>Ran the release-governance team: <b>five siloed dev teams (25–50 devs)</b>, a hot-fix GITflow and a fast-changes GITflow presented to the governance board.</li>
            <li>Ran a health-check on a $1.3B satellite-comms group's org, establishing a long-term DevOps garrison on site.</li>
          </ul>
        </div>
      </div>
      <div class="xp-item">
        <div class="xp-when"><div class="yr">2018 — 2020</div><div class="loc">Milan</div></div>
        <div>
          <div class="xp-role">Lead Business Analyst</div>
          <div class="xp-co">NTT Data <b>(form. Everis)</b></div>
          <ul class="xp-list">
            <li>Led the CPQ-stack transformation for a Scandinavian structural-core-materials leader, integrating legacy MDS and ERP into Salesforce and <b>accelerating quoting by 50%</b>.</li>
            <li>Consulted across a Sales, Service, Marketing and Feedback Management program for an automotive manufacturer; in-house CPQ specialist.</li>
          </ul>
        </div>
      </div>
      <div class="xp-item">
        <div class="xp-when"><div class="yr">2017 — 2018</div><div class="loc">Milan</div></div>
        <div>
          <div class="xp-role">Business &amp; Integration Architecture Analyst</div>
          <div class="xp-co"><b>Accenture</b></div>
          <ul class="xp-list">
            <li>Managed application maintenance across a global IoT company's tech stack.</li>
            <li>In-house CPQ solution specialist.</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="work">
  <div class="wrap">
    <div class="sec-head">
      <span class="sec-num mono">03</span>
      <div>
        <h2>Selected work</h2>
        <p class="sec-sub">Engagements by scale and the problem each one set out to solve.</p>
      </div>
    </div>
    <div class="work-grid">
      <div class="work-card">
        <span class="turn">$360M turnover</span>
        <h3>Industrial automation</h3>
        <p>Owned the <b>Marketing Cloud Account Engagement</b> rollout in a multi-cloud global org, then led a two-business-unit merge into the main Salesforce instance.</p>
      </div>
      <div class="work-card">
        <span class="turn">$200M turnover</span>
        <h3>Scandinavian structural core materials</h3>
        <p>Led the <b>CPQ stack</b> transformation, integrating on-premise MDS and ERP into Salesforce — quoting <b>50% faster</b> and Salesforce ROI validated.</p>
      </div>
      <div class="work-card">
        <span class="turn">$19B turnover</span>
        <h3>International banking group</h3>
        <p>Authored the entire release-management process across a multi-org stack, audit-approved, governing <b>five dev teams</b> through hot-fix and fast-change GITflows.</p>
      </div>
      <div class="work-card">
        <span class="turn">$100M turnover</span>
        <h3>Energy &amp; utilities venture</h3>
        <p>Led business analysts designing a full process roster for a top Italian provider, plus an invoice-billing build on <b>Sales Cloud + MuleSoft</b> against a hard go-live clause.</p>
      </div>
      <div class="work-card">
        <span class="turn">$20M turnover</span>
        <h3>Automotive manufacturing</h3>
        <p>Implemented Sales Cloud phase 2 and migrated Account Engagement to Marketing Cloud Next; ran a Service Cloud discovery into a <b>2027 roadmap</b>.</p>
      </div>
      <div class="work-card">
        <span class="turn">Salesforce Partner Talents 2022</span>
        <h3>Pre-sales &amp; Net Zero Cloud</h3>
        <p>Selected for the 2022 Talents Program; presented a <b>Net Zero Cloud</b> proposal for a global retail &amp; cosmetics player to a C-level board.</p>
      </div>
    </div>
  </div>
</section>

<section id="certs" class="certs">
  <div class="wrap">
    <div class="sec-head">
      <span class="sec-num mono">04</span>
      <div>
        <h2>Certifications</h2>
        <p class="sec-sub">Ten Salesforce credentials across platform, data, sales, service and marketing.</p>
      </div>
    </div>
    <div class="cert-img">
      <img src="data:image/jpeg;base64,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" alt="Salesforce certification badges: Platform App Builder, Service Cloud Consultant, Sales Cloud Consultant, Data 360 Consultant, Marketing Cloud Account Engagement Consultant, Administrator, Platform Data Architect, Marketing Cloud Account Engagement Specialist, CPQ Administrator, and Net Zero Cloud accreditation.">
    </div>
    <div class="cert-extra">
      <span class="cert-pill">Platform App Builder</span>
      <span class="cert-pill">Service Cloud Consultant</span>
      <span class="cert-pill">Sales Cloud Consultant</span>
      <span class="cert-pill">Data 360 / Data Cloud Consultant</span>
      <span class="cert-pill">Marketing Cloud Account Engagement Consultant</span>
      <span class="cert-pill">Administrator</span>
      <span class="cert-pill">Platform Data Architect</span>
      <span class="cert-pill">MCAE Specialist</span>
      <span class="cert-pill">CPQ Administrator</span>
      <span class="cert-pill">Net Zero Cloud (Accredited)</span>
    </div>
  </div>
</section>

<section id="skills">
  <div class="wrap">
    <div class="sec-head">
      <span class="sec-num mono">05</span>
      <div><h2>How I work</h2></div>
    </div>
    <div class="skill-cols">
      <div class="skill-col">
        <span class="eyebrow">Delivery</span>
        <ul>
          <li>Agile / Hybrid Agile</li>
          <li>Project management</li>
          <li>Release management</li>
          <li>Salesforce DevOps</li>
          <li>Team lead</li>
        </ul>
      </div>
      <div class="skill-col">
        <span class="eyebrow">Platform</span>
        <ul>
          <li>Data architecture</li>
          <li>CPQ</li>
          <li>Marketing automation</li>
          <li>Data &amp; Marketing Cloud</li>
          <li>MuleSoft integration</li>
        </ul>
      </div>
      <div class="skill-col">
        <span class="eyebrow">Approach</span>
        <ul>
          <li>Design thinking</li>
          <li>Business analysis</li>
          <li>Pre-sales</li>
          <li>Digital transformation</li>
          <li>Client facing</li>
        </ul>
      </div>
      <div class="skill-col">
        <span class="eyebrow">Domains</span>
        <ul>
          <li>Energy &amp; utilities</li>
          <li>Financial services</li>
          <li>Automotive</li>
          <li>Industrial / IoT</li>
          <li>Scale-ups</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section id="contact" class="contact">
  <div class="wrap">
    <div class="sec-head">
      <span class="sec-num mono">06</span>
      <div><h2 style="font-size:inherit;font-weight:600">Contact</h2></div>
    </div>
    <div class="contact-grid">
      <div>
        <h2>Let's build a <em>community</em>.</h2>
        <p class="contact-sub">If you're untangling a commercial engine, mentoring into the Salesforce ecosystem, or just want to compare notes — reach out.</p>
      </div>
      <div class="contact-links">
        <a class="clink" href="mailto:enrico@y4now.com">
          <span><span class="lbl">Email</span><br><span class="val">enrico@y4now.com</span></span>
          <span class="arr">→</span>
        </a>
        <a class="clink" href="https://www.linkedin.com/in/enricodalcompare" target="_blank" rel="noopener">
          <span><span class="lbl">LinkedIn</span><br><span class="val">in/enricodalcompare</span></span>
          <span class="arr">↗</span>
        </a>
        <a class="clink" href="https://adplist.org" target="_blank" rel="noopener">
          <span><span class="lbl">Mentoring</span><br><span class="val">ADPList · Blue Road Academy</span></span>
          <span class="arr">↗</span>
        </a>
        <div class="clink" style="cursor:default">
          <span><span class="lbl">Location</span><br><span class="val">Copenhagen 2300, Denmark</span></span>
        </div>
      </div>
    </div>
  </div>
</section>

<footer>
  <div class="wrap foot-inner">
    <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEMAAAAxCAYAAACBIBS5AAABCGlDQ1BJQ0MgUHJvZmlsZQAAeJxjYGA8wQAELAYMDLl5JUVB7k4KEZFRCuwPGBiBEAwSk4sLGHADoKpv1yBqL+viUYcLcKakFicD6Q9ArFIEtBxopAiQLZIOYWuA2EkQtg2IXV5SUAJkB4DYRSFBzkB2CpCtkY7ETkJiJxcUgdT3ANk2uTmlyQh3M/Ck5oUGA2kOIJZhKGYIYnBncAL5H6IkfxEDg8VXBgbmCQixpJkMDNtbGRgkbiHEVBYwMPC3MDBsO48QQ4RJQWJRIliIBYiZ0tIYGD4tZ2DgjWRgEL7AwMAVDQsIHG5TALvNnSEfCNMZchhSgSKeDHkMyQx6QJYRgwGDIYMZAKbWPz9HbOBQAAABdklEQVR4nO2a23KDMAwFJab//8vuS9M5TQ1YF0sio33MBCzW0iEw4THGoEWYmVe/K0FSw6wO6fGzcxARHZITaBb1ZteGEBEd0pN7C7F2pmc9x9kiEVgvxHtjRGPiWURGTtzxKyN7XK6I6tw/nRElpFJOIP/GZPcuVMsJRJUZiKS4ijmBTGVUyI+MO9xpZ3gLqZoTyOWYeO1OZE5YajZnBjIrOjInrJt3KyMyPzJFEC12hnahCk/EEpbHZGeHWAPTS6QoM1YWZWZ+SmC+4xqgGrJzAhHLuCpA2hUVcgJRdcbsIjxEZItUjwkW8+ScQMyZoRFRKScQkwxNYdFPohJCH+Gtu7o7cFNvrVXG40WYjMjx0IoLkWEVoc2ms+POPv+SLvI0JCIfIWO1k/DCNWOY/mziyUuANo8+SoaVlgG0DKBlAC0DaBlAyu+MCm+4zP/p+nRaBtAygJYBtAygZQAtA2gZQMsAWgbQMnbx/tpt/JBZD9ZwV883l/j8avsXOoEAAAAASUVORK5CYII=" alt="Y4">
    <span class="fmono">© <span id="yr"></span> Enrico Maria Dal Compare</span>
    <span class="fmono">Salesforce Engagement Lead · Copenhagen</span>
  </div>
</footer>

<script>
  document.getElementById('yr').textContent = new Date().getFullYear();
  // scroll reveal
  var io = new IntersectionObserver(function(es){
    es.forEach(function(e){ if(e.isIntersecting){ e.target.classList.add('in'); io.unobserve(e.target);} });
  }, {threshold:.12});
  document.querySelectorAll('section .wrap > *, .xp-item, .work-card').forEach(function(el){
    el.classList.add('reveal'); io.observe(el);
  });
</script>
</body>
</html>
