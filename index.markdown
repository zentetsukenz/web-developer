---
layout: home
author_profile: false
---

# Introduction

Building software has always been cryptic for everyone. When we see a veteran developer code, we usually see some weird text that looks like English but not typical English grammar. Some are easy to understand, and we can guess what it does.

{% highlight ruby %}
def say_hello_to(name)
  puts "Hello, #{name}"
end
{% endhighlight %}

However, most of the time, we usually see more complex code.

{% highlight ruby %}
def calculate_best_vector(parameters = {})
  volumes ||= parameters[:volumes]
  distance_mapper ||= parameters[:distance_mapper]

  self.vectors.each do |vector| 
    center = vector.vector_elements.select { |e| e.center }.first
    surrounds = initialize_surrounding(vector.vector_elements, center)

    index = 0
    while index < surroundings
      volume = surroudings[index].capacity - center.volume
      # snip ....
      # this is too complex ....
    end
  end
end
{% endhighlight %}

To understand the code above, we will need to understand at least two things, syntax (a.k.a. a programming language grammar) and context (the problem that the code is trying to solve).

# Programming concepts

Programming is a tool we can use to achieve a goal. There are many steps involved, many programming concepts, and many other technologies order than coding to craft one beautiful application.

This handbook will contain the necessary tools, concepts, and techniques necessary for anyone who wants to build an application. From the starter concept, write the first program to an advanced concept used in an enormous application.

# Handbook

There are four sections in this handbook, starter, basic, intermediate, and advance. Each section contains four categories, toolings, programming concepts, techniques, and deployment.

Since this handbook focuses on a Web Developer, all contents inside will be revolving around building a customized web application suit to a particular problem.

Please note that there are already many solutions on the internet that can already solve some problems. For example, to build Web Content, there is a solution called CMS, Content Management System, which revolves around building a post and allowing users to comment. E-commerce, there are also many free and open-source e-commerce platforms waiting for anyone to grab and build their e-commerce website.

These are some of the tools that are already available on the internet. Many tools can already solve some common problems. However, if the goal is to build something new that those tools cannot do their job. This handbook will help anyone who wants to start programming, build something special, and start their software development journey.

Lastly, the author hopes that this handbook will help everyone achieve their goal.

Good luck, and happy coding 🎉

# Epilogue

Feel free to post questions [here](https://github.com/zentetsukenz/web-developer/issues) whether there is already a solution for a specific problem or not. Feedback, improvement, and contribution are also very welcome.

Let us get started!