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
    def __init__(self,weight,bias):
        self.weight = weight
        self.bias = bias
    def activate(self,x):
        return((1/(1+math.exp(-x*self.weight+self.bias))))
{% endhighlight %}
You might be wondering what a sigmoid function looks like...

![Alt text]({{ site.url }}/assets/img.png )
![My helpful screenshot]({{ site.url }}/assets/screenshot.jpg)
s
Ok, cool let's see what it can do. Though it can only handle one input and
one output. Lets see it can approximate a simple binary function. If input a
0 it should return a one if Input a 1 on it should return a zero. So let's 
write some code.

{% highlight python %}

{% endhighlight %}


