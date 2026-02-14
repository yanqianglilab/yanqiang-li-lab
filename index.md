---
layout: default
title: Home
---

<div class="hero">
  <h1>Epigenetics & Computational RNA Biology Laboratory</h1>
  <p>
    We develop computational and experimental methods to decode RNA regulation and RNA modifications,
    with a focus on Nanopore direct RNA sequencing and cancer epitranscriptomics.
  </p>

  <p><b>PI:</b> Yanqiang Li — Professor; The First Affiliated Hospital of Xi'an Jiaotong University, PhD Supervisor</p>

  <span class="badge">Nanopore direct RNA-seq</span>
  <span class="badge">RNA modifications (Nm, Ψ, m6A)</span>
  <span class="badge">Computational biology</span>
  <span class="badge">Cancer epigenetics</span>
</div>

<div class="grid">
  <div class="col-8">
    <div class="card">
      <h3>Research Themes</h3>
      <ul class="list-tight">
        <li><b>AI-enabled Nanopore sequencing</b> for sensitive detection of low-abundance, hard-to-localize RNA modifications.</li>
        <li><b>Mechanisms in urological cancers</b> driven by dysregulated RNA modification pathways.</li>
        <li><b>Therapeutic strategies</b> targeting RNA modification regulators for precision oncology.</li>
      </ul>
      <p style="margin-top:10px;">
        See <a href="{{ "/research/" | relative_url }}">Research</a> for details.
      </p>
    </div>

    <hr class="sep"/>

    <div class="card">
      <h3>Selected Publications</h3>
      <ul class="list-tight">
        <li><b>2024</b>. 2’-O-Methylation at internal site on mRNA promotes RNA stability. <i>Molecular Cell</i>.</li>
        <li><b>2023</b>. Low RNA stability signifies increased post-transcriptional regulation of cell identity gene expression. <i>Nucleic Acids Research</i>.</li>
        <li><b>2021</b>. A PRC2-independent function for EZH2 in regulating rRNA 2′-O methylation and IRES-dependent translation. <i>Nature Cell Biology</i>.</li>
      </ul>
      <p style="margin-top:10px;">
        Full list: <a href="{{ "/publications/" | relative_url }}">Publications</a>.
      </p>
    </div>
  </div>

  <div class="col-4">
    <div class="card">
      <h3>News</h3>
      {% assign news = site.data.news | sort: "date" | reverse %}
      <ul class="list-tight">
        {% for n in news limit:6 %}
          <li><b>{{ n.date }}</b> — {{ n.text }}</li>
        {% endfor %}
      </ul>
      <p style="margin-top:10px;">
        More: <a href="{{ "/news/" | relative_url }}">News</a>.
      </p>
    </div>

    <div style="height:16px"></div>

    <div class="card">
      <h3>Join Us</h3>
      <p>
        We welcome motivated students and postdocs in bioinformatics, epigenetics,
        and RNA biology.
      </p>
      <p><a href="{{ "/join/" | relative_url }}">Open positions & how to apply →</a></p>
    </div>

    <div style="height:16px"></div>

    <div class="card">
      <h3>Contact</h3>
      <p>Email: <a href="mailto:yanqiang.li@xjtu.edu.cn">yanqiang.li@xjtu.edu.cn</a></p>
      <p><a href="{{ "/contact/" | relative_url }}">More contact info →</a></p>
    </div>
  </div>
</div>
