# Oncology project abstract
Bayesian Framework for Optimizing Tarlatamab Dosing in Small Cell Lung Cancer: A Dose-Response Meta-Analysis  
# Background
Tarlatamab, a ﬁrst-in-class bispeciﬁc T-cell engager targeting delta-like ligand 3 (DLL3), has demonstrated promising eﬃcacy in relapsed/refractory small cell lung cancer (SCLC). However, dose selection remains a key challenge due to the trade-off between eﬃcacy and toxicity, particularly cytokine release syndrome (CRS), a dose- dependent immune-related adverse event. While clinical trials have shown comparable objective response rates (ORR) at 10 mg and 100 mg doses, the U.S. Food and Drug Administration (FDA) recommended 10 mg due to lower toxicity. Given these considerations, a Bayesian statistical framework was applied to model dose-response relationships for both eﬃcacy and toxicity, aiming to identify an optimal dose that maximizes clinical beneﬁt while minimizing risk.

# Methods
A Bayesian hierarchical model was developed to analyze dose-response relationships for both objective response rate (ORR) and CRS incidence. Data were extracted from published clinical trials, and separate binomial models were ﬁtted for eﬃcacy (ORR) and toxicity (CRS). An Emax model was used to estimate ED50 and ED90 for eﬃcacy, while a spline-based logistic regression was applied for toxicity modeling. A joint risk-beneﬁt analysis was conducted, incorporating a weighted utility function where toxicity was penalized relative to eﬃcacy. Posterior distributions were generated via Markov Chain Monte Carlo (MCMC) sampling, and model convergence was assessed using R-hat and effective sample size (ESS).

# Results
The estimated ED50 and ED90 for ORR were 4.7 mg and 42.7 mg, respectively. The Bayesian dose-toxicity model indicated increasing CRS incidence at higher doses. A risk-beneﬁt analysis suggested an optimal dose of 29 mg, where eﬃcacy was maximized while keeping toxicity at an acceptable level. Sensitivity analyses varying toxicity weightings supported this ﬁnding. Posterior predictive checks conﬁrmed model ﬁt.

![WhatsApp Image 2025-05-18 at 10 46 57](https://github.com/user-attachments/assets/a3c87d96-9af9-4dc5-9574-3379f743fbd5)
![WhatsApp Image 2025-05-18 at 10 46 56 (1)](https://github.com/user-attachments/assets/89cf01dd-d6b0-475f-8f86-4d7c6bb570dd)
![WhatsApp Image 2025-05-18 at 10 46 56](https://github.com/user-attachments/assets/4f07bead-6869-452d-a068-c733d1400b07)
![WhatsApp Image 2025-05-18 at 10 46 57 (2)](https://github.com/user-attachments/assets/8566c834-fd3f-4ad7-80b6-ee6167580119)

# Conclusions
A Bayesian approach to dose optimization identiﬁed 29 mg as the most favorable Tarlatamab dose in SCLC. This analysis provides a data-driven framework for balancing eﬃcacy and safety, offering insights for future clinical decision-making. Further prospective validation is warranted
