---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
-title: "A Post-Quantum One Time Signature Using Bloom Filter"
		+title: "A Post-Quantum One Time Signature Using Bloom Filter"
		 collection: publications
		-permalink: /publications/2009-10-01-paper-title-number-1
		-venue: "PST 2017: 397-399"
		-excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
		+permalink: /publications/2009-10-01-test-accts-intro
		+venue: "Testing Studies"
		+excerpt: 'This paper is about testing.'
		 date: 2017
		 # paperurl: http://academicpages.github.io/files/paper1.pdf
		-citation: 'Masoumeh Shafieinejad, Rei Safavi-Naini. (2017). "Paper Title Number 1." <i>Journal 1</i>. 1(1).'
		+citation: 'Masoumeh Shafieinejad, Rei Safavi-Naini. (2017). "Test Accounts: An Introduction." <i>Testing Studies</i>. 1(1).'
