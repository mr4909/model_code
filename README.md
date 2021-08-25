# Model Code

## Repository Structure

    |-- code (run in this order; code separated out by topic)  
      |-- import.R              # loads packages, imports dta and xlsx files
      |-- supervision.R         # cleans and aggregates supervision files 
      |-- medical.R             # cleans and aggregates medical files 
      |-- analysis.R            # logistic regression, propensity score analysis
      |-- report.Rmd            # generates report of findings

# Research Proposal: Analysis of Individuals on the Specialized Mental Health Caseload in the Georgia Department of Community Supervision 

## Introduction 

It is widely acknowledged that individuals with mental illness are over-represented in the criminal justice system. While only 5 percent of the U.S. population has a serious mental illness, the number of people in prison or jail with a serious mental illness is as high as 16 percent.1 Once they are returned to the community, individuals with severe and persistent mental illness typically confront numerous psychosocial and economic challenges, from unemployment and homelessness to access to medications and treatment.2 In response to the growing presence of mentally ill individuals in the justice system, states have adopted a variety of policy approaches such as pretrial diversion programs, mental health treatment courts, and specialized supervision of people with mentally illness. Such approaches seek both to serve the mental health needs of this population as well as improve the public safety outcomes of the community. Recent studies have demonstrated that a well-implemented specialized supervision program can also be cost effective compared to traditional probation for people with serious mental illness, with the potential to reduce reliance on emergency, inpatient, and residential services.3 

Georgia is one of the states that has adopted policies to address the needs of mentally ill individuals who are involved in the state’s criminal justice system. In addition to residential programs serving this community, some counties have established mental health treatment courts while others have launched Stepping Up initiatives. The Georgia Department of Community Supervision (DCS) has been supervising individuals with mental illness on specialized caseloads since January 2017. Individuals who are eligible for this specialized caseload include people stepping down from Integrated Treatment Facilities (ITF), individuals released from Georgia Department of Corrections (GDC) custody with a Level III or Level IV mental illness, and individuals placed on supervision who have been diagnosed with a serious mental illness (SMI) or are receiving mental health services. The stated goals of the mental health supervision program include “enhanced supervision, decrease re-arrests, and to ensure treatment/medication compliance.”4 With over three and a half years of experience in supervising individuals with serious mental illness, DCS is interested in assessing the effectiveness of its mental health caseload program. 

The Council of State Governments (CSG) Justice Center proposes to conduct an in-depth analysis of DCS caseloads, with particular focus on the specialized mental health caseloads to (1) evaluate responses to violations of supervision, (2) calculate overall supervision outcomes, and (3) assess the department’s fidelity to the specialized mental health caseload program design. The research will be comprised of individuals placed on DCS supervision at any time between June 2017 and June 2019. From this large data set, the analysis will compare violation history and outcomes for people without serious mental illness on supervision against people with serious mental illness. The analysis will further compare violation history and outcomes for individuals with serious mental illness who are supervised on specialized mental health caseload against individuals with serious mental illness who are supervised on standard caseloads. This latter group will be composed of individuals whose mental health screens nearly qualify them for the mental health caseload but who are deemed stable and placed on standard supervision during the same timeframe. The analysis will also include an assessment of how well the specialized caseload program is adhering to the placement and supervision protocols as outlined by DCS.  

The data to be analyzed will include robust details such as the assessed needs, special supervision conditions, demographics, supervision level and risk score, mental health screening score, criminal and sentencing history, case management history, and any recorded revocations during the supervision period. Some specific lines of research include how many violations are cited for people with serious mental illnesses compared to those without serious mental illness. Additionally, the research will evaluate (1) how long someone is supervised on the mental health caseload before being transferred to standard supervision; (2) whether the selection criteria for placement on the mental health caseloads is capturing all individuals who meet the requirements; and (3) how well the various offices can meet the 40:1 caseload cap per supervising officer. The research design will try to control for the availability of community resources in more rural parts of the state and will distinguish between individuals who were incarcerated in prison prior to supervision by DCS and individuals who were placed on DCS supervision without prison experience. 

In addition to providing an assessment for DCS, findings from this analysis could inform the work of the Mental Health, Courts, and Corrections subcommittee of Georgia’s Behavioral Health Reform and Innovation Commission.  

## Summary of Research Questions for the Analysis 

This proposal offers a multi-pronged research approach that specifically focuses on assessing program outcomes for non-SMI and SMI individuals under supervision, as well as a comparison of the SMI population on standard supervision or on a specialized mental health caseload, and finally, on assessing the fidelity of the mental health caseloads as implemented compared to the program design. For the first part of the research, CSG Justice Center will analyze SMI and non-SMI populations, providing a descriptive comparison of supervision violations and overall outcomes. The range of outcomes to be analyzed include re-arrest events that occurred after the start of supervision, use of prison alternatives to address noncompliance, and technical or new offense violations that result in revocation from supervision. 

For the second part of the research, CSG Justice Center recommends using a propensity score matching technique to create two cohorts of individuals: (1) those individuals placed on specialized mental health caseloads and (2) those not placed on a mental health caseload but whose mental health screens indicated a need in this area. This method results in a closely matched comparison group and can reduce any treatment assignment bias that might influence the outcome analysis. The outcomes to be analyzed will closely resemble the outcomes from the first part of the research: re-arrest events, prison alternatives, and regular revocations. 

The third part of the research project will assess the fidelity to the mental health caseload program. Specifically, the analysis will focus on adherence to the program protocols, degree of exposure (dosage), and program differentiation. Additionally, this part of the analysis will determine the average length of stay of the mental health caseload, the number and type of officer contacts, and the efforts made at achieving medication and treatment compliance. The study will also examine how often individuals on the mental health caseload are referred to community-based services, and if possible, whether those referrals result in treatment engagement.  

## Data Requirements for the Study 

CSG Justice Center staff will require case-level data pulls from the Georgia DCS’s Portal case management system. It is assumed that the case management system will include data on incarcerations in a Georgia Detention Center or in a prison bed for a supervision violation, with start and end dates available to calculate length of stay. If those details are not available in the Portal system, the data request might need to be expanded to include the Georgia Department of Corrections. 

All individuals who started on DCS supervision from July 1, 2017 to June 30, 2019: 
- Demographics: sex, race, age at time of data pull, education level, current risk score and supervision level, assigned judicial circuit, current supervising officer 
- Case Manager History 
- Re-entry programs, needs, and referrals 
- Risk Score History including risk score, risk assessment type, start date, end date, and scores for each metric 
- Responses captured in the DCS mental health screen 
- Mental Health data that was captured from the GDC system, which will allow the cases to be differentiated according to incarceration history  
- Supervision episodes, including start dates and end dates, type of supervision, supervision level history (including comments, where custodial status is indicated) 
- Criminal History, including arrest history, all delinquent reports, sentence summary, sentence adjustments, offenses/charges, and revocations history 
- Drug Screens History 
- Diagnosis and Medications data 
- Indication or history of participation in accountability courts 
- All officer interactions recorded in the Portal, including date of contact, type of contact (e.g. in-person contact, on-line contact, office visit, home visit, etc), contact category, location, and success status 
- Other officer or court responses (e.g. increased reporting, electronic monitoring, curfew, placement in PDCs or county jails, revocations, etc) 
- Referral history to DRCs, RSATs, ITFs, other community treatment providers, to include date of referral and type of treatment provider (mental health, substance use, cognitive behavioral programs, etc) 
 
It will be necessary to combine data from the various data files that are pulled from the Portal case management system; a unique identifying field will be required. Depending on the structure of the Portal system, the unique identifier might be the GDC ID or the SID number. Ideally, a dummy variable can be created by DCS to add an additional layer of confidentiality to the data. CSG Justice Center will work with the Research or IT staff at DCS to determine whether this added layer of security is available. 

Note that this proposal will not include an analysis of community providers of behavioral health services, which is beyond the scope of this project. 

## Anticipated Project Timeline and Next Steps 

The project is expected to take about eight months for a researcher, a policy analyst, and a behavioral health analyst who specializes in mental health services in the criminal justice system to complete once the CSG Justice Center receives all the data. Project deliverables will also receive input from Jessica Saunders, Research Division Director, and other division leadership. The length of time for the data analysis component will be influenced by the availability and quality of supervision data. Once the data analysis is complete, it will take an additional two to three months to develop recommendations. 

## Project Deliverables 

1. Project logic model to supplement the data request 
2. Written project report on the analysis and data findings 
3. Presentation and policy recommendations 
