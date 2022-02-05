# HEART-DISEASE-PREDICTION-
 I have used Machine Learning approach for classifying whether a person is suffering from heart disease or not.


### EXPLORATORY DATA ANALYSIS (EDA)

##### 1.

![image](https://user-images.githubusercontent.com/75883328/152658173-61353a63-2813-4efe-a35e-aab36938089e.png)


Here, “1” is the number of people suffering from heart disease and “0” is the number of people who are not suffering from heart disease.
Hence the number of people suffering from heart disease is “165” and the number of people not suffering from heart disease is “138”.

Clearly, from this, we can assume that this is a classification problem with target variables having values “0” and “1”.




##### 2.
![image](https://user-images.githubusercontent.com/75883328/152658326-a9bd04b7-384c-4c52-a922-7d11d9b19a71.png)


Here, by this count plot, we can see that number of females is less as compared to the number of males.



##### 3.

![image](https://user-images.githubusercontent.com/75883328/152658396-5934a20d-409a-4650-9c97-2374b02d90b0.png)


From the above barplot, we can easily see that the proportion of females suffering from heart disease is more than that of males.



##### 4.
![image](https://user-images.githubusercontent.com/75883328/152658434-8ddae106-ee01-4246-83a7-bf3b7f956979.png)

Here type “0” is for typical anginal, type “1” is for atypical anginal, type “3” is for non-anginal, and type “4” is for asymptotic.
Here, by this count plot, we can see that most of the patients have typical anginal chest pain whereas very few patients suffer from an asymptotic type of chest pain.



##### 5.
![image](https://user-images.githubusercontent.com/75883328/152658464-8c2cb7c4-93ea-42f4-b844-8be34f48eb78.png)


From the above barplot, we can easily see that people having typical anginal pain are much less likely to have heart problems as compared to the rest of the three.



##### 6.
![image](https://user-images.githubusercontent.com/75883328/152658518-c4b1f2ac-e6a0-4edd-97db-eb71af40cc64.png)


Here we see people having fbs >120mg/dl i.e. “0” is very high as compared to people who are having fbs<120 mg/dl.




##### 7.
![image](https://user-images.githubusercontent.com/75883328/152658554-70761d65-4fd9-4d8f-befe-767fddcb99fe.png)


From the above barplot, we can clearly see that fbs does not have much effect on heart problem.



##### 8.
![image](https://user-images.githubusercontent.com/75883328/152658578-0bb51424-c1c3-4f2b-8b93-3ed7b836b30c.png)


Here we can clearly see people having type “0” and type “1” is almost the same whereas people having type “2” is extremely low as compared to type “0” and type “1”.



##### 9.
![image](https://user-images.githubusercontent.com/75883328/152658598-9db16d77-5622-4576-9c21-39e8db582b7e.png)


From the above barplot, we can easily see that people having type “2” are much less likely to have heart problems as compared to type “0” and type “1”.



##### 10.
![image](https://user-images.githubusercontent.com/75883328/152658613-f3a8e44e-94c8-4bbb-9c77-44f0a6b7ab66.png)


Here we can clearly see people having type “0” is more than type “1”.



##### 11.
![image](https://user-images.githubusercontent.com/75883328/152658639-9e1050c3-26b9-4a89-a6b2-ec26166b75b6.png)


From the above barplot, we can easily see that people having type “1” are much less likely to have heart problems as compared to type “0”.



##### 12.
![image](https://user-images.githubusercontent.com/75883328/152658677-f6f2a57e-73de-4404-bbb3-f1b841548a9b.png)


Here we can clearly see people having slope “1” and slope “2” is much more than slope “0”.



##### 13.
![image](https://user-images.githubusercontent.com/75883328/152658698-87c94979-77f2-4eec-90d9-27a05125fd52.png)


From the above barplot, we can easily see that people having slope “2” have much more heart problems as compared to slope “0” and slope “1”.



##### 14.
![image](https://user-images.githubusercontent.com/75883328/152658726-1d24b09b-7437-4e62-84b1-d594edf2e561.png)


From the above countplot we can see that people having ca=0 are extremely high in number as compared to the rest of the ca’s.



##### 15.
![image](https://user-images.githubusercontent.com/75883328/152658745-ed714127-45f8-404a-be41-693de6fc9be0.png)


Here we see that people having ca=4 have a very high number of heart problems. As compared to the rest of the people.



##### 16.
![image](https://user-images.githubusercontent.com/75883328/152658755-528bccca-2788-40dd-b34e-7fd9bbaecbeb.png)


From the above count plot, we can see that people having thal as type “2” is very as compared to the rest of the group.



##### 17.
![image](https://user-images.githubusercontent.com/75883328/152658768-bb082b1f-f51d-451d-b1b9-e9771ac8e9e5.png)


From the above barplot, we can clearly see that type “0” has a high chance of having a heart problem.



##### 18.
![image](https://user-images.githubusercontent.com/75883328/152658833-dfca6b60-aa20-489b-9163-cfbc0ae653ec.png)

From the above plot , we can clearly see the following things:-


   1. cp (Chest Pain) : People with cp equl to 1, 2, 3 are more likely to have heart disease than people with cp equal to 0.


   2. restecg (resting electrocardiographic results): People with value 1 (signals non-normal heart beat, can range from mild symptoms to severe problems) are more likely to        have heart disease.


   3. exang (exercise induced angina) : People with value 0 (No ==> exercice induced angina) have heart disease more than people with value 1 (Yes ==> exercice induced angina)


   4. slope (the slope of the peak exercise ST segment) : People with slope value equal to 2 (Downslopins: signs of unhealthy heart) are more likely to have heart disease than      people with slope value equal to 0 (Upsloping: better heart rate with excercise) or 1 (Flatsloping: minimal change (typical healthy heart)).


   5. ca (number of major vessels (0-3) colored by flourosopy) : the more blood movement the better so people with ca equal to 0 are more likely to have heart disease.


   6. thal (thalium stress result) : People with thal value equal to 2 (fixed defect: used to be defect but ok now) are more likely to have heart disease.




##### 19.
![image](https://user-images.githubusercontent.com/75883328/152658929-0c339188-1222-43bf-a788-f5a6c500ab00.png)


From the above plot , we can clearly see the following thing:-


   1. trestbps : resting blood pressure (in mm Hg on admission to the hospital) anything above 130-140 is typically cause for concern


   2. chol (serum cholestoral in mg/dl) : above 200 is cause for concern.


   3. thalach (maximum heart rate achieved) : People how acheived a maximum more than 140 are more likely to have heart disease.


   4. oldpeak ST depression induced by exercise relative to rest looks at stress of heart during excercise unhealthy heart will stress more.



##### 20.
![image](https://user-images.githubusercontent.com/75883328/152658969-c2cd7c4b-1ac3-4ec8-b95e-411f46e49a36.png)


The above is a scatter plot between Age and Max Heart Rate for Heart Disease.






