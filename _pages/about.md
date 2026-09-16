---
permalink: /
title: "Jennifer Chien"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

> **I'm on the faculty job market this cycle!**

I'm currently an Embedded Ethics Postdoctoral Fellow at Stanford, jointly through the [McCoy Family Center for Ethics in Society](https://ethicsinsociety.stanford.edu/) and the [Institute for Human-Centered AI (HAI)](https://hai.stanford.edu/), working with [James Landay](https://www.landay.org/) and [Leif Wenar](https://www.wenar.info/). I completed my PhD in Computer Science at UC San Diego (dissertation: *User Agency Across the Machine Learning Pipeline*), advised by [Margaret Roberts](http://www.margaretroberts.net/) and [David Danks](https://www.daviddanks.org/), and my BA in Computer Science (minors in Mathematics and Statistics) at Wellesley College, where I graduated Magna Cum Laude and was inducted into Phi Beta Kappa and Sigma Xi.

My work asks how we can design systems that remain responsive to the users and contexts _throughout deployment_ (i.e., when their original assumptions do not hold). I **develop mechanisms** that collect corrective data by enabling users to override decisions and **evaluation methodologies** to show that they succeeded. My work has examined two key facets of user agency: instrumental agency (i.e., what a user can do), and cognitive and epistemic agency (i.e., what a user can think or know), through feedback mechanisms, formal fairness guarantees, post-deployment mitigation strategies, and actionable evaluation metrics and design criteria.

My work has been published in top AI ethics venues ACM FAccT, AAAI/ACM AIES, EAAMO, and ACM CHI, where I received Editor's Choice Award (CHI '24) and has led to invited talks or being featured at Microsoft, IBM, Hugging Face, and at several universities. I have been lucky to have my work supported by the [Graduate Fellowship for STEM Development](https://stemfellowships.org/), the [UCSD School of Global Policy & Strategy Science Policy Fellowship](https://gpsnews.ucsd.edu/science-policy-fellows-program-nurtures-effective-scholars/), and as an [Embedded Ethics Fellow](https://ethicsinsociety.stanford.edu/postdoctoral/application-process-embedded-ethics-fellowship) with the McCoy Family Center for Ethics in Society and the Stanford Institute for Human-Centered AI (HAI).

**Research interests:** Responsible Artificial Intelligence/Machine Learning, Algorithmic Fairness, Algorithmic Recourse, User Agency, Representational Bias/Harms, Sociotechnical Research, Sequential Decision Making, Ethical, Trustworthy, and Safe AI


<aside class="home-updates" markdown="1">
### Recent Updates
<ul class="updates-list">
  <li><span class="update-date">Oct 2026</span><span class="update-text">"What Should AI Generate? Moving Beyond Bias in Generative Systems" accepted to AIES 2026</span></li>
  <li><span class="update-date">Oct 2026</span><span class="update-text">"Making Room for Speech Diversity" accepted to Interspeech 2026</span></li>
  <li><span class="update-date">Sep 2026</span><span class="update-text">"Fairness Vs. Personalization: Towards Equity in Epistemic Utility" accepted to the Journal of Responsible Computing</span></li>
  <li><span class="update-date">Aug 2026</span><span class="update-text">Interviewed by Instyle Magazine for <a href="https://www.instyle.com/how-ai-is-changing-plastic-surgery-in-2026-12013876">"Is AI Face Coming for All of Us?"</a></span></li>
  <li><span class="update-date">Jun 2026</span><span class="update-text">Invited Speaker on the Dialexicon Podcast called <a href="https://open.spotify.com/episode/4rurvKuhfDIvIIbEI8IXec?si=bf692abda2cf45cf&nd=1&dlsi=904f00f88b3e474a">"Unpacking the AI Doom Spiral"</a></span></li>
  <li><span class="update-date">Jun 2026</span><span class="update-text">"Making Ethics Matter: Relatable Pedagogical Approaches for Every Computer Science Student" accepted to RESPECT 2026</span></li>
  <li><span class="update-date">Dec 2025</span><span class="update-text">Invited talk at USD, "Representations: How We Shape Them and How They Shape Us"</span></li>
  <li><span class="update-date">Sep 2025</span><span class="update-text">Started my postdoc at Stanford University</span></li>
  <li><span class="update-date">Jun 2025</span><span class="update-text">Successfully defended my <a href="https://escholarship.org/uc/item/7br693r0">dissertation</a> and graduated!</span></li>
</ul>
</aside>

<br>
<hr class="section-divider" />

### Selected Publications

{% include base_path %}
{% for post in site.publications reversed %}
  {% if post.category == 'conferences' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<hr class="section-divider" />

