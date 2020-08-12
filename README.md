# Can mentalizing interacting shapes lead to empathy in humans?

This project was worked on during Neuromatch Academy (NMA), 2020.  We were mentored by Dr. Marlene Cohen and Dr. Laura Mikula.
Here is the [link](https://www.youtube.com/watch?v=ZSeQvp-rpTE) to our presentation.

## What did we study?
1. Do people empathize with socially interacting shapes?  
2. Which networks in the brain are associated with empathy?
3. Is there any kind of correlation among the regions involved in social cognition which leads to empathy? 
4. Is absence of a task or experimental stimuli (i.e resting state), good control for such tasks? 

## Brief scientific background 
The perceptions of the participants can be directly attributed to the ability to reflect on the emotional and instinctive responses in others often referred to as ‘mentalizing’. However, one concept that goes hand in hand with mentalizing is empathy. 

## Method and Analysis
### Dataset Used: 
We used the The Human Connectome Project dataset. In the Social Cognition aspect of the Human Connectome Project dataset, the dataset consists of observations for 339      participants (called subjects). For each subject, BOLD signals are collected for resting state and active state. BOLD signals are observed due to the difference in magnetic properties of oxygenated and deoxygenated blood, which is captured by the MRI machine. 

In the task based fMRI, the data was collected through two runs. In each run, 5 videos with mental and random interaction each of 23 seconds were shown to subjects with a fixation time of 15s between successive videos, and the response for each video from the participant was recorded. Each run had either 2 videos with mental interaction and 3 videos with random interaction or 3 videos with mental interaction and 2 videos with random interactions. The response from participants recorded belonged to one of the three categories: Mental Interaction, Random Movement, and Not sure.

### Analysis 1: Subtraction Analysis 
- Each comparision contains analysis of three aspects:
  - Contrasts in Parcels for both hemispheres
  - Contrasts in network activations for both hemispheres
  - Visualizing contrasts of activitations in parcels
  
- 4 different comparisons <br/>
This is the nomenclature that we follow for response of participants and condition of videos:<br/>
![Nomenclature](images/nomen.PNG?raw=true "Nomenclature")
  - A. Mental and Random Classes of Videos
  
  ![Case A](images/A.PNG?raw=true "Case A")
  
  - B. Resp_M-M and Resp_R-R
  
  ![Case B](images/B.PNG?raw=true "Case B")
  
  - C. Resp_M-M and Resting State
  
  ![Case C](images/C.PNG?raw=true "Case C")
  
  - D. Resp_M-M and Res_R-M
  
  ![Case D](images/D.PNG?raw=true "Case D")
  
  
### Analysis 2: Correlation Analysis for Functional Connectivity
![FC](images/fc.PNG?raw=true "Functional Connectivity Analysis")

## Conclusion
We observed:
1. Correlations between temporal-parietal-occipital junction, auditory association region, lateral temporal region, and medial-prefrontal cortex, manifesting the underlying connectivity of social cognition.

2. More clear contrast when the true random was considered as control as compared to the resting state condition.

3. Subtraction analysis yielded better results when the participant responses were considered as compared to when only condition-based analysis is performed.

4. The subtraction analysis between the perceived mental and random interactions for the mental condition resulted in relatively high contrast in a region close to the posterior superior temporal sulcus. This is the same region found to be less active for the people having Autism.

It was an amazing experience from figuring out the research question, to diving into the dataset, reframing the hypothesis as and when we gain new insights and performing the analysis.

But, without constant support from NMA, whether it’s TA’s helping hand, Mentors’ guidance or the dataset updates and prompt responses from the Neurostars community, this project and tutorials wouldn’t have possible.

Regards,
Varad Srivastava, Minaxi Goel, Suraj Joshi, Sanil Shrestha
