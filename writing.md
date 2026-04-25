---
layout: page
title: Copy & Article Writing
permalink: /work/writing/
---

<div class="writing-gallery">

  <div class="writing-card" onclick="openWritingModal('seo')">
    <h3>SEO Copywriting</h3>
    <p class="writing-company">Spectrum Content</p>
  </div>

  <div class="writing-card" onclick="openWritingModal('health')">
    <h3>Editorial Writing</h3>
    <p class="writing-company">Get Your Fit Together · Shondaland.com · Career College Central Magazine</p>
  </div>

  <div class="writing-card" onclick="openWritingModal('education')">
    <h3>Persuasive Brand Copy</h3>
    <p class="writing-company">John Baker for Kansas</p>
  </div>

  <div class="writing-card" onclick="openWritingModal('blog')">
    <h3>Blog &amp; Newsletter Writing</h3>
    <p class="writing-company">Creative Teaching Press</p>
  </div>

  <div class="writing-card" onclick="openWritingModal('press')">
    <h3>Press Release Copywriting</h3>
    <p class="writing-company">Andrews McMeel Publishing</p>
  </div>

  <div class="writing-card" onclick="openWritingModal('review')">
    <h3>Review Writing</h3>
    <p class="writing-company">The Tracking-Board · The Industry</p>
  </div>

</div>

<!-- Modals -->

<div id="modal-seo" class="writing-modal">
  <div class="writing-modal-inner">
    <button class="modal-close" onclick="closeWritingModal('seo')">✕</button>
    <h2>SEO Copywriting</h2>
    <p class="writing-company">Spectrum Content</p>
    <p><em>Writing samples coming soon.</em></p>
    <p>[ Placeholder for writing sample / PDF / link ]</p>
  </div>
</div>

<div id="modal-health" class="writing-modal">
  <div class="writing-modal-inner">
    <button class="modal-close" onclick="closeWritingModal('health')">✕</button>
    <h2>Editorial Writing</h2>
    <p class="writing-company">Get Your Fit Together · Shondaland.com · Career College Central Magazine</p>
    <p><em>Published articles coming soon.</em></p>
    <p>[ Placeholder for article links / screenshots ]</p>
  </div>
</div>

<div id="modal-education" class="writing-modal">
  <div class="writing-modal-inner">
    <button class="modal-close" onclick="closeWritingModal('education')">✕</button>
    <h2>Persuasive Brand Copy</h2>
    <p class="writing-company">John Baker for Kansas</p>
    <p><em>Writing samples coming soon.</em></p>
    <p>[ Placeholder for writing sample / PDF / link ]</p>
  </div>
</div>

<div id="modal-blog" class="writing-modal">
  <div class="writing-modal-inner">
    <button class="modal-close" onclick="closeWritingModal('blog')">✕</button>
    <h2>Blog &amp; Newsletter Writing</h2>
    <p class="writing-company">Creative Teaching Press</p>
    <p><em>Writing samples coming soon.</em></p>
    <p>[ Placeholder for writing sample / PDF / link ]</p>
  </div>
</div>

<div id="modal-press" class="writing-modal">
  <div class="writing-modal-inner">
    <button class="modal-close" onclick="closeWritingModal('press')">✕</button>
    <h2>Press Release Copywriting</h2>
    <p class="writing-company">Andrews McMeel Publishing</p>
    <p><em>Writing samples coming soon.</em></p>
    <p>[ Placeholder for writing sample / PDF / link ]</p>
  </div>
</div>

<div id="modal-review" class="writing-modal">
  <div class="writing-modal-inner">
    <button class="modal-close" onclick="closeWritingModal('review')">✕</button>
    <h2>Review Writing</h2>
    <p class="writing-company">The Tracking-Board · The Industry</p>
    <p><em>Writing samples coming soon.</em></p>
    <p>[ Placeholder for writing sample / PDF / link ]</p>
  </div>
</div>

## Additional Bylines

- **KIOSK Magazine** — Contributing Writer
- **University Daily Kansan** — Opinion Columnist

---

## Writing Specialties
SEO writing, brand copywriting, health and wellness content,
education and policy writing, entertainment writing, opinion
and column writing, editorial strategy, short-form and long-form
content, brand voice development.

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
