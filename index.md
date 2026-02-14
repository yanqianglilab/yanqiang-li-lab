---
layout: default
title: Home
---

<div class="hero">

<h1>Epigenetics & Computational RNA Biology Laboratory</h1>

<p>
We develop computational and experimental approaches to decode RNA regulation and epitranscriptomic mechanisms, with a particular focus on Nanopore direct RNA sequencing, RNA modifications, and cancer biology.
</p>

<p>
<b>Principal Investigator:</b>
<b>Yanqiang Li</b> is a Professor at the First Affiliated Hospital of Xi’an Jiaotong University and a PhD supervisor in Bioinformatics.
He earned his bioinformatics Ph.D. from the Shanghai Institutes for Biological Sciences, Chinese Academy of Sciences, in 2016, where he was mentored by Prof. Renyi Liu.
In August 2016, he began postdoctoral training in human epigenetics at Johns Hopkins University under the mentorship of Prof. Zhibin Wang.
From July 2018 to October 2020, he continued his postdoctoral research on computional biology at Houston Methodist Hospital / Weill University e with Prof. Kaifu Chen.
He subsequently joined Harvard Medical School and Boston Children’s Hospital in Prof. Chen’s laboratory, where he conducted further bioinformatics research and was appointed Instructor in October 2022.
In March 2025, he joined the First Affiliated Hospital of Xi’an Jiaotong University as Professor.
His research focuses on tumor-associated RNA modifications, computational epitranscriptomics, long-read sequencing technologies, and molecular mechanisms of cancer.
</p>
<span class="badge">Nanopore direct RNA-seq</span>
<span class="badge">RNA modifications (Nm, Ψ, m6A)</span>
<span class="badge">Computational biology</span>
<span class="badge">Cancer epigenetics</span>

</div>


<div class="grid">

<div class="col-8">

<div class="card">
<h3>Research Directions</h3>

<ul class="list-tight">
<li><b>AI-enabled Nanopore sequencing</b> for sensitive detection of low-abundance and difficult-to-resolve RNA modifications.</li>

<li><b>RNA modification mechanisms in urological cancers</b>, integrating multi-omics, long-read sequencing, and functional validation.</li>

<li><b>Precision oncology strategies</b> targeting RNA-modification regulators and epitranscriptomic pathways.</li>
</ul>

<p style="margin-top:10px;">
See <a href="{{ "/research/" | relative_url }}">Research</a> for details.
</p>

</div>


<hr class="sep"/>


<div class="card">

<h3>Selected Publications</h3>

<ul class="list-tight">

<li><b>2024</b>. 2’-O-Methylation at internal sites on mRNA promotes RNA stability. <i>Molecular Cell</i>.</li>

<li><b>2023</b>. Low RNA stability signifies increased post-transcriptional regulation of cell identity gene expression. <i>Nucleic Acids Research</i>.</li>

<li><b>2021</b>. A PRC2-independent function for EZH2 in regulating rRNA 2′-O methylation and IRES-dependent translation. <i>Nature Cell Biology</i>.</li>

</ul>

<p style="margin-top:10px;">
Full list:
<a href="{{ "/publications/" | relative_url }}">Publications</a>.
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
More:
<a href="{{ "/news/" | relative_url }}">News</a>.
</p>

</div>


<div style="height:16px"></div>


<div class="card">
<h3>Join Us</h3>

<p>
We welcome highly motivated students, clinicians, and postdoctoral fellows interested in bioinformatics, RNA biology, epigenetics, and cancer research.
</p>

<p>
<a href="{{ "/join/" | relative_url }}">Open positions & how to apply →</a>
</p>

</div>


<div style="height:16px"></div>


<div class="card">
<h3>Contact</h3>

<p>Email:
<a href="mailto:yanqiang.li@xjtu.edu.cn">yanqiang.li@xjtu.edu.cn</a>
</p>

<p>
<a href="{{ "/contact/" | relative_url }}">More contact info →</a>
</p>

</div>


</div>

</div>
