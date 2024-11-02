Risk Management Plan
====================

# Scope
*This is a generalized risk management plan for a class II/III device.  Expand on the activities or reduce them down as appropriate for the device in question.  Italicized content is commentary. Parentheticals in headings are references to ISO 14971.  Keep these in, it's super helpful when you're getting audited.  The risk management plan requirements are **only** section 4.4.  If you're wondering where "competence of personnel" or "risk analysis process" fits into planning, it doesn't. Only document what you need to and don't try to do extra.  More is not better with risk management.*

# References

| Document ID | Title |
| ----------- | ----------- |
| ISO 14971 | Medical devices - Application of risk management to medical devices, third edition |
| *document* | *title* | 

# Terms and Definitions

| Term | Definition |
| ---- | ---------- |
| Harm | Injury or damage to the health of people, or damage to property or the environment (ISO 14971)|
| Hazard | Potential source of harm (ISO 14971)|
| Life cycle | Series of all phases in the life of a medical device from initial conception to final decommissioning and disposal (ISO 14941)|
| Risk | Combination of the probability of occurrence of harm and the severity of that harm (ISO 14971)|
| Risk management | Systematic application of management policies, procedures, and practices to the tasks of analyzing, evaluating, controlling, and monitoring risk (ISO 14971)|
| Severity | Measure of the possible consequences of a hazard (ISO 14971)|
| State of the art | Developed state of technical capability at a given time as regards to products, processes, and services, based on the relevant consolodated findings of science, technology and experience (ISO 14971)|

# Risk Management Activities (4.4a)
## Description of the Medical Device
*Option 1 (preferred): A reference to the description of the medical device.  This is probably going to show up elsewhere in your documentation.  Don't repeat the description since it will inevitably get out of sync as the various copies of the device description get word-smithed over the course of your project and then you are going to have conflicting descriptions.*

*Option 2 (not preferred): Add a description of your device.  If it shows up somewhere else in your documentation that will be reviewed I reiterate, don't do this.  It's stupid.*

## Risk Management Life Cycle Phases

*Scope the risk management plan appropriately and tailor to project specific needs.  If post-market activities are outside the scope of the development effort don't mention it.  Same for FMEAs, no one is forcing you you do them.  You can just say that you are doing a hazard analysis and wash your hands of the other analyses if it makes sense.*

| Activity | Phase | *Notes* |
| -------- | ----- | ----- |
| Create risk management plan | Phase 1 / Planning | *Remap the phases to whatever your company calls them* |
| Create clinical hazards list | Phase 1 / Planning | *Super useful, get clinical to give you this.  Good ones have hazards mapped to severities.  Less good ones just tell you what the hazards and related harms are.  If you have this you don't need cliniical to be involved in the fmeas or hazard analysis.* |
| Create initial hazard analysis | Phase 1 / Planning | *Do the initial scoring, but don't bother applying risk controls.* |
| Create system fmea |  Phase 2 / Development | *Don't fall into the trap of "it's a small system, let's just do a system fmea". That line of reasoning will screw you 102% of the time.* |
| Create electrical fmea |  Phase 2 / Development | |
| Create software fmea | Phase 2 / Development | |
| Create use fmea | Phase 2 / Development | |
| Complete hazard analysis | Phase 2 / Development | |
| Verify the implementation and effectiveness of risk controls | Phase 3 / Verification | |
| Create risk benefit analyses | Phase 3 / Verification | *You can combine this into the risk management report, but a lot of times it's easier to have the report tie a bow on the risk management activities and reference other documents.* |
| Create risk management report | Phase 3 / Verification | |
| Create clinical evaluation report | Phase 3 / Verification | *Needed for CE marking* |
| Compile risk management file | Phase 3 / Verification | *If you are one of those companies that does the "risk management index" thing.  An index makes finding documents easier, but someone has to keep the thing up to date.* |
| Risk management file review | Phase 3 / Verification | *Or as a part of design transfer activites* |
| Create process fmea | Phase 4 / Production | *Or as part of the design transfer activities.* |
| Create post-production reports | Phase 4 / Production | *There is a tacit "and update documents as appropriate" in this activity.* |


# Responsibilities and Authorities (4.4b)

*If your project plan states this, just reference the project plan.  Otherwise something like this will work.*

| Role | Name | Responsibility |
| ---- | ---- | -------------- |
| Top management | *name* | Review of risk management file and final approval prior to production. |
| Risk management lead | *name* | Create risk management plan, hazard analysis, risk management report, and compile the risk management file. |
| Clincal lead | *name* | Create clinical hazards list, risk benefit analysis, and clinical evaluation report. |
| Quality assurance | *name* | Conduct risk management reviews. |
| Verification | *name* | Verify risk controls |
| Systems engineering | *name* | Create system fmea |
| Electrical engineering | *name* | Create electrical fmea |
| Mechanical engineering | *name* | Create mechanical fmea |
| Software engineering | *name* | Create software fmea |
| Production | *name* | Create post production reports and process fmea |

*Note: Someone needs to be the final go / no-go.  Top management makes sense for this, but in large organizations you might not get someone in the C-suite for sign off.  Adjust as appropriate.*

*Note 2: The risk management lead is commonly QA, Systems, or Clinical Engineering.  Update the table to the MINIMAL set of individuals required by your organization.  Too many cooks in the kitchen is a common problem in risk management.*

# Review of Risk Management Activities (4.4c)
*Option 1 (preferred): Copy what your QMS says.  The benefit of copying your QMS is that you don't get impacted when quality decides to go on a continuous improvement crusade.  It also allows you to tailor the review activities to your project's needs.  Remember, you are going to have to defend your risk management in an audit.  Don't get stuck defending some crap someone else wrote.*

*Option 2: Reference your QMS.  See above for reasons on why you might not want to do this.*

*Option 3: Make it up yourself.*

Risk management documents are reviewed as a part of phase gate reviews.  The review is documented in the phase gate design review document.  Top management reviews the risk management file prior to production.

# Risk Acceptability (4.4d)
## Policy for Determining Acceptable Risk
Risk acceptability is defined in the table below.

| Risk Level | Risk acceptability |
| ---------- | ------------------ |
| Low        | Risks at this level are acceptable without additional risk control required. |
| Medium     | Risks at this level are accepetable if the application of additional risk controls will not reduce the risk further or if the application of additional risk controls increases the overall residual risk. |
| High       | Risks at this level are accepetable if the application of additional risk controls will not reduce the risk further or if the application of additional risk controls increases the overall residual risk, and a risk benefit analysis determines that benefits outweigh the risk, and the residual risk is disclosed in the instructions for use. |


### Risk Categories
Risk categories are determined using the table below.

| | | | | | |
| -------------- | -------------- | ---------- | ----------- | ------------ | ---------------- |
|                | **Negligible** | **Minor**  | **Serious** | **Critical** | **Catastrophic** |
| **Frequent**   | Low            | Medium     | High        | High         | High             |
| **Probable**   | Low            | Medium     | Medium      | High         | High             |
| **Occasional** | Low            | Low        | Medium      | Medium       | High             |
| **Remote**     | Low            | Low        | Low         | Medium       | Medium           |
| **Improbable** | Low            | Low        | Low         | Low          | Medium           |


### Probability of Occurrence of Harm
Probability of occurrence of harm levels are defined by the table below

| Probability Of Occurrence of Harm | Probability (P) of Occurence of Harm Per Use | Harms (X) per 100,000 Devices Per Year |
| --------------------------------- | -------------------------------------------- | -------------------------------------- |
| Frequent                          | P > 1 in 1,000                               | X > 100,000                            |
| Probable                          | 1 in 10,000 < P <= 1 in 1,000                | 10,000 < X <= 100,000                  |
| Occassional                       | 1 in 100,000 < P <= 1 in 10,000              | 1,000 < X <= 10,000                    |
| Remote                            | 1 in 1,000,000 < P <= 1 in 100,000           | 100 < X <= 1,000                       |
| Improbable                        | P <= 1 in 1,000,000                          | X <= 100                               |

### Severity of Harm
Severity levels are defined in the table below.

| Severity of Harm | Description |
| ---------------- | ----------- |
| Negligible | Discomfort, inconvenience, or no harm.  Property or environmental damage totaling less than $10,000. No change to the treatment of a patient's condition. |
| Minor | Injury requiring non-professional medical intervention or basic first aid to remedy. Iterference with other equipment.  Property or environmental damage totaling at least $10,000 and less than $100,000. A delay or change in the treatment of a condition that does not change the clinical outcome for the patient. |
| Serious | Injury requiring medical intervention to to remedy.  Temporary impartment.  Interference with information technology equipment or infrastructure equipment. Property or environmental damage totaling at least $100,000 and less than $1,000,000. A delay or change in the treatment of a condition that results in serious injury. |
| Critical | Injury resulting in premanent imparment or life long treatment. Interference with non-life sustaining medical equipment. Property or environmental damage totaling at least $1,000,000 and less than $10,000,000. A delay or change in the medical treatment of a condition that results in critical injury. |
| Catastrophic | Injury resulting in death, coma, paralysis, or brain damage.  Immediate life threatening injury.  Interference with life sustaining medical equipment. Property or environmental damage totaling $10,000,000, or more.  A delay or change in the medical treatment of a condition that results in catestrophic injury or immediate life threatening injury. |

## Criteria for Accepting Risks When the Probability of Occurrence of Harm Cannot Be Estimated
*Option 1: If you use a probability of a hazardous situation occurring and a probability of a hazardous situation leading to harm*

When the probability of a hazardous situation occurring cannot be estimated, the probability of the hazardous situation leading to harm is used as the probability of occurrence of harm.  When the probability of a hazardous situation leading to harm cannot be estimated, the probability of the hazardous situation occurring is used as the probability of occurrence of harm.  If neither can be estimated, the probability of occurrence of harm is assumed to be frequent.  The resulting risk is determined using the risk category table above and assessed using the risk acceptability table above.

*Option 2: If you use only a probability of occurrence of harm*

When the probability of occurrence of harm cannot be estimated, it is be assumed to be frequent.  The resulting risk is determined using the risk category table above and assessed using the risk acceptability table above.

# Evaluation of Overall Residual Risk (4.4e)
A clinical evaluation report is compiled evaluating the risk of the device as documented in the risk management file to the state of the art.  State of the art is determined by a survey of the MAUDE database, a literature review, and review of post-market information for predicate devices.  If the overall risk of the device is deemed to be no greater than that of the state of the art, the overall residual risk is deemed to be acceptable.  Otherwise, the overall residual risk can only be deemed acceptable if a risk benefit analysis deems the benefits of the device to outweigh the risks posed.

# Verification of the Implementation and Effectiveness of Risk Controls (4.4f)
The verification of the implementation and effectiveness of risk controls takes place as a part of verification activities as outlined in the verification and validation plan.  The results of the verification is documented in the verification report.


# Collection and Review of Production and Post-Production Information (4.4g)
*A lot of organizations are going to have a separate post-production teams and dedicated post-production procedures.  Refer to those documents and give a high level overview.*

Production and post-production reports are gathered as a part of the complaint handling process.  These complaints and associated health hazard evaluations are compiled and a review is performed at least once every 2 years.  The risk management file is updated as appropriate as a part of this review.
