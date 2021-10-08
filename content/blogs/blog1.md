---
categories:
- ""
- ""
date: "2017-10-31T22:26:15-05:00"
description: "Click here for more information about my recent coding project, regarding critical data for COVID 19"
draft: false
image: coding.JPEG
keywords: ""
slug: Coding
title: Coding
---

## **Welcome to the fourth tile of my website;**

Critcare Data

Summary

**Abstract and Background**
Covid-19 was a virus first identified in China in 2019. This virus has been transmitted around the world and categorised as a pandemic by the World Health Organisation. The virus has led to over 3 million deaths worldwide to date.
Patients with the most severe effects of Covid-19 appear to have a high morbidity and the following report is an analysis of 600 Covid-19 patients entering Intensive Care / Critical Care Units (Critcare), primarily concerned with the survival probabilities of these patients after 30 days.

For each patient entering critical care, the time in days since they entered critical care was recorded and given an indicator of death, or they were censored out of the study. Subsequently eight more variables regarding the patient’s prior health were noted. These variables include age, gender, body mass index, comorbidities, the use of invasive ventilation within 24 hours, prior dependency, deprivation index of postcode and their Apache II Risk Score*.

**Method and Initial Findings**
I have used a number of methods including Kaplan Meier Plot, Cox Proportional Hazard Model, Prognostic Index, Schoenfeld Residuals and the Cook’s Influence Model. These have all been modelled using R.
The initial analysis of the data would suggest that the patients age, BMI, comorbidities, deprivation and their Apache II risk score are all factors that decrease the probability of survival. These are factors that decrease general health, which in turn increases the risk from viruses such as Corona Virus.

**Introduction**
Critcare Data 093 is a subset of 600 patients from a larger set of patient data of people who entered critical care after contracting COVID-19.

For each patient entering Critcare the number of days since entering Critcare was recorded together with Cens and the variables:

Cens : Indicator of death (1) or Censoring (0) Censored out of the study Variables:
  -Age
  -Gender
  -BMI: Body Mass Index
  -Apache: Apache II Risk Score from patient characteristics and biomarkers
  -Comor: Comorbidities
  -Invent: Invasive ventilation
  -Depend: Prior Dependency
  -Depriv: Deprivation Postcode

**Data Overview**
The mean time spent in critical care was 14.42 days, with the majority of patients being censored out rather than dying. Most patients were male with a BMI of 30.93. There were few patients with comorbidities, however over half needed ventilation and 10% had prior dependencies. Finally, the majority tended to be from a more deprived postcode and the average Apache score was 28.97.

This data has been used to produce a comprehensive survival analysis of patients entering critical care. The 2 Kaplan Meier Plots below show survival against time for the Critcare data. As you can see from the left-hand plot, the 30-day survival probability is 0.525, i.e., at 30 days there is a 52.5% chance of survival. The right-hand plot shows the 95% confidence interval, which for the 30-day survival probability is (0.478, 0.578). This can be interpreted as 95% of the time your chance of surviving 30 days in critical care is between 47.8% and 57.8%.



