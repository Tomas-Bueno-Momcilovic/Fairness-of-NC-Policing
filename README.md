Authors: Tomas Bueno dos Santos Momcilovic, Isaac Bravo, Fabiola Schwarz, Haoran Cheng, Zitong Wang
Date: 31.08.2021.

This is a replication package for the final group project in the (EI04017) Machine Intelligence and Society lecture at the Technical University of Munich.

The project includes Python code for determining the fairness of kNN and decision tree machine learning algorithms using the North Carolina policing dataset. Fairness is determined according to Barocas et al. (2019) metrics - independence, separation and sufficiency - and adjusting the thresholds of arrests based on group membership. This is meant to tweak the model towards being fairer according to the definition of (unconditional) demographic parity.

While being standalone, the project does not represent a complete approach, but an example of a solution that could be used to address unfair machine learning algorithms.

###### References ###### 

Work based on metrics from:
-Barocas, S., Hardt, M. & Narayanan, A. (2019). Fairness and Machine Learning [Pre-Published Version]. Retrieved on 20th August 2021 from https://fairmlbook.org
-E. Pierson, C. Simoiu, J. Overgoor, S. Corbett-Davies, D. Jenson, A. Shoemaker, V. Ramachandran, P. Barghouty, C. Phillips, R. Shroff, and S. Goel. “A large-scale analysis of racial disparities in police stops across the United States”. Nature Human Behaviour, Vol. 4, 2020.


Work based on following data sources:
-Stanford University. (n.d.). Open Policing Dataset. Retrieved on 20th August 2021 from https://openpolicing.stanford.edu/data/