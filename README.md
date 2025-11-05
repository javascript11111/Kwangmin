# Kwangmin
Portfolio
<h1 align="left">Kwangmin Cho PORTFOLIO</h1>
<h3 align="left">I am design researcher & industrial designer</h3>
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Kwangmin Cho — Portfolio</title>
  <meta name="description" content="Industrial Designer & Professor — Design Impact, AI-driven UX, Healthcare & Interaction Design." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Pretendard:wght@300;400;600;700&display=swap" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    :root { --bg: #0b0c10; --card:#111217; --muted:#a7b0ba; --brand:#60a5fa; }
    html{scroll-behavior:smooth}
    body{font-family: 'Pretendard', system-ui, -apple-system, Segoe UI, Roboto, "Noto Sans KR", sans-serif; background:var(--bg); color:#e6e9ee}
    .glass{background:linear-gradient(180deg, rgba(255,255,255,0.06), rgba(255,255,255,0.02)); backdrop-filter: blur(8px); border:1px solid rgba(255,255,255,0.08)}
  </style>
</head>
<body>
  <!-- Header -->
  <header class="sticky top-0 z-50 glass">
    <div class="max-w-6xl mx-auto px-6 py-4 flex items-center justify-between">
      <a href="#home" class="font-semibold tracking-tight">Kwangmin Cho</a>
      <nav class="flex gap-6 text-sm text-gray-300">
        <a href="#projects" class="hover:text-white">Projects</a>
        <a href="#case" class="hover:text-white">Case Studies</a>
        <a href="#papers" class="hover:text-white">Publications</a>
        <a href="#awards" class="hover:text-white">Awards</a>
        <a href="#contact" class="hover:text-white">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section id="home" class="max-w-6xl mx-auto px-6 pt-16 pb-12">
    <div class="grid md:grid-cols-2 gap-10 items-center">
      <div>
        <h1 class="text-4xl md:text-5xl font-semibold leading-tight">Industrial Designer & Professor<br><span class="text-[var(--brand)]">Design Impact</span> with AI & Healthcare</h1>
        <p class="mt-5 text-[var(--muted)]">Interactions that shape future design visions. Improving product UX processes and user experience across healthcare, robotics, and smart environments.</p>
        <div class="mt-6 flex gap-3">
          <a href="#projects" class="px-4 py-2 rounded-lg bg-[var(--brand)] text-black font-medium">View Projects</a>
          <a href="#contact" class="px-4 py-2 rounded-lg border border-gray-600">Get in touch</a>
        </div>
        <ul class="mt-6 text-sm text-[var(--muted)] list-disc list-inside">
          <li>Professor, KAIST Industrial Design</li>
          <li>10+ years in product/UX & interaction design</li>
          <li>Focus: Negative-pressure mobile clinics, pediatric play spaces, AI-driven UX</li>
        </ul>
      </div>
      <div class="rounded-2xl overflow-hidden border border-gray-800">
        <img src="https://images.unsplash.com/photo-1557804506-669a67965ba0?q=80&w=1600&auto=format&fit=crop" alt="Hero image" class="w-full h-full object-cover">
      </div>
    </div>
  </section>

  <!-- Projects Grid -->
  <section id="projects" class="max-w-6xl mx-auto px-6 py-14">
    <div class="flex items-end justify-between gap-6">
      <h2 class="text-2xl md:text-3xl font-semibold">Selected Projects</h2>
      <a href="#" class="text-sm text-[var(--brand)]">All projects →</a>
    </div>
    <div class="grid md:grid-cols-3 gap-6 mt-8">
      <!-- Card 1 -->
      <article class="glass rounded-2xl p-5 hover:translate-y-[-2px] transition">
        <img class="rounded-xl border border-gray-800" src="https://images.unsplash.com/photo-1581091014359-90d3cf3a3e30?q=80&w=1600&auto=format&fit=crop" alt="Project thumbnail">
        <h3 class="mt-4 font-semibold">Mobile Clinic Module (MCM)</h3>
        <p class="text-sm text-[var(--muted)] mt-1">Rapid-deploy negative pressure ward system; design for disaster response.</p>
        <ul class="mt-3 text-xs text-gray-400 space-y-1">
          <li>• Role: Lead Designer, Interaction & UX</li>
          <li>• Impact: Reduced setup time by 37% (pilot)</li>
          <li>• Tools: Figma, SolidWorks, Python</li>
        </ul>
      </article>
      <!-- Card 2 -->
      <article class="glass rounded-2xl p-5 hover:translate-y-[-2px] transition">
        <img class="rounded-xl border border-gray-800" src="https://images.unsplash.com/photo-1526256262350-7da7584cf5eb?q=80&w=1600&auto=format&fit=crop" alt="Project thumbnail">
        <h3 class="mt-4 font-semibold">Lumino Play Dome</h3>
        <p class="text-sm text-[var(--muted)] mt-1">Pediatric interactive play space for recovery and stress reduction.</p>
        <ul class="mt-3 text-xs text-gray-400 space-y-1">
          <li>• Role: Creative Direction, UX</li>
          <li>• Impact: +23% engagement in pilot ward</li>
          <li>• Tools: TouchDesigner, Arduino</li>
        </ul>
      </article>
      <!-- Card 3 -->
      <article class="glass rounded-2xl p-5 hover:translate-y-[-2px] transition">
        <img class="rounded-xl border border-gray-800" src="https://images.unsplash.com/photo-1493238792000-8113da705763?q=80&w=1600&auto=format&fit=crop" alt="Project thumbnail">
        <h3 class="mt-4 font-semibold">AI-driven UX for Hospital UI</h3>
        <p class="text-sm text-[var(--muted)] mt-1">Adaptive interface for emergency triage and resource allocation.</p>
        <ul class="mt-3 text-xs text-gray-400 space-y-1">
          <li>• Role: PI, UX Strategy</li>
          <li>• Impact: 15% faster task completion (lab)</li>
          <li>• Tools: Python, Figma, FastAPI</li>
        </ul>
      </article>
    </div>
  </section>

  <!-- Case Studies -->
  <section id="case" class="max-w-6xl mx-auto px-6 py-14">
    <h2 class="text-2xl md:text-3xl font-semibold">Case Studies</h2>
    <div class="mt-6 space-y-6">
      <details class="glass rounded-2xl p-5">
        <summary class="cursor-pointer font-medium">Converting Gymnasiums into Temporary Hospitals</summary>
        <div class="mt-3 text-[var(--muted)] text-sm leading-7">
          <p>Problem framing, service blueprint, user flows, hardware layout, and evaluation framework. Include methods, KPIs, before/after, and lessons learned.</p>
          <a class="text-[var(--brand)] text-sm" href="#">Read full PDF →</a>
        </div>
      </details>
      <details class="glass rounded-2xl p-5">
        <summary class="cursor-pointer font-medium">Privacy in Public Spaces – Design Guidelines</summary>
        <div class="mt-3 text-[var(--muted)] text-sm leading-7">
          <p>Observation protocol, taxonomy, design patterns, and prototype validations. Include downloadable guideline cards.</p>
          <a class="text-[var(--brand)] text-sm" href="#">View guideline cards →</a>
        </div>
      </details>
    </div>
  </section>

  <!-- Publications / Exhibitions -->
  <section id="papers" class="max-w-6xl mx-auto px-6 py-14">
    <h2 class="text-2xl md:text-3xl font-semibold">Publications & Exhibitions</h2>
    <ul class="mt-4 space-y-3 text-sm text-[var(--muted)]">
      <li>[2025] IASDR — Design Impact in Healthcare Environments</li>
      <li>[2024] DIS — Interactive Pillars for Pediatric Play (Honorable Mention)</li>
      <li>[2024] Gwangju Design Biennale — Lumino Dome Installation</li>
    </ul>
  </section>

  <!-- Awards -->
  <section id="awards" class="max-w-6xl mx-auto px-6 py-14">
    <h2 class="text-2xl md:text-3xl font-semibold">Selected Awards</h2>
    <div class="mt-6 grid md:grid-cols-3 gap-6">
      <div class="glass rounded-2xl p-5">
        <h3 class="font-medium">iF Design Award</h3>
        <p class="text-sm text-[var(--muted)]">Healthcare & UX</p>
      </div>
      <div class="glass rounded-2xl p-5">
        <h3 class="font-medium">Red Dot</h3>
        <p class="text-sm text-[var(--muted)]">Product/Concept</p>
      </div>
      <div class="glass rounded-2xl p-5">
        <h3 class="font-medium">IDEA / Spark</h3>
        <p class="text-sm text-[var(--muted)]">Interaction & Social Impact</p>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="max-w-6xl mx-auto px-6 py-16">
    <div class="glass rounded-2xl p-8">
      <h2 class="text-2xl md:text-3xl font-semibold">Contact</h2>
      <p class="mt-2 text-[var(--muted)]">Open to collaborations in AI-based industrial design, healthcare UX, and interaction prototyping.</p>
      <div class="mt-5 grid md:grid-cols-3 gap-4 text-sm">
        <a class="block p-4 rounded-xl border border-gray-700 hover:bg-white/5" href="mailto:email@example.com">email@example.com</a>
        <a class="block p-4 rounded-xl border border-gray-700 hover:bg-white/5" href="https://github.com/your-username" target="_blank" rel="noopener">github.com/your-username</a>
        <a class="block p-4 rounded-xl border border-gray-700 hover:bg-white/5" href="#">LinkedIn</a>
      </div>
    </div>
    <p class="mt-8 text-center text-xs text-gray-500">© <span id="year"></span> Kwangmin Cho. All rights reserved.</p>
  </section>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
