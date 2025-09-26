---
layout: default
title: Research
---

# 🔬 Research

## 📑 Work in Progress

### 🔹 Short-run spillover effects of climate shocks to small-open economies: An empirical investigation. <button type="button" class="expand-btn" onclick="toggleAbstract(this)">Expand</button>
<div class="abstract" hidden>
  <p>
    This study extends recent work in the climate literature by examining how climate shocks—
    specifically temperature and precipitation anomalies—spill over across borders, influencing
    inflation and real economic variables. Using high-resolution gridded climate data, I construct
    sector-sensitive climate shock measures and embed them in a large two-country VAR framework
    for Italy and Malta. The analysis shows that climate shocks in Italy can generate inflationary
    pressures in Malta, particularly through processed food prices, services, and producer prices
    in food manufacturing. Droughts generate effects similar to summer temperature shocks, suggesting
    a shared economic impact pattern across the two countries considered. Importantly, once the
    shock "crosses borders", it may materialise in different inflation components in Malta,
    reflecting country-specific transmission channels. These findings underscore the importance of
    cross-border climate vulnerability, especially for small open economies that are closely integrated
    with larger trading partners.
  </p>
</div>

### 🔹 Unequal Barrels and Slick Consequences: The Distributional Impact of Oil Shocks <small> with [Luis Calderon](https://luiscald.github.io)</small>

## 📚 Publications

### 🔹 The distributional effects of oil supply news shocks <small> with [Haroon Mumtaz](https://sites.google.com/site/hmumtaz77/) and [Angeliki Theophilopoulou](https://sites.google.com/view/angelikitheophilopoulou/home)</small> <button type="button" class="expand-btn" onclick="toggleAbstract(this)">Expand</button>
<div class="abstract" hidden>
  <p>
    This paper uses high-frequency data on the distribution of US income to investigate the heterogeneous
    effects of oil supply news shocks. Using a FAVAR with an external instrument, we show that these
    shocks have large negative effects on the left and right tail of the distribution. For low-income
    individuals, the effect is driven by a decline in wages and proprietors’ income, while a fall in
    corporate profits and interest income drives the effect for affluent individuals.  
    Keywords: Oil shock, Income inequality, FAVAR, External instrument identification
  </p>
</div>  
[Publication](https://doi.org/10.1016/j.econlet.2024.111769) | [Code](https://www.dropbox.com/scl/fo/nwnrtw2jknsdb6ixzd0b7/AJw-LfAeSrDm0OAx9p600ic?rlkey=w0truu7ellhzpfgy3n249j7lk&dl=0)

<div style="text-align: center; margin-top: 50px;">
  <a href="index.html">← Back to Home</a>
</div>

<style>
  .expand-btn {
    margin-left: 0.5rem;
    padding: 0.15rem 0.6rem;
    font-size: 0.8rem;
    border-radius: 999px;
    border: 1px solid #ccc;
    background: #f2f2f2;
    cursor: pointer;
    vertical-align: middle;
    transition: background 0.2s, border-color 0.2s;
  }
  .expand-btn:hover {
    background: #e6e6e6;
    border-color: #aaa;
  }
  .expand-btn:focus {
    outline: none;
    border-color: #666;
  }
  .abstract {
    margin-top: 0.4rem;
    padding-left: 0.8rem;
  }
</style>

<script>
  function toggleAbstract(button) {
    const abstract = button.nextElementSibling;
    if (!abstract) return;
    const isHidden = abstract.hasAttribute("hidden");
    if (isHidden) {
      abstract.removeAttribute("hidden");
      button.textContent = "Collapse";
    } else {
      abstract.setAttribute("hidden", "");
      button.textContent = "Expand";
    }
  }
</script>



