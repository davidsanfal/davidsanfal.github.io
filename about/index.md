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

My name is David Sánchez Falero. Software Engineer. Interesting in Machine Learning, Deep Learning, Python, Robotic and Mountain Gorillas. Co-organizer of C/C++ Madrid. 

## Why Python?

I started with Python in 2013 and I fell in love. I love the way of code python, how you can prototype all you want in just hours. 

I know that it isn't as fast as C++, but it is more agile and pretty. It is impressive the few time you need to convert an idea in code.

For example, in the following codes you have an example with fibonacci in python (6 lines), C++ (23 lines), Java (13 lines).

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

fib(int n){ 
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

**fibonacci.java**

{% highlight java %}
public class Fibona {

    public static void main(String[] args) {
    int elemento = 1000, ant = 0, act = 1, next = 1;

    System.out.print("0, ");
    for (int i = 0; i < elemento - 1; i++) {
        System.out.print(next + " ");
        next = act + ant;
        ant = act;
        act = next;
        }
    }
}
{% endhighlight %}

## Why Machine Learning?

When I was young I dream with the idea of build my own Robot with full intelillence. 

## Why Robotics?

## What can I spect learning it?

Maths + Hacking + expertise

![]({{site.url}}/images/data_science.png)
{: .image-pull-center}

## Why C/C++ Madrid?

## Why Mountain Gorillas?