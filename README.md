# Dermatology-ML-Project
 Aim is to determine the type of Eryhemato-Squamous Disease.
 
The differential diagnosis of erythemato-squamous diseases is a real problem in dermatology. They all share the clinical features of erythema and scaling, with very little differences. 

The diseases in this group are psoriasis, seboreic dermatitis, lichen planus, pityriasis rosea, cronic dermatitis, and pityriasis rubra pilaris.

Used Popular algorithms that can be used for multi-class classification include: k-Nearest Neighbors.Decision Trees.Naive Bayes.Random Forest.Gradient Boosting. Diseases are classified as belonging to one among a range of known classes (psoriasis, seboreic dermatitis, lichen planus, pityriasis rosea, cronic dermatitis, and pityriasis rubra pilaris).

#### The Final Project file is [Engineered.ipynb](https://github.com/arvindkr7/Dermatology-ML-Project/blob/main/Engineered.ipynb)


### Since, the purpose of this project is for comparsion study.
+ Other two files, namely project.ipynb, main.ipynb and Engineered.ipynb have been also producing results and they are intended for Analysis purpose.
+ Project.ipynb is neither standardised nor feature engineered with accuracy of 84% and 11 misclassification.
+ Main.ipynb has been standardaised with 90% accuracy and 4 misclassification.
+ Finally, Engineered.ipynb has been standardised, feature engineering, feature selection processed giving 98% accuracy.

> Results & Visualization
+ in Graphs directory

### Database Information
+ This database contains 34 attributes, 33 of which are linear valued and one of them is nominal. 
+ In the dataset constructed for this domain, the family history feature has the value 1 if any of these diseases has been observed in the family, and 0 otherwise.
+ The age feature simply represents the age of the patient. Every other feature (clinical and histopathological) was given a degree in the range of 0 to 3. 
+ Here, 0 indicates that the feature was not present, 3 indicates the largest amount possible, and 1, 2 indicate the relative intermediate values. 

#### Attribute Information:

> Clinical Attributes: (take values 0, 1, 2, 3, unless otherwise indicated)

1. erythema
2. scaling
3. definite borders
4. itching
5. koebner phenomenon
6. polygonal papules
7. follicular papules
8. oral mucosal involvement
9. knee and elbow involvement
10. scalp involvement
11. family history, (0 or 1)
34. Age (linear)

> Histopathological Attributes: (take values 0, 1, 2, 3)

12. melanin incontinence
13. eosinophils in the infiltrate
14. PNL infiltrate
15. fibrosis of the papillary dermis
16. exocytosis
17. acanthosis
18. hyperkeratosis
19. parakeratosis
20. clubbing of the rete ridges
21. elongation of the rete ridges
22. thinning of the suprapapillary epidermis
23. spongiform pustule
24. munro microabcess
25. focal hypergranulosis
26. disappearance of the granular layer
27. vacuolisation and damage of basal layer
28. spongiosis
29. saw-tooth appearance of retes
30. follicular horn plug
31. perifollicular parakeratosis
32. inflammatory monoluclear inflitrate
33. band-like infiltrate


###  ML Model exported 
+ dtc.pkl
+ ready for predicting result
+ deploy on any website or App
