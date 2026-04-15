---
layout: post
title: "$44K to $370K+ Monthly: An 18-Month Amazon PPC Growth Story"
subtitle: "How a health and personal care brand scaled across six Amazon marketplaces at a 16.77% blended TACOS."
date: 2026-02-01
author: Garret Sumagang
cover-img: 
thumbnail-img: 
share-img: 
tags: [amazon, ppc, tacos, sponsored-products, multi-marketplace, account-growth]
---

<style>
  .blog-post h2 { margin-top: 3rem; margin-bottom: 1.25rem; }
  .blog-post p { margin-bottom: 1.1rem; line-height: 1.8; }
  .blog-post hr { display: none; }
  .blog-post table { margin: 1.5rem 0; }
  .case-study-viz { margin: 2rem 0; }
</style>
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.js"></script>

When I took over this account in July 2021, monthly revenue was sitting at $44K across all marketplaces. The brand had real products and real demand. What it did not have was a structure that could scale.

Eighteen months later, the account was generating over $370K in a single month across six Amazon marketplaces, with a blended TACOS of 16.77% on $3.19M in total revenue.

This is the story of how that happened.

<div class="case-study-viz">
<style>
  .hero-grid { display: grid; grid-template-columns: repeat(4, minmax(0,1fr)); gap: 1px; background: var(--color-border-tertiary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); overflow: hidden; margin: 1.5rem 0; }
  .hero-card { background: var(--color-background-primary); padding: 1.5rem 1.25rem; display: flex; flex-direction: column; gap: 6px; }
  .hero-label { font-size: 11px; color: var(--color-text-secondary); text-transform: uppercase; letter-spacing: 0.06em; font-weight: 500; }
  .hero-value { font-size: 28px; font-weight: 500; color: var(--color-text-primary); line-height: 1.1; }
  .hero-sub { font-size: 12px; color: var(--color-text-secondary); }
  @media (max-width: 520px) { .hero-grid { grid-template-columns: repeat(2, minmax(0,1fr)); } }
</style>
<div class="hero-grid">
  <div class="hero-card">
    <span class="hero-label">Starting revenue</span>
    <span class="hero-value">$44K</span>
    <span class="hero-sub">Monthly, Jul 2021</span>
  </div>
  <div class="hero-card">
    <span class="hero-label">Peak revenue</span>
    <span class="hero-value">$370K+</span>
    <span class="hero-sub">Monthly, Dec 2022</span>
  </div>
  <div class="hero-card">
    <span class="hero-label">Total revenue</span>
    <span class="hero-value">$3.19M+</span>
    <span class="hero-sub">18-month period</span>
  </div>
  <div class="hero-card">
    <span class="hero-label">Blended TACOS</span>
    <span class="hero-value">16.77%</span>
    <span class="hero-sub">All six marketplaces</span>
  </div>
</div>
</div>

---

## Where It Started

At $44K monthly across all marketplaces, the account had room to grow.

US and UK were the two active markets. Four European markets had some presence but were not being actively managed.

My first priority was not growth. It was understanding what I was working with.

The US had reasonable ACOS but TACOS was creeping upward. The UK was healthier, with TACOS in the 11-13% range, but campaign structure was limiting control. Budgets were shared across unrelated terms. High-performing search terms had no dedicated spend.

I started with the fundamentals: cleaning up structure, establishing baseline budgets on proven terms, and bringing the EU markets under active management.

<div class="case-study-viz">
<style>
  .ws-note { font-size: 11px; color: #999; margin-top: 10px; }
  .ws-legend { display: flex; gap: 20px; margin-bottom: 12px; font-size: 12px; color: #666; }
  .ws-swatch { width: 10px; height: 10px; border-radius: 2px; display: inline-block; margin-right: 5px; vertical-align: middle; }
</style>
<div class="ws-legend">
  <span><span class="ws-swatch" style="background:#1a3a5c;"></span>US</span>
  <span><span class="ws-swatch" style="background:#4a90c4;"></span>UK</span>
  <span><span class="ws-swatch" style="background:#a8c7e8;"></span>EU markets</span>
</div>
<div style="position: relative; width: 100%; height: 240px;">
  <canvas id="wsChart" role="img" aria-label="Starting monthly revenue by marketplace in July 2021. US $17,236, UK $25,425, DE $627, ES $423, IT $213, FR not yet active.">Starting revenue: US $17,236, UK $25,425, DE $627, ES $423, IT $213, FR not yet active.</canvas>
</div>
<p class="ws-note">July 2021 starting point. US and UK were the primary markets. EU presence was minimal.</p>
<script>
(function() {
  new Chart(document.getElementById('wsChart'), {
    type: 'bar',
    data: {
      labels: ['US','UK','DE','ES','IT','FR'],
      datasets: [{ data: [17236,25425,627,423,213,0], backgroundColor: ['#1a3a5c','#4a90c4','#a8c7e8','#a8c7e8','#a8c7e8','#a8c7e8'], borderRadius: 4, borderWidth: 0 }]
    },
    options: {
      responsive: true, maintainAspectRatio: false,
      plugins: { legend: { display: false }, tooltip: { callbacks: { label: function(ctx) { return ' $' + ctx.parsed.y.toLocaleString(); } } } },
      scales: {
        x: { ticks: { color: '#888', font: { size: 12 } }, grid: { display: false } },
        y: { ticks: { color: '#888', font: { size: 11 }, callback: function(v) { return '$' + (v/1000).toFixed(0) + 'K'; } }, grid: { color: 'rgba(128,128,128,0.1)' } }
      }
    }
  });
})();
</script>
</div>

---

## The First Phase: Steady Growth

From July 2021 through early 2022, growth was deliberate rather than aggressive.

US revenue moved from $17K to $42K by December 2021. TACOS improved from 17.35% to 13.76%, a sign that organic was beginning to compound. The UK followed a similar curve, growing from $25K to $67K with TACOS staying between 11% and 14%. The EU markets started generating consistent numbers for the first time.

This phase was about stabilizing the account and capturing early wins. Building enough data to understand where the real opportunities were.

At this point, aggressive scaling was not the plan. That changed when the client came back with new ambitions.

<div class="case-study-viz">
<style>
  .fp-legend { display: flex; gap: 20px; margin-bottom: 12px; font-size: 12px; color: #666; }
  .fp-swatch { width: 10px; height: 10px; border-radius: 2px; display: inline-block; margin-right: 5px; vertical-align: middle; }
  .fp-note { font-size: 11px; color: #999; margin-top: 10px; }
</style>
<div class="fp-legend">
  <span><span class="fp-swatch" style="background:#1a3a5c;"></span>US total sales</span>
  <span><span class="fp-swatch" style="background:#4a90c4;"></span>UK total sales (USD)</span>
</div>
<div style="position: relative; width: 100%; height: 280px;">
  <canvas id="fpChart" role="img" aria-label="US and UK monthly revenue from July 2021 through March 2022. US grew from $17K to $51K. UK grew from $25K to $55K.">US revenue grew from $17,236 in July 2021 to $51,651 in March 2022. UK revenue grew from $25,425 to $55,575 over the same period.</canvas>
</div>
<p class="fp-note">July 2021 to March 2022. Both markets growing steadily before the full structural audit was initiated.</p>
<script>
(function() {
  var labels = ['Jul 21','Aug 21','Sep 21','Oct 21','Nov 21','Dec 21','Jan 22','Feb 22','Mar 22'];
  var usData = [17236,25184,19321,32945,34231,42581,42864,30842,51651];
  var ukData = [25425,32950,31820,48333,57576,66874,61852,58134,55575];
  new Chart(document.getElementById('fpChart'), {
    type: 'line',
    data: {
      labels: labels,
      datasets: [
        { label: 'US total sales', data: usData, borderColor: '#1a3a5c', backgroundColor: 'transparent', borderWidth: 2, pointBackgroundColor: '#1a3a5c', pointRadius: 4, tension: 0.3 },
        { label: 'UK total sales', data: ukData, borderColor: '#4a90c4', backgroundColor: 'transparent', borderWidth: 2, borderDash: [5,4], pointBackgroundColor: '#4a90c4', pointStyle: 'triangle', pointRadius: 5, tension: 0.3 }
      ]
    },
    options: {
      responsive: true, maintainAspectRatio: false,
      plugins: { legend: { display: false }, tooltip: { callbacks: { label: function(ctx) { return ' $' + ctx.parsed.y.toLocaleString(); } } } },
      scales: {
        x: { ticks: { color: '#888', font: { size: 11 }, autoSkip: false, maxRotation: 45 }, grid: { color: 'rgba(128,128,128,0.1)' } },
        y: { ticks: { color: '#888', font: { size: 11 }, callback: function(v) { return '$' + (v/1000).toFixed(0) + 'K'; } }, grid: { color: 'rgba(128,128,128,0.1)' } }
      }
    }
  });
})();
</script>
</div>

---

## The Inflection Point

By late 2021 and into early 2022, the client had taken out a bank loan and made his intention clear: he wanted to scale aggressively.

A significant step up in spend requires a full account review. What is working at one level of investment needs to be stress-tested before you push it harder. I ran a structured audit across both US and UK before increasing spend, identifying where the account was strong and where it needed work before we scaled.

The findings shaped everything that followed.

By early 2022, both ACOS and TACOS were climbing. But TACOS was rising faster. By March 2022 it had crossed 20%, a sign that paid was doing more of the revenue work than organic. Pushing more spend into that dynamic without addressing the underlying structure would have compounded the problem.

<div class="case-study-viz">
<style>
  .div-legend { display: flex; gap: 20px; margin-bottom: 12px; font-size: 12px; color: #666; }
  .div-swatch { width: 10px; height: 10px; border-radius: 2px; display: inline-block; margin-right: 5px; vertical-align: middle; }
  .div-callout { display: inline-block; background: #faeeda; color: #633806; font-size: 11px; padding: 4px 10px; border-radius: 4px; margin-bottom: 12px; }
  .div-note { font-size: 11px; color: #999; margin-top: 10px; }
</style>
<div class="div-callout">TACOS crossed 20% by March 2022. A signal that paid was carrying more of the revenue load than organic.</div>
<div class="div-legend">
  <span><span class="div-swatch" style="background:#1a3a5c;"></span>TACOS %</span>
  <span><span class="div-swatch" style="background:#c0392b;"></span>Audit point</span>
</div>
<div style="position: relative; width: 100%; height: 260px;">
  <canvas id="divChart" role="img" aria-label="US TACOS from July 2021 to March 2022, rising from 17.35% to 20.70% with the audit initiated at March 2022.">US TACOS rose from 17.35% in July 2021, dipped to 13.76% in December 2021, then climbed to 20.70% by March 2022.</canvas>
</div>
<p class="div-note">TACOS dipped in the second half of 2021 as organic compounded, then rose sharply from January 2022 as spend increased without a matching organic lift.</p>
<script>
(function() {
  var labels2 = ['Jul 21','Aug 21','Sep 21','Oct 21','Nov 21','Dec 21','Jan 22','Feb 22','Mar 22'];
  var tacosData = [17.35,17.27,16.34,15.50,14.96,13.76,15.85,19.03,20.70];
  new Chart(document.getElementById('divChart'), {
    type: 'line',
    data: {
      labels: labels2,
      datasets: [{
        label: 'TACOS',
        data: tacosData,
        borderColor: '#1a3a5c',
        backgroundColor: 'rgba(26,58,92,0.06)',
        fill: true,
        borderWidth: 2,
        pointBackgroundColor: function(ctx) { return ctx.dataIndex === 8 ? '#c0392b' : '#1a3a5c'; },
        pointRadius: function(ctx) { return ctx.dataIndex === 8 ? 8 : 4; },
        tension: 0.3
      }]
    },
    options: {
      responsive: true, maintainAspectRatio: false,
      plugins: {
        legend: { display: false },
        tooltip: { callbacks: { label: function(ctx) { var s = ctx.dataIndex === 8 ? ' — audit initiated' : ''; return ' TACOS: ' + ctx.parsed.y.toFixed(2) + '%' + s; } } }
      },
      scales: {
        x: { ticks: { color: '#888', font: { size: 11 }, autoSkip: false, maxRotation: 45 }, grid: { color: 'rgba(128,128,128,0.1)' } },
        y: { min: 10, max: 25, ticks: { color: '#888', font: { size: 11 }, callback: function(v) { return v + '%'; } }, grid: { color: 'rgba(128,128,128,0.1)' } }
      }
    }
  });
})();
</script>
</div>

The March 2022 numbers made it concrete:

<div class="case-study-viz">
<style>
  .snap-grid { display: grid; grid-template-columns: repeat(5, minmax(0,1fr)); gap: 8px; margin: 1.25rem 0; }
  .snap-card { background: #f7f9fc; border: 0.5px solid #dce3ed; border-radius: 8px; padding: 0.875rem 1rem; }
  .snap-card.warn { background: #faeeda; border-color: #ef9f27; }
  .snap-label { font-size: 11px; color: #888; text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 4px; }
  .snap-card.warn .snap-label { color: #633806; }
  .snap-value { font-size: 18px; font-weight: 500; color: #1a3a5c; line-height: 1.1; }
  .snap-card.warn .snap-value { color: #633806; }
  @media (max-width: 520px) { .snap-grid { grid-template-columns: repeat(2, minmax(0,1fr)); } }
</style>
<div class="snap-grid">
  <div class="snap-card">
    <div class="snap-label">PPC Spend</div>
    <div class="snap-value">$10,678</div>
  </div>
  <div class="snap-card">
    <div class="snap-label">PPC Sales</div>
    <div class="snap-value">$27,242</div>
  </div>
  <div class="snap-card">
    <div class="snap-label">Total Sales</div>
    <div class="snap-value">$52,937</div>
  </div>
  <div class="snap-card warn">
    <div class="snap-label">ACOS</div>
    <div class="snap-value">39%</div>
  </div>
  <div class="snap-card warn">
    <div class="snap-label">TACOS</div>
    <div class="snap-value">20%</div>
  </div>
</div>
</div>

Campaigns were going out of budget 23% of the time. Amazon's native data showed the estimated missed sales in dollar terms. Based on that figure, roughly 25.7% of potential revenue was not captured during that period. The client's budget at the time was the primary constraint on growth, not campaign performance. With a bank loan now backing the account, that constraint was lifted.

Spend allocation reflected where the account was in its development. SP was consuming 84% of total budget, which is expected for an account at this stage. SP is the foundation, the highest intent format, and the right place to concentrate spend while the account is being built and optimized. SD and SB investment makes sense once SP is stable and budget allows for upper funnel expansion.

With the client now committing significantly more budget, that expansion was finally viable. SD was at 1% and SB-Headline at 2%, both well below where they needed to be to support aggressive scaling.

<div class="case-study-viz">
<style>
  .adm-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 2rem; margin: 1.5rem 0; }
  .adm-title { font-size: 13px; font-weight: 500; color: #1a3a5c; margin-bottom: 12px; }
  .adm-legend { display: flex; flex-direction: column; gap: 6px; margin-top: 14px; font-size: 12px; color: #666; }
  .adm-legend-row { display: flex; align-items: center; justify-content: space-between; }
  .adm-swatch { width: 10px; height: 10px; border-radius: 2px; display: inline-block; margin-right: 6px; vertical-align: middle; }
  .adm-callout { display: inline-block; background: #faeeda; color: #633806; font-size: 11px; padding: 4px 10px; border-radius: 4px; margin-bottom: 14px; }
  .adm-note { font-size: 11px; color: #999; margin-top: 1rem; }
  @media (max-width: 480px) { .adm-grid { grid-template-columns: 1fr; } }
</style>
<div class="adm-callout">Target benchmark: 70% SP / 20% SB / 10% SD. SD was the primary gap in both accounts.</div>
<div class="adm-grid">
  <div>
    <p class="adm-title">US — at audit</p>
    <div style="position: relative; width: 100%; height: 180px;">
      <canvas id="adUS" role="img" aria-label="US ad spend mix at audit: SP 84%, SB-Video 13.1%, SB-Headline 2%, SD 1%.">US ad spend: SP 84%, SB-Video 13.1%, SB-Headline 2%, SD 1%.</canvas>
    </div>
    <div class="adm-legend">
      <div class="adm-legend-row"><span><span class="adm-swatch" style="background:#1a3a5c;"></span>SP</span><span>84.0%</span></div>
      <div class="adm-legend-row"><span><span class="adm-swatch" style="background:#4a90c4;"></span>SB-Video</span><span>13.1%</span></div>
      <div class="adm-legend-row"><span><span class="adm-swatch" style="background:#a8c7e8;"></span>SB-Headline</span><span>2.0%</span></div>
      <div class="adm-legend-row"><span><span class="adm-swatch" style="background:#c0392b;"></span>SD</span><span>1.0%</span></div>
    </div>
  </div>
  <div>
    <p class="adm-title">UK — at audit</p>
    <div style="position: relative; width: 100%; height: 180px;">
      <canvas id="adUK" role="img" aria-label="UK ad spend mix at audit: SP 76.2%, SB-Video 14.6%, SB-Headline 8.6%, SD 0.7%.">UK ad spend: SP 76.2%, SB-Video 14.6%, SB-Headline 8.6%, SD 0.7%.</canvas>
    </div>
    <div class="adm-legend">
      <div class="adm-legend-row"><span><span class="adm-swatch" style="background:#1a3a5c;"></span>SP</span><span>76.2%</span></div>
      <div class="adm-legend-row"><span><span class="adm-swatch" style="background:#4a90c4;"></span>SB-Video</span><span>14.6%</span></div>
      <div class="adm-legend-row"><span><span class="adm-swatch" style="background:#a8c7e8;"></span>SB-Headline</span><span>8.6%</span></div>
      <div class="adm-legend-row"><span><span class="adm-swatch" style="background:#c0392b;"></span>SD</span><span>0.7%</span></div>
    </div>
  </div>
</div>
<p class="adm-note">SP-heavy allocation is expected at this stage of account development. With the client committing significantly more budget, SD and SB-Headline expansion became viable for the first time.</p>
<script>
(function() {
  var colors = ['#1a3a5c','#4a90c4','#a8c7e8','#c0392b'];
  function makeDoughnut(data, id) {
    new Chart(document.getElementById(id), {
      type: 'doughnut',
      data: { labels: ['SP','SB-Video','SB-Headline','SD'], datasets: [{ data: data, backgroundColor: colors, borderWidth: 0 }] },
      options: { responsive: true, maintainAspectRatio: false, cutout: '65%', plugins: { legend: { display: false }, tooltip: { callbacks: { label: function(ctx) { return ' ' + ctx.label + ': ' + ctx.parsed.toFixed(1) + '%'; } } } } }
    });
  }
  makeDoughnut([84.0,13.1,2.0,1.0], 'adUS');
  makeDoughnut([76.2,14.6,8.6,0.7], 'adUK');
})();
</script>
</div>

The ASIN-level spend review gave context to the budget distribution. Two variants were running at 54.99% and 91.84% TACOS respectively. Both were in an active launch and ranking phase at the time. Higher TACOS is expected and intentional at this stage. The priority is velocity and rank, not margin efficiency. The audit confirmed this was working as designed and flagged them to be brought in line with the rest of the portfolio as they matured.

<div class="case-study-viz">
<style>
  .asin-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 2rem; margin: 1.5rem 0; }
  .asin-title { font-size: 13px; font-weight: 500; color: #1a3a5c; margin-bottom: 12px; }
  .asin-legend { display: flex; gap: 16px; margin-bottom: 14px; font-size: 12px; color: #666; }
  .asin-swatch { width: 10px; height: 10px; border-radius: 2px; display: inline-block; margin-right: 5px; vertical-align: middle; }
  .asin-callout { display: inline-block; background: #faeeda; color: #633806; font-size: 11px; padding: 4px 10px; border-radius: 4px; margin-bottom: 14px; }
  .asin-note { font-size: 11px; color: #999; margin-top: 1rem; }
  @media (max-width: 480px) { .asin-grid { grid-template-columns: 1fr; } }
</style>
<div class="asin-callout">Two ASINs in active launch phase running at elevated TACOS. Intentional. The audit confirmed strategy alignment across the portfolio.</div>
<div class="asin-legend">
  <span><span class="asin-swatch" style="background:#1a3a5c;"></span>Established (optimizing for margin)</span>
  <span><span class="asin-swatch" style="background:#c0392b;"></span>Launch phase (optimizing for rank)</span>
</div>
<div class="asin-grid">
  <div>
    <p class="asin-title">US — top ASINs by TACOS</p>
    <div style="position: relative; width: 100%; height: 280px;">
      <canvas id="asinUS" role="img" aria-label="US ASIN TACOS comparison ranging from 0.43% to 91.84%.">US ASIN TACOS ranging from 0.43% to 91.84%.</canvas>
    </div>
  </div>
  <div>
    <p class="asin-title">UK — top ASINs by TACOS</p>
    <div style="position: relative; width: 100%; height: 280px;">
      <canvas id="asinUK" role="img" aria-label="UK ASIN TACOS comparison ranging from 0.29% to 33.03%.">UK ASIN TACOS ranging from 0.29% to 33.03%.</canvas>
    </div>
  </div>
</div>
<p class="asin-note">Launch phase ASINs run at higher TACOS by design. As they matured and rankings stabilized, the plan was to bring their spend in line with the rest of the portfolio.</p>
<script>
(function() {
  function makeBar(labels, data, colors, id) {
    new Chart(document.getElementById(id), {
      type: 'bar',
      data: { labels: labels, datasets: [{ data: data, backgroundColor: colors, borderWidth: 0, borderRadius: 3 }] },
      options: {
        indexAxis: 'y', responsive: true, maintainAspectRatio: false,
        plugins: { legend: { display: false }, tooltip: { callbacks: { label: function(ctx) { return ' TACOS: ' + ctx.parsed.x.toFixed(2) + '%'; } } } },
        scales: {
          x: { ticks: { color: '#888', font: { size: 11 }, callback: function(v) { return v + '%'; } }, grid: { color: 'rgba(128,128,128,0.1)' } },
          y: { ticks: { color: '#888', font: { size: 11 } }, grid: { display: false } }
        }
      }
    });
  }
  makeBar(['ASIN 8','ASIN 7','ASIN 6','ASIN 5','ASIN 4','ASIN 3','ASIN 2','ASIN 1'],[91.84,54.99,33.67,28.33,9.66,6.97,4.82,0.43],['#c0392b','#c0392b','#c0392b','#c0392b','#1a3a5c','#1a3a5c','#1a3a5c','#1a3a5c'],'asinUS');
  makeBar(['ASIN 9','ASIN 8','ASIN 7','ASIN 6','ASIN 5','ASIN 4','ASIN 3','ASIN 2','ASIN 1'],[33.03,17.93,16.56,10.92,8.77,7.76,3.89,3.14,0.29],['#c0392b','#c0392b','#c0392b','#1a3a5c','#1a3a5c','#1a3a5c','#1a3a5c','#1a3a5c','#1a3a5c'],'asinUK');
})();
</script>
</div>

The campaign structure needed to evolve to handle the level of spend the client was committing to.

With the audit complete, I worked through each area systematically. Proven converters got dedicated budgets and Top of Search modifiers. Spend was redirected away from high-TACOS variants toward those with demonstrated efficiency. 

SD and SB-Headline campaigns had been running but were significantly underinvested. With the budget constraint lifted, both were scaled aggressively for the first time. Listing issues on the top ASINs in both markets were flagged and corrected.

With the structural work done, we were ready to scale.

---

## After the Audit: Scaling with Control

With the structural work done, I pushed spend more aggressively through the second half of 2022.

The results were not linear. US revenue spiked to $165K in July 2022, then pulled back to $125K in September before recovering to $154K by December. TACOS rose during the scaling phase, peaking at 23.64% in September before moderating toward year end.

The UK told a cleaner story. Revenue grew from roughly $50K at the start of 2022 to $201K by December, with TACOS staying in the 13-17% range throughout.

<div class="case-study-viz">
<style>
  .traj-legend { display: flex; flex-wrap: wrap; gap: 20px; margin-bottom: 12px; font-size: 12px; color: #666; }
  .traj-swatch { width: 10px; height: 10px; border-radius: 2px; display: inline-block; margin-right: 5px; vertical-align: middle; }
  .traj-callout { display: inline-block; background: #e8f0f7; color: #1a3a5c; font-size: 11px; padding: 4px 10px; border-radius: 4px; margin-bottom: 14px; }
  .traj-note { font-size: 11px; color: #999; margin-top: 10px; }
</style>
<div class="traj-callout">Audit completed March 2022. Aggressive scaling initiated.</div>
<div class="traj-legend">
  <span><span class="traj-swatch" style="background:#1a3a5c;"></span>US total sales</span>
  <span><span class="traj-swatch" style="background:#4a90c4;"></span>UK total sales (USD)</span>
  <span><span class="traj-swatch" style="background:#c0392b;"></span>Audit point</span>
</div>
<div style="position: relative; width: 100%; height: 320px;">
  <canvas id="trajChart" role="img" aria-label="US and UK monthly revenue from July 2021 through December 2022. Audit marked at March 2022. Combined account peaked at $370K+ in December 2022.">US revenue grew from $17,236 in July 2021 to a peak of $164,934 in July 2022. UK revenue grew steadily from $25,425 to $201,566 by December 2022.</canvas>
</div>
<p class="traj-note">Results were not linear. US revenue spiked, pulled back, then recovered. UK told a cleaner story with a steadier growth curve throughout.</p>
<script>
(function() {
  var labels3 = ['Jul 21','Aug 21','Sep 21','Oct 21','Nov 21','Dec 21','Jan 22','Feb 22','Mar 22','Apr 22','May 22','Jun 22','Jul 22','Aug 22','Sep 22','Oct 22','Nov 22','Dec 22'];
  var usData3 = [17236,25184,19321,32945,34231,42581,42864,30842,51651,80856,126603,77360,164934,148401,125806,153739,129034,153557];
  var ukData3 = [25425,32950,31820,48333,57576,66874,61852,58134,55575,60577,83611,98893,105300,81045,105238,163101,177416,201566];
  new Chart(document.getElementById('trajChart'), {
    type: 'line',
    data: {
      labels: labels3,
      datasets: [
        {
          label: 'US total sales', data: usData3, borderColor: '#1a3a5c', backgroundColor: 'rgba(26,58,92,0.05)', fill: true, borderWidth: 2,
          pointBackgroundColor: function(ctx) { return ctx.dataIndex === 8 ? '#c0392b' : '#1a3a5c'; },
          pointRadius: function(ctx) { return ctx.dataIndex === 8 ? 7 : 3; }, tension: 0.3
        },
        {
          label: 'UK total sales', data: ukData3, borderColor: '#4a90c4', backgroundColor: 'transparent', borderWidth: 2, borderDash: [5,4],
          pointBackgroundColor: function(ctx) { return ctx.dataIndex === 8 ? '#c0392b' : '#4a90c4'; },
          pointStyle: function(ctx) { return ctx.dataIndex === 8 ? 'circle' : 'triangle'; },
          pointRadius: function(ctx) { return ctx.dataIndex === 8 ? 7 : 4; }, tension: 0.3
        }
      ]
    },
    options: {
      responsive: true, maintainAspectRatio: false,
      plugins: { legend: { display: false }, tooltip: { callbacks: { label: function(ctx) { var s = ctx.dataIndex === 8 ? ' — audit point' : ''; return ' $' + ctx.parsed.y.toLocaleString() + s; } } } },
      scales: {
        x: { ticks: { color: '#888', font: { size: 11 }, autoSkip: true, maxTicksLimit: 9, maxRotation: 45 }, grid: { color: 'rgba(128,128,128,0.1)' } },
        y: { ticks: { color: '#888', font: { size: 11 }, callback: function(v) { return '$' + (v/1000).toFixed(0) + 'K'; } }, grid: { color: 'rgba(128,128,128,0.1)' } }
      }
    }
  });
})();
</script>
</div>

---

## The Final Numbers

<div class="case-study-viz">
<style>
  .fn-section-label { font-size: 12px; font-weight: 500; color: #1a3a5c; text-transform: uppercase; letter-spacing: 0.06em; margin: 2rem 0 0.75rem; }
  .fn-legend { display: flex; gap: 20px; margin-bottom: 12px; font-size: 12px; color: #666; }
  .fn-swatch { width: 10px; height: 10px; border-radius: 2px; display: inline-block; margin-right: 5px; vertical-align: middle; }
  .fn-chart-note { font-size: 11px; color: #999; margin-top: 8px; margin-bottom: 2rem; }
  .fn-eu-note { font-size: 13px; color: #555; background: #f7f9fc; border-left: 3px solid #1a3a5c; padding: 12px 16px; border-radius: 0 4px 4px 0; margin: 1rem 0 2rem; line-height: 1.6; }
  .fn-totals-grid { display: grid; grid-template-columns: repeat(3, minmax(0,1fr)); gap: 10px; margin: 1rem 0 2rem; }
  .fn-totals-card { background: #f7f9fc; border: 0.5px solid #dce3ed; border-radius: 8px; padding: 1rem 1.25rem; }
  .fn-totals-label { font-size: 11px; color: #888; text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 4px; }
  .fn-totals-value { font-size: 22px; font-weight: 500; color: #1a3a5c; line-height: 1.1; }
  .fn-totals-card.accent { background: #1a3a5c; border-color: #1a3a5c; }
  .fn-totals-card.accent .fn-totals-label { color: #a8c7e8; }
  .fn-totals-card.accent .fn-totals-value { color: #fff; }
  @media (max-width: 480px) { .fn-totals-grid { grid-template-columns: repeat(2, minmax(0,1fr)); } }
</style>

<p class="fn-section-label">US trajectory — total sales and TACOS</p>
<div class="fn-legend">
  <span><span class="fn-swatch" style="background:#1a3a5c;"></span>Total sales</span>
  <span><span class="fn-swatch" style="background:#c0392b;"></span>TACOS %</span>
</div>
<div style="position: relative; width: 100%; height: 280px;">
  <canvas id="fnUsChart" role="img" aria-label="US monthly total sales and TACOS from July 2021 to December 2022.">US revenue grew from $17,236 to a peak of $164,934 before settling at $153,557. TACOS ranged from 13.76% to 20.70%.</canvas>
</div>
<p class="fn-chart-note">Hover over any point to see exact figures. TACOS peaked during aggressive scaling then moderated toward year end.</p>

<p class="fn-section-label">UK trajectory — total sales and TACOS</p>
<div class="fn-legend">
  <span><span class="fn-swatch" style="background:#4a90c4;"></span>Total sales (USD)</span>
  <span><span class="fn-swatch" style="background:#c0392b;"></span>TACOS %</span>
</div>
<div style="position: relative; width: 100%; height: 280px;">
  <canvas id="fnUkChart" role="img" aria-label="UK monthly total sales in USD and TACOS from July 2021 to December 2022.">UK revenue grew steadily from $25,425 to $201,566. TACOS stayed between 11.28% and 17.40%.</canvas>
</div>
<p class="fn-chart-note">UK told a cleaner story. Steady growth with controlled TACOS throughout.</p>

<p class="fn-section-label">EU markets (DE, ES, IT, FR combined)</p>
<div class="fn-eu-note">The EU markets remained lean throughout the engagement. By December 2022, the combined contribution reached roughly $15K per month in revenue that did not exist when I took over the account. All four markets ran TACOS between 9% and 16%.</div>

<p class="fn-section-label">18-month totals</p>
<div class="fn-totals-grid">
  <div class="fn-totals-card accent">
    <div class="fn-totals-label">Total revenue</div>
    <div class="fn-totals-value">$3.19M+</div>
  </div>
  <div class="fn-totals-card accent">
    <div class="fn-totals-label">Total PPC sales</div>
    <div class="fn-totals-value">$1.65M</div>
  </div>
  <div class="fn-totals-card accent">
    <div class="fn-totals-label">Total PPC spend</div>
    <div class="fn-totals-value">$534K</div>
  </div>
  <div class="fn-totals-card">
    <div class="fn-totals-label">Blended TACOS</div>
    <div class="fn-totals-value">16.77%</div>
  </div>
  <div class="fn-totals-card">
    <div class="fn-totals-label">Blended ROAS</div>
    <div class="fn-totals-value">3.09x</div>
  </div>
  <div class="fn-totals-card">
    <div class="fn-totals-label">Marketplaces</div>
    <div class="fn-totals-value">6</div>
  </div>
</div>

<script>
(function() {
  var allLabels = ['Jul 21','Aug 21','Sep 21','Oct 21','Nov 21','Dec 21','Jan 22','Feb 22','Mar 22','Apr 22','May 22','Jun 22','Jul 22','Aug 22','Sep 22','Oct 22','Nov 22','Dec 22'];
  var usSales = [17236,25184,19321,32945,34231,42581,42864,30842,51651,80856,126603,77360,164934,148401,125806,153739,129034,153557];
  var usTacos = [17.35,17.27,16.34,15.50,14.96,13.76,15.85,19.03,20.70,20.56,15.40,16.69,18.74,22.08,23.64,22.17,17.59,16.95];
  var ukSales = [25425,32950,31820,48333,57576,66874,61852,58134,55575,60577,83611,98893,105300,81045,105238,163101,177416,201566];
  var ukTacos = [11.28,12.80,14.07,15.03,13.27,13.93,15.35,13.14,13.46,13.51,13.03,14.23,14.50,14.91,16.52,17.46,16.03,17.40];
  var gridColor = 'rgba(128,128,128,0.1)';
  var tickColor = '#888';
  function makeCombo(salesData, tacosData, salesColor, canvasId) {
    new Chart(document.getElementById(canvasId), {
      type: 'bar',
      data: {
        labels: allLabels,
        datasets: [
          { type: 'bar', label: 'Total sales', data: salesData, backgroundColor: salesColor, borderRadius: 3, yAxisID: 'y' },
          { type: 'line', label: 'TACOS %', data: tacosData, borderColor: '#e07b39', backgroundColor: 'transparent', borderWidth: 2, pointBackgroundColor: '#e07b39', pointRadius: 3, tension: 0.3, yAxisID: 'y2' }
        ]
      },
      options: {
        responsive: true, maintainAspectRatio: false,
        interaction: { mode: 'index', intersect: false },
        plugins: {
          legend: { display: false },
          tooltip: { callbacks: { label: function(ctx) { if (ctx.datasetIndex === 0) return ' Revenue: $' + ctx.parsed.y.toLocaleString(); return ' TACOS: ' + ctx.parsed.y.toFixed(2) + '%'; } } }
        },
        scales: {
          x: { ticks: { color: tickColor, font: { size: 11 }, autoSkip: true, maxTicksLimit: 9, maxRotation: 45 }, grid: { color: gridColor } },
          y: { position: 'left', ticks: { color: tickColor, font: { size: 11 }, callback: function(v) { return '$' + (v/1000).toFixed(0) + 'K'; } }, grid: { color: gridColor } },
          y2: { position: 'right', min: 0, max: 35, ticks: { color: tickColor, font: { size: 11 }, callback: function(v) { return v + '%'; } }, grid: { drawOnChartArea: false } }
        }
      }
    });
  }
  makeCombo(usSales, usTacos, 'rgba(26,58,92,0.75)', 'fnUsChart');
  makeCombo(ukSales, ukTacos, 'rgba(74,144,196,0.75)', 'fnUkChart');
})();
</script>
</div>

<h2>What I Took From This</h2>

<p>A few things this engagement reinforced.</p>

<p>TACOS and ACOS divergence is a specific diagnostic signal, not a general warning. When TACOS rises faster than ACOS, the account is becoming more dependent on paid traffic to generate revenue. Treating it as a bidding problem makes it worse.</p>

<p>Budget sufficiency in performing campaigns is a precondition for scale, not an optimization on top of it. Amazon's native data showed campaigns going out of budget 23% of the time. Based on the estimated missed sales figure, roughly 25.7% of potential revenue was not captured. Underfunded campaigns on converting keywords leave growth on the table regardless of how well the bids are optimized.</p>

<p>Structure determines what you can control. Isolation of high-value terms into dedicated campaigns is not a cleanup task. It is what makes real optimization possible.</p>

<p>The audit was a turning point, but the turning point was earned by the 12 months of groundwork before it. Without that foundation, there would have been nothing meaningful to scale.</p>

<p><em>From $44K to $370K monthly. Six marketplaces. $3.19M+ in total revenue. 16.77% blended TACOS.</em></p>