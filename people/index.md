---
title: People
nav:
  order: 2
---

# <i class="fas fa-users"></i>People

{% include section.html %}

{%
  include feature.html
  image="images/headshots/fong.png"
  headline="Ming-fai Fong"
  text="Ming-fai Fong received her BS in Mechanical Engineering from MIT and PhD in Neuroscience from Emory University.  She completed her postdoctoral training in the Department of Brain and Cognitive Sciences at MIT and a visiting lectureship in the Neuroscience Department at Wellesley College.  Dr. Fong will be joining the Coulter Department of Biomedical Engineering at Georgia Tech and Emory as an assistant professor in Fall 2021."
%}


{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: manager"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: technician"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: graduate"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergraduate"
%}

{:.center}

{% include section.html}

{%
  include link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
  style="button"
%}
{:.center}

{% include section.html %}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: alum"
%}
