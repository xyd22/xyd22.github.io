---
layout: default
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---

<div class="cv-page">
    <div class="cv-header">
        <h1>Curriculum Vitae</h1>
        <a href="/files/CV.pdf" download class="download-btn">
            📥 Download PDF
        </a>
    </div>

    <div class="cv-preview">
        <iframe src="/files/CV.pdf" width="100%" height="800px" style="border: none;">
            <p>Your browser doesn't support PDF preview. 
               <a href="/files/CV.pdf" download>Download the CV instead</a>.
            </p>
        </iframe>
    </div>

    <div class="cv-alternative">
        <p>Alternative: <a href="/files/CV.pdf" target="_blank">Open PDF in new tab</a></p>
    </div>
</div>

<style>
.cv-page {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

.cv-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 30px;
    flex-wrap: wrap;
    gap: 15px;
}

.download-btn {
    background: #00369f;
    color: white;
    padding: 12px 24px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}

.download-btn:hover {
    background: #00257a;
}

.cv-preview {
    border: 1px solid #ddd;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.cv-alternative {
    text-align: center;
    margin-top: 15px;
    color: #666;
}
</style>