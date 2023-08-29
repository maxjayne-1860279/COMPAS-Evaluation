# Evaluating COMPAS Criminal Recidivism Prediction Model

---

Maxwell Jayne

[COMPAS Evaluation](https://github.com/maxjayne-1860279/COMPAS-Evaluation)

&emsp;The Correctional Offender Management Profiling for Alternative Sanctions (COMPAS) algorithm is used to assess defendants for recidivism risk: the risk a defendant may perform another crime. The COMPAS model is a commercial risk aseessment tool that was developed and is owned by Equivant (formerly Northpointe) and has been used in US courts and during pretrial detention with a recorded accuracy of 65% in recidivism prediction. COMPAS or similar risk assessment models are used in 46 states across the US and many, similar to COMPAS, have proprietary algorithms, meaning the general public cannot learn how these risk recidivism risk scores are calculated. The COMPAS test itself is made up of 137 questions, and race is not asked about.

&emsp;In 2016, ProPublica--a non-profit online news source based out of New York--published an investigation of COMPAS, and found the algorithm to be racially biased, quoting, "Black defendants were also twice as likely as white defendants to be misclassified as being a higher risk of violent recidivism. And white violent recidivists were 63% more likley to have been misclassified as a low risk of violent recidivism, compared with black violent recidivists" (Larson, et al.). Additionally, the investigation found that of the recidivism predictions COMPAS made, only 20% actually re-offended. Equivant responded with a statement critiquing the ProPublica investigation and disagreeing with its claims of racial bias. The investigation was also criticized by a criminal justice think tank, Community Resources for Justice, stating the results of ProPublica's investigation contradicted existing studies that concluded risk can be calculated without racial or gender bias. (Larson, et al.) (Angwin, et al.).

&emsp;This study examines COMPAS scoring data using a dataset compiled by ProPublica from Florida public records, and evaluate the model in terms of statistical accuracy and racial bias, specifically pertaining to treatment of Caucasian and African American individuals. Initial analysis will be conducted, and confusion matrices constructed for comparison. Similar predictions models will then be created to compare to the COMPAS algorithm results.