<!doctype html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Business English Idioms — Lesson &amp; Practice</title>
<style>
  :root {
    font-family: Georgia, 'Times New Roman', serif;
    color: #1f2937;
    background: #0f172a;
  }
  * { box-sizing: border-box; }
  body { margin: 0; min-height: 100vh; display: flex; flex-direction: column; align-items: center; justify-content: center; padding: 24px; }
  .deck {
    width: 100%;
    max-width: 900px;
    background: #ffffff;
    border-radius: 16px;
    box-shadow: 0 20px 60px rgba(0,0,0,.45);
    overflow: hidden;
  }
  .progress-bar { height: 6px; background: #e2e8f0; }
  .progress-fill { height: 100%; background: linear-gradient(90deg, #2563eb, #7c3aed); transition: width .3s ease; }
  .slide {
    display: none;
    padding: 40px 48px 32px;
    min-height: 520px;
    flex-direction: column;
  }
  .slide.active { display: flex; }
  h1 { font-size: 34px; margin: 0 0 6px; color: #0f172a; }
  h2 { font-size: 26px; margin: 0 0 18px; color: #1d4ed8; border-bottom: 3px solid #dbeafe; padding-bottom: 8px; }
  h3 { font-size: 19px; margin: 18px 0 8px; color: #374151; }
  p, li { font-size: 17px; line-height: 1.55; }
  .kicker { text-transform: uppercase; letter-spacing: 2px; font-size: 12px; color: #6b7280; margin-bottom: 10px; font-family: Verdana, sans-serif; }
  .idiom-card {
    background: #f1f5f9;
    border-left: 5px solid #2563eb;
    border-radius: 8px;
    padding: 14px 18px;
    margin: 10px 0;
  }
  .idiom-card b { color: #1d4ed8; font-size: 18px; }
  .example { font-style: italic; color: #475569; margin-top: 6px; }
  .example u { text-decoration: none; background: #fef08a; padding: 0 3px; border-radius: 3px; }
  .navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 14px 20px;
    background: #0f172a;
    color: #e2e8f0;
    font-family: Verdana, sans-serif;
    font-size: 14px;
  }
  .navbar button {
    background: #2563eb;
    color: #fff;
    border: none;
    border-radius: 8px;
    padding: 10px 22px;
    font-size: 15px;
    cursor: pointer;
    transition: background .2s;
  }
  .navbar button:hover:not(:disabled) { background: #1d4ed8; }
  .navbar button:disabled { background: #334155; color: #64748b; cursor: default; }
  .match-item { display: flex; align-items: center; gap: 12px; margin: 14px 0; }
  .match-item select { font-size: 16px; padding: 6px 10px; border-radius: 6px; border: 1px solid #cbd5e1; font-family: inherit; flex: 1; }
  .feedback { font-weight: bold; }
  .ok { color: #16a34a; }
  .no { color: #dc2626; }
  .answer-hidden { display: none; margin-top: 12px; background: #ecfdf5; border-left: 5px solid #16a34a; padding: 12px 16px; border-radius: 8px; }
  .btn-show {
    margin-top: 14px;
    background: #7c3aed;
    color: #fff;
    border: none;
    border-radius: 8px;
    padding: 9px 18px;
    font-size: 15px;
    cursor: pointer;
  }
  .btn-show:hover { background: #6d28d9; }
  .gap { border-bottom: 2px solid #9ca3af; display: inline-block; min-width: 150px; text-align: center; color: #2563eb; font-weight: bold; }
  .bank {
    background: #eff6ff;
    border: 1px dashed #2563eb;
    border-radius: 8px;
    padding: 10px 16px;
    margin: 10px 0 18px;
    font-style: italic;
    color: #1e40af;
  }
  textarea {
    width: 100%;
    min-height: 90px;
    border: 1px solid #cbd5e1;
    border-radius: 8px;
    padding: 10px;
    font-family: inherit;
    font-size: 16px;
    resize: vertical;
  }
  .hint { font-size: 14px; color: #6b7280; }
  ol li { margin-bottom: 10px; }
</style>
</head>
<body>
<div class="deck">
  <div class="progress-bar"><div class="progress-fill" id="progress"></div></div>

  <!-- SLIDE 1: PRESENTATION -->
  <section class="slide active" id="s0">
    <div class="kicker">Vocabulary · Business English</div>
    <h1>Six Idioms for Business English</h1>
    <p>These common sayings appear constantly in meetings, emails and presentations. Study the meaning and example for each one — you will practise them in the next slides!</p>

    <div class="idiom-card"><b>1. Get the ball rolling</b><br>
      <span><i>Meaning:</i> to start a process, project or meeting.</span>
      <div class="example">Let's <u>get the ball rolling</u> on the marketing campaign before our competitors launch theirs.</div>
    </div>
    <div class="idiom-card"><b>2. Think outside the box</b><br>
      <span><i>Meaning:</i> to think creatively, beyond the usual or obvious ideas.</span>
      <div class="example">Our sales are falling, so we need to <u>think outside the box</u> and try a completely new strategy.</div>
    </div>
    <div class="idiom-card"><b>3. Back to the drawing board</b><br>
      <span><i>Meaning:</i> to start planning again because a plan or idea has failed.</span>
      <div class="example">The client rejected our proposal, so it's <u>back to the drawing board</u>.</div>
    </div>
    <div class="idiom-card"><b>4. Cut to the chase</b><br>
      <span><i>Meaning:</i> to skip the small talk and go directly to the main point.</span>
      <div class="example">I only have ten minutes for this call, so let's <u>cut to the chase</u>: what is your final price?</div>
    </div>
    <div class="idiom-card"><b>5. The bottom line</b><br>
      <span><i>Meaning:</i> the most important fact; the final result (originally: the final figure in accounts).</span>
      <div class="example">We can discuss details all day, but <u>the bottom line</u> is that we can't afford the rent increase.</div>
    </div>
    <div class="idiom-card"><b>6. Burn the midnight oil</b><br>
      <span><i>Meaning:</i> to work or study late into the night.</span>
      <div class="example">The team <u>burned the midnight oil</u> all week to finish the report before the deadline.</div>
    </div>
  </section>

  <!-- SLIDE 2: MATCHING -->
  <section class="slide" id="s1">
    <div class="kicker">Exercise 1 · Recognition</div>
    <h2>Match the idiom to its meaning</h2>
    <p>Choose the correct meaning for each idiom, then check your answers.</p>
    <div class="match-item" data-a="3">
      <b>a) Get the ball rolling</b>
      <select>
        <option value="">— choose —</option>
        <option value="1">to work late into the night</option>
        <option value="2">to skip small talk and reach the main point</option>
        <option value="3">to start a process or project</option>
        <option value="4">to start planning again after a failure</option>
      </select>
      <span class="feedback"></span>
    </div>
    <div class="match-item" data-a="6">
      <b>b) Burn the midnight oil</b>
      <select>
        <option value="">— choose —</option>
        <option value="5">the most important fact or final result</option>
        <option value="6">to work late into the night</option>
        <option value="7">to think creatively and unconventionally</option>
        <option value="8">to skip small talk and reach the main point</option>
      </select>
      <span class="feedback"></span>
    </div>
    <div class="match-item" data-a="7">
      <b>c) Think outside the box</b>
      <select>
        <option value="">— choose —</option>
        <option value="5">the most important fact or final result</option>
        <option value="6">to start a process or project</option>
        <option value="7">to think creatively and unconventionally</option>
        <option value="4">to start planning again after a failure</option>
      </select>
      <span class="feedback"></span>
    </div>
    <div class="match-item" data-a="4">
      <b>d) Back to the drawing board</b>
      <select>
        <option value="">— choose —</option>
        <option value="1">to start planning again after a failure</option>
        <option value="2">to think creatively and unconventionally</option>
        <option value="3">to start a process or project</option>
        <option value="4">to start planning again after a failure</option>
      </select>
      <span class="feedback"></span>
    </div>
    <div class="match-item" data-a="5">
      <b>e) The bottom line</b>
      <select>
        <option value="">— choose —</option>
        <option value="5">the most important fact or final result</option>
        <option value="6">to work late into the night</option>
        <option value="2">to skip small talk and reach the main point</option>
        <option value="3">to start a process or project</option>
      </select>
      <span class="feedback"></span>
    </div>
    <div class="match-item" data-a="2">
      <b>f) Cut to the chase</b>
      <select>
        <option value="">— choose —</option>
        <option value="1">to start a process or project</option>
        <option value="2">to skip small talk and reach the main point</option>
        <option value="5">the most important fact or final result</option>
        <option value="7">to think creatively and unconventionally</option>
      </select>
      <span class="feedback"></span>
    </div>
    <button class="btn-show" onclick="checkMatch()">Check answers</button>
  </section>

  <!-- SLIDE 3: FILL IN THE BLANKS -->
  <section class="slide" id="s2">
    <div class="kicker">Exercise 2 · Controlled practice</div>
    <h2>Complete the sentences</h2>
    <p>Fill each gap with the correct idiom. Think about meaning and grammar (you may need to change the verb form).</p>
    <div class="bank">Word bank: <b>get the ball rolling · think outside the box · back to the drawing board · cut to the chase · the bottom line · burn the midnight oil</b></div>
    <ol>
      <li>I don't have much time, so please _________ and tell me how much the project costs.</li>
      <li>Our first design failed the safety test, so it's _________ for the engineering team.</li>
      <li>Everyone is here and the agenda is ready — let's _________ with the first item.</li>
      <li>_________ is that we need to increase revenue by 10% this year.</li>
      <li>The developers _________ for three nights to release the app on time.</li>
      <li>If traditional advertising isn't working, maybe we should _________ and partner with influencers.</li>
    </ol>
    <button class="btn-show" onclick="reveal('a3')">Show answers</button>
    <div class="answer-hidden" id="a3">
      1. cut to the chase · 2. back to the drawing board · 3. get the ball rolling · 4. The bottom line · 5. burned the midnight oil · 6. think outside the box
    </div>
  </section>

  <!-- SLIDE 4: CHOOSE THE RIGHT IDIOM (context) -->
  <section class="slide" id="s3">
    <div class="kicker">Exercise 3 · Understanding in context</div>
    <h2>Which idiom is the speaker using?</h2>
    <p>Read each mini-dialogue and decide which idiom best describes the situation.</p>
    <ol>
      <li><i>"Great pitch, but the investors said no. Let's redesign the whole offer from the beginning."</i><br>
        → The team is going <span class="gap" data-a="back to the drawing board" onclick="fill(this)"></span></li>
      <li><i>"Okay everyone, the quarter starts today. Let's begin the new sales plan right now."</i><br>
        → The manager wants to <span class="gap" data-a="get the ball rolling" onclick="fill(this)"></span></li>
      <li><i>"Forget the slides about our history — what discount can you actually give us?"</i><br>
        → The buyer asked them to <span class="gap" data-a="cut to the chase" onclick="fill(this)"></span></li>
      <li><i>"We stayed in the office until 2 a.m. every night this week to finish the audit."</i><br>
        → The accountants <span class="gap" data-a="burned the midnight oil" onclick="fill(this)"></span></li>
      <li><i>"What really matters is that the project is losing money. Everything else is detail."</i><br>
        → The losing money is <span class="gap" data-a="the bottom line" onclick="fill(this)"></span></li>
      <li><i>"No one has a budget for ads... what if we organised a free street event instead?"</i><br>
        → She is trying to <span class="gap" data-a="think outside the box" onclick="fill(this)"></span></li>
    </ol>
    <p class="hint">💡 Click on a gap to reveal the answer.</p>
  </section>

  <!-- SLIDE 5: GUIDED PRODUCTION -->
  <section class="slide" id="s4">
    <div class="kicker">Exercise 4 · Guided production</div>
    <h2>Finish the sentences in your own words</h2>
    <p>Complete each sentence so it makes sense in a real business situation. Say your answers out loud, or write them in the boxes.</p>
    <h3>1. To get the ball rolling on our new project, first we need to…</h3>
    <textarea placeholder="Write your sentence here…"></textarea>
    <h3>2. The last time my team had to burn the midnight oil was when…</h3>
    <textarea placeholder="Write your sentence here…"></textarea>
    <h3>3. If our manager tells us to think outside the box, I would suggest…</h3>
    <textarea placeholder="Write your sentence here…"></textarea>
    <h3>4. The bottom line for me when choosing a job is…</h3>
    <textarea placeholder="Write your sentence here…"></textarea>
  </section>

  <!-- SLIDE 6: OPEN PRODUCTION (role play) -->
  <section class="slide" id="s5">
    <div class="kicker">Exercise 5 · Open practice</div>
    <h2>Role play: the crisis meeting</h2>
    <p><b>Scenario:</b> You are a manager at a small company. Your biggest client has just cancelled their contract, and your team must find a solution today.</p>
    <p>Prepare and perform a short speech to your team (1–2 minutes). Your goal is to use <b>at least four</b> of the six idioms.</p>
    <h3>Guiding questions</h3>
    <ul>
      <li>How will you <b>cut to the chase</b> and start the meeting with bad news?</li>
      <li>What is <b>the bottom line</b> — what will happen if you don't find a solution?</li>
      <li>Should some plans go <b>back to the drawing board</b>? Which ones?</li>
      <li>What creative idea will you ask the team for — how will you tell them to <b>think outside the box</b>?</li>
      <li>Who will need to <b>burn the midnight oil</b> this week, and why?</li>
      <li>What is the very first action you will take to <b>get the ball rolling</b>?</li>
    </ul>
    <textarea placeholder="Write your speech or notes here…"></textarea>
  </section>

  <!-- SLIDE 7: OPEN PRODUCTION (free writing) -->
  <section class="slide" id="s6">
    <div class="kicker">Exercise 6 · Free production</div>
    <h2>Write your own business story</h2>
    <p>Write a short paragraph (5–8 sentences) about a company — real or imaginary — that faces a problem and solves it.</p>
    <ul>
      <li>Use <b>as many of the six idioms as you can</b> (aim for all six!).</li>
      <li>Give the company a name and describe the problem clearly.</li>
      <li>Finish with a positive result.</li>
    </ul>
    <h3>Example opening</h3>
    <p class="example">"When Pixel Cafe lost half its customers to a new competitor, the owner knew it was time to think outside the box…"</p>
    <textarea style="min-height: 160px;" placeholder="Write your story here…"></textarea>
    <h3>Self-check</h3>
    <p class="hint">☐ Did you use the idioms in the correct form? (e.g. "got the ball rolling", "burned the midnight oil") ☐ Is each idiom used in a logical situation? ☐ Did you use at least four different idioms?</p>
  </section>

  <div class="navbar">
    <button id="prevBtn" onclick="go(-1)">← Previous</button>
    <span id="counter">Slide 1 / 7</span>
    <button id="nextBtn" onclick="go(1)">Next →</button>
  </div>
</div>

<script>
  const total = 7;
  let idx = 0;

  function render() {
    document.querySelectorAll('.slide').forEach((s, i) => s.classList.toggle('active', i === idx));
    document.getElementById('counter').textContent = 'Slide ' + (idx + 1) + ' / ' + total;
    document.getElementById('progress').style.width = ((idx + 1) / total * 100) + '%';
    document.getElementById('prevBtn').disabled = (idx === 0);
    document.getElementById('nextBtn').disabled = (idx === total - 1);
  }

  function go(d) {
    const n = idx + d;
    if (n < 0 || n >= total) return;
    idx = n;
    render();
  }

  function reveal(id) {
    const el = document.getElementById(id);
    el.style.display = (el.style.display === 'block') ? 'none' : 'block';
  }

  function fill(span) {
    span.textContent = span.dataset.a;
    span.style.background = '#fef08a';
  }

  function checkMatch() {
    document.querySelectorAll('.match-item').forEach(item => {
      const sel = item.querySelector('select');
      const fb = item.querySelector('.feedback');
      if (!sel.value) { fb.textContent = '✗'; fb.className = 'feedback no'; return; }
      const ok = sel.value === item.dataset.a;
      fb.textContent = ok ? '✓ Correct' : '✗ Try again';
      fb.className = 'feedback ' + (ok ? 'ok' : 'no');
    });
  }

  document.addEventListener('keydown', e => {
    if (e.key === 'ArrowRight') go(1);
    if (e.key === 'ArrowLeft') go(-1);
  });

  render();
</script>
</body>
</html>
