**I focussed on simplicity over anything else.** 

 - My main idea was to exploit the text summary and use straight forward and simple NLP preprocessing technique. 
 - I performed some statistical feature scaling on the investment amount to also include it in the features for the model to learn. 
 - I figured out that Vendor_Code and GL_Code do not contribute much to the predictions and thus isolated them.
 - The rest was simple text preprocessing, model comparison and hyperparameter tuning to avoid overfitting. 
 - I used min-max scaling for one normalizing the investment amount.
 - I performed stemming because it is faster than lemmatization and relevant to the problem statement.
 - I finally decided to go with a simple deep Random Forest model due to its simplicity and robustness. 
 - I also performed five-fold cross-validation to evaluate the models.

**My Comments**

> Overall I enjoyed the contest. I completed the entire thing in less than 2 to 2.5 hours, in one go basically. I wanted to focus on simplicity and robustness. I hope I will be shortlisted for the next round. Cheers!

**Contact Me**

amitrajitbose9@gmail.com