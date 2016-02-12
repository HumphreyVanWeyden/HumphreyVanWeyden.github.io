---
layout: post
title: Fun with Machine Learning
---

So after a brief skim of the literature I have the following Neuron.
It is pretty simple It takes one input, and returns one output. It
uses the sigmouid activation function.

{% highlight python %}
import math
class node:
    def __init__(self,weight):
        self.weight = weight
    def activate(self,x):
	#this is an implementation of the sigmoid function.
        return((1/(1+math.exp(-x*self.weight))))
{% endhighlight %}
You might be wondering what a sigmoid function looks like...
![Sigmoid function]]({{ site.url }}/assets/img.png )
So why this function. Well as you probably noticed it's output is limited from
0 to 1. 

Ok, cool let's see what it can do. Though it can only handle one input and
one output. Lets see it can approximate a simple binary function. If input a
0 it should return a one if Input a 1 on it should return a zero. So let's 
write some code.

{% highlight python %}

{% endhighlight %}


