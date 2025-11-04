---
# layout: default
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---

<div class="cv-container">
    <div class="cv-header">
        <h1>Curriculum Vitae</h1>
        <a href="files/CV.pdf" download class="download-btn">
            📥 Download PDF
        </a>
    </div>

    <div class="cv-preview">
        <iframe src="/assets/docs/CV.pdf#view=FitH" width="100%" height="800px" style="border: none;">
            <p>Your browser doesn't support PDF preview. 
               <a href="/assets/docs/CV.pdf" download>Download the CV instead</a>.
            </p>
        </iframe>
    </div>

    <div class="cv-alternative">
        <p>Alternative: 
            <a href="/assets/docs/CV.pdf" target="_blank">Open PDF in new tab</a> | 
            <a href="/assets/docs/CV.pdf" download>Direct Download</a>
        </p>
    </div>
</div>

<style>
.cv-container {
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
    transition: background 0.3s ease;
}

.download-btn:hover {
    background: #00257a;
    text-decoration: none;
    color: white;
}

.cv-preview {
    border: 1px solid #ddd;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    margin-bottom: 20px;
}

.cv-alternative {
    text-align: center;
    color: #666;
    font-size: 0.9em;
}

.cv-alternative a {
    color: #00369f;
    text-decoration: none;
}

.cv-alternative a:hover {
    text-decoration: underline;
}

/* 响应式设计 */
@media (max-width: 768px) {
    .cv-header {
        flex-direction: column;
        text-align: center;
    }
    
    .cv-preview iframe {
        height: 600px;
    }
}
</style>