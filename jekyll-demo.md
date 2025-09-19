---
layout: default
title: Jekyll Demo
---

<!-- Load MathJax for this page -->
<script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

<!-- Reuse your site's CSS so this page matches index.html -->
<link rel="stylesheet" href="styles.css" />

<!-- Optional: back link -->
<p><a href="index.html">← Back to Home (HTML version)</a></p>

<div class="container">
<h1>Welcome to My Jekyll Page</h1>

<p>This page is written in <strong>Markdown</strong> but styled to match your HTML page.</p>

<h2>Inline & Block Math</h2>

<p>Inline: 
  
  $E = mc^2$
  
  or \( E = mc^2 \)</p>

<p>Block:</p>

$$
\int_{-\infty}^{\infty} e^{-x^2}\, dx = \sqrt{\pi}
$$

<h2>Bullet Points</h2>

- Easier to type than HTML
- Uses Markdown + LaTeX
- Styled with your <code>styles.css</code>
</div>
