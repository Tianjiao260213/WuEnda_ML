# Start


## Welcome to ML

It’s a science of getting computers to learn without being explicitly programmed.

## Applications of ML

It turns out that there are a few basic things that we could program a machine to do, such as how to find the shortest path from A to B, like in your GPS. But for the most part, we just did not know how to write an explicit program to do many of the more interesting things, such as perform web search, recognize human speech, diagnose diseases from x-rays, or build a self-driving car.

The only way we knew how to do these things was to have a machine learn to do it by itself.

Looking even further into the future, many people, include me, are excited about the AI dream of someday building machines as intelligent as you or me. This is sometimes called Artificial General Intelligence, or AGI.

## What is ML

Arthur Samuel(1959): Field of study that gives computers the ability to learn without being explicitly programmed.

What he did was he had programmed the computer to play maybe tens of thousands of games against itself. And by watching what sorts of board positions tended to lead to wins, and what positions tended to lead to losses, the checkers playing program learned over time what are good or bad board positions. By trying to get to good and avoid bad positions, this program learned to get better and better at playing checkers. Because the computer had the patience to play tens of thousands of games against itself, it was able to get so much checkers playing experience that eventually it became a better player than Arthur himself.

 Question: If the checkers program had been allowed to play only ten games(instead of tens of thousands) against itself, a much smaller number of games, how would this have affected its performance?
 A Would have made it better
 B Would have made it worse

 In general, the more opportunities you give a learning algorithm to learn, the better it will perform.

 ..If you didn't select the correct answer the first time, that's totally okay, too. The point of these quiz questions isn't to see if you can get them all correct on the first try. These questions are here just to help you practice the concepts you're learning.

 Machine learning algorithms

- Supervised learning
- Unsupervised learning

reinforcement learning
practical advice for applying learning algorithms

And so too in machine learning, making sure you have the tools is really important. And so it's making sure that you know how to appy the tools of machine learning effectively.

## Supervised Learning Part 1

I think 99% of the economic value created by machine learning today is through one tpye of machine learning, which is called supervised learning.

refers to algorithms that learn x to y, or input to output mappings. The key characteristic of supervised learning is that you give your learning algorithm examples to learn from that include the right answers, where by right answer I mean the correct lable y for a given input x. And it's by seeingn correct pairs of input x and desired output label y that the learning algorithm eventually learns to take just the input alone without the output label and gives a reasonably accurate prediction or guess of the output.

One of the things you see later in this class is how you can decide whether to fit a straight line, a curve, or another function that is even more complex to the data.

this housing price prediction is a particular type of supervised learning called regression. And by regression, I mean we're trying to predict a number from infinitely many possible numbers.

## Supervised learning Part 2

Classification

One reason that this is different from regression is that we're trying to predict only a small number of possible outputs, or categories.

and it can predict if a tumor is benign or malignant.

predict categories
small number of possible outputs

what the learning algorithm might do is find some boundary that separates out the malignant tumors from the benign ones.

In other machine learning problems, often many more input values are required.

So to recap, supervised learning maps input x to output y. Learns from being given "right answers"

The two major types of supervised learning are regression and classification.

## Unsupervised Learning Part 1

The most widely used form of machine learning is unsupervised learning.

I think, just as super as supervised learning. In unsupervised learning, we're given data that isn't associated with any output labels Y. Say you're given data on patients and their tumor size and the patient's age, but not whether the tumor was benign or malignant. We're not asked to diagnose whether the tumor is benign or malignant because we're not given any labels Y in the dataset. Instead, our job is to find some structure or some pattern, or just find something interesting in the data.

We call it unsupervised because we're not trying to supervise the algorithm to give some quote right answer for every input. Instead, we ask the algorithm to figure out all by itself what's interesting or what patterns or structures there might be in this dataset.

An unsupervised learning algorithm might decide that the data can be assigned to two different groups or two different clusters. And so it might decide that there's one cluster or group over here, and there's another cluster or group over here.

clustering algorithms: it places the unlabeled data into different clusters.

Clustering: Google news