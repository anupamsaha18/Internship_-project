# FIFA WORLD CUP ANALYSIS
Table of contents
•	Overview
•	Project Goal
•	Technical Aspects
•	Installation
•	Used Technologies
•	Appendix
•	FAQ
•	Author
Overview
The FIFA World Cup, often simply called the World Cup, is an international association football competition contested by the senior men's national teams of the members of the Fédération Internationale de Football Association (FIFA), the sport's global governing body. The championship has been awarded every four years since the inaugural tournament in 1930, except in 1942 and 1946 when it was not held because of the Second World War. The current champion is Germany, which won its fourth title at the 2014 tournament in Brazil.
Project Goal
This complete project is made as a part of Data Science Internship at iNeuron.ai.
Technical Aspects
The whole project has been divided into three parts. These are listed as follows :
• 𝐃𝐚𝐭𝐚 𝐏𝐫𝐞𝐩𝐚𝐫𝐚𝐭𝐢𝐨𝐧 : The Data is prepared in Python as well as Power BI And Data Cleaning , EDA and Visualization is done.
• Data Visualization: The processed data is Accessed using various graphs and plots like Bar, Hist, And pie charts and used to find the insights
• Dashboards : It is used to find the following insights:-
	Most Number of World Cup Winning Title
	Number of Goal Per Country
	Attendance, Number of Teams, Goals, and Matches per Cup
	Goals Per Team Per World Cup
	Matches With Highest Number Of Attendance
	Stadium with Highest Average Attendance
	Which countries had won the cup ?
	Number of goal per country
	Match outcome by home and away teams

Installation
The Code is written in Python 3.8.8. If you don't have Python installed you can find it here. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:
pip install -r requirements.txt
Run on your Local Machine :
python server.py
This will start the run the server.py which will also trigger code for server_app.py because of the use of asynchronous execution (threading) and will connect our ML model to Anvil application UI and will keep the server running till the web page rendered by flask application gets closed but to keep the server running forever, we used the heroku cloud to run our server continuously.







Used Technologies
    
Appendix
Link for video regarding to the explanation of the project :
https://drive.google.com/file/d/1PkUzDJSgya7YWwuW7OVA7Rc0CnZ9oEJ5/view
Link for App Documentation :
https://github.com/mahammadodj/iNeuron-Internship-Project/tree/master/Documents
FAQ
What is the source of data?
Dataset link : https://drive.google.com/drive/folders/12oHYj0qH2uZD8I13cVDiymTNDYldeJRa?usp=sharing
What techniques were you using for data pre-processing?
•	Removing unwanted attributes
•	Visualizing relation of independent variables with each other and output variables
•	Checking and changing Distribution of continuous values
•	Removing outliers
•	Cleaning data and imputing if null values are present.
•	Converting categorical data into numeric values.
•	Scaling the data
.
Author
Anupam Saha

