---
title: 
layout: single
classes: wide
permalink: /research/
---
<br/> 

<!-- Google Tag Manager (noscript) -->
<!-- End Google Tag Manager (noscript) -->

# <center> Working Papers </center>
- - -

**Exploit or Explore? An Empirical Study of Resource Allocation in Scientific Labs.** 
2022.
<br/>
<small>[ <a href="#/" onclick="visib('ee')">Abstract</a> | [Paper][ee_paper] | [Online Appendices][ee_app] ] </small>

<div id="ee" style="display: none; text-align: justify; line-height: 1.2" ><small>
Allocating innovation resources to their most productive uses is a challenge for innovators because they have incomplete information about which projects will be most productive. I empirically study how a group of large scientific labs traded off the exploitation of existing opportunities
versus the exploration of new ones, that is whether they pursued safe projects to maximize short-term productivity or undertook high-variance projects to acquire information and improve long-term productivity. To recover how these labs made the exploitation-exploration tradeoff, I estimate a dynamic model of decision-making, assuming the labs approximated the value of exploration with a simple Upper Confidence Bound (UCB) index. The type of index is well-studied in theory and well-used in practice but has not been applied to estimation of empirical decision models. The index model captures the labs’ decision-making well. Estimates of its free parameters suggest that the labs explored extensively. Counterfactual simulations show that, had the labs not explored, their output quantity would have decreased by 51%, and their citations would have decreased by 57%.
</small><br><br/></div>

[ee_paper]: https://ranzhuo17.github.io/files/RanZhuo_JMP_main_current.pdf
[ee_app]:https://ranzhuo17.github.io/files/RanZhuo_JMP_appendices_current.pdf


**Examining Selection Pressures in the Publication Process Through the Lens of Sniff Tests** 
(with Christopher Snyder). 2022.
*Revised and Resubmitted, Review of Economics and Statistics.*
<br/>
<small>[ <a href="#/" onclick="visib('bias')">Abstract</a> ] </small>

<div id="bias" style="display: none; text-align: justify; line-height: 1.2" ><small>
The increasing demand for empirical rigor has led to the growing use of auxiliary tests (balance, pre-trends, over-identification, placebo, etc.) to help assess the credibility of a paper’s main results. We dub these “sniff tests” because rejection is bad news for the author and standards for passing are informal. We use these sniff tests—a sample of nearly 30,000 hand collected from scores of economics journals—as a lens to examine selection pressures in the publication process. We derive bounds under plausible nonparametric assumptions on the latent proportion of significant sniff tests removed by the publication process (whether by p-hacking or relegation to the file drawer) and the proportion whose significance was due to true misspecification, not bad luck. For the subsample of balance tests in randomized controlled trials, we find that the publication process removed at least 34.0% of significant p-values. For the subsample of other tests, we find a that at least 42.7% of significant p-values indicated true misspecification. We use textual analysis to assess whether authors over-attribute significant sniff tests to bad luck.
</small><br><br/></div>


# <center> Work in Progress </center>
- - -

**Demand Fluctuations and Supply Coordination in Semiconductor Manufacturing** 
(with Audrey Tiew).
<br/>
<small>[ <a href="#/" onclick="visib('semi')">Abstract</a> ] </small>

<div id="semi" style="display: none; text-align: justify; line-height: 1.2" ><small>
We study how supply capacity coordination can reduce social inefficiency from demand uncertainty and market power in the context of the semiconductor manufacturing industry. Market power generates misalignment between firm profit-maximizing capacity investments and welfare-maximizing capacity investments. To quantify the extent of this inefficiency and explore how various forms of supply coordination can mitigate it, we estimate a static structural model of semiconductor demand and a dynamic model of supply-side investment in technology and capacity. The data we have assembled to perform this exercise are, to our knowledge, the most comprehensive data on the industry in academic research. We obtain: (i) detailed proprietary buyer-level product demand data, covering around 20% of world orders, from 2004 to 2015, and (ii) proprietary world-wide, plant-level technology and capacity investment in semiconductor manufacturing plants from 1995 to 2015. We compare in counterfactual scenarios the relative efficacy of various forms of supply coordination (e.g., social planner, monopoly manufacturer, coordination on technology and capacity investment but competition in product market) in reducing inefficiency.
</small><br><br/></div>

**Upgraded Software and Embedded Improvements: Using Spiders to Track Bugs on the Web** 
(with Raviv Murciano-Goroff and Shane Greenstein).
<br/>
<small>[ <a href="#/" onclick="visib('oss2')">Abstract</a> ] </small>

<div id="oss2" style="display: none; text-align: justify; line-height: 1.2" ><small>
Our prior research (Murciano-Goroff, Zhuo, Greenstein, 2021) documented webserver usage across the US economy over the last two decades and identified enormous heterogeneity in the propensity to upgrade web server software. We investigate the causes of this heterogeneity in upgrades. We focus on quasi-natural experiments after the appearance of a severe security bug, and we analyze empirically why firms accelerate their rate of upgrading webserver software when a severe bug arises. A reverse causality issue arises due to a correlation between the (low) propensity to upgrade and a (high) prevalence of software that contains known security vulnerabilities. We develop hazard model approaches that account for firm-specific propensities to upgrade. We find that firms accelerate upgrading when their webserver supports electronic commerce instead of providing merely an informational or coordinating role. We also find acceleration when firms have recently displayed an unusually good financial performance. Finally, we find a significant propensity to upgrade merely because a new version has appeared, suggesting many firms gain protection against bugs as a byproduct of routine administrative processes that support maintaining frontier software.
</small><br><br/></div>

# <center> Publications </center>
- - -

**Hidden Software and Veiled Value Creation: Illustrations from Server Software Usage** 
(with Raviv Murciano-Goroff and Shane Greenstein). 2021.
*Research Policy 50 (9): 104333.*
<br/>
<small>[ <a href="#/" onclick="visib('hs')">Abstract</a> | [Publisher's Version][hs_pub] ] </small>

<div id="hs" style="display: none; text-align: justify; line-height: 1.2" ><small>
How do you measure the value of a commodity that transacts at a price of zero from an economic standpoint? This study examines the potential for and extent of omission and misattribution in standard approaches to economic accounting with regards to open source software, an unpriced commodity in the digital economy. The study is the first to follow usage and upgrading of unpriced software over a long period of time. It finds evidence that software updates mislead analyses of sources of firm productivity and identifies several mechanisms that create issues for mismeasurement. To illustrate these mechanisms, this study closely examines one asset that plays a critical role in the digital economic activity, web server software. We analyze the largest dataset ever compiled on web server use in the United States and link it to disaggregated information on over 200,000 medium to large organizations in the United States between 2001 and 2018. In our sample, we find that the omission of economic value created by web server software is substantial and that this omission indicates there is over $4.5 billion dollars of mismeasurement of server software across organizations in the United States. This mismeasurement varies by organization age, geography, industry and size. We also find that dynamic behavior, such as improvements of server technology and entry of new products, further exacerbates economic mismeasurement. Instead of requiring that parallel trends holds exactly, we impose restrictions on how different the post-treatment violations of parallel trends can be from the pre-treatment differences in trends ("pre-trends"). The causal parameter of interest is partially identified under these restrictions. We introduce two approaches that guarantee uniformly valid inference under the imposed restrictions, and we derive novel results showing that they have desirable power properties in our context. We illustrate how economic knowledge can inform the restrictions on the possible violations of parallel trends in two economic applications. We also highlight how our approach can be used to conduct sensitivity analyses showing what causal conclusions can be drawn under various restrictions on the possible violations of the parallel trends assumption.
</small><br><br/></div>

[hs_pub]: https://www-sciencedirect-com.ezp-prod1.hul.harvard.edu/science/article/pii/S0048733321001323?dgcid=coauthor

**The Impact of the General Data Protection Regulation on Internet Interconnection** 
(with Bradley Huffaker, kc claffy, and Shane Greenstein). 2021.
*Telecommunications Policy 45 (2): 102083.*
<br/>
<small>[ <a href="#/" onclick="visib('gdpr')">Abstract</a> | [Publisher's Version][gdpr_pub] ] </small>

<div id="gdpr" style="display: none; text-align: justify; line-height: 1.2" ><small>
The Internet comprises thousands of independently operated networks, interconnected using bilaterally negotiated data exchange agreements. The European Union (EU)'s General Data Protection Regulation (GDPR) imposes strict restrictions on handling of personal data of European Economic Area (EEA) residents. A close examination of the text of the law suggests significant cost to application firms. Available empirical evidence confirms reduction in data usage in the EEA relative to other markets. We investigate whether this decline in derived demand for data exchange impacts EEA networks' decisions to interconnect relative to those of non-EEA OECD networks. Our data consists of a large sample of interconnection agreements between networks globally in 2015–2019. All evidence estimates zero effects: the number of observed agreements, the inferred agreement types, and the number of observed IP-address-level interconnection points per agreement. We also find economically small effects of the GDPR on the entry and the observed number of customers of networks. We conclude there is no visible short run effects of the GDPR on these measures at the internet layer.
</small><br><br/></div>

[gdpr_pub]: https://www-sciencedirect-com.ezp-prod1.hul.harvard.edu/science/article/pii/S0308596120301737?dgcid=author


**Do Low‐Price Guarantees Guarantee Low Prices? Evidence from Competition between Amazon and Big‐Box Stores.** 
2017.
*Journal of Industrial Economics 65 (4): 719-738.*
<br/>
<small>[ <a href="#/" onclick="visib('pm')">Abstract</a> | [Publisher's Version][pm_pub] ] </small>

<div id="pm" style="display: none; text-align: justify; line-height: 1.2" ><small>
It has long been understood in theory that price-match guarantees can be anticompetitive, but to date, scant empirical evidence is available outside of some narrow markets. This paper broadens the scope of empirical analysis, studying a wide range of products sold on a national online market. Using an algorithm that extracts data from charts, I obtain a novel source of data from online price trackers. I examine prices of goods sold on Amazon before and after two big-box stores (Target and Best Buy) announced a guarantee to match Amazon's prices. Employing both difference-in-difference and regression-discontinuity approaches, I robustly estimate a positive causal effect of six percentage points. The effect was heterogeneous, with larger price increases for initially lower-priced items. My results support anticompetitive theories which predict price increases for Amazon, a firm that did not adopt the guarantee, and are consistent with plausible mechanisms for the heterogeneous impact.
</small><br><br/></div>

[pm_pub]: https://onlinelibrary.wiley.com/doi/10.1111/joie.12154


[//]: This java script is the button to show abstract
<script>
 function visib(id) {
  var x = document.getElementById(id);
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</script>

[//]:&emsp;<button onclick="visib('polariz')" class="btn btn--inverse btn--small">Abstract</button>
