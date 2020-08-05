An Accurate Solution for Credit Valuation Adjustment (CVA) and Wrong Way Risk

Tim Xiao

Journal of Fixed Income, 25(1) 84-95 Summer 2015

ABSTRACT This paper presents a Least Square Monte Carlo approach for accurately calculating credit value adjustment (CVA). In contrast to previous studies, the model relies on the probability distribution of a default time/jump rather than the default time itself, as the default time is usually inaccessible. As such, the model can achieve a high order of accuracy with a relatively easy implementation. We find that the valuation of a defaultable derivative is normally determined via backward induction when their payoffs could be positive or negative. Moreover, the model can naturally capture wrong or right way risk.

Key Words: credit value adjustment (CVA), wrong way risk, right way risk, credit risk modeling, least square Monte Carlo, default time approach (DTA), default probability approach (DPA), collateralization, margin and netting.

Conclusion

This article presents a framework for pricing risky contracts and their CVAs. The model relies on the probability distribution of the default jump rather than the default jump itself, because the default jump is normally inaccessible. We find that the valuation of risky assets and their CVAs, in most situations, has a backward recursive nature and requires a backward induction valuation. An intuitive explanation is that two counterparties implicitly sell each other an option to default when entering into an OTC derivative transaction. If we assume that a default may occur at any time, the default options are American style options. If we assume that a default may only happen on the payment dates, the default options are Bermudan style options. Both Bermudan and American options require backward induction valuations.

Based on our theory, we propose a novel cash-flow-based framework (see appendix) for calculating bilateral CVA at the counterparty portfolio level. This framework can easily incorporate various credit mitigation techniques, such as netting agreements and margin agreements, and can capture wrong/right way risk. Numerical results show that these credit mitigation techniques and wrong/right way risk have significant impacts on CVA.

Reference

Brigo, D., and Capponi, A., 2008, Bilateral counterparty risk valuation with stochastic dynamical models and application to Credit Default Swaps, Working paper.

Duffie, Darrell, and Ming Huang, 1996, Swap rates and credit quality, Journal of Finance, 51, 921-949.

Duffie, Darrell, and Kenneth J. Singleton, 1999, Modeling term structure of defaultable bonds, Review of Financial Studies, 12, 687-720.

FinPricing, 2015, Market Data, https://finpricing.com/lib/IrCurve.html

Gregory, Jon, 2009, Being two-faced over counterparty credit risk, RISK, 22, 86-90.

Hull, J. and White, A., 2013, CVA and wrong way risk, forthcoming, Financial Analysts Journal.

Jarrow, R. A., and Protter, P., 2004, Structural versus reduced form models: a new information based perspective, Journal of Investment Management, 2, 34-43.

Jarrow, Robert A., and Stuart M. Turnbull, 1995, Pricing derivatives on financial securities subject to credit risk, Journal of Finance, 50, 53-85.

Lipton, A., and Sepp, A., 2009, Credit value adjustment for credit default swaps via the structural default model, Journal of Credit Risk, 5(2), 123-146.

Longstaff, Francis A., and Eduardo S. Schwartz, 2001, Valuing American options by simulation: a simple least-squares approach, The Review of Financial Studies, 14 (1), 113-147.

Moody’s Investor’s Service, 2000, Historical default rates of corporate bond issuers, 1920-99.

J. P. Morgan, 1999, The J. P. Morgan guide to credit derivatives, Risk Publications.

O’Kane, D. and S. Turnbull, 2003, Valuation of credit default swaps, Fixed Income Quantitative Credit Research, Lehman Brothers, QCR Quarterly, 2003 Q1/Q2, 1-19.

Pykhtin, Michael, and Steven Zhu, 2007, A guide to modeling counterparty credit risk, GARP Risk Review, July/August, 16-22.

Sorensen, E. and T. Bollier, 1994, Pricing swap default risk, Financial Analysts Journal, 50, 23-33.

Xiao, T., 2013a, The impact of default dependency and collateralization on asset pricing and credit risk modeling, Working paper.

Xiao, T., 2013b, An economic examination of collateralization in different financial market, Working paper.
