---
layout: default
title: "Contact Us"
description: "Get in touch with the ARYX Lumina team. Questions, corrections, topic suggestions, or brand collaborations."
permalink: /contact-us/
---

<style>
.page-hero { background:linear-gradient(135deg,var(--bg-card),var(--neon-dim)); border-bottom:1px solid var(--border); padding:3rem 1.5rem; text-align:center; margin:-16px -16px 32px; }
.page-hero-tag { display:inline-block; background:var(--tag-bg); color:var(--neon); border:1px solid var(--border); padding:0.3rem 0.9rem; border-radius:20px; font-size:0.8rem; font-weight:600; letter-spacing:1px; text-transform:uppercase; margin-bottom:1.2rem; font-family:'DM Sans',sans-serif; }
.page-hero h1 { font-family:'Playfair Display',Georgia,serif; font-size:clamp(1.8rem,4vw,2.8rem); font-weight:800; margin-bottom:0.8rem; }
.page-hero h1 span { color:var(--neon); text-shadow:var(--neon-glow); }
.page-hero p { color:var(--text2); font-size:1rem; max-width:550px; margin:0 auto; }
.page-content { max-width:820px; margin:0 auto; }
.page-content h2 { font-family:'Playfair Display',Georgia,serif; font-size:1.4rem; font-weight:700; color:var(--neon); margin-bottom:1rem; padding-left:1rem; border-left:3px solid var(--neon); }
.page-content p { color:var(--text2); margin-bottom:1rem; font-size:1rem; line-height:1.8; }
.info-card { background:var(--bg-card); border:1px solid var(--border); border-radius:10px; padding:1.2rem 1.5rem; margin-bottom:1rem; display:flex; gap:1rem; align-items:flex-start; }
.info-label { font-size:0.75rem; color:var(--neon); font-weight:700; text-transform:uppercase; margin-bottom:0.3rem; font-family:'DM Sans',sans-serif; }
.info-text { font-size:0.95rem; color:var(--text2); }
.tag-list { display:flex; flex-wrap:wrap; gap:0.6rem; margin-top:1rem; }
.tag-chip { background:var(--tag-bg); border:1px solid var(--border); color:var(--neon); padding:0.4rem 0.8rem; border-radius:20px; font-size:0.8rem; font-family:'DM Sans',sans-serif; }
.form-card { background:var(--bg-card); border:1px solid var(--border); border-radius:16px; padding:2rem; margin-top:2rem; }
.form-group { margin-bottom:1.2rem; }
.form-group label { display:block; font-size:0.9rem; margin-bottom:0.5rem; font-weight:600; color:var(--text); font-family:'DM Sans',sans-serif; }
.form-group input, .form-group select, .form-group textarea { width:100%; background:var(--bg); border:1px solid var(--border); color:var(--text); padding:0.8rem 1rem; border-radius:8px; font-size:1rem; box-sizing:border-box; outline:none; font-family:'DM Sans',sans-serif; transition:border-color 0.2s; }
.form-group input:focus, .form-group select:focus, .form-group textarea:focus { border-color:var(--border-glow); box-shadow:var(--neon-glow); }
.form-group select option { background:var(--bg-sidebar); }
.submit-btn { width:100%; background:var(--neon); color:#fff; padding:0.9rem; border:none; border-radius:8px; font-weight:700; cursor:pointer; font-size:1rem; font-family:'Playfair Display',Georgia,serif; box-shadow:var(--neon-glow); transition:all 0.2s; }
.submit-btn:hover { box-shadow:var(--neon-strong); transform:translateY(-1px); }
.status-box { display:none; text-align:center; padding:2rem; }
.divider { border:0; border-top:1px solid var(--border); margin:2rem 0; }
</style>

<div class="page-hero">
  <div class="page-hero-tag">Contact</div>
  <h1>Let's <span>Talk</span></h1>
  <p>Got a question, a topic idea, or something you want us to cover? Fill in the form below.</p>
</div>

<div class="page-content">

  <section>
    <h2>Before You Write In</h2>
    <p>We are a small team, so we cannot always reply the same day. But we do read everything that comes in, and good suggestions actually make it into our content schedule.</p>
    <p>If you spotted a mistake in one of our articles, we especially want to hear that. Getting things right matters to us more than looking right.</p>

    <div class="info-card">
      <div style="font-size:1.5rem;">⏱️</div>
      <div>
        <div class="info-label">Response Time</div>
        <div class="info-text">We aim to reply within 2 to 3 business days. Longer for complex questions.</div>
      </div>
    </div>

    <div class="info-card">
      <div style="font-size:1.5rem;">🤝</div>
      <div>
        <div class="info-label">Collaborations</div>
        <div class="info-text">For brand partnerships, select "Brand or product collaboration" in the form.</div>
      </div>
    </div>

    <div style="margin-top:1.5rem;">
      <h2>Topics We Hear About Most</h2>
      <div class="tag-list">
        <span class="tag-chip">Skincare routines</span>
        <span class="tag-chip">Ingredient questions</span>
        <span class="tag-chip">Hair care tips</span>
        <span class="tag-chip">Hormonal skin</span>
        <span class="tag-chip">PCOS and skin</span>
        <span class="tag-chip">Postpartum care</span>
        <span class="tag-chip">Budget-friendly picks</span>
        <span class="tag-chip">Article corrections</span>
      </div>
    </div>
  </section>

  <hr class="divider"/>

  <div class="form-card">
    <div id="form-ui">
      <h2 style="border:none;padding:0;margin-bottom:0.5rem;">Send a Message</h2>
      <p style="margin-bottom:1.5rem;">We read every message. Fill in the details below.</p>

      <div id="err-display" style="display:none;color:#ff6b6b;margin-bottom:1rem;font-size:0.9rem;"></div>

      <div class="form-group">
        <label>Name</label>
        <input type="text" id="sender-name" placeholder="Your name"/>
      </div>
      <div class="form-group">
        <label>Email Address *</label>
        <input type="email" id="sender-email" placeholder="you@example.com"/>
      </div>
      <div class="form-group">
        <label>Topic *</label>
        <select id="sender-topic">
          <option value="">Select a topic</option>
          <option value="General">General question</option>
          <option value="Suggestion">Article suggestion</option>
          <option value="Correction">Article correction</option>
          <option value="Brand">Brand collaboration</option>
        </select>
      </div>
      <div class="form-group">
        <label>Your Message *</label>
        <textarea id="sender-msg" rows="6" placeholder="Write your message here..."></textarea>
      </div>
      <button class="submit-btn" onclick="handleSubmission()">Send Message</button>
    </div>

    <div id="success-ui" class="status-box">
      <div style="font-size:3rem;margin-bottom:1rem;">✅</div>
      <h3 style="font-family:'Playfair Display',Georgia,serif;">Message sent successfully</h3>
      <p style="color:var(--text2);">We got it. You will hear from us soon.</p>
    </div>
  </div>

</div>

<script>
async function handleSubmission(){
  var name = document.getElementById('sender-name').value;
  var email = document.getElementById('sender-email').value;
  var topic = document.getElementById('sender-topic').value;
  var msg = document.getElementById('sender-msg').value;
  var err = document.getElementById('err-display');
  if(!email || !topic || !msg){
    err.textContent = "Please fill in all required fields.";
    err.style.display = "block";
    return;
  }
  try {
    var response = await fetch('https://formspree.io/f/maqpbvgy', {
      method: 'POST',
      headers: {'Content-Type': 'application/json'},
      body: JSON.stringify({name: name, email: email, topic: topic, message: msg})
    });
    if(response.ok){
      document.getElementById('form-ui').style.display = 'none';
      document.getElementById('success-ui').style.display = 'block';
    }
  } catch(e){
    err.textContent = "Something went wrong. Please try again.";
    err.style.display = "block";
  }
}
</script>
