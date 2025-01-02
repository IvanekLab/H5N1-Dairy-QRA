# Quantitative risk assessment of human H5N1 infection from consumption of fluid cow's milk
## <ins>K.J. Koebel</ins>, E. Bulut, S.D. Alcaine, A. Trmcic, M. Nooruzzaman, L.M. Covaleda, D.G. Diel, & R. Ivanek

MedRxiv Preprint: https://www.medrxiv.org/content/10.1101/2024.12.20.24319470v1

These two quantitative microbial risk assessment models (QMRAs) are designed to evaluate the public health risk from the H5N1 clade 2.3.4.4b emerging infectious disease (EID) scenario as it relates to the United States fluid milk supply.

The Aims of this investigation are as follows:
- (i) estimate the public health risk of human H5N1 infection from consumption of raw or pasteurized fluid milk
- (ii) assess intervention strategies
- (iii) identify key knowledge gaps

These models are built in Microsoft Excel (Microsoft Corp. Redmond, VA) and function utilizing the Monte Carlo simulation add-on @RISK (Lumivero, Denver, CO). Our analysis was conducted with 50,000 iterations with Latin hypercube sampling, Mersenne twister pRNG, and set seed =11.

**HPAI_QRA_model_pasteurized.xlsx**: Pasteurized milk model. Reports risk in terms of the probability of infection per serving and projected annual number of infections.

**HPAI_QRA_raw_model.xlsx**: Raw milk model. Reports risk in terms of the probability of infection per serving. This model differentiates two raw milk purchasing pathways (retail and farmstore). Additionally, a Boolean in cell D122 allows the evaluation of bulk tank milk PCR testing as a public health intervention strategy. 
