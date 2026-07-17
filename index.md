---
layout: page
---

# Ruijie Wu

<img src="/images/images/avatar.jpg" class="floatpic" alt="Ruijie Wu">

### Existential Psychotherapist  
### Dance Movement Therapist

<br>

> **Breathing · Flowing · Being**

---

## About

Hello, I'm **Ruijie (Eagle) Wu**.

I am an existential psychotherapist, dance movement therapist, and psychomotor therapist whose work centers on the relationship between body, movement, emotion, and meaning.

My clinical practice integrates existential psychotherapy, embodiment, trauma-informed care, and dance movement therapy. Rather than viewing the body and mind as separate, I see movement, emotion, relationship, and lived experience as different expressions of the same human process.

Originally from China, my professional journey has taken me through clinical work, research, and study across China, France, and Germany. These experiences continue to shape how I understand psychotherapy—not only as a profession, but as an ongoing practice of curiosity, presence, and encounter.

RJ Dasein is more than a personal website.

It is a digital garden where I document ideas, therapeutic practice, movement, writing, workshops, and the everyday experiences that continue shaping my understanding of what it means to be human.

I hope this space invites you to pause, breathe, and perhaps discover something meaningful along the way.

---

## Professional Journey

<div class="timeline-item timeline-item--current">
  <div class="timeline-dot" style="background: #ffffff;">
    <img src="/images/logo/srh.svg" alt="SRH">
  </div>
  <div class="timeline-card">
    <div class="timeline-header">
      <div class="timeline-role">
        M.A. Dance Movement Therapy
        <span class="timeline-sep">|</span>
        <span class="timeline-company">SRH University Heidelberg</span>
      </div>
      <span class="timeline-time">Oct. 2026 – Present</span>
    </div>
    <div class="timeline-details">
      Beginning a new chapter in Germany, exploring the intersection of psychotherapy, movement, embodiment, and creative expression through Dance Movement Therapy.
    </div>
  </div>
</div>

  <div class="timeline-item">
  <div class="timeline-dot" style="background: #ffffff;">
    <img src="/images/logo/paris.svg" alt="Paris">
  </div>
  <div class="timeline-card">
    <div class="timeline-header">
      <div class="timeline-role">
        Existential Psychotherapist
        <span class="timeline-sep">|</span>
        <span class="timeline-company">Private Practice · Paris</span>
      </div>
      <span class="timeline-time">2025 – 2026</span>
    </div>
    <div class="timeline-details">
      Providing psychotherapy for adults from diverse cultural backgrounds while facilitating movement-based therapeutic groups and workshops.
    </div>
  </div>
</div>

  <div class="timeline-item">
  <div class="timeline-dot" style="background: #ffffff;">
    <img src="/images/logo/upc.svg" alt="Université Paris Cité">
  </div>
  <div class="timeline-card">
    <div class="timeline-header">
      <div class="timeline-role">
        University Diploma in Psychotraumatology
        <span class="timeline-sep">|</span>
        <span class="timeline-company">Université Paris Cité</span>
      </div>
      <span class="timeline-time">2025</span>
    </div>
    <div class="timeline-details">
      Advanced training in trauma, PTSD, grief, attachment, and evidence-informed psychotherapy.
    </div>
  </div>
</div>

 <div class="timeline-item">
  <div class="timeline-dot" style="background: #ffffff;">
    <img src="/images/logo/isrp.svg" alt="ISRP Paris">
  </div>
  <div class="timeline-card">
    <div class="timeline-header">
      <div class="timeline-role">
        Master in Psychomotor Therapy
        <span class="timeline-sep">|</span>
        <span class="timeline-company">ISRP Paris</span>
      </div>
      <span class="timeline-time">2023 – 2024</span>
    </div>
    <div class="timeline-details">
      Studied embodiment, developmental psychology, psychomotor rehabilitation, and therapeutic movement in clinical settings.
    </div>
  </div>
</div>

  <div class="timeline-item">
  <div class="timeline-dot" style="background: #ffffff;">
    <img src="/images/logo/hospital.svg" alt="Psychiatric Hospital">
  </div>
  <div class="timeline-card">
    <div class="timeline-header">
      <div class="timeline-role">
        Psychotherapist
        <span class="timeline-sep">|</span>
        <span class="timeline-company">Psychiatric Hospital</span>
      </div>
      <span class="timeline-time">2020 – 2022</span>
    </div>
    <div class="timeline-details">
      Worked within a multidisciplinary psychiatric hospital, providing psychotherapy and rehabilitation support for individuals living with severe mental health conditions.
    </div>
  </div>
</div>
<div class="timeline-item">
  <div class="timeline-dot">
      🌿
  </div>
  <div class="timeline-card">
    <div class="timeline-header">
      <div class="timeline-role">
        Still Becoming
        <span class="timeline-sep">|</span>
        <span class="timeline-company">RJ Dasein</span>
      </div>
      <span class="timeline-time">Present →</span>
    </div>
    <div class="timeline-details">
      Every place I have lived, every person I have met, every movement I have explored continues to shape the therapist—and the human being—I am becoming.
    </div>
  </div>
</div>
</div>

<script>
(function() {
  var timelineProgress = document.getElementById('timeline-progress');
  var timeline = document.querySelector('.timeline');
  if (!timelineProgress || !timeline) return;

  var items = timeline.querySelectorAll('.timeline-item');

  // IntersectionObserver for in-view class
  if ('IntersectionObserver' in window) {
    var observer = new IntersectionObserver(function(entries) {
      entries.forEach(function(entry) {
        if (entry.isIntersecting) {
          entry.target.classList.add('in-view');
        }
      });
    }, { rootMargin: '0px 0px -15% 0px' });

    items.forEach(function(item, idx) {
      if (idx < 3) {
        // Reveal first 3 immediately on load (still gets the stagger transition)
        item.classList.add('in-view');
      } else {
        observer.observe(item);
      }
    });
  } else {
    items.forEach(function(item) { item.classList.add('in-view'); });
  }

  // Scroll progress bar
  window.addEventListener('scroll', function() {
    var rect = timeline.getBoundingClientRect();
    var totalHeight = timeline.offsetHeight;
    var windowH = window.innerHeight;
    var lineTop = 30;
    var lineBottom = 30;
    var lineHeight = totalHeight - lineTop - lineBottom;

    if (rect.top < windowH && rect.bottom > 0) {
      var scrolled = Math.min(1, Math.max(0, (windowH - rect.top - lineTop) / (totalHeight - lineTop + windowH * 0.4)));
      timelineProgress.style.height = Math.min(scrolled * lineHeight, lineHeight) + 'px';
    }
  }, { passive: true });
})();
</script>

If you are interested in any aspect of me, I am always open to discussions and collaborations. Feel free to reach out to me at - hello@rjdasein.com

**<font color="#990000">Seeking Software Engineer and Machine Learning roles — AI Infrastructure, Applied AI / Agents, and ML Systems. Feel free to reach out!</font>**

---

## Practice

My practice is grounded in existential philosophy, embodied awareness, and the belief that meaningful change emerges through relationship, movement, and lived experience.

Rather than working from a single theoretical orientation, I integrate different approaches according to each person's unique way of being in the world.

### Areas of Practice

- Existential Psychotherapy
- Dance Movement Therapy
- Trauma & PTSD
- Grief & Loss
- Embodiment
- Cross-cultural Mental Health
- Group Therapy
- Creative Arts in Psychotherapy

---

> *"The body remembers, movement reveals, and relationship transforms."*
</div>

---




---

## Current

📍 Hanoi, Vietnam

Currently exploring...

• Figure skating
• Violin
• German
• Dance Movement Therapy
• Cross-cultural psychotherapy

Recently visited...

🇯🇵 Japan
🇮🇩 Indonesia
🇲🇾 Malaysia

Next...

🇩🇪 Heidelberg
