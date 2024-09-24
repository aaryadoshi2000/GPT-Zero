

We have created an app called GPT ZERO

A Flask app with PostgreSQL, using a scikit-learn model to identify AI vs. human text.
Published in: ICAT (https://proceedings.icatsconf.org/conf/index.php/ICAT/article/view/36/21), showcasing skills in web development and machine learning.


Steps to run app on EC2:

1. Create an instance 
2. Clone the repository from : "https://github.com/aaryadoshi2000/GPT-Zero.git"
3. Install all the required packages 
4. Run it by : "python3.7 final.py"

Steps to run app locally: 

1. uncomment the code in final.py "app.run(host="localhost",port="8000")" and comment the one with host value "0.0.0.0" in it
2. uncomment the code in routes.py "vectorizer=..." and comment the one already in use.
3. Run it by: "python3 final.py" 