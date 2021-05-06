# InstaNutri
**Macronutrient Estimator; Buyuan Lin; buruce.edu**

**Product Mission** <br />
Develop an App/API for calculating and tracking the nutrient and calories provided in each meal or dish of the user. Then, provide advice is needed.

**Goals** <br />
- Easy to use, ex. simply by taking one picture.
- Relative accurate: Use trained object detection model to ensure the accuracy.
- Health advices: Analyze the user’s diet. Makes suggestion if the user’s diet is lack of some the nutrient or the user’s diet is unhealthy.

**MVP & User Stories** <br />
- As a developer, I wish to spend minimum time training the model.
- As a user, I want to record and analyze my nutrient and calories intake of each dish.
- As a user, I wish there’s an application that can give me advice about my diet behavior and warn me if I’m eating unhealthily.
- As a user, I wish the described functionality can be done easily such as taking a photo of the I’m eating instead of manually enter all the ingredients.

**Technologies to evaluate** <br />
- Tensorflow, keras: Probably the most popular opensource machine learning right now. With exhaustive documentation and lots of existing projects.
- Tensorflow Lite: Compress the model so it can be deployed on mobile deveices such as cell phone.
- Python: The most wildly used language for machine learning.

**Functionalies** <br />
- Allow the user to take picture of food that they are having or use picture of foods they've had before.
- After Tensorflow mobile API returned the result, the app will ask the user to type in how many servings of that food that they are having.
- Then the application will return the nutrient information and store the data to the current date. So that the user can keep tracking their calorie intakes.


**Development Environment** <br />
Tensorflow; Python; keras; numpy; 

 
**Video link:** <br />
oneDrive link, please let me know if the link doesn't work. Uploading the video to google drive takes too much time: 
https://1drv.ms/v/s!AoOolAg_SGVagfYgkUFhrWiezJOXsA
