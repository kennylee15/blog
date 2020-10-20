---
layout: page
title : About
permalink: /about/
---

<center><h1>   </h1></center>
<div class="separator separator-danger">♦</div>

### Hi, I'm Kenny.

I am an economist based in New York City. I am interested in how data and new technologies push the boundaries of research in economics and other social sciences.

Please visit my <a href="http://{{ site.personalpage }}"><i class="fa fa-home"></i> personal website</a> or contact me via: 
<ul>
  {% if site.email %}
    <li>
      <a href="mailto:{{ site.email }}?Subject=Hello!" target="_top"><i class="fa fa-envelope-square"></i> Email</a>
    </li>  
  {% endif %}
  {% if site.linkedin_username %}
    <li>
      <a href="https://www.linkedin.com/in/{{ site.linkedin_username }}"><i class="fa fa-linkedin-square"></i> LinkedIn</a>
    </li>
  {% endif %}
  {% if site.github_username %}
    <li>
      <a href="https://github.com/{{ site.github_username }}"><i class="fa fa-github-square"></i> Github</a>
    </li>
  {% endif %}
  {% if site.twitter_username %}
    <li>
      <a href="https://twitter.com/{{ site.twitter_username }}"><i class="fa fa-twitter-square"></i> Twitter</a>
    </li>
  {% endif %}
</ul>

<div class="separator">♦</div>

### Numerical Thoughts

The world is immeasurably unpredictable. I'd lke to share anything related to data and tools (Julia, Python and R) that might help us measure this world better.
