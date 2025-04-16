## Ch 4. Common Types of Adaptive Trial Designs

### Presenter : Chungsoo Kim 
- [LinkedIn](https://www.linkedin.com/in/chungsoo-kim-42419b175/), [Github](https://github.com/ChungsooKim), [Personal page](https://medicine.yale.edu/profile/chungsoo-kim/)

### Chapter Summary
This chapter covers several commonly used types of adaptive trial designs, including **sequential designs, sample size re-assessment, adaptive randomisation, minimisation, response-adaptive randomisation, enrichment designs, and seamless designs**.

Compared to conventional fixed designs, adaptive trials provide greater flexibility but also introduce additional complexities, necessitating <ins>meticulous planning</ins> during the design phase.

### Introduction
Although there are countless variations of adaptive trial designs, they commonly focus on adaptations to key design elements such as **sample size, allocation ratios, and eligibility criteria**. Adaptive designs are often categorized based on the specific aspect of the trial that is subject to modification.

| Design types | Details |
|---------------------------------|------------------------------------|
| Sequential design | A group of designs that allows one or more interim analyses to be conducted to stop the trial early. <br>Early stopping can be made based on either superiority and/or futility. |
| Sample size re-assessment | Re-estimate the target sample size or number of events during the trial to ensure the desired statistical power. |
| Minimization | Adaptive randomization that adjusts allocation based on prespecified covariates to minimize prognostic factor imbalance between comparison groups ('covariate' adaptive randomization). |
| Response adaptive randomisation | The allocation ratio can be adjusted over time to favor the study group with the more favorable interim outcome ('outcome' adaptive randomization). |
| Adaptive enrichment design | Potential modification of trial eligibility for narrower patient groups likely to benefit more from the indicated treatment. |
| Seamless design | Linked two phases of clinical trials, allowing immediate progression from one phase to the next (e.g., Phase IIB/III design). |

### Common types of adaptive trial designs

#### 1. Sequential design
- Definition

    1. A group of trial design that permit early termination based on the results of interim analyses.
    2. An interim analysis involves calculating a test statistics (e.g., p-value) and the trial or specific arm is typically stopped if the test statistic reaches a predefined threshold.
    3. Early stopping can be made based on factors such as superiority(effective), futility (lack of benefit/sufficient activity), or harm (safety/adverse events).
    4. If the assumed treatment effect underestimates the true effect, the planned sample size might exceed what is actually needed. In such cases, interim analyses for superiority can be valuable in reducing the expected sample size of the trial.

- Types 
    1. How error rate should be controlled and what statistical metrics will be used
    2. Frequentist approach 
        1. Conditional power refers to the probability that the final result will be statistically significant at a future sample size, based on the data observed at the interim analysis and assuming a specified treatment effect.
        2. Pocock, O'Brien-Fleming, and Haybittle-Peto tests 
    
    3. Bayesian approach
        1. Bayesian predictive probability refers to a probability of eventual trial success at the future sample size, given the current data and the assumed prior distributions. Less prone to misinterpretation.
        2. Bayesian rules has been increasing in recent trial research. **Trial simulation** is performed under the null effect scenario.

- Challenges
    1. False error rate associated with stopping
    2. Bias in the estimate of the treatment effect
    3. However, if the size of the burn-in period is adequately large, the bias is generally small. 
    4. Ethical and efficiency consideration should outweigh the concerns.


#### 2. Sample size re-assessment (Sample Size)
- Definition
    1. Assumptions for sample size calculations are often based on findings from historical studies, but have limitation.
    2. Sample size re-assessment is an adaptive trial design approach developed to reduce the risk of false-negative findings resulting from underpowered trials.
    3. Conditional power or Bayesian predictive power can be used to determine the sample size.

- Types
    1. Blinded re-assessment: estimation of the variance or the overall event reate of the primary endpoint from blinded interim data, where the observations from both groups are pooled without revealing the data.
    2. Unblinded re-assessment: based on unblinded interim treatment effect estimates

- Challenges
    1. Leakage of information about decision
    2. Operational bias (investigators' behavior may change as a result)
    3. For the unblinded re-assessment, the interim estimate of the treatment effect can be misleading if it is based on small partial data.

#### 3. Adaptive randomization (Allocation)
In clinical trials employing adaptive design, allocation probagbilities can be adjusted based on accumulating data throughtout the course of the trial.

##### 3-1. Minimization (Covariate adaptive randomization)
- Definition
    1. Adapts allocation to minimize imbalance of pre-specified prognostic factors between groups.
    2. Treatment allocation of the new paitent enrolling into the trial is determined based on the **characteristics of the patients already enrolled**.

- Challenges
    1. Allocation procedure is dependent on known baseline factors, so the theoretical properties of archieving balance of both known and unknown factors are not clear.
    2. If unimportant prognostic factors are chosen, minimization may result in a balance that is not relevant for statitstical inference.
    2. Practical challenges: allocation concealment is difficult (secure allocation system should be used) -> Raise complexity and Cost

##### 3-2. Response adaptive randomzation (Outcome adaptive randomization)
- Definition
    1. Clinicians often perceive randomization as being uncomfortable and potentially conflicting with patient care. Patients' willingness to participate in RCT can also vary greatly.
    2. A type of adaptive trial design in which allocation ratios are preferentially adapted in favor of study arm based on interim results.
    3. Use past treatment assignments AND **patient responses** to adapt the allocation probability for future patients beingn enrolled.
    4. More patients could be randomized to the superior treatment (Ethically appealing properties)

- Challenges
    1. Unequal balance of patients
    2. Statistical challenges
    3. No RCTs have examined the effect of response adaptive randomization (2018)

#### 4. Adaptive enrichment design (Eligibility criteria)
- Definition
    1. Modifiaction of trial eligibility criteria based on an interim analysis to restrict future enrolment to narrower groups of patients (more responsive to treatments).
    2. Often involve predictive biomarkers (e.g., gene mutations)
    3. If evidence suggests that the biomarker-positive subpopulation is more likely to benefit from the treatment, the trial may be adapted by modifying eligibility criteria-either exlcuding the biomarker-negative or reducing their enrollment proportion (positive group **"enriched"**).

- Challenges
    1. Rely on baseline information of biomarker status
    2. make smaller potential pool of an eligible population (difficult to recruit patients)
    3. Add trial cost
    4. Generalizability (if the trial ends up making a false enrichment decision)

#### 5. Seamless Design
- Definition
    1. Seamless design are a type of adaptive trial design that enable a direct transition from one phase of the trial to the next without interruption (e.g., Phase IIB/III trials).
    2. this approach is particularly useful for reducing the overall duration of clinical drug development process.

- Types
    1. Operationally seamless: Eliminates time between the tow phases, but analyses in the later phase would not include the data collected from the earlier phase.
    2. Inferentially seamless: Use data from both phases for analysis.

- Challenges
    1. Require early data can be rapidly analysed and interpreted to inform decisions about transition into the subsequent phase
    2. Challenges on administration and infrastructure

### Conclusion
We discussed common types of adaptive trial designs and how they leverage accumulating interim data to implement pre-specified adaptations. 
It is crucial to clearly pre-specify and transparently report the interim analysis plan, including endpoints, statistical methods, stopping criteria, timing of the first interim analysis (burn-in period), and the number of frequency of subsequent analyses.
