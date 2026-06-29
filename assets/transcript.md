# P1

Good morning. I am Yufa You from The Hong Kong Polytechnic University.

Today, I will present our paper, "Physical Human--Robot Interaction: A Review from the Guide Robot Perspective."

# P2

My presentation have three parts: the motivation, the three-stage review, and finally discuss the diagnosis and future directions.

# P3

First, I would like to explain the motivation for this review.

The first question is: why should we choose HRI, and especially physical HRI, now? I am currently a PhD student, and I previously worked as a software engineer. According to my own career, human-only work is becoming not efficient enough, while full autonomy has not yet been achieved in many complex tasks. Therefore, human--robot interaction is a stage that we have to face.

The second question is why guide robot.
As shown in figure 1,
Guide-robot demands can be mapped to general pHRI, from blue to green.
Guide-robot research has broad application value, from green to red.

Our main contribution includes a three-stage review, a cross-stage diagnosis, and two future directions.

# P4

Now, let us move to the three-stage review.

# P5


This is where the idea of the three stages comes from. 

I reviewed some representative studies and organized these research into three stages.

The first stage is modeling and optimization. This is a traditional robotics approach. We define a cost function, constraints, and differential equations. The guidance task then becomes an optimization problem that we can solve.

The second stage aims to achieve better perception. For example, researchers add force sensors or force estimators so that the robot can better handle its relationship with the human. This leads to methods such as force planning and compliance control.

In the third stage, we try to teach the robot to learn human behavior. Methods such as neural networks and reinforcement learning are used for this purpose.

# P6

Now, let us compare the three stages.

These tables in our review briefly compares the three stages.
And then I will introduce them in detail.

# P7


Stage I is modeling and optimization. 

We describe the problem using a cost function, constraints, and differential equations, and then solve it as an optimization problem.

Sometimes optimal solution may not be ideal.

# P8


Stage II is real-time interaction control. 

Force sensors or force estimators provide better perception of the human--robot relationship and support force planning or compliance control.



# P9


Stage III data-driven policy learning.


Learn complex dynamics and distributions from data or
simulation.

# P10

jump

# P11

Then, we come to the Cross-stage diagnosis and the final problem:

 what is still missing?

we identified two problems. 

First, 
Second, many methods produce only a single solution, but we do need a plan B for something unpredictable?

# P12

These problems lead to two future directions.

I list some architecture that I designed for guide robot system.
because I am doing my own phd research in these direction.

# P13

Next, the second direction.

I also list some method to escape from a local optima.
But to achieve a multimodal planning, we still have a long way to go.

# P14

To conclude, this review organizes guide-robot research into three stages, provides a cross-stage diagnosis, and points out future directions. It also uses the guide-robot perspective to think about physical human--robot interaction more broadly.

# P15

That is the end of my presentation.

Thank you for your listening, and I welcome your questions.
