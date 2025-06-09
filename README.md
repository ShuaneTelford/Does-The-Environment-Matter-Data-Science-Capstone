# Abstract

This study investigates the impact of Environmental, Social, and Governance (ESG) rating disclosures on stock returns. This study focuses on the Automobile and Auto Components (AUX), Textiles, Apparel, and Luxury Goods (TEX), and Oil and Gas Refining and Marketing (OGX) industries. The research employs an event study metholody and utilises the *Capital Asset Pricing Model* (CAPM) and *Fama-French three-factor model* to analyse cumulative average abnormal returns (CAAR) following the release of ESG scores by Sustainalytics. A sample of 39 North American publicly traded firms, randomly selected from S&P Global’s Corporate Sustainability Assessment universe, was analyzed over a 15-day event window. Contrary to existing literature suggesting ESG performance influences investor behavior (Luo, 2022; Peiris & Evans, 2010; Shanaev & Ghimire, 2022), results indicate statistically insignificant CAAR across all industries (*p*-values > 0.05). This implies that Sustainalytics’ ESG score releases do not significantly alter stock returns, potentially due to the rater’s limited market influence, unaccounted anticipation effects, or methodological limitations. The findings challenge prevailing assumptions about ESG’s immediate market impact and highlight industry-specific complexities in ESG valuation.

# Discussions and Findings

## Key Findings

- **Insignificant Market Reaction**
  - CAAR estimates for AUX, TEX, and OGX industries showed no statistically significant response to ESG score releases (Figure 2). T-scores clustered near zero, indicating market expectations aligned with actual returns during the event window.
  - The OGX industry exhibited slight positive CAAR trends post-event (e.g., Day 7: CAAR = 0.037, *p* = 0.504), while AUX and TEX showed minor fluctuations with none surpassing the 5% significance threshold.

- **Contrast with Literature**
  - These results contradict studies linking ESG performance to stock returns. For example, Peiris and Evans (2010) observed positive ESG-return correlations in U.S. stocks, while Shanaev and Ghimire (2022) documented significant declines (-1.4%) for firms with worsening ESG scores.
  - Possible avenues of divergence:
    - **Rater Influence:** Sustainalytics’ lesser market prominence versus dominant raters like MSCI (Gregory, 2022; Larcker et al., 2022).
    - **Industry Heterogeneity:** Prior studies often aggregated industries, masking sector-specific dynamics (e.g., oil firms inherently face higher environmental risks).

## Methodological Limitations

- **Event Definition:**
  - The "event" (ESG score release date) did not differentiate between score improvements, deteriorations, or stability. Grouping firms irrespective of score direction diluted results (e.g., AUX included Tesla [improved] and Harley-Davidson [declined]).

- **Sample Constraints:**
  - Firm samplings were limited to large North American entities (per S&P Global’s criteria), excluding smaller firms potentially more sensitive to ESG shocks.

- **Antecedent Noise:**
  - Pre-event CAAR trends (Figure 3) suggest external factors (e.g., press releases) may have preempted ESG score impacts, necessitating a wider event window to capture anticipation/adjustment effects (Shanaev & Ghimire, 2022).

## Theoretical Implications

- **Investor Priorities:** Institutional investors may prioritize long-term ESG-driven corporate resilience over short-term returns (Pedersen et al., 2021), explaining the muted reaction to score releases.

- **Rater Credibility:** ESG rating divergence across agencies (Chatterji et al., 2016) may reduce investor reliance on single-rater assessments like Sustainalytics.

## Future Research Directions

- **Intra-Industry Analysis:** Compare CAAR for firms with improving versus deteriorating ESG scores within the same industry.
- **Multi-Rater Integration:** Incorporate scores from prominent raters (e.g., MSCI) to assess rater-specific market influence.
- **Extended Event Windows:** Test 30-60 day (or longer) windows to capture delayed investor reactions.
- **Cross-Regional Samples:** Include Asian or European firms to evaluate geographic heterogeneity in ESG responsiveness.

## Reference Images


<img src="https://github.com/ShuaneTelford/Does-The-Environment-Matter-Data-Science-Capstone/blob/main/Images/Figure%201..png"/>

<img src="https://github.com/ShuaneTelford/Does-The-Environment-Matter-Data-Science-Capstone/blob/main/Images/Figure%202.png"/>

<img src="https://github.com/ShuaneTelford/Does-The-Environment-Matter-Data-Science-Capstone/blob/main/Images/Figure%203.png"/>

## References

Chatterji, A. K., Durand, R., Levine, D. I., & Touboul, S. (2016). Do ratings of firms converge? Implications for managers, investors and strategy researchers. Strategic Management Journal, 37(8), 1597-1614. https://doi.org/10.1002/smj.2407

Fama, E. F., & French, K. R. (2004). The Capital Asset Pricing Model: Theory and Evidence. The Journal of Economic Perspectives, 18(3), 25-46. https://doi.org/10.1257/0895330042162430

Gregory, R. P. (2022). The influence of firm size on ESG score controlling for ratings agency and industrial sector. Journal of Sustainable Finance & Investment, 1-14. https://doi.org/10.1080/20430795.2022.2069079

Larcker, D. F., Pomorski, L., Tayan, B., & Watts, E. M. (2022). ESG Ratings: A Compass without Direction [Working Paper]. Stanford Closer Look series. https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4179647

Luo, D. (2022). ESG, liquidity, and stock returns. Journal of International Financial Markets, Institutions and Money, 78, Article 101526. https://doi.org/10.1016/j.intfin.2022.101526
MacKinley, A. C. (1997). Event studies in economics and finance. Journal of Economic Literature, 35(1), 13-39. https://www.proquest.com/docview/213164851?pq-origsite=summon

Mishra, S., & Suar, D. (2010). Does Corporate Social Responsibility Influence Firm Performance of Indian Companies? Journal of Business Ethics, 95(4), 571-601. https://doi.org/10.1007/s10551-010-0441-1

Pedersen, L. H., Fitzgibbons, S., & Pomorski, L. (2021). Responsible investing: The ESG-efficient frontier. Journal of Financial Economics, 142(2), 572-597. https://doi.org/10.1016/j.jfineco.2020.11.001

Peiris, D., & Evans, J. (2010). The Relationship Between Environmental Social Governance Factors and U.S. Stock Performance. Journal of Investing, 19(3), 104-112. Evans, John R. and Peiris, Dinusha, The Relationship between Environmental Social Governance Factors and Stock Returns (August 29, 2010). Available at SSRN: https://ssrn.com/abstract=1725077 or http://dx.doi.org/10.2139/ssrn.1725077

Peterdy, K. (2022). ESG (Environmental, Social and Governance). Corporate Finance Institute. https://corporatefinanceinstitute.com/resources/esg/esg-environmental-social-governance/

Pisani, F., & Russo, G. (2021). Sustainable Finance and COVID-19: The Reaction of ESG Funds to the 2020 Crisis. Sustainability, 13(23). https://doi.org/10.3390/su132313253

Shanaev, S., & Ghimire, B. (2022). When ESG meets AAA: The effect of ESG rating changes on stock returns. Finance Research Letters, 46(Part A), Article 102302. https://doi.org/10.1016/j.frl.2021.102302

S&P Global. (2022, November 25). Invited companies. S&P Global. Retrieved December 18, 2022, from https://www.spglobal.com/esg/csa/invited-companies

Trisnowati, Y., Achsani, N. A., Sembel, R., & Andati, T. (2022). The Effect of ESG Score, Financial Performance, and Macroeconomics on Stock Returns during the Pandemic Era in Indonesia. International Journal of Energy Economics and Policy, 12(4), 166–172. https://doi.org/10.32479/ijeep.13212
