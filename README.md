
<style>
@import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;700&family=Fira+Code:wght@400;500&display=swap');
*{box-sizing:border-box;margin:0;padding:0}
.rm{font-family:'Space Grotesk',sans-serif;background:#0d1117;color:#e6edf3;border-radius:16px;overflow:hidden;padding:0 0 2.5rem}
.hero{padding:2.5rem 2rem 2rem;border-bottom:1px solid #21262d}
.hero h1{font-size:28px;font-weight:700;color:#e6edf3;letter-spacing:-0.5px;margin-bottom:4px}
.hero h3{font-size:13px;color:#8b949e;font-family:'Fira Code',monospace;font-weight:400;margin-bottom:1rem}
.hero p{font-size:13px;color:#6e7681;max-width:480px;line-height:1.6}
.sec{padding:1.5rem 2rem 0}
.lbl{font-size:11px;font-family:'Fira Code',monospace;color:#6e7681;letter-spacing:1.2px;text-transform:uppercase;margin-bottom:.85rem;display:flex;align-items:center;gap:8px}
.lbl::after{content:'';flex:1;height:1px;background:#21262d}
.badges{display:flex;flex-wrap:wrap;gap:6px}
.badge{height:24px;border-radius:5px;display:flex;align-items:center;gap:5px;padding:0 9px;font-size:11px;font-weight:500;border:1px solid transparent;cursor:default;transition:transform .12s}
.badge:hover{transform:translateY(-1px)}
.bd{width:7px;height:7px;border-radius:50%}
.bpy{background:rgba(55,130,153,.18);color:#79c0ff;border-color:rgba(55,130,153,.3)}
.bjs{background:rgba(210,153,34,.18);color:#e3b341;border-color:rgba(210,153,34,.3)}
.bts{background:rgba(41,101,190,.18);color:#58a6ff;border-color:rgba(41,101,190,.3)}
.bda{background:rgba(1,117,194,.18);color:#58bdff;border-color:rgba(1,117,194,.3)}
.bnx{background:rgba(255,255,255,.07);color:#c9d1d9;border-color:rgba(255,255,255,.12)}
.bre{background:rgba(97,218,251,.1);color:#61dafb;border-color:rgba(97,218,251,.25)}
.btw{background:rgba(56,178,172,.13);color:#2dd4bf;border-color:rgba(56,178,172,.25)}
.bfl{background:rgba(2,86,155,.18);color:#58a6ff;border-color:rgba(2,86,155,.3)}
.blx{background:rgba(252,198,36,.13);color:#e3b341;border-color:rgba(252,198,36,.25)}
.bgit{background:rgba(240,80,51,.13);color:#ff7b72;border-color:rgba(240,80,51,.25)}
.bgd{background:rgba(71,140,191,.13);color:#79c0ff;border-color:rgba(71,140,191,.25)}
.bol{background:rgba(255,255,255,.07);color:#8b949e;border-color:rgba(255,255,255,.12)}
.projs{display:flex;flex-direction:column;gap:1px;border:1px solid #21262d;border-radius:10px;overflow:hidden}
.pc{background:#0d1117;padding:.9rem 1.1rem;transition:background .15s;cursor:pointer;text-decoration:none;display:block;border-bottom:1px solid #21262d}
.pc:last-child{border-bottom:none}
.pc:hover{background:#161b22}
.ph{display:flex;align-items:center;justify-content:space-between;margin-bottom:4px}
.pn{font-size:13px;font-weight:500;color:#58a6ff;font-family:'Fira Code',monospace}
.pt{font-size:10px;padding:2px 7px;border-radius:10px;font-family:'Fira Code',monospace}
.tpy{background:rgba(55,130,153,.2);color:#79c0ff}
.tgd{background:rgba(71,140,191,.2);color:#79c0ff}
.tts{background:rgba(41,101,190,.2);color:#79c0ff}
.pd{font-size:12px;color:#8b949e;line-height:1.5;margin-bottom:6px}
.pm{display:flex;align-items:center;gap:10px;font-size:11px;color:#6e7681;font-family:'Fira Code',monospace}
.ld{width:9px;height:9px;border-radius:50%;display:inline-block}
.sg{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.sc{background:#161b22;border:1px solid #21262d;border-radius:10px;padding:.9rem;text-align:center}
.sn{font-size:26px;font-weight:700;line-height:1;margin-bottom:3px}
.sl{font-size:11px;color:#6e7681;font-family:'Fira Code',monospace}
.bl{color:#58a6ff}.gr{color:#3fb950}.or{color:#ff7b72}.pu{color:#bc8cff}
.abar{display:flex;align-items:flex-end;gap:3px;height:36px;margin-top:.85rem}
.acol{flex:1;border-radius:2px 2px 0 0;background:#1f6feb;transition:opacity .15s}
.acol:hover{opacity:1!important}
.div{height:1px;background:#21262d;margin:1.5rem 2rem 0}
.cb{display:inline-flex;align-items:center;gap:6px;background:#21262d;border:1px solid #30363d;color:#c9d1d9;font-size:12px;font-family:'Space Grotesk',sans-serif;padding:5px 12px;border-radius:5px;cursor:pointer;text-decoration:none;transition:background .15s,border-color .15s}
.cb:hover{background:#30363d;border-color:#58a6ff;color:#58a6ff}
.trow{font-family:'Fira Code',monospace;font-size:13px;color:#8b949e;display:flex;align-items:center;gap:4px;margin-bottom:.85rem}
.cur{width:2px;height:14px;background:#58a6ff;animation:blink 1s step-end infinite;display:inline-block;vertical-align:middle}
@keyframes blink{0%,100%{opacity:1}50%{opacity:0}}
.sr-only{position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0,0,0,0)}
</style>

<div class="rm">
  <h2 class="sr-only">GitHub profile README preview for john200tim-hash</h2>

  <div class="hero">
    <h1>John Tim</h1>
    <h3>full-stack dev &middot; ai systems &middot; the occasional bad idea that works</h3>
    <p>Building high-performance web apps, cross-platform tools, and experimenting with local LLMs. Currently turning caffeine into code.</p>
  </div>

  <div class="sec">
    <div class="trow"><span id="typed"></span><span class="cur"></span></div>
  </div>

  <div class="sec">
    <div class="lbl">stack</div>
    <div class="badges">
      <div class="badge bpy"><span class="bd" style="background:#3776AB"></span>Python</div>
      <div class="badge bjs"><span class="bd" style="background:#F7DF1E"></span>JavaScript</div>
      <div class="badge bts"><span class="bd" style="background:#3178C6"></span>TypeScript</div>
      <div class="badge bda"><span class="bd" style="background:#0175C2"></span>Dart</div>
      <div class="badge bnx">Next.js</div>
      <div class="badge bre"><span class="bd" style="background:#61DAFB"></span>React</div>
      <div class="badge btw">Tailwind</div>
      <div class="badge bfl"><span class="bd" style="background:#02569B"></span>Flutter</div>
      <div class="badge bol">Ollama</div>
      <div class="badge blx"><span class="bd" style="background:#FCC624"></span>Linux</div>
      <div class="badge bgit"><span class="bd" style="background:#F05033"></span>Git</div>
      <div class="badge bgd"><span class="bd" style="background:#478CBF"></span>Godot</div>
    </div>
  </div>

  <div class="div"></div>

  <div class="sec">
    <div class="lbl">projects</div>
    <div class="projs">

      <a class="pc" href="https://github.com/john200tim-hash/KipsigisLLM" target="_blank">
        <div class="ph">
          <span class="pn">KipsigisLLM</span>
          <span class="pt tpy">Python &middot; MIT</span>
        </div>
        <p class="pd">Language model for Kipsigis — dataset prep, tokenizer training, weights config. Low-resource NLP the hard way.</p>
        <div class="pm"><span><span class="ld" style="background:#3572A5"></span> Python</span><span>updated 2 days ago</span></div>
      </a>

      <a class="pc" href="https://github.com/john200tim-hash/OllamaOrganizer" target="_blank">
        <div class="ph">
          <span class="pn">OllamaOrganizer</span>
          <span class="pt tpy">Python</span>
        </div>
        <p class="pd">Desktop organization via local LLMs. Your file system, but with a brain that actually works offline.</p>
        <div class="pm"><span><span class="ld" style="background:#3572A5"></span> Python</span><span>updated last week</span></div>
      </a>

      <a class="pc" href="https://github.com/john200tim-hash/Piduino" target="_blank">
        <div class="ph">
          <span class="pn">Piduino</span>
          <span class="pt tpy">Python</span>
        </div>
        <p class="pd">Python automation bridging Arduino and Raspberry Pi. Robots, sensors, and serial ports behaving themselves.</p>
        <div class="pm"><span><span class="ld" style="background:#3572A5"></span> Python</span><span>updated May</span></div>
      </a>

      <a class="pc" href="https://github.com/john200tim-hash/clinic-monorepo" target="_blank">
        <div class="ph">
          <span class="pn">clinic-monorepo</span>
          <span class="pt tts">TypeScript</span>
        </div>
        <p class="pd">Clinic management website. Monorepo architecture, clean TypeScript throughout.</p>
        <div class="pm"><span><span class="ld" style="background:#3178C6"></span> TypeScript</span><span>updated May</span></div>
      </a>

      <a class="pc" href="https://github.com/john200tim-hash/Senna" target="_blank">
        <div class="ph">
          <span class="pn">Senna</span>
          <span class="pt tgd">GDScript</span>
        </div>
        <p class="pd">A Godot project. Still in progress, still interesting.</p>
        <div class="pm"><span><span class="ld" style="background:#478CBF"></span> GDScript</span><span>updated 3 weeks ago</span></div>
      </a>

    </div>
  </div>

  <div class="div"></div>

  <div class="sec">
    <div class="lbl">stats</div>
    <div class="sg">
      <div class="sc"><div class="sn bl" id="cnum">0</div><div class="sl">commits this year</div></div>
      <div class="sc"><div class="sn gr">5</div><div class="sl">public repos</div></div>
      <div class="sc"><div class="sn or">3</div><div class="sl">languages</div></div>
      <div class="sc"><div class="sn pu">on</div><div class="sl">local llm infra</div></div>
    </div>
    <div style="background:#161b22;border:1px solid #21262d;border-radius:10px;padding:.9rem;margin-top:10px">
      <div style="font-size:11px;color:#6e7681;font-family:'Fira Code',monospace;margin-bottom:8px">contribution graph</div>
      <div class="abar" id="abar"></div>
    </div>
  </div>

  <div class="div"></div>

  <div class="sec">
    <div class="lbl">contact</div>
    <div style="display:flex;gap:8px;flex-wrap:wrap">
      <a class="cb" href="https://github.com/john200tim-hash" target="_blank">
        <i class="ti ti-brand-github" aria-hidden="true" style="font-size:15px"></i> GitHub
      </a>
      <a class="cb" href="mailto:john200tim@gmail.com">
        <i class="ti ti-mail" aria-hidden="true" style="font-size:15px"></i> john200tim@gmail.com
      </a>
      <button class="cb" onclick="sendPrompt('What should a full-stack AI developer focus on building in 2026?')">
        ask me anything ↗
      </button>
    </div>
  </div>

</div>

<script>
const phrases=["writing Python that barely passes review","training LLMs nobody asked for","turning Arduino into a problem","shipping Flutter apps that mostly work","running models locally because why not"];
let pi=0,ci=0,del=false;
const el=document.getElementById('typed');
function type(){
  const p=phrases[pi];
  if(!del){el.textContent=p.slice(0,++ci);if(ci===p.length){del=true;setTimeout(type,1600);return}}
  else{el.textContent=p.slice(0,--ci);if(ci===0){del=false;pi=(pi+1)%phrases.length}}
  setTimeout(type,del?35:65);
}
type();

let c=0;
const t=setInterval(()=>{c=Math.min(c+5,142);document.getElementById('cnum').textContent=c;if(c>=142)clearInterval(t)},25);

const b=document.getElementById('abar');
[22,38,15,55,42,78,35,88,50,68,28,92,47,60,20,84,45,70,33,86,48,65,40,76,30,90,44,62,25,80].forEach(h=>{
  const d=document.createElement('div');
  d.className='acol';
  d.style.height=h+'%';
  d.style.opacity=0.25+(h/100)*0.75;
  b.appendChild(d);
});
</script>
