# Stochastic-Modeling-and-Discrete-Event-Simulation-of-an-Emergency-Department-ED-

![image](https://user-images.githubusercontent.com/54616551/234515917-fe929092-5666-45b8-bece-3f5ab2a73885.png)

Abstract

Background: In recent times, there has been an increase in the amount of waiting time patient experience in an emergency department (ED). In addition, crowded situations and inefficient resource utilization in the EDs have led to prolonged patient service time and poor patient satisfaction on national surveys. Nonetheless, in this project we attempted to model the ED system and replicate multiple scenarios that will aid the optimization of the ED service through efficient resource utilization, solve overcrowding problem, and reduce average waiting and service time in the ED.

---

Model Methodology: While we could not precisely validate the model accuracy, simulation would inform us about the behavior and normal operating conditions of the system as simulation experiments are designed with the intent to model a real system scenario that enhances the capability of the end-users and managers to evaluate various strategies and decisions. Hence, it’s always important to validate the model by comparing it with actual system behavior. However, in this project’s case, predetermined ED conditions from a sample case were subjected to a dynamic modeling technique that involved a system’s stochastic behavior. To run the analysis, Discrete event simulation modeling with the assumption of a uniform distribution of the population was executed with the aid of R-programming software. After initial results were obtained, suggestions by adding additional resources to the model were implemented to analyze the impact of the change between the 2 systems. 

---

Results: After executing both models for a runtime of 1440mins (24hrs) with 20 replications, there were significant differences in the results, the average waiting time for system 1 (Normal sample conditions) was “22.4372” mins, while after adding additional resource in system2 the average waiting time was “1.128757” mins. Also, in system 1, 85 % resource utilization was when compared with system 2 which was 58% utilization. The queue size reduced from 8 patients in system 1 to less than 2 patients in system 2 except on few occasions when it was 3 during the early hours of run time.

---

Conclusion: In conclusion, employing additional doctor resources in system 2 appeared to be a better option, however most managers of the Eds are usually constrained on hiring additional resources. Practical solutions might be to recreate the model environment with a different simulation technique more focused on the resources – Agent Based Simulation Model (ABM) which is designed to find ways to optimize resources in the ED or system. 
