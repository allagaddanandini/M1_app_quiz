# TEST PLAN
## High Level Test Plan
|HLR_ID| Description|expected i/p|expected o/p|actula o/p|Test type|
|:----------|:-------------|:-------------:|:---------:|:---------------:|:-------:|
 |HLR_1|Entering the quiz|S|S|Pass|Requirement|
 |HLR_2|Participates in quiz|1|1|Pass|Requirement|
 |HLR_3|QUIZ Result|

## Low level Test plan
|LLR_ID| Description|Expected i/p|Expected o/p|Actual o/p|Test type|
|:---------|:---------------------------------|:----------------------:|:-----------------:|:------------------:|:-------------:|
|LLR_1_HLR_1|Participants give y to enter n to exit in char type. |	
|LLR_2_HLR_1|Show "Give proper response", when give other than y (or) n. |	
|LLR_3_HLR_1|Continue quiz if y given, exit when n is given.|	
|LLR_1_HLR_2|Show preview of quiz to the participants.|	
|LLR_2_HLR_2|Enter name to participates in quiz in char string type.|	
|LLR_3_HLR_2|Provide question with options by entering into new functions question1.|	
|LLR_4_HLR_2|Participares have to choice one choice in th given choices.|	
|LLR_5_HLR_2|Show "Give proper response", when give other than given choices|	


| Test_Id  |   Description  |  Expected I/O | Expected O/P  | Actual O/P|Test type|
| -------- |   --------------   |  -------------- | ---------------      | ------------- | -------------|
| LP01     |   User View all the rules of the game     |  Character Y    | View Rules and Exits | Pass  | Requirement |
| LP02     |   user has an option to exit  |  Character N    | Exits     | Pass          | Requirement |
| LP03     |   User Can View the score                 |  Character Y    | Open Results   | Pass | Requirement |


