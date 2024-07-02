
Data Science Tools and Ecosystem
In this notebook , Data science Tools and Ecosystem are summarized.

Some of the popular languages that Data Scientists use are:

1.Python. 
2.R. 
3.SQL. 
4.Java. 
5.Julia. 
6.Scala. 
7.C/C++. 
8.JavaScript.

Some of the commonly used libraries used by Data Scientists include:

TensorFlow.
NumPy.
SciPy.
Pandas.
Matplotlib

Data Science Tools:

Data Science Tools SAS. It is one of those data science tools which are specifically designed for statistical operation Apache Spark BigML

# Arithmetic operations

code = compile("5 + 4", 

"<string>", "eval")
eval(code)
#result:9




import math
# Volume of a sphere
code2 = compile("4 / 3 * math.pi * math.pow(25, 3)", "<string>", "eval")
eval(code2)
#result:65449.84694978735

days = 0
hours = 0
mins = 0

time = 200
#days = time / 1440
leftover_minutes = time % 1440
hours = leftover_minutes / 60
#mins = time - (days*1440) - (hours*60)
print(str(days) + " days, " + str(hours) + " hours, " + str(mins) +  " mins. ")
#result:0 days, 3.3333333333333335 hours, 0 mins.

objectives:
Below the introduction cell created in Exercise 3, insert a new markdown cell to list the objectives that this notebook covered (i.e. some of the key takeaways from the course). In this new cell start with an introductory line titled: Objectives: in bold font. Then using an unordered list (bullets) indicate 3 to 5 items covered in this notebook, such as List popular languages for Data Science.

Author:
Ambati Mokesh Reddy

