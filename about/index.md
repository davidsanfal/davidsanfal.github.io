---
layout: page
title: About me
tags: [about]
modified: 2014-08-08T20:53:07.573882-04:00
comments: true
image:
  feature: me.png
  credit: David Sánchez Falero
  creditlink:
---

My name is David Sánchez Falero. Software Engineer. Interested in Machine Learning, Python, Robotic and Mountain Gorillas. Co-organizer of C/C++ Madrid.

## Why Mountain Gorillas?

All the people have their secrets love, the mountain gorrillas are mine. I discovered they when I was watching a documentary in the TV "Titus the gorilla king", when I saw what we were doing with these animals I decided to help with one of the organizations who are helping them, ["The Dian Fossey Gorilla Fund International"](http://gorillafund.org/).

## Why Machine Learning?

When I was young my dream was to create a robot capable of learning and I have never lost this dream. For this reason, I try to read and learn about Machine Learning, Neural networks and Deep Leanings always I have some time.

## Why Python?

I started with Python in 2013 and I fell in love. I love the way of code python, how you can prototype all you want in just hours. 

I know that it isn't as fast as C++, but it is more agile and pretty. It is impressive the few time you need to convert an idea in code.

![]({{ site.url }}/images/py_vs_cpp.png)

For example, in the following code you have an implementation of the fibonacci Sequence in python (6 lines) and C++ (23 lines).

**[Fibonacci Number by wikipedia.org](http://en.wikipedia.org/wiki/Fibonacci_number)**

> In mathematical terms, the sequence Fn of Fibonacci numbers is defined by the recurrence relation
> 
> ![](http://upload.wikimedia.org/math/0/c/e/0cebc512d9a3ac497eda6f10203f792e.png)
> 
> with seed values
> 
> ![](http://upload.wikimedia.org/math/4/3/d/43d30dc03ffec0a82d4471f1009ef519.png)
> 
> or
> 
> ![](http://upload.wikimedia.org/math/a/9/2/a92c5f0981136ba333124cdfe6d3c3ce.png) 

**fibonacci.py**

{% highlight python %}
def fib(n):
    a, b = 0, 1
    while a < n:
        print a
        a, b = b, a+b
fib(1000)
{% endhighlight %}

**fibonacci.cpp**

{% highlight cpp %}
#include<iostream>
 
using namespace std;

fib(int n)
{ 
    int c, first = 0, second = 1, next;
    for ( c = 0 ; c < n ; c++ )
    {
        if ( c <= 1 )
        next = c;
    else
    {
        next = first + second;
        first = second;
        second = next;
    }
    cout << next << endl;
}

main()
{
    fib(1000);
    return 0;
}
{% endhighlight %}

## Why C/C++ Madrid?

I funded [C/C++ Madrid](http://www.meetup.com/Madrid-C-Cpp) with my friend [Francisco Fernandez](https://github.com/fcofdez) in 2014 because we were locking for a Meetup about it and we didn't find nothing. I don't have good skill with C/C++ but it is the language with which I learned to program and one of the most efficient, so I am always trying to improve my level.

[![C/C++ Madrid]({{ site.url }}/images/banner.png)](http://www.meetup.com/Madrid-C-Cpp)
