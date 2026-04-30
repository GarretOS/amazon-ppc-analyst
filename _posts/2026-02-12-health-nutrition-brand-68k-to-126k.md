---
layout: post
title: "Three Mandates, One Account: A 15-Month Amazon PPC Adaptation Story"
subtitle: "From $68K to $126K peak monthly revenue. TACoS from 42% to 15.8%. Three completely different goals."
date: 2026-02-12
author: Garret Sumagang
tags: [amazon-ppc, canada, case-study, adaptability, ecommerce]
---

<style>
  .blog-post h2 { margin-top: 3rem; margin-bottom: 1.25rem; }
  .blog-post h3 { margin-top: 2rem; margin-bottom: 1rem; }
  .blog-post p { margin-bottom: 1.1rem; line-height: 1.8; }
  .blog-post hr { display: none; }
  .case-study-viz { margin: 2rem 0; }
</style>
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.js"></script>


I took over this account in May 2024. A Canadian health and nutrition brand on Amazon.ca. Revenue at $68K monthly. TACoS at 42%.

The first mandate was simple: grow. I pushed the campaigns hard, and within a month revenue crossed $100K.

Then the mandates started changing.

Twelve months later, revenue had nearly doubled to a new peak of $126K. TACoS sat at 15.8% by the close of management. The goal kept changing. The results did not.

<div class="case-study-viz">
<style>
  .hero-grid { display: grid; grid-template-columns: repeat(4, minmax(0,1fr)); gap: 1px; background: #dce3ed; border: 0.5px solid #dce3ed; border-radius: 10px; overflow: hidden; margin: 1.5rem 0; }
  .hero-card { background: #f7f9fc; padding: 1.5rem 1.25rem; display: flex; flex-direction: column; gap: 6px; }
  .hero-card.accent { background: #1a3a5c; }
  .hero-label { font-size: 11px; color: #888; text-transform: uppercase; letter-spacing: 0.06em; font-weight: 500; }
  .hero-card.accent .hero-label { color: #a8c7e8; }
  .hero-value { font-size: 28px; font-weight: 500; color: #1a3a5c; line-height: 1.1; }
  .hero-card.accent .hero-value { color: #fff; }
  .hero-sub { font-size: 12px; color: #888; }
  .hero-card.accent .hero-sub { color: #a8c7e8; }
  @media (max-width: 520px) { .hero-grid { grid-template-columns: repeat(2, minmax(0,1fr)); } }
</style>
<div class="hero-grid">
  <div class="hero-card">
    <span class="hero-label">Starting Revenue</span>
    <span class="hero-value">$68K</span>
    <span class="hero-sub">Monthly, May 2024</span>
  </div>
  <div class="hero-card accent">
    <span class="hero-label">Peak Revenue</span>
    <span class="hero-value">$126K</span>
    <span class="hero-sub">Monthly, May 2025</span>
  </div>
  <div class="hero-card">
    <span class="hero-label">Starting TACoS</span>
    <span class="hero-value">42.1%</span>
    <span class="hero-sub">May 2024</span>
  </div>
  <div class="hero-card">
    <span class="hero-label">Closing TACoS</span>
    <span class="hero-value">15.8%</span>
    <span class="hero-sub">July 2025</span>
  </div>
</div>
</div>

---

## The Account as I Found It

A Canadian health and nutrition brand on Amazon.ca. Multiple SKUs across two product lines. Established catalog, real consumer demand, and a monthly revenue figure that looked stable on the surface.

But the numbers underneath told a different story.

SP was carrying 97% of all ad spend. SB Headline existed but was spending more than it returned. SB Video had never been activated. The account was running on one engine.

Match type distribution had no clear logic behind it. PHRASE was doing the most work. EXACT had nearly the same spend but a fraction of the efficiency. AUTO was burning budget at a 92% ACOS. Nearly $22,000 out of $54,000 in SP spend over the prior 60 days had generated zero orders.

TACoS sat at 42%. Not because the account was scaling aggressively. Because the spend was not converting.

That was the account I inherited in May 2024.

<div class="case-study-viz">
<style>
  .snap-cards { display: grid; grid-template-columns: repeat(3, minmax(0,1fr)); gap: 8px; margin: 1.25rem 0; }
  .snap-card { background: #faeeda; border: 0.5px solid #ef9f27; border-radius: 8px; padding: 0.875rem 1rem; }
  .snap-card-label { font-size: 11px; color: #633806; text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 4px; font-weight: 700; }
  .snap-card-value { font-size: 22px; font-weight: 500; color: #633806; line-height: 1.1; }
  .snap-card-sub { font-size: 12px; color: #633806; margin-top: 4px; }
  @media (max-width: 480px) { .snap-cards { grid-template-columns: 1fr; } }
</style>
<div class="snap-cards">
  <div class="snap-card">
    <div class="snap-card-label">TACoS at Takeover</div>
    <div class="snap-card-value">42.1%</div>
    <div class="snap-card-sub">May 2024. Not a scaling problem. A conversion problem.</div>
  </div>
  <div class="snap-card">
    <div class="snap-card-label">Non-Converting SP Spend</div>
    <div class="snap-card-value">$22,250</div>
    <div class="snap-card-sub">Out of $54,209 total SP spend in the prior 60 days. Zero orders.</div>
  </div>
  <div class="snap-card">
    <div class="snap-card-label">SP Share of Total Ad Spend</div>
    <div class="snap-card-value">97%</div>
    <div class="snap-card-sub">SB Headline active but underperforming. SB Video never launched. SD negligible.</div>
  </div>
</div>
</div>

---

## The First Read

The 42% TACoS was not one problem. It was several problems layered on top of each other.


<div class="case-study-viz">
<style>
  .asin-chart-caption { font-size: 11px; color: #999; margin-top: 10px; font-style: italic; }
  .asin-legend { display: flex; gap: 20px; margin-bottom: 12px; font-size: 12px; color: #666; }
  .asin-swatch { width: 10px; height: 10px; border-radius: 2px; display: inline-block; margin-right: 5px; vertical-align: middle; }
</style>
<div class="asin-legend">
  <span><span class="asin-swatch" style="background:#c0392b;"></span>Spend Share %</span>
  <span><span class="asin-swatch" style="background:#1a3a5c;"></span>Sales Share %</span>
</div>
<div style="position: relative; width: 100%; height: 340px;">
  <canvas id="asinChart" role="img" aria-label="Spend share vs sales share by ASIN. ASIN-A has 13.7% spend share but only 4.7% sales share. ASIN-D has 8.6% spend share but 12.4% sales share."></canvas>
</div>
<p class="asin-chart-caption">Top 10 ASINs by spend share, representing ~79% of total SP budget. Budget followed inertia, not performance. Data covers 60 days prior to May 2024 takeover.</p>
<script>
(function() {
  var labels = ['ASIN-A','ASIN-B','ASIN-C','ASIN-D','ASIN-E','ASIN-F','ASIN-G','ASIN-H','ASIN-I','ASIN-J'];
  var spendShare = [13.7, 12.9, 9.0, 8.6, 7.8, 7.4, 6.2, 4.9, 4.5, 3.7];
  var salesShare = [4.7, 9.9, 7.6, 12.4, 8.4, 3.2, 9.5, 1.8, 3.6, 2.2];
  new Chart(document.getElementById('asinChart'), {
    type: 'bar',
    data: {
      labels: labels,
      datasets: [
        { label: 'Spend Share %', data: spendShare, backgroundColor: '#c0392b', borderRadius: 3, borderWidth: 0 },
        { label: 'Sales Share %', data: salesShare, backgroundColor: '#1a3a5c', borderRadius: 3, borderWidth: 0 }
      ]
    },
    options: {
      responsive: true, maintainAspectRatio: false,
      indexAxis: 'y',
      plugins: {
        legend: { display: false },
        tooltip: { callbacks: { label: function(ctx) { return ' ' + ctx.dataset.label + ': ' + ctx.parsed.x.toFixed(1) + '%'; } } }
      },
      scales: {
        x: { ticks: { color: '#888', font: { size: 11 }, callback: function(v) { return v + '%'; } }, grid: { color: 'rgba(128,128,128,0.1)' }, title: { display: true, text: 'Share of Total (%)', color: '#888', font: { size: 11 } } },
        y: { ticks: { color: '#1a3a5c', font: { size: 12 } }, grid: { display: false } }
      }
    }
  });
})();
</script>
</div>

The clearest one was budget misallocation at the ASIN level. The account's biggest spenders were not its biggest earners. ASIN-A was consuming 13.7% of total ad spend while generating 4.7% of revenue, at a TACoS of 115%. ASIN-B had nearly the same spend share with returns that did not justify it. ASIN-H was spending more in ads than it was generating in total sales.

Meanwhile, the ASINs that actually converted well were being underserved. The account's top-revenue products had healthy TACoS and strong sales share but were not getting proportional budget support.

The budget wasn't going where the data pointed. It was going where it had always gone.

<div class="case-study-viz">
<style>
  .mt-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 2rem; margin: 1.5rem 0; }
  .mt-title { font-size: 13px; font-weight: 500; color: #1a3a5c; margin-bottom: 12px; }
  .mt-legend { display: flex; flex-direction: column; gap: 6px; margin-top: 14px; font-size: 12px; color: #666; }
  .mt-legend-row { display: flex; align-items: center; justify-content: space-between; }
  .mt-swatch { width: 10px; height: 10px; border-radius: 2px; display: inline-block; margin-right: 6px; vertical-align: middle; }
  .mt-note { font-size: 11px; color: #999; margin-top: 10px; font-style: italic; }
  @media (max-width: 480px) { .mt-grid { grid-template-columns: 1fr; } }
</style>
<div class="mt-grid">
  <div>
    <p class="mt-title">PPC Sales by Match Type</p>
    <div style="position: relative; width: 100%; height: 200px;">
      <canvas id="mtSalesChart" role="img" aria-label="PPC sales by match type: PHRASE 43.4%, PAT 35.5%, EXACT 26.1%, BROAD 18.4%, AUTO 16.7%."></canvas>
    </div>
    <div class="mt-legend">
      <div class="mt-legend-row"><span><span class="mt-swatch" style="background:#1a3a5c;"></span>PHRASE</span><span>43.4%</span></div>
      <div class="mt-legend-row"><span><span class="mt-swatch" style="background:#4a90c4;"></span>PAT</span><span>35.5%</span></div>
      <div class="mt-legend-row"><span><span class="mt-swatch" style="background:#a8c7e8;"></span>EXACT</span><span>26.1%</span></div>
      <div class="mt-legend-row"><span><span class="mt-swatch" style="background:#dce3ed;"></span>BROAD</span><span>26.0%</span></div>
      <div class="mt-legend-row"><span><span class="mt-swatch" style="background:#e07b39;"></span>AUTO</span><span>16.7%</span></div>
    </div>
  </div>
  <div>
    <p class="mt-title">Spend by Match Type</p>
    <div style="position: relative; width: 100%; height: 200px;">
      <canvas id="mtSpendChart" role="img" aria-label="Spend by match type: PHRASE 27.0%, PAT 22.4%, EXACT 22.4%, BROAD 15.9%, AUTO 13.3%."></canvas>
    </div>
    <div class="mt-legend">
      <div class="mt-legend-row"><span><span class="mt-swatch" style="background:#1a3a5c;"></span>PHRASE</span><span>27.0%</span></div>
      <div class="mt-legend-row"><span><span class="mt-swatch" style="background:#4a90c4;"></span>PAT</span><span>22.4%</span></div>
      <div class="mt-legend-row"><span><span class="mt-swatch" style="background:#a8c7e8;"></span>EXACT</span><span>22.4%</span></div>
      <div class="mt-legend-row"><span><span class="mt-swatch" style="background:#dce3ed;"></span>BROAD</span><span>15.9%</span></div>
      <div class="mt-legend-row"><span><span class="mt-swatch" style="background:#e07b39;"></span>AUTO</span><span>13.3%</span></div>
    </div>
  </div>
</div>
<p class="mt-note">No match type was doing its job cleanly. PHRASE generated the most sales but AUTO was burning budget at 92% ACOS. EXACT had nearly the same spend as PHRASE with a fraction of the return.</p>
<script>
(function() {
  var colors = ['#1a3a5c','#4a90c4','#a8c7e8','#dce3ed','#e07b39'];
  function makeDoughnut(data, id) {
    new Chart(document.getElementById(id), {
      type: 'doughnut',
      data: { labels: ['PHRASE','PAT','EXACT','BROAD','AUTO'], datasets: [{ data: data, backgroundColor: colors, borderWidth: 0 }] },
      options: { responsive: true, maintainAspectRatio: false, cutout: '65%', plugins: { legend: { display: false }, tooltip: { callbacks: { label: function(ctx) { return ' ' + ctx.label + ': ' + ctx.parsed.toFixed(1) + '%'; } } } } }
    });
  }
  makeDoughnut([43.4, 35.5, 26.1, 16.0, 16.7], 'mtSalesChart');
  makeDoughnut([27.0, 22.4, 22.4, 15.9, 13.3], 'mtSpendChart');
})();
</script>
</div>

Placement told the same story. Top of Search converted at nearly double the rate of Product Pages, but budget was not weighted to reflect that. Rest of Search was close to breakeven. Product Pages had the highest impression volume and some of the weakest conversion in the account.

The structure was not broken in one place. It was leaking in all of them.

---

## Growth Order: Push the Campaigns

The mandate was growth, and the timing was right.

A newly launched product line was gaining traction. The opportunity was there but it needed ad support to scale. I pushed spend behind it aggressively, prioritizing visibility and impression capture over efficiency.

The rest of the catalog got the same treatment. Budgets were increased on converting targets. I expanded into broader match types to widen the discovery funnel and tested new targets across the catalog to find incremental demand.

The account responded fast. Revenue jumped from $68K in May to $106K in June. It held at $110K in July, carrying through Prime Day on the back of campaigns that were already converting.

TACoS stayed elevated at 41 to 42% through this period. That was acceptable. Efficiency was not the goal. Volume was. And volume is what the account delivered.

<div class="case-study-viz">
<style>
  .growth-grid { display: grid; grid-template-columns: repeat(3, minmax(0,1fr)); gap: 1px; background: #dce3ed; border: 0.5px solid #dce3ed; border-radius: 10px; overflow: hidden; margin: 1.25rem 0; }
  .growth-card { background: #f7f9fc; padding: 1.5rem 1.25rem; display: flex; flex-direction: column; gap: 6px; }
  .growth-card.accent { background: #1a3a5c; }
  .growth-card.mid { background: #fff; display: flex; align-items: center; justify-content: center; }
  .growth-label { font-size: 11px; color: #888; text-transform: uppercase; letter-spacing: 0.06em; font-weight: 500; }
  .growth-card.accent .growth-label { color: #a8c7e8; }
  .growth-value { font-size: 28px; font-weight: 500; color: #1a3a5c; line-height: 1.1; }
  .growth-card.accent .growth-value { color: #fff; }
  .growth-sub { font-size: 12px; color: #888; }
  .growth-card.accent .growth-sub { color: #a8c7e8; }
  .growth-delta { text-align: center; }
  .growth-delta-value { font-size: 22px; font-weight: 700; color: #e07b39; display: block; }
  .growth-delta-sub { font-size: 11px; color: #888; display: block; margin-top: 2px; }
  @media (max-width: 480px) { .growth-grid { grid-template-columns: 1fr; } }
</style>
<div class="growth-grid">
  <div class="growth-card">
    <span class="growth-label">May 2024</span>
    <span class="growth-value">$68,293</span>
    <span class="growth-sub">Month one. Campaigns live.</span>
  </div>
  <div class="growth-card mid">
    <div class="growth-delta">
      <span class="growth-delta-value">+56%</span>
      <span class="growth-delta-sub">in one month</span>
    </div>
  </div>
  <div class="growth-card accent">
    <span class="growth-label">June 2024</span>
    <span class="growth-value">$106,848</span>
    <span class="growth-sub">Revenue crosses $100K.</span>
  </div>
</div>
</div>

---

## The Pivot: Two Cuts, One Direction

The first cut came in August 2024, and it was not a profitability play.

The original director had seen the TACoS holding above 35% through the growth phase and wanted it brought down without killing momentum. The new goal was controlled growth: keep scaling, but stop the TACoS from spiraling. I rebuilt the bid strategy around that constraint. Targets with poor historical data got purged. Spend dropped from $39,511 to $21,904, a 45% reduction in one month. TACoS came down from 35.8% to 24.0%.

Revenue pulled back from $110K to $91K. The account was not bleeding anymore.

December 2024 was the low point at $62K, but that was not a campaign problem. Several products went out of stock and demand had nowhere to convert. When inventory returned, I pushed spend back up deliberately to rebuild organic rank on the affected products. TACoS climbed temporarily as a result. That was the plan. You spend to regain position, then ease off as rank stabilizes.

It worked. By May 2025, the account hit a new all-time peak of $126,902, higher than anything the aggressive growth phase had produced, with TACoS at 21.6%.

Then a new director came in.

The third mandate was different in tone and in scale. Maximum profitability, no exceptions. Spend was cut from $27,389 to $13,360, a 51% reduction in one month. TACoS dropped to 16.2% in June and 15.8% in July. Revenue settled at $82 to $84K and held.

Three mandates across fifteen months. Every one of them delivered.

<div class="case-study-viz">
<style>
  .rev-legend { display: flex; gap: 20px; margin-bottom: 12px; font-size: 12px; color: #666; }
  .rev-swatch { width: 10px; height: 10px; border-radius: 2px; display: inline-block; margin-right: 5px; vertical-align: middle; }
  .rev-note { font-size: 11px; color: #999; margin-top: 10px; font-style: italic; }
</style>
<div class="rev-legend">
  <span><span class="rev-swatch" style="background:#1a3a5c;"></span>Monthly Revenue (CAD)</span>
  <span><span class="rev-swatch" style="background:#e07b39;"></span>TACoS %</span>
</div>
<div style="position: relative; width: 100%; height: 350px; padding-top: 20px; box-sizing: border-box;">
  <canvas id="revComboChart" role="img" aria-label="Monthly revenue and TACoS from May 2024 to July 2025. Revenue peaked at $126,902 in May 2025. TACoS closed at 15.8% in July 2025."></canvas>
</div>
<p class="rev-note">Monthly revenue (CAD) and TACoS % across the 15-month management window. Dashed lines mark the two spend cuts. December 2024 dip reflects out-of-stock periods, not campaign failure.</p>
<script>
(function() {
  var labels = ['May 24','Jun 24','Jul 24','Aug 24','Sep 24','Oct 24','Nov 24','Dec 24','Jan 25','Feb 25','Mar 25','Apr 25','May 25','Jun 25','Jul 25'];
  var revenue = [68293,106848,110484,91248,85775,85914,81624,62146,86850,99822,102363,118832,126902,82249,84599];
  var tacos   = [42.05,41.81,35.76,24.00,26.35,28.12,24.13,15.60,22.23,27.16,24.03,24.38,21.58,16.24,15.81];

  var verticalLinePlugin = {
    id: 'verticalLines',
    afterDraw: function(chart) {
      var ctx = chart.ctx;
      var xAxis = chart.scales.x;
      var yAxis = chart.scales.y;
      [3, 13].forEach(function(index) {
        var x = xAxis.getPixelForValue(index);
        ctx.save();
        ctx.beginPath();
        ctx.moveTo(x, yAxis.top);
        ctx.lineTo(x, yAxis.bottom);
        ctx.lineWidth = 1.5;
        ctx.strokeStyle = '#aab8c8';
        ctx.setLineDash([5, 4]);
        ctx.stroke();
        ctx.setLineDash([]);
        ctx.fillStyle = '#7a92aa';
        ctx.font = '10px sans-serif';
        ctx.textAlign = 'center';
        ctx.fillText(index === 3 ? 'Cut 1' : 'Cut 2', x, yAxis.top + 14);
        ctx.restore();
      });
    }
  };

  new Chart(document.getElementById('revComboChart'), {
    plugins: [verticalLinePlugin],
    data: {
      labels: labels,
      datasets: [
        { type: 'bar', label: 'Monthly Revenue (CAD)', data: revenue, backgroundColor: '#1a3a5c', borderRadius: 3, yAxisID: 'y', order: 2 },
        { type: 'line', label: 'TACoS %', data: tacos, borderColor: '#e07b39', backgroundColor: 'transparent', pointBackgroundColor: '#e07b39', pointRadius: 4, pointHoverRadius: 6, borderWidth: 2, tension: 0.3, yAxisID: 'y2', order: 1 }
      ]
    },
    options: {
      responsive: true, maintainAspectRatio: false,
      interaction: { mode: 'index', intersect: false },
      plugins: {
        legend: { display: false },
        tooltip: { callbacks: { label: function(ctx) { if (ctx.dataset.label === 'TACoS %') return ' TACoS: ' + ctx.parsed.y.toFixed(1) + '%'; return ' Revenue: $' + ctx.parsed.y.toLocaleString(); } } }
      },
      scales: {
        x: { ticks: { color: '#888', font: { size: 10 }, maxRotation: 45, minRotation: 45 }, grid: { display: false } },
        y: { position: 'left', ticks: { color: '#888', font: { size: 11 }, callback: function(v) { return '$' + (v/1000).toFixed(0) + 'K'; } }, grid: { color: 'rgba(128,128,128,0.1)' }, title: { display: true, text: 'Monthly Revenue (CAD)', color: '#888', font: { size: 11 } } },
        y2: { position: 'right', min: 0, max: 55, ticks: { color: '#e07b39', font: { size: 11 }, callback: function(v) { return v + '%'; } }, grid: { drawOnChartArea: false }, title: { display: true, text: 'TACoS %', color: '#e07b39', font: { size: 11 } } }
      }
    }
  });
})();
</script>
</div>

---

## The Scoreboard

The numbers across fifteen months tell a cleaner story than any single month does.

Revenue started at $68,293 in May 2024 and peaked at $126,902 in May 2025. That is an 86% increase across a window that included three mandate shifts, an inventory crisis, and two separate spend cuts. The growth was not linear. It was interrupted and rebuilt. The peak still came.

TACoS opened at 42.1% and closed at 15.8% in July 2025. A 62% reduction in ad cost relative to total revenue. The account became more efficient in every phase, including the phases where efficiency was not the primary goal.

By the final weeks of management, the weekly data pushed even further. TACoS dropped below 11% in back-to-back weeks. The account was not just hitting its target. It was moving past it.

<div class="case-study-viz">
<style>
  .scoreboard-grid { display: grid; grid-template-columns: repeat(3, minmax(0,1fr)); gap: 8px; margin: 1.25rem 0; }
  .scoreboard-card { background: #f7f9fc; border: 0.5px solid #dce3ed; border-radius: 8px; padding: 0.875rem 1rem; }
  .scoreboard-card.positive { background: #eef6ee; border-color: #5a9e5a; }
  .scoreboard-label { font-size: 11px; color: #888; text-transform: uppercase; letter-spacing: 0.05em; margin-bottom: 8px; font-weight: 700; }
  .scoreboard-card.positive .scoreboard-label { color: #2e6b2e; }
  .scoreboard-row { display: flex; align-items: center; gap: 10px; flex-wrap: wrap; }
  .scoreboard-before { font-size: 18px; font-weight: 500; color: #c0392b; }
  .scoreboard-arrow { font-size: 16px; color: #e07b39; }
  .scoreboard-after { font-size: 22px; font-weight: 500; color: #1a3a5c; }
  .scoreboard-card.positive .scoreboard-after { color: #2e6b2e; }
  .scoreboard-sub { font-size: 12px; color: #888; margin-top: 4px; }
  .scoreboard-card.positive .scoreboard-sub { color: #4a8a4a; }
  @media (max-width: 480px) { .scoreboard-grid { grid-template-columns: 1fr; } }
</style>
<div class="scoreboard-grid">
  <div class="scoreboard-card">
    <div class="scoreboard-label">Monthly Revenue</div>
    <div class="scoreboard-row">
      <span class="scoreboard-before">$68,293</span>
      <span class="scoreboard-arrow">&#8594;</span>
      <span class="scoreboard-after">$126,902</span>
    </div>
    <div class="scoreboard-sub">May 2024 to peak in May 2025. Up 86% across three mandate shifts.</div>
  </div>
  <div class="scoreboard-card">
    <div class="scoreboard-label">Monthly TACoS</div>
    <div class="scoreboard-row">
      <span class="scoreboard-before">42.1%</span>
      <span class="scoreboard-arrow">&#8594;</span>
      <span class="scoreboard-after">15.8%</span>
    </div>
    <div class="scoreboard-sub">May 2024 to July 2025. A 62% reduction in ad cost relative to total revenue.</div>
  </div>
  <div class="scoreboard-card positive">
    <div class="scoreboard-label">Weekly TACoS at Close</div>
    <div class="scoreboard-row">
      <span class="scoreboard-after">&lt;11%</span>
    </div>
    <div class="scoreboard-sub">Back-to-back weeks in late July 2025. The account was still accelerating at handoff.</div>
  </div>
</div>
</div>

---

## On Adaptability

Most PPC engagements run on a single brief.

This one had three.

The goal changed while campaigns were live. A new director arrived fourteen months in with a completely different definition of success. None of that was in the original scope.

That is the reality of managing accounts for growing brands. Leadership changes. Priorities rotate. The operator either adapts or becomes a liability.

What kept this account on track was not flexibility for its own sake. It was having a clear enough read on the data at every point that a mandate change could be absorbed without losing weeks to re-diagnosis.

The numbers always told you what to do next. The mandate just told you which direction to go.

*Health and nutrition brand managed on Amazon.ca. Performance data covers May 2024 through July 2025.*