---
layout: default
title: About
---

<div class="hero">
  <div class="hero-header">
    <h1>Mohammed Abdul <strong>Hafeez</strong> Khan</h1>
    <div class="subtitle">PhD Student, Florida Tech · NASA Research Assistant</div>
  </div>

  <img src="{{ '/assets/images/headshot.png' | relative_url }}" alt="Headshot">

  <div class="hero-body">
    <p>
      Welcome! I am a PhD student specializing in how models adapt under distribution shift, 
      addressing challenges in continual learning, and few-shot learning. 
      My advisor is <a href="https://www.fit.edu/faculty-profiles/b/bhattacharyya-siddhartha/" target="_blank">Siddhartha Bhattacharyya</a>, 
      and I am funded by NASA, where I am working on lane detection for autonomous driving and taxiing on airports. 
    </p>

    <p>
      Previously, I completed my undergraduate studies at BITS Pilani Dubai, 
      where I finished my thesis under the guidance of 
      <a href="https://www.bits-pilani.ac.in/dubai/raja-muthalagu/" target="_blank">Raja Muthalaghu</a> and received the 
      Outstanding Undergraduate Thesis Award. 
      Alongside my PhD, I have worked closely with mentors from Microsoft Research, NASA Langley, UTHealth Houston, Collins Aerospace. 
      Through these collaborations, I have gained extensive experience especially in self-supervised models, diffusion models, and multimodal large-language models.
    </p>

    <p>
      <em>I’m open to collaborations—feel free to reach out by email if our interests align.</em>
    </p>

    <p>
      <strong>Also, I’m actively seeking a research internship for Summer 2026—ideally one where the loss goes down, and my learning goes up!!</strong>
    </p>
  </div>
</div>

{% include news.html %}

<h2>Selected Publications</h2>
<div class="pub-list">
  {% bibliography --file papers --query @*[selected=true] %}
</div>

<div class="contact-icons">
  <a href="mailto:mkhan@my.fit.edu" target="_blank">
    <img src="{{ '/assets/icons/gmail.png' | relative_url }}" alt="Gmail">
  </a>
  <a href="https://scholar.google.com/citations?user=zSD4PWoAAAAJ&hl=en&oi=ao" target="_blank">
    <img src="{{ '/assets/icons/scholar.png' | relative_url }}" alt="Google Scholar">
  </a>
  <a href="https://github.com/hafeezkhan909" target="_blank">
    <img src="{{ '/assets/icons/github.png' | relative_url }}" alt="GitHub">
  </a>
  <a href="https://www.linkedin.com/in/mahafeezkhan/" target="_blank">
    <img src="{{ '/assets/icons/linkedin.png' | relative_url }}" alt="LinkedIn">
  </a>
</div>
