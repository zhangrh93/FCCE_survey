# FCCE_survey

All survey phase samples, test images, and explanations are included.

## Survey Process
The survey can be divided into three parts: training (P1), testing (P2), and quality test (P3).
All parts with unique display are shown with random samples from different groups.

At the training part P1, participants are firstly shown with ***Train.png*** to get familar with the tasks.
Then, they need to complete the catch trial in ***Train_catch_train.png***. 

For testing part P2, all participants need to complete 4 pages of tasks with 4 images in each page.
***Test.png***, ***ACE_Test.png***, and ***CVE_Test.png*** are the samples with different class pairs. 
ICE and FCCE shares the same descriptions of the explanations. ACE and CVE are slightly different to fit the explanations.

At last, they need to complete the quality test in ***Testq.png***. 

## Explanations in Different Groups

All participants are divided into 10 groups. 
ACE, CVE, ICE, and FCCE. ICE and FCCE have 4 different versions (w/wo local explanations and feature text descriptions).
All these explanations can be found in CUB and CUB_CVE folder.

106_107, 142_143, 153_154, 59_63 are used for test pages. The remaining class pairs are used for training and catch trial. Note that CVE use a different class pair for catch trial as it is not concept-based explanations. It cannot provide explainers with wrong concept features. The mistakes of CVE explainers in catch trial is that it can not classify obviously wrong images. All groups have similar pass rates for catch trails. Catch trials are easy. Participants who understand the task should be able to figure out the mistakes of the explainers and pass the catch trials.

For each methods and class pairs, ***glo*** folder contains global explanations, ***loc*** contains local explanations (if available). ***wt*** in the file name refer to explanations with feature text descriptions. 

For samples of test phases, we simply change the explanation images and class names to create different survey pages.
