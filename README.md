# Predicting Emergency Hospital Admissions from Football Injuries: A Machine Learning Approach

## Introduction

Every sport comes with its risks, and football is no exception — it's actually one of the most injury-prone recreational activities, with many players ending up in the Emergency Room (ER). In the fast-paced world of the Emergency Department (ED), one of the key challenges is quickly figuring out which patients need to be admitted to the hospital. This is where Machine Learning (ML) can really make a difference by helping doctors make those tough calls more accurately.

In this project, we set out to build ML models that could assist healthcare professionals in the ED, specifically focusing on football-related injuries. Our goal is to improve the decision-making process so that the right patients get admitted when they need to be, ultimately enhancing the quality of emergency care. We will start by selecting a simple model and then leverage PyCaret to experiment with a variety of algorithms. This approach will streamline the process and help us quickly identify the best model for achieving our objectives.

## Data

The dataset for this study was sourced from the National Electronic Injury Surveillance System (NEISS), which is a nationally representative sample of hospitals across the United States and its territories. NEISS collects patient information from each participating hospital for every emergency visit involving an injury related to consumer products. The injury data is compiled from the ED of approximately 100 hospitals, selected as a probability sample from over 5,000 U.S. hospitals.

For this project, we focused on data related to emergency room visits for football - related injuries (code: 1211) over the past five years (2019 to 2023). The dataset includes various features such as age, race, gender, location of the injury, body part affected, preliminary diagnoses from triage, and the size of the care center. Our goal is to use this information to predict whether an individual will be admitted to the hospital.
