**PROJECT TITLE:  ANIMAL SURVIVAL**

**PROJECT DESCRIPTION**

**Brief overview of what the project does.**


This model predicts the likelihood that an animal brought into the shelter will die or survive before leaving the facility, using intake-related information available at the time of arrival.

**The problem it solves or the purpose it serves.**


- I used logistic regression and the model serves as a decision-making tool for animal shelter operators, adopters, the owners of the animals, veterinarians, and policy makers to  identify at risk animals early and improve welfare outcomes. 
- The model predicts whether an animal will be dead or not at the end of its stay at the shelter.
- This is a binary classification with 0 if its not dead and 1 if its dead. It helps come up with a probability score and a categorical label which allows end users to have a preliminary assessment to in turn assist them in prioritizing resources and high risk cases.
- This model is particularly useful for spotting vulnerable animals such as the very young, the injured, or those surrendered under poor conditions and intervening as early as possible.

**DATASET SOURCE**


GitHub Dataset: Long beach Animal shelter

Entries: 3,896 entries


**Model Performance**


Final model: Random Forest


Accuracy on test set: ~88%


**ACKNOWLEDGEMENTS**


This project would not have been possible without the invaluable support of:
- Professor GT, for providing expert guidance and reviewing the project structure.
- My family and friends, for their patience and encouragement throughout this journey.

  
**PREDICTORS**


1) animal_type: Species name of the animal. 


2) sex factor: Altered Sex of the animal. 


3) dob date: Date of Birth 


4) intake_date: Date on which Animal was brought to the shelter . 


5) intake_condition: Condition of animal at intake. 


6) intake_type: The reason for intake such as stray capture, wildlife captures, adopted but returned, owner surrendered etc.


7) reason_for_intake: The reason an owner surrendered their animal. 


8) outcome_date: Exit or Outcome date such as date of adoption or date animal died.


9) jurisdiction: Geographical jurisdiction of where an animal originated.

**WHO CAN USE THIS:**

1) Animal Shelter Staff and Management.To identify animals at high risk of death upon intake, so they can prioritize medical care, behavioral support, or fast-track adoption efforts.
2) Veterinary Teams. To flag incoming animals that may require immediate or intensive care.
3) Animal Welfare Organizations. To design targeted intervention programs, improve rescue prioritization, or advocate for policy changes.
4) Shelter Operations Analysts / Data Analysts. To continuously monitor trends, evaluate shelter performance, and improve shelter processes based on predictive risk profiles.
5) Local Government / City Officials. To make funding, policy, and operational decisions related to animal sheltering and public health.
6) Potential Collaborators or Rescuers. To select animals for rescue partnerships or medical interventions based on urgency.
