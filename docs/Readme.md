# Regional Equity Model

The Regional Equity model is a demonstration system dynamics model illustrating the difference between equality and equity based approaches to reduce health inequities.

# Overview

The model (shown below) represents the social determinants of health ( $SDOH$ ) for each census tract in the county as the Health Equity Index (HEI) with initial values from 2021 provided by [HealthyNeo](https://www.healthyneo.org/indexsuite/index/healthequity). The loop B1 allocates the total resources to reduce SDOH for each tract, which is distirbuted based on the selected policy (status quote, equality, or equity). 

<img src="https://user-images.githubusercontent.com/8854922/189573496-d90e6c42-9d6d-46d6-a431-9e0a43925c3f.png" width="50%">

# Policies

The model simulates three different types of policies for allocating resources to reducing health inequities: 

* Status quo: no investments are made.
* Equality: the total resources are distributed equally across census tracts.
* Equity: the total resources are distributed based on need with census tracts with greater need receiving a greater allocation of resources. 

# Simulate Policies

Click on the buttons in the simulation interface below to run the policy from 2021 to 2031. 

<iframe src="https://exchange.iseesystems.com/public/psh/hei-demo/index.html#page1" width="1066px" height="600px"></iframe>
