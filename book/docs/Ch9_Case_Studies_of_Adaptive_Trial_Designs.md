## Ch 9. Case Studies of Adaptive Trial Designs

### Presenter : Chungsoo Kim 
- [LinkedIn](https://www.linkedin.com/in/chungsoo-kim-42419b175/), [Github](https://github.com/ChungsooKim), [Personal page](https://medicine.yale.edu/profile/chungsoo-kim/)

### Chapter Summary

- This chapter presents six examples of adaptive clinical trials, serving as a practical extension of the concepts introduced in earlier chapters. 
- The case studies are grouped according to their primary adaptive design characteristics. 
- Each example provides background context, outlines important aspects of the trial design, and summarizes the overall findings. 

### Introduction

- The case studies are categorized based on their principal adaptive features. 
- Each example includes a brief overview of the trial’s background, a summary of key design elements, and a report of the main results.

#### 1. Group Sequential Design

| Design types | Details |
|---------------------------------|------------------------------------|
| Sequential design | A group of designs that allows one or more interim analyses to be conducted to stop the trial early. <br>Early stopping can be made based on either superiority and/or futility. |

##### Case Study 9.1: MUSEC Trial (NCT00552604)
1) Background

- The MUltiple Sclerosis and Extract of Cannabis (MUSEC) trial was a phase III, randomized, double-blind, placebo-controlled study designed to evaluate the effectiveness of an oral cannabis extract in alleviating muscle stiffness among patients with stable multiple sclerosis (MS) (ClinicalTrials.gov identifier: NCT00552604).

- This study aimed to test whether oral cannabis extract could provide symptom relief for muscle stiffness and pain in adults aged 18–64 living with MS.

2) Design and Methods

- Adults diagnosed with MS who had experienced stable disease for at least six months—and had reported persistent muscle stiffness for a minimum of three months—were eligible for participation. 
- Participants were randomly assigned in a 1:1 ratio to receive either the cannabis extract or a placebo.

- The study included a 2-week dose-adjustment phase, followed by a 10-week fixed-dose treatment period.  Follow-up assessments were scheduled at weeks 2, 4, 8, and 12. 

- The primary outcome was the proportion of participants achieving meaningful improvement in muscle stiffness (rating 0–3 vs. 4–10) at the 12-week mark.

- The main analysis followed the intention-to-treat principle, comparing responder rates at 12 weeks between the two study groups. 
- Sample size estimates were based on assumptions of a 27% response rate in the placebo arm and a 15% absolute increase in the treatment arm, yielding a target response rate of 42%.

- To achieve 80% power at a one-sided alpha of 0.025, approximately 340 participants (170 per group) were needed. Anticipating up to 15% attrition, the target enrollment was increased to 400 (200 per group).

- An interim analysis was pre-specified once 200 participants had been assessed (representing 50% of the planned information fraction), using an O’Brien–Fleming boundary with an alpha of 0.0026 for early stopping based on superiority. Following this interim review, the independent Data and Safety Monitoring Board (DSMB) **advised reducing the final sample size to 300**, concluding that this would be sufficient to maintain a conditional power of 95%. To preserve the overall type I error rate at 0.025, the significance level for the final analysis was adjusted to 0.024.


#### 2. Seamless Design

| Design types | Details |
|---------------------------------|------------------------------------|
| Seamless design | Linked two phases of clinical trials, allowing immediate progression from one phase to the next (e.g., Phase IIB/III design). |

##### Case Study 9.3: Broad-Spectrum HPV Vaccine Study (NCT00543543)
1) Background
- Cervical cancer is primarily caused by persistent infection with human papillomavirus (HPV), with types 16 and 18 responsible for approximately 70% of cases. 
- At the time this study was conducted, the standard of care for HPV prevention was the quadrivalent HPV vaccine, which offers protection against four HPV strains: 6, 11, 16, and 18. Because this vaccine includes coverage for types 16 and 18, it was estimated to reduce cervical cancer risk by about 70%.

- The investigators of this trial hypothesized that expanding vaccine coverage to include additional high-risk HPV types could further enhance protection. 
- To test this, they evaluated a nine-valent HPV vaccine (targeting types 6, 11, 16, 18, 31, 33, 45, 52, and 58) in a seamless phase IIB/III study, using the quadrivalent vaccine as the comparator (ClinicalTrials.gov Identifier: NCT00543543).

2) Design and Methods
- This trial started as a phase IIB trial with three different formulations with varying doses (low, medium, and high) of 9-valent HPV vaccine with the goal of identifying an optimal formulation for the phase III evaluation (Table 9.2). 

| Intervention Group | Control Group | Target sample size or events| Primary analysis| 
|---|---|---|---|
|Phase IIB|
| Three doses of 9-valent HPV vaccine: Low/medium/high | 4-valent HPV vaccine | 1,240 (310 per arm) | Non-inferiority testing of antibody  response |
|Phase III|
|One dose of 9-valent HPV vaccine selected from Phase IIB| 4-valent HPV vaccine | 30 events and 14,000 patients (7,000 patients per arm) |Superiority testing of High-grade cervical, vulvar, or vaginal disease related to HPV-31, -33, -45, -52, and -58 (strains covered by 9-valent HPV vaccine and not by 4-valent HPV vaccine.)|

- The three formulations of 9-valent were three-dose regimens with two subsequent doses being administered at month 2 and month 6 after the first dose, but with varying concentrations that could be characterised as ‘low-dose’, ‘medium-dose’, and ‘high-dose’. The control group with 4-valent HPV followed the same dosing schedule.

- The enrolment target for **phase IIB** portion of this trial was set at 310 patients per group (a total of 1,240 subjects) to obtain 209 to 230 evaluable patients per arm assuming an attrition rate of 10%. 
- This was determined with the primary analysis being defined based on per-protocol analysis of non-inferiority of antibody responses to four types of HPVs that are protected by the control group at month 7. 
- The per-protocol analysis group was defined by those who received three full doses of vaccine during the pre-specified visit intervals and provided the 7-month serum sample for assessment of the immunogenicity. 

- For **phase III**, a per-protocol comparison of the rate of high-grade cervical, vulvar, or vaginal disease related to HPV strains not covered by 4-valent HPV vaccines (HPV-31, -33, -45, -52, and -58) was used as the primary analysis. 
- The target sample size was determined at 14,000 patients (7,000 per group) for the final analysis being targeted when there were at least 30 events observed in the trial [Reference Joura, Giuliano and Iversen13]. Vaccine efficacy was defined by relative risk reduction (calculated by 1 – risk ratio in 9-valent vaccine/risk ratio in 4-valent vaccine). 
- The target efficacy was defined by having a minimum threshold of 25% in the lower boundary of the 95% confidence interval of the vaccine efficacy. Assuming a true vaccine efficacy of 83% in favour of 9-valent HPV vaccine, a target of 30 events would provide 90% power to demonstrate the target efficacy of 25%. 
- As a key secondary analysis, a non-inferiority testing of the same immunogenicity endpoint was used but with a narrower non-inferiority margin of a 1.5-fold decrease in phase III versus a 2.0-fold decrease that was used in phase IIB. With such a margin, a statistically significant non-inferiority finding would require the lower boundary of the 95% confidence interval for the difference in percentage points to be greater than –5%.


#### 3. Sample Size Re-Assessment Design
| Design types | Details |
|---------------------------------|------------------------------------|
| Sample size re-assessment | Re-estimate the target sample size or number of events during the trial to ensure the desired statistical power. |

#### Case Study 9.4: VALOR (NCT01191801)
1) Background
- Vosaroxin and Ara-c combination evaLuating Overall survival in Relapsed/refractory acute myeloid leukaemia (VALOR) was a phase III, double-blinded, adaptive randomised trial that evaluated vosaroxin + cytarabine versus placebo + cytarabine in patients with first relapsed or refractory acute myeloid leukaemia (AML) (NCT01191801). 
- The relapsed or refractory AML has poor prognosis with median survival that is generally less than 1 year. Before VALOR began, a phase II trial on vosaroxin + cytarabine showed promising early results that supported the initiation of phase III evaluation.
- ***While it is often the case that phase II data are used to plan phase III confirmatory trials, it is important to note that estimates from phase II can be subject to uncertainty.*** This makes planning difficult for phase III trials, especially when there are financial constraints. 
- In this case study, we discuss how a method for adaptive sample size re-assessment called a ‘promising zone design’ developed by Mehta and Pocock was used to plan and execute VALOR.

2) Design and Methods
- VALOR is an event-driven randomised trial that randomised AML patients 1:1 to the vosaroxin arm or to the placebo. The primary endpoint was overall survival (OS) with the intention-to-treat principle being used as the primary analysis. 
- The initial accrual target was set at 375 deaths in 450 patients based on available phase II data that suggested that an improvement in median OS from 5 months in the placebo group to 7 months in the treatment group could be expected. The initial target would provide 90% power at 5.0% two-sided type I error rate to detect such improvement, which translated to a hazard ratio (HR) of 0.71 (5/7 = 0.71).

- As part of a promising zone design, one interim analysis was planned after 173 events, approximately half of the targeted events (Table 9.3). 

Table 9.3 

|Zone|Threshold|Possible decision options at interim analysis|
|--|--|--|
| Efficacy zone | One-side p-value of 0.0015 or lower (defined by O'Brien-Fleming boundary) | Option 1A) Stop trial early for superiority |
| Favourable zone | Conditional power greater than 90% | Option 2) Continue trial as planned |
| Promising zone | Conditional power 30%-90% | Option 3) Increase sample size and events by 50 % |
|Unfavoruable zone | Conditional power 10-30% | Option 2) Continue trial as planned|
| Futility zone | Conditional power < 10% | Option 1B) Stop trial early for futility |

- In VALOR, conditional power with a maximum number of 562 events and sample size of 675 was calculated assuming the treatment effect observed at the interim was a true effect. 
- If the conditional power was greater than 90%, the treatment was considered to be in the favourable zone where the trial could continue onto the initial target events and sample size. 
- If the conditional fell between 30% and 90%, this was considered the promising zone where the target number of events and sample size would be increased by 50%. 
- If the conditional power was between 10% and 30% (unfavourable zone), it did not warrant a sample size increase since the sample size would need to be increased beyond what is feasible to recruit to ensure adequate conditional power. 
- If the conditional power was less than 10%, the trial could stop early for futility because the treatment would be a lost cause.

#### 4. Response Adaptive Randomisation Design
| Design types | Details |
|---------------------------------|------------------------------------|
| Response adaptive randomisation | The allocation ratio can be adjusted over time to favor the study group with the more favorable interim outcome ('outcome' adaptive randomization). |

##### Case Study 9.5: RACE (NCT01665092)
1) Background
- The Rapid Administration of Carnitine in Sepsis (RACE) trial was a phase IIB, randomized, placebo-controlled clinical study designed with a Bayesian response-adaptive framework to evaluate the therapeutic potential of L-carnitine in patients experiencing septic shock (ClinicalTrials.gov Identifier: NCT01665092). 
- Based on evidence suggesting that L-carnitine may mitigate the hemodynamic disturbances associated with sepsis, the investigators proposed that early administration of L-carnitine as an adjunctive therapy in patients requiring vasopressors could reduce cumulative organ dysfunction within 48 hours, measured via the Sequential Organ Failure Assessment (SOFA) score, and improve 28-day survival. 
- The study aimed to compare three different dosages of L-carnitine to placebo in order to determine the optimal dose for potential evaluation in a subsequent phase III trial.

2) Design and Methods
- Participants were randomly allocated to one of four groups: placebo or one of three L-carnitine dose levels—6 g, 12 g, or 18 g—administered intravenously over a 12-hour period. The primary outcome was the change in SOFA score from baseline to 48 hours, with negative changes indicating clinical improvement. A secondary endpoint included mortality at 28 days.

- The planned sample size was 250 patients, with approximately one-third consistently allocated to placebo, and the remaining participants assigned across the three treatment groups using response-adaptive randomisation. During the initial “burn-in” phase (the first 40 patients), equal allocation (1:1:1:1) was maintained across all groups. 

- Thereafter, interim analyses occurred after every 12 enrolled patients, allowing the allocation ratios among the three active arms to be adjusted according to each dose’s evolving likelihood of being the most effective at improving SOFA scores.

Table 9.4

| Adaptation |
|---|
| Burn-in period: |
|Fixed allocation (1:1:1:1) for 40 patients|
| Post burn-in period: |
|Interim analyses every 12 patients up to 250 patients or a stopping rule|

- The trial incorporated pre-specified stopping criteria. If no L-carnitine dose showed at least a 40% posterior probability of being superior to placebo in reducing SOFA scores, the study could be halted for futility. 

|Stopping||
|---|---|
|Response adaptive randomization |~1/3 fixed allocation maintained to control <br> ~2/3 of allocation can be adapted to the best doseFootnote*|
|Early stopping for futility| <40% posterior probability that the most promising dose leads to improvement in SOFA at 48 hours versus placebo |
|Early stopping for superiority|>90% posterior probability that the most promising dose leads to improvement in SOFA at 48 hours versus placebo & >70% predictive probability of successFootnote|

- Conversely, if a dose exhibited both (1) over 90% posterior probability of benefit on SOFA score compared to placebo and (2) more than 70% predictive probability of achieving statistical significance for 28-day mortality in a future phase III trial (enrolling 2,000 patients in a 1:1 allocation), the study could be stopped early for superiority.

- A positive trial result required one or more doses to surpass a 90% posterior probability of benefit in SOFA reduction and a predictive probability of at least 30% for success in a subsequent phase III trial based on mortality. Simulation studies (30,000 iterations) were used to refine the design, ensuring desirable operating characteristics. 

- These simulations estimated an overall type I error rate of 4.3% and a statistical power of 91.1% under a scenario where the treatment effects of the three L-carnitine doses were 0, –1, and –2 compared to placebo.

#### 5. Adaptive Enrichment Design
| Design types | Details |
|---------------------------------|------------------------------------|
| Adaptive enrichment design | Potential modification of trial eligibility for narrower patient groups likely to benefit more from the indicated treatment. |

##### Case Study 9.6: TAPPAS (NCT02979899)
1) Background
- The TAPPAS trial (Trc105 And Pazopanib versus Pazopanib Alone in Patients with Advanced Angiosarcoma) was a phase III, randomized controlled study that employed an adaptive enrichment design. 
- Its objective was to evaluate whether the combination of carotuximab (Trc105) and pazopanib offered improved outcomes over pazopanib alone in patients with angiosarcoma. 
- Prior exploratory research suggested that this drug combination might be particularly effective in patients with cutaneous angiosarcoma, prompting the use of an adaptive strategy in the TAPPAS trial. 
- This design allowed for possible modifications to the enrolled population or sample size mid-trial, depending on emerging evidence from an interim analysis.

2) Design and Methods
- Participants were randomized in a 1:1 ratio to receive either carotuximab plus pazopanib or pazopanib alone. 
- The randomization followed a stratified permuted block design with variable block sizes (2 or 4), and stratification factors included angiosarcoma subtype (cutaneous vs. non-cutaneous) and number of prior systemic treatments (0 vs. 1–2). 
- The primary endpoint was progression-free survival (PFS), evaluated on an intention-to-treat basis.

- The original plan targeted 95 PFS events, with a total enrollment of 190 patients to provide 83% power at a two-sided alpha of 0.05. 
- This was based on detecting a hazard ratio (HR) of 0.55, corresponding to an increase in median PFS from 4 to 7.27 months.

- To address potential heterogeneity in treatment response between subtypes, the study employed an adaptive enrichment framework. 
- An interim analysis was scheduled to occur after 40 events or 30 days following the enrollment of the 120th participant, whichever came first. 
- At that point, two conditional power metrics were calculated: one for the full study population (CP-full) and another restricted to patients with cutaneous angiosarcoma (CP-cutaneous). 
- Based on these values, the trial could fall into one of four zones:

Table 9.6: Decision rules for interim analysis in TAPPAS

|Zone|Threshold|Possible decision options|
|--|--|--|
|Favourable zone|CP-full >95%|Option 1) Continue as planned to 190 patients/95 events|
|Promising zone|CP-full 30-95%|Option 2) Increase enrolment target from 190 patients/95 events to 340 patients/170 events|
|Enrichment zone|CP-full <30% and CP-cutaneous >50%| Option 3) Enrich and enrol 160 cutaneous patients only thereafter for a final analysis done at 110 events in the enriched group
|Unfavourable zone|CP-full <0% and CP-cutaneous <= 50%|Option 1) Continue as planned to 190 patients and 95 events|
|Futility zone|Up to the judgment of the independent DSMB|Option 4) End the trial for futility|

While there were no formal stopping rules for futility, the Data and Safety Monitoring Board (DSMB) retained the discretion to recommend halting the study if interim results suggested the treatment was underperforming compared to control.