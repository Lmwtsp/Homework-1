# Homework-1
![](RackMultipart20230527-1-qvo1r5_html_3a18facc6624cd24.png)

**Equipo 2**

Lucero Jannete López García A01736938

Daniela Piña Botello A01735524

Félix Sánchez Gómez A01737356

Diana Meneses Muñoz A01737237

**Collaborative activity: Mini case 1 - Linear programming**

**Decision Support Analysis (Gpo 351)**

**26/05/2023**

Link del caso: [https://github.com/HesusG/python-decision-making-support-analysis/blob/main/module\_1/Postwork1.md](https://github.com/HesusG/python-decision-making-support-analysis/blob/main/module_1/Postwork1.md)

1. **What are the two parameters that the LpProblem function implements?**

The LpProblem function contemplates 2 parameters, the first one is the name of the problem "The Whiskas Problem" which in programming is called a string being a datatype that's mainly used to represent text. The second one is either LpMinimize or LpMaximize, depending on the Lp type of problem we are trying to solve which in this case is LpMinimize. Then the parameters would be seen as followed:

prob= LpProblem ("The Whiskas Problem", LpMinimize)

1. **Is it mandatory to name the prob variable as prob?**

It is not mandatory to name the problem variable as prob, since a variable is just an identifying name that we assign to be able to save or retrieve a value, this can be texts, numbers or states as true or false.

1. **What are LpContinuous and LpInteger used for?**

LpContinuous is used mainly in linear programming. It is a type of variable that can take on any real value within a specified range, In contrast, LpInteger is also used in linear programming but can only take integer values as its name says. For example: the x1 = LpVariable ('x1', cat = LpInteger)

![](RackMultipart20230527-1-qvo1r5_html_91e2c6ff082e89d7.png)

1. **Explain and copy the section of code that defines the objective function.**![](RackMultipart20230527-1-qvo1r5_html_5cd21161fdff4a42.png)

There is a formula that is adding the price of both ingredients of the final product. It indicates the percentage that every ingredient of the can represents and when it's run you get the total cost for producing a can.

1. **Explain and copy the section of code that defines the constraints.**

![](RackMultipart20230527-1-qvo1r5_html_7456a3d030f0f25b.png)

In this part of our code we can view the constraints that are applied, talking about nutritional contents required in percentage to obtain the cat food like the original recipe says.

1. **Is this a minimization or maximization problem?**

A minimization problem because we are using the parameter LpMinimize, also because what we want is to know what ingredients must be dealt with to produce the number of cans of cat food; Another piece of information is to know the cost per can and thus know if our capacity is optimal to produce.

1. **Run the WhiskasModel1.py code. (no need to make changes, just runt it as is) What is the value of the following variables? Status: BeefPercent = ChickenPercent = Total Cost of Ingredients per can =**

**Whiskas 1**

![](RackMultipart20230527-1-qvo1r5_html_b3bb2215a8e81930.png)

- Status: Optimal
- BeefPercent = 66.0
- ChickenPercent = 34.0
- Total Cost of Ingredients per can = 0.97

1. **OPTIONAL - (5/100 Extra Points for Final Test) Write all your answers as a markdown document (.md) and upload it to your github account.**

[https://github.com/Lucero1110/Collaborative-activity-Mini-case-1---Linear-programming/blob/main/Homework1](https://github.com/Lucero1110/Collaborative-activity-Mini-case-1---Linear-programming/blob/main/Homework1)

**Executed programs:**

Whiskas 1:

[https://colab.research.google.com/drive/1Qidp037IU09MRZ5wgUDO536Qdwvv4vmy?usp=sharing](https://colab.research.google.com/drive/1Qidp037IU09MRZ5wgUDO536Qdwvv4vmy?usp=sharing)

Whiskas 2:

[https://colab.research.google.com/drive/1SbiOyetexUQV0kNlrLG7gnpDNyzOTyTf?usp=sharing](https://colab.research.google.com/drive/1SbiOyetexUQV0kNlrLG7gnpDNyzOTyTf?usp=sharing)
