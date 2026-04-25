---
layout: page
title: Social Media & Digital Marketing
permalink: /work/social-media/
---

<div class="writing-gallery">

  <div class="writing-card" onclick="openWritingModal('rhv')">
    <h3>Shadow Sheltie</h3>
    <p class="writing-company">Relentless Health Value</p>
  </div>

  <div class="writing-card" onclick="openWritingModal('jbk')">
    <h3>Baker4Kansas</h3>
    <p class="writing-company">John Baker for Kansas Senate</p>
  </div>

  <div class="writing-card" onclick="openWritingModal('vb')">
    <h3>Volunteer Blue</h3>
    <p class="writing-company">Volunteer Blue</p>
  </div>

  <div class="writing-card" onclick="openWritingModal('ctp')">
    <h3>Creative Teaching Press</h3>
    <p class="writing-company">Creative Teaching Press</p>
  </div>

  <div class="writing-card" onclick="openWritingModal('rhv2')">
    <h3>Relentless Health Value</h3>
    <p class="writing-company">Relentless Health Value</p>
  </div>

</div>

<!-- Modals -->

<div id="modal-rhv" class="writing-modal">
  <div class="writing-modal-inner">
    <button class="modal-close" onclick="closeWritingModal('rhv')">✕</button>
    <h2>Audience Growth for a Niche Healthcare Podcast</h2>
    <p class="writing-company">Relentless Health Value | 2014–Present</p>
    <h3>The Challenge</h3>
    <p>Relentless Health Value is a top-ranked healthcare policy podcast with a highly specific audience — healthcare professionals, policy advocates, and industry insiders. Growing an engaged following in such a niche space required more than just posting consistently. It required a deep understanding of the audience and a content strategy built around their specific needs and interests.</p>
    <h3>The Approach</h3>
    <p>Tasha built and led the organic social media strategy from the ground up, developing a content voice that resonated with a highly informed audience. She applied audience analytics to inform content decisions, optimized posts for social SEO and metadata discoverability, and crafted captions that drove meaningful engagement rather than passive scrolling.</p>
    <h3>The Results</h3>
    <ul>
      <li>Grew the audience from <strong>0 to 5,650+ highly engaged followers</strong></li>
      <li>Built a loyal niche community in a specialized industry space</li>
      <li>Consistently increased organic reach through social SEO strategy</li>
    </ul>
    <p><em>Analytics screenshots, content examples, and engagement data coming soon.</em></p>
  </div>
</div>

<div id="modal-ctp" class="writing-modal">
  <div class="writing-modal-inner">
    <button class="modal-close" onclick="closeWritingModal('ctp')">✕</button>
    <h2>Multi-Platform Content Strategy</h2>
    <p class="writing-company">Creative Teaching Press | 2022–2025</p>
    <h3>The Challenge</h3>
    <p>Creative Teaching Press had an established social presence but needed a more strategic and consistent approach to content across platforms to support 100+ product launches per year and grow their audience.</p>
    <h3>The Approach</h3>
    <p>Tasha developed a daily content cadence across all social platforms, keeping the brand voice consistent while tailoring content for each channel. She built and managed content calendars that kept the team aligned around product launches and seasonal campaigns, and led an email performance audit that identified key opportunities for improvement.</p>
    <h3>The Results</h3>
    <ul>
      <li>Managed content strategy for a following of <strong>97k across social platforms</strong></li>
      <li>Directed cross-channel campaigns for 100+ products annually</li>
      <li>Email audit drove a <strong>25% increase in click-through rate</strong></li>
    </ul>
    <p><em>Content calendar screenshots, campaign examples, and analytics coming soon.</em></p>
  </div>
</div>

<div id="modal-jbk" class="writing-modal">
  <div class="writing-modal-inner">
    <button class="modal-close" onclick="closeWritingModal('jbk')">✕</button>
    <h2>Political Campaign Social Strategy</h2>
    <p class="writing-company">John Baker for Kansas Senate | 2024</p>
    <h3>The Challenge</h3>
    <p>A Kansas Senate campaign needed a social media presence built quickly and strategically, with platform-native content that could cut through the noise and drive real voter engagement across multiple platforms under tight deadlines.</p>
    <h3>The Approach</h3>
    <p>Tasha created and managed the full social content calendar for the campaign, producing and editing short-form video for TikTok, Instagram, and Facebook. She ensured quality and consistency across all published content while keeping messaging aligned with key campaign platforms and voter outreach goals.</p>
    <h3>The Results</h3>
    <ul>
      <li>Built and managed a full campaign social presence across three platforms</li>
      <li>Produced and edited short-form video content throughout the campaign</li>
      <li>Maintained brand consistency and quality across all published content</li>
    </ul>
    <p><em>Campaign content examples and video samples coming soon.</em></p>
  </div>
</div>

<div id="modal-rhv2" class="writing-modal">
  <div class="writing-modal-inner">
    <button class="modal-close" onclick="closeWritingModal('rhv2')">✕</button>
    <h2>Relentless Health Value</h2>
    <p class="writing-company">Relentless Health Value</p>
    <p><em>Work samples coming soon.</em></p>
  </div>
</div>

<div id="modal-vb" class="writing-modal">
  <div class="writing-modal-inner">
    <button class="modal-close" onclick="closeWritingModal('vb')">✕</button>
    <h2>Coalition Digital Media Management</h2>
    <p class="writing-company">Volunteer Blue | 2023</p>
    <h3>The Challenge</h3>
    <p>Volunteer Blue needed someone to build and manage a cohesive cross-platform digital presence for a coalition of organizations, ensuring consistent branding and timely content across all channels.</p>
    <h3>The Approach</h3>
    <p>Tasha built a cross-platform content and asset library from scratch across Instagram, Facebook, TikTok, and YouTube.</p>
    <h3>The Results</h3>
    <p><em>Results coming soon.</em></p>
    <p><em>Work samples coming soon.</em></p>
  </div>
</div>

---

## Social Media Specialties
Organic social strategy, audience growth, content calendar management,
social SEO, short-form video, multi-platform campaigns, community management,
email marketing, analytics and reporting, brand voice development.

---

[← Back to Work](/work) | [Get In Touch](/contact)

<script>
function openWritingModal(id) {
  document.getElementById('modal-' + id).classList.add('active');
  document.body.style.overflow = 'hidden';
}
function closeWritingModal(id) {
  document.getElementById('modal-' + id).classList.remove('active');
  document.body.style.overflow = '';
}
document.querySelectorAll('.writing-modal').forEach(function(modal) {
  modal.addEventListener('click', function(e) {
    if (e.target === modal) {
      modal.classList.remove('active');
      document.body.style.overflow = '';
    }
  });
});
</script>
