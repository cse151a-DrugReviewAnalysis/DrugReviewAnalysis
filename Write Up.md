**We will replace the README with this once it is complete, and move the contents of the current README into another file**

Introduction of your project. Why chosen? why is it cool? General/Broader impact of having a good predictive mode. i.e. why is this important?
> 

Figures (of your choosing to help with the narration of your story) with legends (similar to a scientific paper) For reference you search machine learning and your model in google scholar for reference examples.
> 

Methods section (this section will include the exploration results, preprocessing steps, models chosen in the order they were executed. Parameters chosen. Please make sub-sections for every step. i.e Data Exploration, Preprocessing, Model 1, Model 2, Model 3, (note models can be the same i.e. CNN but different versions of it if they are distinct enough). You can put links here to notebooks and/or code blocks using three ` in markup for displaying code. so it would look like this: ``` MY CODE BLOCK ```
* Note: A methods section does not include any why. the reason why will be in the discussion section. This is just a summary of your methods
> #### Data Exploration
> * 
> #### Preprocessing
> * 
> #### Model 1 - Decision Tree Regressor
> * 
> #### Model 1.1 - Linear Regression
> * 
> #### Model 2 - ...
> * 
> #### Model 3 - Neural Network Regressor using BERT word embeddings
> * The model built upon a pre-trained Bidirectional Encoder Representation from Transformers (BERT) classification model from Hugging Face `transformers` package, which includes various high-quality natural language processing models. We fine-tuned the pre-existing BERT classification model on our training data and restricted the output so that it only predicts a single value rather than attempting to classify our `processed_reviews` for the inputs. Additionally, we used a non-lemmatized version of our processed reviews for the dataset and kept the stop-words. Then, the dataset for testing was split into validation and test sets, so that the split between training, validation, and testing would be $75-10-15$.

Results section. This will include the results from the methods listed above (C). You will have figures here about your results as well.
* No exploration of results is done here. This is mainly just a summary of your results. The sub-sections will be the same as the sections in your methods section.
* > #### Data Exploration
> * 
> #### Preprocessing
> * 
> #### Model 1 - Decision Tree Regressor
> * 
> #### Model 1.1 - Linear Regression
> * 
> #### Model 2 - ...
> * 
> #### Model 3 - Neural Network Regressor using BERT word embeddings
> * 

Discussion section: This is where you will discuss the why, and your interpretation and your though process from beginning to end. This will mimic the sections you have created in your methods section as well as new sections you feel you need to create. You can also discuss how believable your results are at each step. You can discuss any short comings. It's ok to criticize as this shows your intellectual merit, as to how you are thinking about things scientifically and how you are able to correctly scrutinize things and find short comings. In science we never really find the perfect solution, especially since we know something will probably come up int he future (i.e. donkeys) and mess everything up. If you do it's probably a unicorn or the data and model you chose are just perfect for each other!
> #### Data Exploration
> * 
> #### Preprocessing
> * 
> #### Model 1 - Decision Tree Regressor
> * 
> #### Model 1.1 - Linear Regression
> * 
> #### Model 2 - ...
> * 
> #### Model 3 - Neural Network Regressor using BERT word embeddings
> * 

Conclusion section: This is where you do a mind dump on your opinions and possible future directions. Basically what you wish you could have done differently. Here you close with final thoughts
> *...reflection of work...*
> * Given the prevalence of BERT in discussions of natural language processing tasks, it may be fruitful if we continued the direction we took for our final model. For example, if we had more time, we could have tried to better integrate BERT into a model of our chosing rather than focusing on fine-tuning the BERT model as we have done in model 3. However, due to a lack of experience from the members of the group with regards to using the relevant packages/frameworks, we did not have enough time to fully explore all our possibilities and truly find the most optimal structrue for our model.
> * Another interesting possibility would be to try and use gradient boosting and random forests to continue our work with the decision tree regressor we tried in our first milestone. The professor mentioned in his lectures that such approaches showed optimal results prior to the surge of progress made in the field of neural networks. Even if it ultimately proved to be lacking compared to other potential models, the process of experimentation can be fruitful all the same.

Collaboration section: This is a statement of contribution by each member. This will be taken into consideration when making the final grade for each member in the group. Did you work as a team? was there a team leader? project manager? coding? writer? etc. Please be truthful about this as this will determine individual grades in participation. There is no job that is better than the other. If you did no code but did the entire write up and gave feedback during the steps and collaborated then you would still get full credit. If you only coded but gave feedback on the write up and other things, then you still get full credit. If you managed everyone and the deadlines and setup meetings and communicated with teaching staff only then you get full credit. Every role is important as long as you collaborated and were integral to the completion of the project. If the person did nothing. they risk getting a big fat 0. Just like in any job, if you did nothing, you have the risk of getting fired. Teamwork is one of the most important qualities in industry and academia!!!
* Start with Name: Title: Contribution. If the person contributed nothing then just put in writing: Did not participate in the project.

> Kenneth Chuang - **Title**:
> * **Contribution**
>
> Steven Liu - **Title**:
> * **Contribution**
>
> Wesley Hu - **Title**:
> * **Contribution**
>
> Hantian Lin - **Title**:
> * **Contribution**
>
> Niharika Malhotra - **Title**:
> * **Contribution**
>
> Neal Parimoo - **Title**:
> * **Contribution**
>
> Madhav Bansal - **Title**:
> * **Contribution**
>
> Zhirui Xia - **Title**:
> * **Contribution**
>
> Safia Mahamed - **Title**:
> * **Contribution**
>
> Zixuan Chen - **Title**:
> * **Contribution**