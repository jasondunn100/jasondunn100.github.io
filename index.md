---
layout: page
title: Jason Dunn
---
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">

# Jason Dunn
**PhD Candidate | Department of Economics, Boston University**

<div style="display: flex; align-items: flex-start; gap: 30px;">
  
  <!-- Left Column: Picture + Horizontal Social Row -->
  <div style="width: 400px; flex-shrink: 0; display: flex; flex-direction: column; gap: 10px;">
    <img src="assets/img/prof_pic.jpg" style="width: 100%; border-radius: 8px;">
    
    <!-- Row of 6 Square Icon Buttons -->
    <div style="display: flex; justify-content: space-between; gap: 4px;">
      <a href="mailto:jtdunn@bu.edu" class="social-icon-btn" title="Email">
        <i class="fa-regular fa-envelope"></i>
      </a>
      <a href="assets/dunn_cv.pdf" target="_blank" class="social-icon-btn" title="Curriculum Vitae">
        <span style="font-weight: bold; font-size: 0.85em; font-family: sans-serif;">CV</span>
      </a>
      <a href="https://scholar.google.com/citations?user=mKzc0Q4AAAAJ" target="_blank" rel="noopener noreferrer" class="social-icon-btn" title="Google Scholar">
        <i class="fa-solid fa-graduation-cap"></i>
      </a>
      <a href="https://github.com/jasondunn100" target="_blank" rel="noopener noreferrer" class="social-icon-btn" title="GitHub">
        <i class="fa-brands fa-github"></i>
      </a>
      <a href="https://www.linkedin.com/in/jasondunn99/" target="_blank" rel="noopener noreferrer" class="social-icon-btn" title="LinkedIn">
        <i class="fa-brands fa-linkedin-in"></i>
      </a>
      <a href="https://x.com/JasonTDunnEcon" target="_blank" rel="noopener noreferrer" class="social-icon-btn" title="X (Twitter)">
        <i class="fa-brands fa-x-twitter"></i>
      </a>
    </div>
  </div>
  
  <!-- Right Column: Bio Text -->
  <div style="font-size: 1.2em; line-height: 1.5;">
  Hello, and welcome to my website! I am a PhD candidate at the <a href="https://www.bu.edu/econ/">Boston University Department of Economics</a>. My research specializes mainly in economic history, labor, migration, and education. I am particularly interested in leveraging modern computational methods (e.g. LLMs, OCR, and GIS) to digitize large-scale historical records for economic analysis.
    <br><br>
    I formerly worked as a research associate at the <a href="https://www.stlouisfed.org/research">St. Louis Federal Reserve</a>. My research with Fernando Leibovici on international shipping and trade has been featured on the <a href="https://www.wsj.com/articles/new-studies-find-unprecedented-impact-from-supply-chain-turmoil-11641587220">Wall Street Journal</a>, <a href="https://www.barrons.com/articles/baltimore-key-bridge-collapse-us-economy-3f39bccc">Barron’s</a>, and <a href="https://www.economist.com/business/2024/12/03/how-painful-will-trumps-tariffs-be-for-american-businesses">The Economist</a>.
  </div>

</div>

<div style="height: 0px;"></div>

### Working Papers

* **Ghost Towns and Big Cities: Historical Mining Districts and Economic Activity in the American West** with <a href="https://jamessiodla.com/">James Siodla</a><br>(Conditionally Accepted at the _Journal of Economic History_)
  <div style="margin-top: 5px;">
    <a href="assets/mining.pdf" target="_blank" class="paper-btn">Paper</a>
    <a href="assets/mining_appendix.pdf" target="_blank" class="paper-btn">Online Appendix</a>
    <details style="margin-top: 4px;">
      <summary style="cursor: pointer; color: #4A148C; font-weight: bold;">
        Abstract
      </summary>
      <div style="margin-top: 5px; font-style: italic; font-size: 0.95em;">
        This paper identifies the impact of gold and silver mining discoveries in the American West on the origins and death rates of western towns and the region's long-run population distribution. Between 1850 and 1940, the discovery of mining sites increased the likelihood that a town formed nearby relative to other locations. Many of these towns eventually died, however, due largely to their relatively poor geography. Nevertheless, locations near mining sites exhibit conditional persistence: they are denser today than surrounding areas, but only when accounting for geographic confounders. Our findings suggest that historical mining activity influenced the locations of cities and towns in the American West and geography helped determine their long-run prospects for survival.
      </div>
    </details>
  </div>

* **Navigating the Waves of Global Shipping: Drivers and Aggregate Implications** <br>with <a href="https://www.fernandoleibovici.com/">Fernando Leibovici</a><br>(Revise & Resubmit at the _American Economic Review_)
  <div style="margin-top: 5px;">
    <a href="assets/shipping.pdf" target="_blank" class="paper-btn">Paper</a>
    <a href="assets/shipping_appendix.pdf" target="_blank" class="paper-btn">Online Appendix</a>
    <details style="margin-top: 4px;">
      <summary style="cursor: pointer; color: #4A148C; font-weight: bold;">
        Abstract
      </summary>
      <div style="margin-top: 5px; font-style: italic; font-size: 0.95em;">
        This paper studies the drivers of global shipping dynamics and their aggregate implications. We document novel evidence on the dynamics of global shipping supply, demand, and costs. Motivated by this evidence, we set up a dynamic model of international trade with a global shipping market where shipping firms and importers endogenously determine shipping supply and costs. We find the model accounts for the dynamics of global shipping observed at business cycle frequencies and in the aftermath of COVID-19. Accounting for global shipping significantly affects the dynamics of aggregate economic activity.
      </div>
    </details>
  </div>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    const links = document.querySelectorAll("a");
    links.forEach(link => {
      // Automatically opens external links and internal asset PDFs in a new tab
      if (link.hostname !== window.location.hostname || link.href.includes('.pdf')) {
        if (!link.href.startsWith('mailto:')) {
          link.target = "_blank";
          link.rel = "noopener noreferrer";
        }
      }
    });
  });
</script>
