---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
I am a software engineer with experience in web development, development operations and building of REST APIS in the ICT industry.

I also possess training experience in Math and Chemistry in the education sector.

I have interest in Data Science

<b>Technologies proficient in:</b><br>
<i>
    ReactJS, HTML5, CSS, Material-UI, Semantic-UI, Python(Django/Flask), Axios, PostgreSQL,Git & Github, Bootstrap,, Travis CI,
    Heroku, Docker, Kubernetes, SQL, Auth0
</i>

<b>Technologies familiar with:</b><br>
<i>
    Node, Sequelize, Vue TypeORM, SQL, Webpack, Enzyme, Mocha, Chai, Jest, DevOps
</i>

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>