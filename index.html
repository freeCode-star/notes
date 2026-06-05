<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Deep Notes — IMAP & PhonePe</title>
<link href="https://fonts.googleapis.com/css2?family=Caveat:wght@400;500;600;700&family=Kalam:wght@300;400;700&family=Patrick+Hand&family=Permanent+Marker&display=swap" rel="stylesheet">
<style>
:root {
  --paper:#fdf8ef;
  --paper2:#fef9f0;
  --ink:#1a1208;
  --ink2:#2d1f0a;
  --faint:#c8b89a;
  --rule:#d4c4a8;
  --blue-ink:#1a3a6b;
  --red-ink:#8b1a1a;
  --green-ink:#1a5c2a;
  --purple-ink:#3d1a6b;
  --orange-ink:#8b4a00;
  --highlight:#fff176;
  --highlight2:#b2f5b2;
  --highlight3:#ffc2c2;
  --sticky1:#fffde7;
  --sticky2:#e8f5e9;
  --sticky3:#e3f2fd;
  --sticky4:#fce4ec;
  --tape:#e8dcc8;
  --margin-line:#e8a0a0;
}

*{margin:0;padding:0;box-sizing:border-box}

body {
  background: #c8bba8;
  background-image:
    radial-gradient(ellipse at 20% 20%, #b8ad9e 0%, transparent 60%),
    radial-gradient(ellipse at 80% 80%, #d4c9b8 0%, transparent 60%);
  min-height:100vh;
  font-family: 'Kalam', cursive;
  overflow-x:hidden;
}

/* ── Page tabs ── */
#tabs {
  display:flex;
  justify-content:center;
  gap:0;
  padding:24px 20px 0;
  position:sticky;
  top:0;
  z-index:100;
}
.tab {
  padding:10px 28px 8px;
  font-family:'Permanent Marker',cursive;
  font-size:14px;
  cursor:pointer;
  background:var(--paper);
  border:2px solid var(--faint);
  border-bottom:none;
  color:var(--ink2);
  opacity:.7;
  transform:translateY(4px);
  transition:all .2s;
  position:relative;
  border-radius:8px 8px 0 0;
}
.tab:first-child{border-right:1px solid var(--faint)}
.tab.active{opacity:1;transform:translateY(0);z-index:10;background:var(--paper);border-color:var(--faint)}
.tab span{display:block;font-size:10px;font-family:'Kalam',cursive;opacity:.6;margin-top:1px}

/* ── Notebook wrapper ── */
.notebook {
  max-width:960px;
  margin:0 auto;
  padding:0 16px 60px;
}

/* ── Page ── */
.page {
  display:none;
  background:var(--paper);
  border:1px solid var(--faint);
  box-shadow: 4px 4px 0 #b0a090, 8px 8px 0 #a09080, 12px 12px 0 rgba(0,0,0,.15);
  position:relative;
  padding:40px 52px 60px 90px;
  min-height:100vh;
  overflow:hidden;
}
.page.active{display:block}

/* Ruled lines */
.page::before {
  content:'';
  position:absolute;
  inset:0;
  background-image:
    repeating-linear-gradient(transparent, transparent 27px, var(--rule) 27px, var(--rule) 28px);
  background-position:0 52px;
  pointer-events:none;
}

/* Margin red line */
.page::after {
  content:'';
  position:absolute;
  left:72px;
  top:0;
  bottom:0;
  width:1.5px;
  background:var(--margin-line);
  pointer-events:none;
}

/* Spiral holes */
.holes {
  position:absolute;
  left:0;
  top:40px;
  bottom:40px;
  width:50px;
  display:flex;
  flex-direction:column;
  justify-content:space-around;
  align-items:center;
  pointer-events:none;
}
.hole {
  width:22px;
  height:22px;
  border-radius:50%;
  background:#c8bba8;
  border:2px solid #b0a090;
  box-shadow:inset 0 2px 4px rgba(0,0,0,.25);
}

/* ── Typography ── */
h1.page-title {
  font-family:'Permanent Marker',cursive;
  font-size:32px;
  color:var(--blue-ink);
  margin-bottom:6px;
  line-height:1.2;
  position:relative;
  z-index:1;
}
h1.page-title::after {
  content:'';
  display:block;
  height:3px;
  background:var(--blue-ink);
  margin-top:4px;
  width:100%;
  border-radius:2px;
}

.subtitle {
  font-family:'Patrick Hand',cursive;
  font-size:13px;
  color:var(--faint);
  margin-bottom:30px;
  margin-left:2px;
}

h2 {
  font-family:'Permanent Marker',cursive;
  font-size:22px;
  color:var(--red-ink);
  margin:32px 0 10px;
  position:relative;
  display:inline-block;
}
h2::after {
  content:'';
  position:absolute;
  bottom:-3px;
  left:0;
  width:100%;
  height:2px;
  background:var(--red-ink);
  border-radius:1px;
  opacity:.5;
}

h3 {
  font-family:'Caveat',cursive;
  font-size:19px;
  color:var(--blue-ink);
  margin:20px 0 6px;
  font-weight:700;
}

h4 {
  font-family:'Caveat',cursive;
  font-size:16px;
  color:var(--green-ink);
  margin:12px 0 4px;
  font-weight:600;
}

p, li {
  font-family:'Kalam',cursive;
  font-size:15px;
  color:var(--ink);
  line-height:1.75;
  position:relative;
  z-index:1;
}

ul {
  list-style:none;
  padding-left:20px;
  margin:6px 0;
}
ul li::before {
  content:'→';
  color:var(--blue-ink);
  font-family:'Permanent Marker',cursive;
  margin-right:8px;
  font-size:12px;
}

/* ── Highlight ── */
.hl  { background:var(--highlight); padding:0 3px; border-radius:2px; }
.hl2 { background:var(--highlight2); padding:0 3px; border-radius:2px; }
.hl3 { background:var(--highlight3); padding:0 3px; border-radius:2px; }

/* ── Box / callout ── */
.box {
  border:2px solid var(--blue-ink);
  border-radius:4px;
  padding:12px 16px;
  margin:16px 0;
  background:rgba(26,58,107,.04);
  position:relative;
  z-index:1;
}
.box.red   { border-color:var(--red-ink);   background:rgba(139,26,26,.04); }
.box.green { border-color:var(--green-ink); background:rgba(26,92,42,.04); }
.box.orange{ border-color:var(--orange-ink);background:rgba(139,74,0,.04); }
.box.purple{ border-color:var(--purple-ink);background:rgba(61,26,107,.04); }

.box-label {
  font-family:'Permanent Marker',cursive;
  font-size:12px;
  position:absolute;
  top:-10px;
  left:10px;
  background:var(--paper);
  padding:0 6px;
  color:var(--blue-ink);
}
.box.red .box-label    { color:var(--red-ink); }
.box.green .box-label  { color:var(--green-ink); }
.box.orange .box-label { color:var(--orange-ink); }
.box.purple .box-label { color:var(--purple-ink); }

/* ── Sticky notes ── */
.sticky {
  background:var(--sticky1);
  border:1px solid #e8d88a;
  padding:10px 14px;
  margin:12px 0;
  transform:rotate(-1.2deg);
  box-shadow:2px 3px 6px rgba(0,0,0,.12);
  position:relative;
  z-index:2;
  font-family:'Caveat',cursive;
  font-size:14px;
  color:var(--ink2);
}
.sticky::before {
  content:'';
  position:absolute;
  top:-8px;
  left:50%;
  transform:translateX(-50%);
  width:40px;
  height:16px;
  background:var(--tape);
  opacity:.8;
  border-radius:2px;
}
.sticky.green  { background:var(--sticky2); border-color:#8ec98e; transform:rotate(.8deg); }
.sticky.blue   { background:var(--sticky3); border-color:#8ab4d4; transform:rotate(-0.5deg); }
.sticky.pink   { background:var(--sticky4); border-color:#e8a0a0; transform:rotate(1.4deg); }

/* ── Code / command ── */
.cmd {
  font-family:'Patrick Hand',cursive;
  background:var(--ink);
  color:#a8e6a0;
  padding:2px 8px;
  border-radius:3px;
  font-size:13px;
  display:inline-block;
}
.code-block {
  background:#1a1208;
  color:#c8e6a0;
  font-family:'Patrick Hand',cursive;
  font-size:12.5px;
  padding:12px 16px;
  border-radius:6px;
  margin:10px 0;
  position:relative;
  z-index:1;
  line-height:1.8;
  border-left:3px solid var(--green-ink);
}
.code-block .comment { color:#8a9e78; }
.code-block .kw      { color:#e8a050; }
.code-block .str     { color:#a8d890; }
.code-block .num     { color:#8af0e8; }

/* ── Flow diagram ── */
.flow {
  display:flex;
  align-items:center;
  flex-wrap:wrap;
  gap:6px;
  margin:14px 0;
  position:relative;
  z-index:1;
}
.fnode {
  background:var(--blue-ink);
  color:#fff;
  font-family:'Caveat',cursive;
  font-size:13px;
  padding:6px 14px;
  border-radius:20px;
  font-weight:600;
  cursor:pointer;
  transition:transform .15s;
  position:relative;
}
.fnode:hover { transform:scale(1.06); }
.fnode.red    { background:var(--red-ink); }
.fnode.green  { background:var(--green-ink); }
.fnode.orange { background:var(--orange-ink); }
.fnode.purple { background:var(--purple-ink); }
.farrow {
  font-family:'Permanent Marker',cursive;
  font-size:18px;
  color:var(--faint);
}

/* ── Tooltip on click ── */
.fnode .tip {
  display:none;
  position:absolute;
  bottom:calc(100% + 8px);
  left:50%;
  transform:translateX(-50%);
  background:var(--ink);
  color:var(--paper);
  font-family:'Kalam',cursive;
  font-size:12px;
  padding:8px 12px;
  border-radius:6px;
  width:220px;
  text-align:left;
  line-height:1.5;
  z-index:100;
  box-shadow:0 4px 12px rgba(0,0,0,.4);
}
.fnode.open .tip { display:block; }
.fnode .tip::after {
  content:'';
  position:absolute;
  top:100%;
  left:50%;
  transform:translateX(-50%);
  border:6px solid transparent;
  border-top-color:var(--ink);
}

/* ── BIG vertical flow ── */
.vflow {
  margin:20px 0;
  position:relative;
  z-index:1;
  padding-left:30px;
}
.vflow-line {
  position:absolute;
  left:14px;
  top:0;
  bottom:0;
  width:2px;
  background:repeating-linear-gradient(to bottom,var(--blue-ink) 0 8px,transparent 8px 14px);
  border-radius:2px;
}
.vstep {
  display:flex;
  gap:14px;
  margin-bottom:18px;
  position:relative;
}
.vstep-num {
  width:28px;
  height:28px;
  border-radius:50%;
  background:var(--blue-ink);
  color:#fff;
  font-family:'Permanent Marker',cursive;
  font-size:13px;
  display:flex;
  align-items:center;
  justify-content:center;
  flex-shrink:0;
  margin-top:2px;
  cursor:pointer;
  transition:transform .15s, background .15s;
  position:relative;
  z-index:2;
}
.vstep-num:hover { transform:scale(1.15); }
.vstep-num.red    { background:var(--red-ink); }
.vstep-num.green  { background:var(--green-ink); }
.vstep-num.orange { background:var(--orange-ink); }
.vstep-num.purple { background:var(--purple-ink); }
.vstep-body { flex:1 }
.vstep-title {
  font-family:'Caveat',cursive;
  font-weight:700;
  font-size:17px;
  color:var(--blue-ink);
  cursor:pointer;
}
.vstep-title:hover { text-decoration:underline; }
.vstep-title.red    { color:var(--red-ink); }
.vstep-title.green  { color:var(--green-ink); }
.vstep-title.orange { color:var(--orange-ink); }
.vstep-title.purple { color:var(--purple-ink); }
.vstep-desc {
  font-size:14px;
  color:var(--ink2);
  margin-top:3px;
  font-family:'Kalam',cursive;
  line-height:1.6;
}
.vstep-detail {
  display:none;
  background:rgba(26,58,107,.05);
  border-left:3px solid var(--blue-ink);
  padding:8px 12px;
  margin-top:8px;
  border-radius:0 6px 6px 0;
  font-size:13.5px;
  line-height:1.65;
  font-family:'Kalam',cursive;
}
.vstep-detail.open { display:block; }
.vstep-detail.red    { border-color:var(--red-ink); }
.vstep-detail.green  { border-color:var(--green-ink); }
.vstep-detail.orange { border-color:var(--orange-ink); }
.vstep-detail.purple { border-color:var(--purple-ink); }

.click-hint {
  font-family:'Patrick Hand',cursive;
  font-size:11px;
  color:var(--faint);
  margin-bottom:16px;
  font-style:italic;
}

/* ── Two columns ── */
.cols {
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:20px;
  margin:16px 0;
  position:relative;
  z-index:1;
}
@media(max-width:700px){ .cols{grid-template-columns:1fr} }

/* ── Section divider ── */
.divider {
  text-align:center;
  margin:30px 0 20px;
  position:relative;
  z-index:1;
}
.divider::before {
  content:'';
  position:absolute;
  top:50%;
  left:0;
  right:0;
  height:1px;
  background:var(--rule);
}
.divider span {
  background:var(--paper);
  padding:0 12px;
  font-family:'Permanent Marker',cursive;
  font-size:13px;
  color:var(--faint);
  position:relative;
}

/* ── Comparison table ── */
.ctable {
  width:100%;
  border-collapse:collapse;
  font-family:'Kalam',cursive;
  font-size:13.5px;
  margin:12px 0;
  position:relative;
  z-index:1;
}
.ctable th {
  background:var(--blue-ink);
  color:#fff;
  padding:8px 10px;
  text-align:left;
  font-family:'Caveat',cursive;
  font-weight:700;
}
.ctable td {
  padding:7px 10px;
  border-bottom:1px dashed var(--rule);
  line-height:1.5;
}
.ctable tr:nth-child(even) td { background:rgba(0,0,0,.025); }

/* ── Page number ── */
.page-num {
  position:absolute;
  bottom:24px;
  right:40px;
  font-family:'Permanent Marker',cursive;
  font-size:18px;
  color:var(--faint);
}

/* ── Annotation / arrow doodle ── */
.annotate {
  font-family:'Caveat',cursive;
  font-size:13px;
  color:var(--red-ink);
  position:relative;
  display:inline-block;
  margin-left:8px;
  font-style:italic;
}

/* ── Big concept word ── */
.bigword {
  font-family:'Permanent Marker',cursive;
  font-size:48px;
  color:rgba(26,58,107,.06);
  position:absolute;
  right:40px;
  pointer-events:none;
  z-index:0;
  letter-spacing:-2px;
}

/* ── Important star ── */
.star::before {
  content:'★ ';
  color:var(--red-ink);
  font-size:14px;
}

/* ── Q&A box ── */
.qa {
  margin:10px 0;
  position:relative;
  z-index:1;
}
.qa-q {
  font-family:'Caveat',cursive;
  font-weight:700;
  font-size:16px;
  color:var(--purple-ink);
  cursor:pointer;
  display:flex;
  align-items:center;
  gap:8px;
}
.qa-q::before { content:'Q:'; font-family:'Permanent Marker',cursive; font-size:13px; color:var(--red-ink); flex-shrink:0; }
.qa-q .arrow { transition:transform .2s; font-size:14px; color:var(--faint); }
.qa-q.open .arrow { transform:rotate(90deg); }
.qa-a {
  display:none;
  padding:8px 14px;
  font-family:'Kalam',cursive;
  font-size:14px;
  line-height:1.7;
  color:var(--ink2);
  border-left:3px solid var(--purple-ink);
  margin-left:28px;
  margin-top:4px;
  background:rgba(61,26,107,.04);
  border-radius:0 6px 6px 0;
}
.qa-a.open { display:block; }
.qa-a::before { content:'A: '; font-family:'Permanent Marker',cursive; font-size:12px; color:var(--green-ink); }

/* ── Margin notes ── */
.margin-note {
  position:absolute;
  left:-62px;
  width:52px;
  font-family:'Caveat',cursive;
  font-size:10px;
  color:var(--red-ink);
  text-align:right;
  line-height:1.3;
  z-index:3;
}

/* ── PhonePe specific ── */
.phonepe-badge {
  display:inline-flex;
  align-items:center;
  gap:6px;
  background:#5f259f;
  color:#fff;
  padding:3px 12px;
  border-radius:20px;
  font-family:'Caveat',cursive;
  font-size:14px;
  font-weight:600;
}
.status-badge {
  display:inline-block;
  padding:2px 10px;
  border-radius:12px;
  font-family:'Caveat',cursive;
  font-size:13px;
  font-weight:600;
}
.s-pending  { background:#fff8e1; color:#f57f17; border:1px solid #f57f17; }
.s-success  { background:#e8f5e9; color:#1b5e20; border:1px solid #2e7d32; }
.s-failed   { background:#ffebee; color:#b71c1c; border:1px solid #c62828; }

/* ── Warning box ── */
.warn {
  background:rgba(139,74,0,.06);
  border:2px dashed var(--orange-ink);
  padding:10px 14px;
  border-radius:6px;
  margin:12px 0;
  font-family:'Kalam',cursive;
  font-size:14px;
  color:var(--orange-ink);
  position:relative;
  z-index:1;
}
.warn::before { content:'⚠ '; font-size:18px; }
</style>
</head>
<body>

<div id="tabs">
  <div class="tab active" onclick="showPage(1)">
    📡 Page 1
    <span>IMAP & Raw Sockets</span>
  </div>
  <div class="tab" onclick="showPage(2)">
    💳 Page 2
    <span>PhonePe Integration</span>
  </div>
</div>

<div class="notebook">

<!-- ═══════════════════════════════════════════════ PAGE 1 ══ -->
<div class="page active" id="page1">
  <div class="holes">
    <div class="hole"></div><div class="hole"></div><div class="hole"></div>
    <div class="hole"></div><div class="hole"></div><div class="hole"></div>
    <div class="hole"></div><div class="hole"></div>
  </div>
  <div class="bigword" style="top:80px">IMAP</div>
  <div class="bigword" style="top:420px;font-size:36px">SOCKET</div>

  <h1 class="page-title">How Emails Are Fetched</h1>
  <div class="subtitle">Raw TCP/IP · IMAP Protocol · SSL/TLS · Charset Encoding — explained for everyone</div>

  <!-- WHAT IS RAW SOCKET -->
  <h2>What is a "Raw Socket" / Low-Level Communication?</h2>

  <p>When our PHP code fetches emails, it does <span class="hl">NOT</span> use any helper library. Instead it talks <strong>directly to the mail server</strong> over the internet using what's called a <span class="hl2">TCP Socket</span> — think of it like picking up a telephone and dialling the mail server directly, speaking its exact language word by word.</p>

  <div class="sticky">
    <strong>Analogy:</strong> Imagine you want to ask your bank something. You <em>could</em> use the app (a library). Or you could call the bank's direct phone line, press the right buttons, speak in exactly the right way. That direct call = Raw Socket.
  </div>

  <div class="box">
    <div class="box-label">Technical Term</div>
    <p><span class="hl3">Raw Socket Communication</span> = opening a direct TCP connection to a server port and sending/receiving text commands yourself, without any library handling it for you. Also called <strong>"Low-Level Socket Programming"</strong> or <strong>"Wire-Protocol Implementation"</strong>.</p>
  </div>

  <p class="click-hint">👆 Click any step below to expand details</p>

  <!-- THE BIG FLOW -->
  <h2>The Full Journey: Your Code → Gmail's Server → Back</h2>

  <div class="vflow">
    <div class="vflow-line"></div>

    <div class="vstep">
      <div class="vstep-num" onclick="toggleStep(this)">1</div>
      <div class="vstep-body">
        <div class="vstep-title" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">DNS Lookup — Finding the Server's Address</div>
        <div class="vstep-desc">Your code says "I want to connect to <em>imap.gmail.com</em>"</div>
        <div class="vstep-detail">
          Before any connection, your server asks the internet's phone book — called <strong>DNS (Domain Name System)</strong> — "What is the IP address of imap.gmail.com?" DNS responds with something like <span class="cmd">142.250.76.101</span>. An IP address is like a house's street address number. Without this step, your computer has no idea WHERE on the internet Gmail lives.
          <br><br>
          <strong>Who does this?</strong> Your operating system, automatically, when you call <span class="cmd">stream_socket_client()</span>.
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num green" onclick="toggleStep(this)">2</div>
      <div class="vstep-body">
        <div class="vstep-title green" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">TCP Handshake — Establishing the Connection</div>
        <div class="vstep-desc">A 3-way handshake before ANY data flows</div>
        <div class="vstep-detail green">
          TCP (Transmission Control Protocol) is the <em>rulebook</em> for reliable internet communication. Before sending a single byte of email data, your code and Gmail's server do this dance:
          <br><br>
          <span class="cmd">Your PHP</span> → SYN → <span class="cmd">Gmail</span> <em>(hey, I want to talk)</em><br>
          <span class="cmd">Gmail</span> → SYN-ACK → <span class="cmd">Your PHP</span> <em>(ok I'm ready)</em><br>
          <span class="cmd">Your PHP</span> → ACK → <span class="cmd">Gmail</span> <em>(let's go!)</em><br><br>
          This guarantees both sides are alive and ready. Only then does data flow.
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num purple" onclick="toggleStep(this)">3</div>
      <div class="vstep-body">
        <div class="vstep-title purple" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">TLS Handshake — Encrypting the Tunnel</div>
        <div class="vstep-desc">SSL/TLS wraps everything in an encrypted tunnel</div>
        <div class="vstep-detail purple">
          <strong>SSL</strong> (Secure Sockets Layer) and <strong>TLS</strong> (Transport Layer Security) are encryption protocols. TLS is the modern successor to SSL. When you connect to port 993, Gmail immediately says "before we talk, let's encrypt everything."
          <br><br>
          <strong>How it works (simplified):</strong><br>
          1. Gmail sends its <em>Certificate</em> (like a digital ID card, proves it's really Gmail)<br>
          2. Your code and Gmail's server agree on an <em>encryption key</em> (using math called Diffie-Hellman)<br>
          3. ALL further communication is scrambled — nobody watching the network can read it<br><br>
          <strong>Why port 993?</strong> Port 993 = IMAP over SSL/TLS. Port 143 = plain IMAP (no encryption, dangerous). Ports are like apartment numbers in a building.
          <br><br>
          In code: <span class="cmd">ssl://imap.gmail.com:993</span> tells PHP to use TLS automatically.
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num red" onclick="toggleStep(this)">4</div>
      <div class="vstep-body">
        <div class="vstep-title red" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">IMAP Protocol — Speaking Gmail's Language</div>
        <div class="vstep-desc">The actual command/response text conversation</div>
        <div class="vstep-detail red">
          <strong>IMAP</strong> = Internet Message Access Protocol. It's a text-based protocol — meaning both sides literally send human-readable text lines (over the encrypted tunnel).
          <br><br>
          After connecting, Gmail sends:<br>
          <span class="cmd">* OK Gimap ready for requests</span><br><br>
          Then our PHP sends (LOGIN):<br>
          <span class="cmd">A0001 LOGIN "user@gmail.com" "password"</span><br><br>
          Gmail replies:<br>
          <span class="cmd">A0001 OK [CAPABILITY …] user@gmail.com logged in</span><br><br>
          Every command gets a unique tag (A0001, A0002…) so responses can be matched to commands. This is called a <strong>tagged command/response</strong> protocol.
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num orange" onclick="toggleStep(this)">5</div>
      <div class="vstep-body">
        <div class="vstep-title orange" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">SELECT Mailbox → SEARCH → Fetch UIDs</div>
        <div class="vstep-desc">Finding which emails to retrieve</div>
        <div class="vstep-detail orange">
          <strong>SELECT:</strong> <span class="cmd">A0002 SELECT "INBOX"</span> — Opens a mailbox. Server tells you how many messages exist.<br><br>
          <strong>UID SEARCH:</strong> <span class="cmd">A0003 UID SEARCH ALL</span> — Gets unique IDs of all messages. UIDs are permanent numbers assigned to each email (like a ticket number). They never change even if you move emails around.<br><br>
          <strong>Why UIDs instead of sequence numbers?</strong> Sequence numbers change when emails are deleted. UIDs are forever. If email #5 is deleted, the next one doesn't become #5 — it keeps its original UID.
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num green" onclick="toggleStep(this)">6</div>
      <div class="vstep-body">
        <div class="vstep-title green" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">Batch FETCH — Getting Headers & Bodies</div>
        <div class="vstep-desc">One command fetches many emails at once</div>
        <div class="vstep-detail green">
          <strong>The old way (php-imap library):</strong> One round-trip per email = 50 emails = 50 network calls = SLOW<br><br>
          <strong>Our way (raw IMAP batch fetch):</strong><br>
          <span class="cmd">A0004 UID FETCH 1001,1002,1003,1004,1005 (FLAGS RFC822.SIZE BODY.PEEK[HEADER.FIELDS (FROM TO SUBJECT DATE)])</span><br><br>
          One command → server sends all 5 emails' headers in one big response. This is called <strong>pipelining</strong> or <strong>batching</strong>. For a page of 25 emails, we make 1 network call instead of 25. That's ~25× faster!<br><br>
          <strong>BODY.PEEK</strong> = fetch body without marking as "Seen". Without PEEK, just reading the header would mark the email as read!
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num" onclick="toggleStep(this)">7</div>
      <div class="vstep-body">
        <div class="vstep-title" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">Parsing the IMAP Response (Literal Strings)</div>
        <div class="vstep-desc">The trickiest part — reading binary-length-prefixed data</div>
        <div class="vstep-detail">
          IMAP responses look like this:<br>
          <span class="cmd">* 3 FETCH (UID 1003 RFC822.SIZE 4821 BODY[HEADER] {312}</span><br>
          <span class="cmd">From: Priya Sharma &lt;priya@example.com&gt;</span><br>
          <span class="cmd">Subject: =?UTF-8?B?5L2g5aW9?=</span><br>
          <span class="cmd">)</span><br><br>
          The <span class="hl3">{312}</span> means "next 312 bytes are literal data." Our parser reads EXACTLY 312 bytes — no more, no less. This is called a <strong>Literal String</strong> in IMAP spec. It handles binary data, special characters, everything.
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num purple" onclick="toggleStep(this)">8</div>
      <div class="vstep-body">
        <div class="vstep-title purple" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">MIME Parsing — Cracking Open the Email</div>
        <div class="vstep-desc">Understanding the email's structure and parts</div>
        <div class="vstep-detail purple">
          Every email is a <strong>MIME</strong> (Multipurpose Internet Mail Extensions) document. Think of it like a Russian doll — parts inside parts.<br><br>
          A typical email structure:<br>
          <code>multipart/mixed</code> (the outer wrapper)<br>
          &nbsp;&nbsp;├── <code>multipart/alternative</code> (text OR html)<br>
          &nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── <code>text/plain</code> (fallback plain text)<br>
          &nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── <code>text/html</code> (the pretty version)<br>
          &nbsp;&nbsp;├── <code>image/png</code> (inline image with CID)<br>
          &nbsp;&nbsp;└── <code>application/pdf</code> (attachment)<br><br>
          Our <span class="hl2">MimeParser::parse()</span> recursively splits these parts using the <strong>boundary string</strong> that separates them.
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num red" onclick="toggleStep(this)">9</div>
      <div class="vstep-body">
        <div class="vstep-title red" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">Charset Decoding — Reading Every Language</div>
        <div class="vstep-desc">Converting 60+ encodings to UTF-8</div>
        <div class="vstep-detail red">
          Emails from different countries use different character encodings. A Japanese email might use <strong>Shift-JIS</strong>. Russian uses <strong>KOI8-R</strong>. Arabic uses <strong>Windows-1256</strong>. Chinese uses <strong>GB2312/GBK</strong>.<br><br>
          Headers encode non-ASCII characters using <strong>RFC 2047 encoded-words</strong>:<br>
          <span class="cmd">=?UTF-8?B?5L2g5aW9?=</span> = base64 encoded UTF-8<br>
          <span class="cmd">=?ISO-2022-JP?Q?=1B=24=42?=</span> = QP encoded Japanese<br><br>
          Our parser decodes these, then converts everything to UTF-8 using <strong>iconv()</strong> and <strong>mb_convert_encoding()</strong> with a 60-entry alias table covering every major language on earth.
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num orange" onclick="toggleStep(this)">10</div>
      <div class="vstep-body">
        <div class="vstep-title orange" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">Transfer Encoding — Decoding the Body</div>
        <div class="vstep-desc">Base64, Quoted-Printable, 7bit</div>
        <div class="vstep-detail orange">
          The body of an email can't always be sent as raw bytes. So it's encoded:<br><br>
          <strong>Base64:</strong> Converts binary data to A-Z,a-z,0-9,+,/ characters. Used for attachments and HTML. Decode with <span class="cmd">base64_decode()</span>.<br><br>
          <strong>Quoted-Printable (QP):</strong> For mostly-text content with occasional special chars. Special bytes become <code>=XX</code> hex notation. e.g. <code>=E2=82=AC</code> = € symbol.<br><br>
          <strong>7bit/8bit:</strong> Plain text, no encoding needed.
        </div>
      </div>
    </div>
  </div>

  <!-- SSL/TLS DEEP DIVE -->
  <h2>SSL & TLS — The Encryption Layer</h2>

  <div class="cols">
    <div class="box">
      <div class="box-label">What is SSL?</div>
      <p><strong>SSL</strong> = Secure Sockets Layer. Invented by Netscape in 1995. Now deprecated (insecure). But people still say "SSL" to mean TLS.</p>
    </div>
    <div class="box green">
      <div class="box-label">What is TLS?</div>
      <p><strong>TLS</strong> = Transport Layer Security. The modern, secure version of SSL. Current version is TLS 1.3 (2018). This is what actually runs.</p>
    </div>
  </div>

  <div class="sticky blue">
    <strong>Simple analogy:</strong> SSL/TLS is like putting your letter in a locked box before handing it to the postman. Even if someone steals it mid-journey, they can't open it without the key. Both the sender and receiver have keys.
  </div>

  <h3>How TLS Works (Step by Step)</h3>
  <div class="flow">
    <div class="fnode" onclick="toggleTip(this)">Client Hello
      <div class="tip">Your PHP says: "I support TLS 1.2/1.3, here are my supported cipher suites (encryption algorithms)"</div>
    </div>
    <div class="farrow">→</div>
    <div class="fnode red" onclick="toggleTip(this)">Server Hello
      <div class="tip">Gmail responds: "Let's use TLS 1.3 with AES-256-GCM. Here's my Certificate (proving I'm really Gmail)"</div>
    </div>
    <div class="farrow">→</div>
    <div class="fnode green" onclick="toggleTip(this)">Key Exchange
      <div class="tip">Using math (Elliptic Curve Diffie-Hellman), both sides compute the SAME secret key without ever sending it over the wire!</div>
    </div>
    <div class="farrow">→</div>
    <div class="fnode orange" onclick="toggleTip(this)">Encrypted Tunnel
      <div class="tip">Now ALL data — IMAP commands, emails, passwords — is AES-256 encrypted. Nobody can read it in transit.</div>
    </div>
  </div>

  <!-- IMAP COMMANDS REFERENCE -->
  <h2>IMAP Commands Cheat Sheet</h2>

  <table class="ctable">
    <tr><th>Command</th><th>What it does</th><th>Example</th></tr>
    <tr><td><span class="cmd">LOGIN</span></td><td>Authenticate with username + password</td><td><code>A001 LOGIN user pass</code></td></tr>
    <tr><td><span class="cmd">SELECT</span></td><td>Open a mailbox for read+write</td><td><code>A002 SELECT INBOX</code></td></tr>
    <tr><td><span class="cmd">EXAMINE</span></td><td>Open a mailbox read-only (safer)</td><td><code>A003 EXAMINE INBOX</code></td></tr>
    <tr><td><span class="cmd">UID SEARCH</span></td><td>Find emails matching criteria</td><td><code>A004 UID SEARCH UNSEEN</code></td></tr>
    <tr><td><span class="cmd">UID FETCH</span></td><td>Get headers/body of emails</td><td><code>A005 UID FETCH 1,2,3 (FLAGS RFC822.SIZE)</code></td></tr>
    <tr><td><span class="cmd">UID STORE</span></td><td>Change flags (read/starred)</td><td><code>A006 UID STORE 5 +FLAGS (\Seen)</code></td></tr>
    <tr><td><span class="cmd">UID COPY</span></td><td>Copy email to another folder</td><td><code>A007 UID COPY 5 "Trash"</code></td></tr>
    <tr><td><span class="cmd">EXPUNGE</span></td><td>Permanently delete \Deleted emails</td><td><code>A008 EXPUNGE</code></td></tr>
    <tr><td><span class="cmd">STATUS</span></td><td>Get folder counts without opening it</td><td><code>A009 STATUS INBOX (MESSAGES UNSEEN)</code></td></tr>
    <tr><td><span class="cmd">LIST</span></td><td>List all mailboxes/folders</td><td><code>A010 LIST "" "*"</code></td></tr>
    <tr><td><span class="cmd">LOGOUT</span></td><td>Gracefully disconnect</td><td><code>A011 LOGOUT</code></td></tr>
  </table>

  <!-- CHARSET DEEP DIVE -->
  <h2>International Mail — Charset Encoding</h2>

  <div class="cols">
    <div>
      <h3>What is a Charset?</h3>
      <p>A <span class="hl">charset</span> (character set) is a mapping from numbers to characters. The letter 'A' might be number 65 in ASCII. But '€' is number 8364 in Unicode. Different countries developed their own mappings before Unicode existed.</p>

      <div class="box purple">
        <div class="box-label">The Problem</div>
        <p>A Japanese email says: bytes [0x82,0xA0]. In Shift-JIS that's 'あ'. But if you read it as ISO-8859-1, it's garbage characters. Without knowing the charset, you can't read the email.</p>
      </div>
    </div>
    <div>
      <h3>Encodings by Country</h3>
      <ul>
        <li><strong>Japan:</strong> Shift-JIS, EUC-JP, ISO-2022-JP</li>
        <li><strong>China:</strong> GB2312, GBK, GB18030, Big5</li>
        <li><strong>Korea:</strong> EUC-KR, KS_C_5601</li>
        <li><strong>Russia:</strong> KOI8-R, Windows-1251</li>
        <li><strong>Arabic:</strong> ISO-8859-6, Windows-1256</li>
        <li><strong>Thai:</strong> TIS-620, Windows-874</li>
        <li><strong>Hebrew:</strong> ISO-8859-8, Windows-1255</li>
        <li><strong>Western Europe:</strong> ISO-8859-1, Windows-1252</li>
        <li><strong>Modern (all):</strong> UTF-8 ✓</li>
      </ul>
    </div>
  </div>

  <h3>RFC 2047 — Encoding Non-ASCII in Headers</h3>
  <p>Email headers (From, Subject, etc.) can only contain ASCII by design. To include Japanese, Arabic, etc., RFC 2047 defines <span class="hl2">encoded-words</span>:</p>
  <div class="code-block">
    <span class="comment"># Format: =?charset?encoding?encoded-text?=</span><br>
    <span class="comment"># 'B' = Base64, 'Q' = Quoted-Printable</span><br><br>
    =?UTF-8?B?SGVsbG8gV29ybGQ=?=       <span class="comment"># "Hello World" in base64</span><br>
    =?Shift_JIS?B?g2WDZ4Nl?=           <span class="comment"># Japanese subject</span><br>
    =?Windows-1256?Q?=E3=ED=E1=C8?=    <span class="comment"># Arabic subject</span><br>
    =?ISO-8859-1?Q?Caf=E9?=            <span class="comment"># "Café" in Latin-1</span>
  </div>

  <!-- FAQ -->
  <h2>Common Questions</h2>

  <div class="qa">
    <div class="qa-q" onclick="toggleQa(this)">Why not use the php-imap extension? <span class="arrow">▶</span></div>
    <div class="qa-a">The php-imap extension is a C library that many shared hosting providers don't install. Our raw socket approach works on ANY PHP server that has network access. Also, php-imap fetches one email per network round-trip — our batch approach is 10-25× faster for page loads. Plus we have full control over charset handling and MIME parsing.</div>
  </div>

  <div class="qa">
    <div class="qa-q" onclick="toggleQa(this)">What does stream_socket_client() actually do? <span class="arrow">▶</span></div>
    <div class="qa-a">It's PHP's low-level function to open a TCP socket connection. With the ssl:// prefix it wraps the connection in TLS. It's equivalent to calling the C function connect() in a socket program. Once open, you use fwrite() to send data and fread() to receive it — just like reading/writing a file, but across the network.</div>
  </div>

  <div class="qa">
    <div class="qa-q" onclick="toggleQa(this)">What is a "port" and why is IMAP on port 993? <span class="arrow">▶</span></div>
    <div class="qa-a">A server can run many services. Ports are like different doors to the same building. Port 80 = HTTP website. Port 443 = HTTPS website. Port 25 = sending email (SMTP). Port 143 = IMAP (unencrypted). Port 993 = IMAP over SSL/TLS. The mail server listens on port 993 specifically for encrypted IMAP connections. These are internationally standardized by IANA (Internet Assigned Numbers Authority).</div>
  </div>

  <div class="qa">
    <div class="qa-q" onclick="toggleQa(this)">What is the difference between POP3 and IMAP? <span class="arrow">▶</span></div>
    <div class="qa-a">POP3 (Post Office Protocol v3) downloads emails to your device and (usually) deletes them from the server. IMAP (Internet Message Access Protocol) keeps emails on the server — you sync a VIEW of them. IMAP lets you access the same inbox from multiple devices (phone + laptop + webmail). Our project uses IMAP because we need server-side folders, flags, search, and multi-device sync.</div>
  </div>

  <div class="qa">
    <div class="qa-q" onclick="toggleQa(this)">What are CID images and how are they embedded? <span class="arrow">▶</span></div>
    <div class="qa-a">CID = Content-ID. Some emails include images INSIDE the email itself (not as URLs). Each image has a Content-ID like &lt;image001.jpg@abc123&gt;. The HTML body then references them as src="cid:image001.jpg@abc123". Our parser finds all parts with Content-ID, base64-encodes their binary data, and replaces every cid: reference with a data URI (data:image/png;base64,…). This means images display without any extra HTTP requests.</div>
  </div>

  <div class="qa">
    <div class="qa-q" onclick="toggleQa(this)">What does "novalidate-cert" mean in the old php-imap code? <span class="arrow">▶</span></div>
    <div class="qa-a">In the old code, the IMAP host string was {imap.gmail.com:993/imap/ssl/novalidate-cert}. The "novalidate-cert" flag told php-imap to NOT verify the SSL certificate. Our new code uses stream_context_create with verify_peer=false for the same reason — on some shared hosting servers, the CA certificate bundle is outdated and legitimate servers (like cPanel mail) fail certificate validation. In production with proper hosting, you'd set verify_peer=true.</div>
  </div>

  <div class="page-num">— 1 —</div>
</div>


<!-- ═══════════════════════════════════════════════ PAGE 2 ══ -->
<div class="page" id="page2">
  <div class="holes">
    <div class="hole"></div><div class="hole"></div><div class="hole"></div>
    <div class="hole"></div><div class="hole"></div><div class="hole"></div>
    <div class="hole"></div><div class="hole"></div>
  </div>
  <div class="bigword" style="top:80px;font-size:40px">PhonePe</div>
  <div class="bigword" style="top:380px;font-size:36px">PAYMENT</div>

  <h1 class="page-title">PhonePe Payment Integration</h1>
  <div class="subtitle">Complete guide — API flow · Transaction IDs · Retry · Failed · User dropped off · Edge cases</div>

  <div style="display:flex;align-items:center;gap:12px;margin-bottom:20px;position:relative;z-index:1">
    <span class="phonepe-badge">🟣 PhonePe PG</span>
    <span style="font-family:'Caveat',cursive;font-size:14px;color:var(--faint)">Powered by PhonePe Payment Gateway API v1</span>
  </div>

  <!-- WHAT IS PHONEPE PG -->
  <h2>What is PhonePe Payment Gateway?</h2>
  <p>PhonePe PG (Payment Gateway) is a service that lets your app/website <span class="hl">accept payments</span> from users via UPI, credit cards, debit cards, net banking, and wallets — all through a single API. You (the merchant) talk to PhonePe's servers, and PhonePe handles talking to the banks.</p>

  <div class="sticky green">
    <strong>Actors involved:</strong> User (payer) → Your App (merchant) → PhonePe PG → Bank/UPI → Money moves → PhonePe tells you SUCCESS or FAIL.
  </div>

  <!-- KEY CONCEPTS -->
  <h2>Key Concepts Before Anything Else</h2>

  <div class="cols">
    <div class="box">
      <div class="box-label">merchantId</div>
      <p>Your unique identifier given by PhonePe when you register. Like a shop licence number. Never changes.</p>
    </div>
    <div class="box green">
      <div class="box-label">saltKey + saltIndex</div>
      <p>Your secret key for signing requests. <strong>Never expose this to the frontend!</strong> Only used server-side.</p>
    </div>
    <div class="box orange">
      <div class="box-label">merchantTransactionId</div>
      <p>YOUR unique ID for one payment attempt. This is the <span class="hl3">most important concept</span> — see full section below.</p>
    </div>
    <div class="box purple">
      <div class="box-label">transactionId</div>
      <p>PhonePe's own ID for the same transaction. They give you this. Different from yours!</p>
    </div>
  </div>

  <!-- THE FULL FLOW -->
  <h2>Complete Payment Flow — Step by Step</h2>

  <p class="click-hint">👆 Click any step to expand full details</p>

  <div class="vflow">
    <div class="vflow-line"></div>

    <div class="vstep">
      <div class="vstep-num" onclick="toggleStep(this)">1</div>
      <div class="vstep-body">
        <div class="vstep-title" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">User Clicks "Pay ₹500"</div>
        <div class="vstep-desc">Trigger on your frontend → call your backend API</div>
        <div class="vstep-detail">
          User taps Pay. Your frontend calls your own backend API: <span class="cmd">POST /api/create-order</span><br><br>
          Your backend immediately:<br>
          1. Creates an order in your DB (status = <span class="status-badge s-pending">PENDING</span>)<br>
          2. Generates a <strong>merchantTransactionId</strong> (e.g. <span class="cmd">TXN_20241201_1234567890_abc</span>)<br>
          3. Saves it in DB with the order details<br>
          4. Does NOT call PhonePe yet — just prepares
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num green" onclick="toggleStep(this)">2</div>
      <div class="vstep-body">
        <div class="vstep-title green" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">Build the PhonePe Initiate Payment Request</div>
        <div class="vstep-desc">Server-side only — construct + sign the payload</div>
        <div class="vstep-detail green">
          Build the JSON payload:
          <div class="code-block">
            <span class="kw">{</span><br>
            &nbsp;&nbsp;<span class="str">"merchantId"</span>: <span class="str">"YOUR_MERCHANT_ID"</span>,<br>
            &nbsp;&nbsp;<span class="str">"merchantTransactionId"</span>: <span class="str">"TXN_20241201_abc"</span>,<br>
            &nbsp;&nbsp;<span class="str">"merchantUserId"</span>: <span class="str">"USER_123"</span>,<br>
            &nbsp;&nbsp;<span class="str">"amount"</span>: <span class="num">50000</span>, <span class="comment">// in PAISE! ₹500 = 50000</span><br>
            &nbsp;&nbsp;<span class="str">"redirectUrl"</span>: <span class="str">"https://yoursite.com/payment/callback"</span>,<br>
            &nbsp;&nbsp;<span class="str">"redirectMode"</span>: <span class="str">"POST"</span>,<br>
            &nbsp;&nbsp;<span class="str">"callbackUrl"</span>: <span class="str">"https://yoursite.com/payment/webhook"</span>,<br>
            &nbsp;&nbsp;<span class="str">"paymentInstrument"</span>: <span class="kw">{</span><span class="str">"type"</span>: <span class="str">"PAY_PAGE"</span><span class="kw">}</span><br>
            <span class="kw">}</span>
          </div>
          Then: <span class="cmd">base64(JSON)</span> → <span class="cmd">base64 + "/pg/v1/pay" + saltKey</span> → <span class="cmd">SHA256</span> → <span class="cmd">checksum = hash + "###" + saltIndex</span>
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num purple" onclick="toggleStep(this)">3</div>
      <div class="vstep-body">
        <div class="vstep-title purple" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">Call PhonePe API → Get Payment URL</div>
        <div class="vstep-desc">POST to PhonePe's server from YOUR server</div>
        <div class="vstep-detail purple">
          <span class="cmd">POST https://api.phonepe.com/apis/hermes/pg/v1/pay</span><br>
          Headers: <span class="cmd">Content-Type: application/json</span> + <span class="cmd">X-VERIFY: {checksum}</span><br><br>
          PhonePe validates your checksum. If valid, responds:<br>
          <div class="code-block">
            <span class="kw">{</span><br>
            &nbsp;&nbsp;<span class="str">"success"</span>: <span class="kw">true</span>,<br>
            &nbsp;&nbsp;<span class="str">"code"</span>: <span class="str">"PAYMENT_INITIATED"</span>,<br>
            &nbsp;&nbsp;<span class="str">"data"</span>: <span class="kw">{</span><br>
            &nbsp;&nbsp;&nbsp;&nbsp;<span class="str">"instrumentResponse"</span>: <span class="kw">{</span><br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="str">"redirectInfo"</span>: <span class="kw">{</span><br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="str">"url"</span>: <span class="str">"https://mercury-t2.phonepe.com/transact/…"</span><br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="kw">}</span><br>
            &nbsp;&nbsp;&nbsp;&nbsp;<span class="kw">}</span><br>
            &nbsp;&nbsp;<span class="kw">}</span><br>
            <span class="kw">}</span>
          </div>
          Return this URL to frontend → redirect user there.
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num orange" onclick="toggleStep(this)">4</div>
      <div class="vstep-body">
        <div class="vstep-title orange" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">User Pays on PhonePe's Page</div>
        <div class="vstep-desc">User is on PhonePe's domain — you have no control here</div>
        <div class="vstep-detail orange">
          The user is now on PhonePe's payment page. They choose UPI / card / wallet and pay.<br><br>
          <strong>You have ZERO visibility here.</strong> You don't know if they:<br>
          • Are filling the form right now<br>
          • Opened another app<br>
          • Dropped the phone<br>
          • Pressed back button<br>
          • Internet disconnected<br><br>
          This is why you must <strong>NEVER update your order status to SUCCESS</strong> until you receive confirmation. The DB remains <span class="status-badge s-pending">PENDING</span>.
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num red" onclick="toggleStep(this)">5</div>
      <div class="vstep-body">
        <div class="vstep-title red" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">Two Simultaneous Return Paths</div>
        <div class="vstep-desc">Redirect (user-facing) + Webhook (server-to-server)</div>
        <div class="vstep-detail red">
          PhonePe sends payment result in TWO ways at the same time:<br><br>
          <strong>Path A — Redirect:</strong> Browser redirects user to your <code>redirectUrl</code> with the result in the POST body. BUT: this can fail — user might close browser, internet might drop.<br><br>
          <strong>Path B — Webhook:</strong> PhonePe's server makes a POST call to your <code>callbackUrl</code> directly. This happens on PhonePe's server → your server, no user browser involved. This is MORE RELIABLE.<br><br>
          <strong>Rule:</strong> Always trust the Webhook. Treat the Redirect as a hint, then verify via Status Check API.
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num green" onclick="toggleStep(this)">6</div>
      <div class="vstep-body">
        <div class="vstep-title green" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">Verify Payment — Status Check API</div>
        <div class="vstep-desc">ALWAYS verify from your server — never trust frontend</div>
        <div class="vstep-detail green">
          When you receive a redirect or webhook, <strong>never trust it blindly.</strong> Always verify:<br><br>
          <span class="cmd">GET /pg/v1/status/{merchantId}/{merchantTransactionId}</span><br><br>
          Sign with: <span class="cmd">SHA256("/pg/v1/status/MID/TXNID" + saltKey) + "###" + saltIndex</span><br><br>
          PhonePe responds with one of:
          <br>
          <span class="status-badge s-success">PAYMENT_SUCCESS</span> → update DB, fulfil order<br>
          <span class="status-badge s-failed">PAYMENT_ERROR</span> → mark failed, don't fulfil<br>
          <span class="status-badge s-pending">PAYMENT_PENDING</span> → wait, check again later
        </div>
      </div>
    </div>

  </div>

  <!-- MERCHANT TRANSACTION ID — BIG SECTION -->
  <h2>🔑 merchantTransactionId — The Most Important Concept</h2>

  <div class="warn">
    This is where most developers make mistakes. Read every word carefully.
  </div>

  <div class="box orange">
    <div class="box-label">What is it?</div>
    <p>A unique ID that <strong>YOU generate</strong> for each payment ATTEMPT. PhonePe uses it to identify the transaction. Rules:</p>
    <ul>
      <li>Max 38 characters</li>
      <li>Only alphanumeric + hyphens + underscores</li>
      <li>Must be unique per attempt — <strong>never reuse for a different attempt</strong></li>
      <li>Once submitted to PhonePe, this ID is "consumed" for that attempt</li>
    </ul>
  </div>

  <h3>Generating a Good merchantTransactionId</h3>
  <div class="code-block">
    <span class="comment">// Good format: PREFIX_ORDERID_TIMESTAMP_RANDOM</span><br>
    <span class="str">"MT_"</span> . orderId . <span class="str">"_"</span> . time() . <span class="str">"_"</span> . substr(uniqid(), -6)<br>
    <span class="comment">// e.g.: MT_4521_1701388800_a7f3b2</span><br><br>
    <span class="comment">// Or use UUID v4:</span><br>
    <span class="str">"MT-"</span> . str_replace(<span class="str">'-'</span>, <span class="str">''</span>, Str::uuid())<br>
    <span class="comment">// e.g.: MT-550e8400e29b41d4a716446655440000</span>
  </div>

  <!-- RETRY / FAILED / BACK BUTTON — COMPREHENSIVE -->
  <h2>Edge Cases — Retry, Failed, Back Button</h2>

  <p class="click-hint">👆 Click each scenario to see the correct handling</p>

  <div class="vflow">
    <div class="vflow-line"></div>

    <div class="vstep">
      <div class="vstep-num red" onclick="toggleStep(this)">!</div>
      <div class="vstep-body">
        <div class="vstep-title red" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">Scenario 1: Payment FAILED</div>
        <div class="vstep-desc">User's card declined / UPI timeout / insufficient balance</div>
        <div class="vstep-detail red">
          <strong>What PhonePe does:</strong> Redirects user to your redirectUrl with PAYMENT_ERROR. Also sends webhook.<br><br>
          <strong>What you MUST do:</strong><br>
          1. Call Status Check API to verify (don't trust redirect alone)<br>
          2. Update DB: order status = <span class="status-badge s-failed">FAILED</span>, mark merchantTransactionId as failed<br>
          3. Show user a "Payment Failed" page with a <strong>Retry button</strong><br><br>
          <strong>For RETRY:</strong> Generate a <span class="hl3">NEW</span> merchantTransactionId. You CANNOT reuse the failed one — PhonePe will reject it as "duplicate transaction". The old transaction ID is forever associated with a failed attempt.<br><br>
          <strong>DB Structure:</strong> Your order can have MULTIPLE payment attempts (one-to-many). Each attempt = new row with new merchantTransactionId.
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num orange" onclick="toggleStep(this)">!</div>
      <div class="vstep-body">
        <div class="vstep-title orange" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">Scenario 2: User Presses Browser BACK Button</div>
        <div class="vstep-desc">User leaves PhonePe page without completing payment</div>
        <div class="vstep-detail orange">
          This is the trickiest case. When the user presses Back:<br><br>
          <strong>Option A — PhonePe redirects back to you:</strong> You'll get a redirect with code like <code>PAYMENT_PENDING</code> or nothing at all.<br><br>
          <strong>Option B — Browser navigates away:</strong> No redirect happens at all. Your backend never hears anything.<br><br>
          <strong>What to do:</strong><br>
          1. Show user a "Payment Incomplete" page<br>
          2. Add a <strong>Check Status</strong> button → calls your Status API → calls PhonePe Status API<br>
          3. If status is PENDING, show "Payment is being processed"<br>
          4. If status is FAILURE, offer retry with NEW merchantTransactionId<br>
          5. <strong>Never assume failure just because user pressed Back!</strong> Sometimes UPI payments succeed in background.
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num purple" onclick="toggleStep(this)">!</div>
      <div class="vstep-body">
        <div class="vstep-title purple" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">Scenario 3: User Closes App / Internet Drops</div>
        <div class="vstep-desc">Complete dropout — you receive nothing</div>
        <div class="vstep-detail purple">
          User could be in any state — payment may have succeeded even if you never got the redirect.<br><br>
          <strong>Solution — Polling + Timeout system:</strong><br>
          1. Run a background job (cron/queue) every 5 minutes<br>
          2. Find all orders in PENDING state older than 2 minutes<br>
          3. For each: call PhonePe Status Check API<br>
          4. Update status based on response<br>
          5. After 30 minutes of PENDING → mark as EXPIRED, notify user<br><br>
          <strong>PhonePe holds PENDING transactions for up to 2 hours</strong> on UPI. After that, if not completed, they automatically fail.
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num red" onclick="toggleStep(this)">!</div>
      <div class="vstep-body">
        <div class="vstep-title red" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">Scenario 4: Duplicate Webhook Delivery</div>
        <div class="vstep-desc">PhonePe may send the same webhook MULTIPLE times</div>
        <div class="vstep-detail red">
          PhonePe guarantees "at-least-once" delivery — meaning they may send the same webhook 2 or 3 times if your server was slow to respond.<br><br>
          <strong>Your webhook handler MUST be idempotent:</strong><br>
          <div class="code-block">
            <span class="comment">// Check if already processed BEFORE doing anything</span><br>
            <span class="kw">if</span> ($order->status === <span class="str">'SUCCESS'</span>) {<br>
            &nbsp;&nbsp;<span class="comment">// Already processed — just return 200 OK</span><br>
            &nbsp;&nbsp;http_response_code(200); exit;<br>
            }<br><br>
            <span class="comment">// Process and update only if still PENDING</span><br>
            DB::transaction(<span class="kw">function</span>() { ... });
          </div>
          Always respond with <span class="cmd">HTTP 200</span> to webhooks even if already processed. If you return 4xx/5xx, PhonePe will retry.
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num green" onclick="toggleStep(this)">!</div>
      <div class="vstep-body">
        <div class="vstep-title green" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">Scenario 5: User Opens Payment Page Twice</div>
        <div class="vstep-desc">Double-clicking Pay, or opening same order in two tabs</div>
        <div class="vstep-detail green">
          If user somehow initiates payment twice for the same order:<br><br>
          <strong>Solution — Lock order before calling PhonePe:</strong><br>
          1. Use DB-level locking: <span class="cmd">SELECT ... FOR UPDATE</span><br>
          2. Check if order already has an ACTIVE or SUCCESS payment attempt<br>
          3. If yes → return existing PhonePe URL (if still valid) or error<br>
          4. If no → create new attempt, call PhonePe, return new URL<br><br>
          Never call PhonePe initiate API twice for the same "logical" payment. Each call creates a new transaction that would need to be reconciled.
        </div>
      </div>
    </div>

    <div class="vstep">
      <div class="vstep-num orange" onclick="toggleStep(this)">!</div>
      <div class="vstep-body">
        <div class="vstep-title orange" onclick="toggleStep(this.closest('.vstep').querySelector('.vstep-num'))">Scenario 6: Refund Flow</div>
        <div class="vstep-desc">When user wants money back</div>
        <div class="vstep-detail orange">
          Call PhonePe Refund API with a NEW <strong>merchantTransactionId</strong> (for the refund) and the original PhonePe transactionId.<br><br>
          <span class="cmd">POST /pg/v1/refund</span><br><br>
          Payload includes: originalTransactionId (PhonePe's ID), refund amount, your new refund transaction ID.<br><br>
          Refunds can be full or partial. Typically takes 5-7 business days to reach user's bank.
        </div>
      </div>
    </div>
  </div>

  <!-- DB SCHEMA -->
  <h2>Recommended Database Structure</h2>

  <div class="cols">
    <div class="box">
      <div class="box-label">orders table</div>
      <p style="font-family:'Patrick Hand',cursive;font-size:13px;line-height:1.9">
        id (PK)<br>
        user_id<br>
        amount (in paise)<br>
        status: PENDING | SUCCESS | FAILED | EXPIRED<br>
        item_details<br>
        created_at<br>
        fulfilled_at
      </p>
    </div>
    <div class="box green">
      <div class="box-label">payment_attempts table</div>
      <p style="font-family:'Patrick Hand',cursive;font-size:13px;line-height:1.9">
        id (PK)<br>
        order_id (FK → orders)<br>
        <strong>merchant_transaction_id (UNIQUE)</strong><br>
        phonepe_transaction_id<br>
        status: INITIATED | SUCCESS | FAILED | EXPIRED<br>
        amount<br>
        created_at<br>
        completed_at
      </p>
    </div>
  </div>

  <div class="sticky pink">
    <strong>Key rule:</strong> One order → MANY payment_attempts. Each attempt has its own merchantTransactionId. SUCCESS on any attempt = fulfil the order (but don't double-fulfil if webhook comes twice!).
  </div>

  <!-- Q&A -->
  <h2>PhonePe Q&amp;A</h2>

  <div class="qa">
    <div class="qa-q" onclick="toggleQa(this)">Do I need a new merchantTransactionId for every retry? <span class="arrow">▶</span></div>
    <div class="qa-a">YES, 100%. PhonePe treats each merchantTransactionId as a unique payment event. If you retry with the same ID that already has a FAILED status, PhonePe returns an error like "DUPLICATE_TRANSACTION". Generate a new ID every single time the user clicks "Try Again". The format can be: original_order_id + "_retry_" + timestamp.</div>
  </div>

  <div class="qa">
    <div class="qa-q" onclick="toggleQa(this)">What is X-VERIFY header and why does it matter? <span class="arrow">▶</span></div>
    <div class="qa-a">X-VERIFY is a checksum that proves the request came from you (the legitimate merchant) and wasn't tampered with. It's computed as: SHA256(base64EncodedPayload + "/pg/v1/pay" + saltKey) + "###" + saltIndex. PhonePe recomputes this on their end using your saltKey (which only you and PhonePe know). If it doesn't match, PhonePe rejects the request. This prevents hackers from faking payment requests even if they intercept your network traffic.</div>
  </div>

  <div class="qa">
    <div class="qa-q" onclick="toggleQa(this)">What's the difference between redirectUrl and callbackUrl? <span class="arrow">▶</span></div>
    <div class="qa-a">redirectUrl = where the user's browser is sent after payment completes. It's user-facing. callbackUrl (webhook) = where PhonePe's servers call your server directly, independent of the user's browser. redirectUrl can fail if user closes browser. callbackUrl is more reliable because it's server-to-server. ALWAYS implement both. Process payment confirmation in the webhook handler. Show success page at redirectUrl after verifying via Status API.</div>
  </div>

  <div class="qa">
    <div class="qa-q" onclick="toggleQa(this)">How do I handle ₹ amount vs paise? <span class="arrow">▶</span></div>
    <div class="qa-a">PhonePe API always uses PAISE (1 rupee = 100 paise). So ₹499 = 49900 paise. Always store amounts in your DB in paise too (integer, no floating point) to avoid rounding errors. Display to user as amount/100. Never use floats for money — floating point arithmetic can give 0.1 + 0.2 = 0.30000000004.</div>
  </div>

  <div class="qa">
    <div class="qa-q" onclick="toggleQa(this)">UAT vs Production — what changes? <span class="arrow">▶</span></div>
    <div class="qa-a">UAT (testing) base URL: https://api-preprod.phonepe.com/apis/pg-sandbox/. Production URL: https://api.phonepe.com/apis/hermes/. UAT uses test credentials — no real money moves. Use test UPI: success@ybl (simulates success), failure@ybl (simulates failure). Switch URLs and credentials when going live. Never commit saltKey to Git — use environment variables.</div>
  </div>

  <div class="qa">
    <div class="qa-q" onclick="toggleQa(this)">What if the webhook signature verification fails? <span class="arrow">▶</span></div>
    <div class="qa-a">REJECT the webhook and return HTTP 400. Don't process it. A mismatched signature could mean: (1) someone is faking a success webhook to get free service, or (2) your saltKey is wrong. Log the raw payload for debugging. Verify: SHA256(responseBody + "/pg/v1/pay" + saltKey) should equal the X-VERIFY header value sent by PhonePe.</div>
  </div>

  <!-- PRODUCTION CHECKLIST -->
  <h2>Production Checklist ✓</h2>

  <div class="box green">
    <div class="box-label">Before Going Live</div>
    <ul>
      <li>saltKey stored in environment variable, never in code</li>
      <li>Webhook endpoint publicly accessible (not localhost)</li>
      <li>Webhook handler is idempotent (safe to call multiple times)</li>
      <li>Status Check API called to verify every payment</li>
      <li>New merchantTransactionId generated for every attempt</li>
      <li>Amounts stored in paise (integer, not float)</li>
      <li>Background job to resolve PENDING transactions</li>
      <li>HTTPS on all endpoints (PhonePe requires HTTPS)</li>
      <li>Tested with PhonePe UAT test cards/UPI</li>
      <li>Error logging for all PhonePe API calls</li>
    </ul>
  </div>

  <div class="page-num">— 2 —</div>
</div>

</div><!-- .notebook -->

<script>
function showPage(n) {
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.querySelectorAll('.tab').forEach(t=>t.classList.remove('active'));
  document.getElementById('page'+n).classList.add('active');
  document.querySelectorAll('.tab')[n-1].classList.add('active');
  window.scrollTo({top:0,behavior:'smooth'});
}

function toggleStep(el) {
  const step = el.closest('.vstep');
  const detail = step.querySelector('.vstep-detail');
  const num = step.querySelector('.vstep-num');
  if (detail) {
    const open = detail.classList.toggle('open');
    // colour the detail to match the num
    const cls = ['red','green','orange','purple'].find(c=>num.classList.contains(c))||'';
    if (cls) detail.classList.toggle(cls, open);
  }
}

function toggleTip(el) {
  el.classList.toggle('open');
  document.querySelectorAll('.fnode.open').forEach(n=>{ if(n!==el) n.classList.remove('open'); });
}

function toggleQa(el) {
  const qa = el.closest('.qa');
  const ans = qa.querySelector('.qa-a');
  el.classList.toggle('open');
  ans.classList.toggle('open');
}

// Close tips on outside click
document.addEventListener('click', e => {
  if (!e.target.closest('.fnode')) {
    document.querySelectorAll('.fnode.open').forEach(n=>n.classList.remove('open'));
  }
});
</script>
</body>
</html>
