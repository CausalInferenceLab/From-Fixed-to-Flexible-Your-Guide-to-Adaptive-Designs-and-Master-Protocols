# Chapter 5 - Clinical Trial Simulation

# Presenter : HeeSeok Yoo


# **Introduction** 


- Monte Carlo simulation : example of coin toss 


| General Steps                   | Applied to te coin toss example                |
| *Specify numerical values for*: |                                                |                                
| - Simulation parameters         | Probability of heads = 0.50                    |
| - Sample size                   | 10 tosses of the coin                          |
| - Analysis/test statistics      | Number of heads out of the 10 tosses           |
| *For each replication*:         |                                                |
| 1. Generate data                | Generate 10 random coin tosses                 |
| 2. Run Analysis                 | Count the number of heads out of 10 tosses     |
| 3. Keep track of the performance| Keep track of 2 and repeat 1,000 times         |

* In Clinical trial, we can't repeat the trial like coin flip. 
* The Utility of simulation studies in a clinical design prcess has become very important.



# Clinical Trial Simulation

## Terms

* Operating characteristics - description of how a design performs under various scenarios.
* Scenario - List of values specifying the 'true' underlying parameters, such as true response rates, recuritment rate, etc. 
* Simulation - Repeated analyses of randomly generated datasets drawn under specific assumptions.
* Simulation report - Written documents that provides the explanation, details, and justification of the simulation study.
* Trial design - Details about how the trial is conducted.
* Virtual trial - Clinical trial being simulated in computer.

## Overview of Clinical Trial Simulation

* The goal of cilnical trial sumulation is to make virtual trial design match as closely as possible how the trial will be conducted.
* General steps of simulation for an adaptive clinical trial would involve:
  ** Step 1: Simulate the arrival time of the next patient.
  ** Step 2: Check the stopping rules to see if the trial should be stopped.
  ** Step 3: If the trial not stopped, enroll more patients into the nexy interim analysis.
  ** Step 4: Simulate the patient outcome as a fuction of the treatment.
  ** Step 5: Repeat steps 1-4

## Principles of Simulation-Guided Trial Design

* Simulation-guided trial design encourages evaluating multiple design options early to ensure the most efficient and ethical choice is made for each clinical question.
* Adaptive designs can improve trial success by anticipating potential regrets and adjusting accordingly, serving as a form of 'insurance' against trial failure.


# Simulation-Guided Design Planning Case Study

* Simulation studies help explore the trade-offs between trial designs beyond average behavior.
* Rather than recommending one design, a Bayesian adaptive approach is used to review different metrics.

## Design and Scenario Assumptions

| No. | Trial designs                         | Scenarios                                        |
| 1   | Equal randomisation                   | Equal treatment effect/response rate (Null)      |
|     | - 1:1 allocation to E and S           | - pS = 0.3 and pE = 0.3                          |
| 2   | RAR with no minimum/maximum allocation| 10% higher response rate in E                    |
|     | - At interim analysis, adapt the      | - pS = 0.3 and pE = 0.4                          |
|     |   allocation probability for E to     |                                                  |
|     |   probability that E has higher       |                                                  |
|     |   response rate than S (pE)           |                                                  |
|     | - Allocation of S would be 1 − pE     |                                                  |
| 3   | RAR with minimum/maximum allocation   | 20% higher response rate in E                    |
|     | - Same as Design 2 with 10% minimum   | - pS = 0.3 and pE = 0.5                          |
|     |   and 90% maximal allocation          |                                                  |
|     |   probabilities, to ensure that the   |                                                  |
|     |   allocation does not get ‘stuck’     |                                                  |
|     |   on one study arm                    |                                                  |

* Patient enrollment followed a Poisson process with interim analysis every 10 subjects after a 30-subject burn-in.
* Response probabilities:  
  * pS ~ Beta(0.2, 0.8)  
  * pE ~ Beta(0.2, 0.8)  
* Stopping rules:  
  * Superiority threshold = 0.995  
  * Futility threshold = 0.005  
  * Ensures Type I error < 3.3% under null
 
## Simulation results

* Type I error ~0.03 in Scenario 1 across designs
* Design 1 has highest power in all scenarios (0.72 in Scenario 3)
* Early stopping rates and mean sample sizes vary
* P20 metric introduced: % of trials where ≥20 more patients assigned to SOC

## Examination of Singl Virtual Trials

* Figures display randomization probabilities over time for virtual trials
* Design 2 shows large imbalance in some trials, e.g., 172:26 (SOC:E) in null scenario
* Design 3 mitigates imbalance via min allocation threshold
* In Scenario 2 and 3, some trials assigned more to inferior treatment → RAR risk
* P20 exposes ethical risk of RAR misallocating patients
* Even fixed randomization (Design 1) can show imbalance without blocked randomization
* Design evaluation must go beyond averages — include worst-case risks

## Simulation Reports
* Essential for adaptive and complex trials
* DIA-ADSWG recommends including:
  * Objectives, inputs, design rules
  * Scenario definitions, operating characteristics
  * Discussion and justification of chosen design (Table 5.4)

## Simulation Software
* **Commercial**: EAST®, ADDPLAN®, COMPASS®, FACTS
  * Advantages: ready-to-use, no coding required
  * Limitations: cost, limited flexibility for custom designs
* **Open-source (R-based)**:
  * Notable packages: `rpact`, `MAMS`, `Mediana`, `multiarm`, `adaptr`, `OCTOPUS`, `gsDesign`
  * Many offer vignette tutorials
  * Available on CRAN and GitHub

## Conclusion
* Simulation is critical to evaluate trial design operating characteristics
* Adaptive designs may improve ethics but carry trade-offs
* No universal best design — simulation helps identify the most efficient and ethical option per research question