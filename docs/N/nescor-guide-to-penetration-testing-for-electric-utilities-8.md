---
layout: default
title: 8 End-to-End Penetration Test Analysis      
parent: §  NESCOR Guide to Penetration Testing for Electric Utilities 
grand_parent: N 
nav_order: 80 
---
<style>
.dont-break-out {
  /* These are technically the same, but use both */
  overflow-wrap: break-word;
  word-wrap: break-word;

  -ms-word-break: break-all;
  /* This is the dangerous one in WebKit, as it breaks things wherever */
  word-break: break-all;
  /* Instead use this non-standard one: */
  word-break: break-word;
}
</style>

<div class="dont-break-out" markdown="1">
1. TOC
{:toc}

## 8 End-to-End Penetration Test Analysis
The final task in any penetration test should be a gap analysis of communications that span the entire system. This should include a review of input and output from external systems that may not be in scope for this assessment. For instance, when testing an AMI meter system, a tester might have performed tests on all components from the meter to the headend. However this final end-to-end task should ensure that all possible inputs from external systems to in-scope systems have been tested and evaluated as possible attack angles, such as an out-of-scope backend systems dependent on data from the in-scope system. Also, malicious data from out-of-scope systems that is accepted and used by in-scope systems, such as public key infrastructure (PKI) servers, should be considered in this part of the assessment. Penetration testers should also identity if any vulnerabilities found later in the testing process affect components tested earlier or by other testing teams.

***
#### Table of Contents
{: .no_toc}

<ul><li> <a href="/docs/N/national-plug-in-electric-vehicles-infrastructure-analysis-1/">1 Introduction</a></li><li> <a href="/docs/N/national-plug-in-electric-vehicles-infrastructure-analysis-2/">2 Existing Vehicle and Infrastructure Status</a></li><li> <a href="/docs/N/national-plug-in-electric-vehicles-infrastructure-analysis-3/">3 Non-Residential L2 and DCFC for Community Charging</a></li><li> <a href="/docs/N/national-plug-in-electric-vehicles-infrastructure-analysis-4/">4 DCFCs for Corridor Charging</a></li><li> <a href="/docs/N/national-plug-in-electric-vehicles-infrastructure-analysis-5/">5 Conclusions</a></li><li> <a href="/docs/N/national-plug-in-electric-vehicles-infrastructure-analysis-6/">References</a></li><li> <a href="/docs/N/national-plug-in-electric-vehicles-infrastructure-analysis-7/">Appendix A - Supplementary Statistics on Existing EVSE</a></li><li> <a href="/docs/N/national-plug-in-electric-vehicles-infrastructure-analysis-8/">Appendix B - EVSE/PEV Adjustment Factors to Account for Local Conditions</a></li><li> <a href="/docs/N/national-plug-in-electric-vehicles-infrastructure-analysis-9/">Appendix C - Central Scenario PEV/EVSE Estimates by State</a></li><li> <a href="/docs/N/national-plug-in-electric-vehicles-infrastructure-analysis-10/">Appendix D - Long-Distance Travel Frequency from the SHRP2 NDS</a></li></ul>

***

</div>
