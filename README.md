# Probabilities-and-Statistics-Project

## Project Summary

I actively participated in the development of two probability and statistics case studies, collaborating with a teammate on the first one.
The first case study is related to a multi-stage activity having a probability of moving on to a next stage, which varies and therefore it determines simulated values, meaning that there will be a forecast of the behavior over time (associated with a continuous discrete variable with the mass function equal to the exponential one) related to the completion of all the stages of this activity.
The second describes the mass functions of random variables, and based on established samples, the corresponding estimators are determined using the method of moments and that of maximum likelihood.

# Project Content

- An activity with n stages, a probability of transitioning from stage i to i + 1 of alpha_i.  
The time spent at a stage is associated with a continuous random variable T_i with a mass function equal to the exponential function of rate lambda_i. T is the total time for the completed stages.  
10^6 simulations are performed, and the behavior of the mean E(T), the probability P(completion_n_stages) of completing the activity, the probability P(completion_n_stages_<=_sigma) of completing the activity in a time less than or equal to sigma, the minimum and maximum completion time of the activity from the 10^6 simulations, and the probabilities P(stop_before_stage_k) of stopping before a stage k where k takes all values from 1 to n are observed. For each of these subproblems, where possible, the values are both simulated and obtained through direct calculation, with the proofs of these calculations provided in the documentation.  
- A Shiny application in which distribution functions of given random variables are graphically represented, and the calculation of means and variances for random variables defined by functions with customizable parameters is performed.  
- The method of moments (illustrated only through calculation) and the maximum likelihood method (illustrated through calculation and in code) for the given mass functions of random variables and samples established in the requirement, comparing the estimator theta obtained through both methods.

# Continut proiect

- Activitate cu n etape, o probabilitate de a trece de la etapa i la i + 1 de alfa_i.
Timpul petrecut la o etapa e asociat unei variabile aleatoare continue T_i cu functia de masa
egala cu cea exponentiala de rata lambda_i. T este timpul total pentru etapele parcurse.
Sunt facute 10^6 simulari si se observa comportamentul mediei E(T), probabilitatii P(finalizare_n_etape)
de a finaliza activitatea, probabilitatea P(finalizare_n_etape_<=_sigma) de a finaliza activitatea intr-un
timp mai mic sau egal cu sigma, timpul minim si maxim de terminare a activitatii din cele 10^6 simulari si
probabilitatile P(oprire_inainte_etapa_k) de oprire inainte de o etapa k unde k va lua toate valorile de la 1
la n. La fiecare dintre aceste subprobleme, acolo unde s-a putut, valorile sunt atat simulate, cat si obtinute
prin calcul direct, demonstratiile acestor calcule fiind in documentatie.
- Aplicatie Shiny in care s-au reprezentat grafic niste functii de repartitie ale unor variabile aleatoare date
si calculul unor medii si variante pentru variabile aleatore definite de functii cu parametri particularizabili
- Metoda momentelor (ilustrata doar prin calcul) si cea a verosimilitatii maxime (ilustrata prin calcul si in cod)
pentru functiile de masa date ale unor variabile aleatoare si esantioane stabilite in cerinta, comparand estimatorul
teta obtinut prin ambele metode.
