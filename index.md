---
---

Welcome to BioInCode Lab!
We are pioneering breakthroughs in biomedical research through advanced AI and machine learning approaches.

{% include section.html %}

## Notice
BIC Lab 에서 함께 연구할 2025학년도 학부연구생 및 2025/2026학년도 대학원생 (석사, 박사과정) 을 모집합니다. 관심있는 학생들은 교수님 이메일로 간단한 자기소개와 이력서 (CV) 를 보내기 바랍니다.

BIC Lab is looking for undergraduate and graduate students (M.S. and Ph.D.) for 2025 and 2026, respectively. Students who want to join BIC Lab send CV to Prof. Lee.

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
