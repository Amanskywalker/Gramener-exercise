---
layout: post
title: "General Approach"
date: 2017-10-23 18:17:00 +0530
comments: false
---

The General Approach to solve the given problem boils down to the following steps

Firstly load the required libraires which are needed to analyse the data.

{% highlight python %}
import numpy as np                # to load numpy library
import pandas as pd               # to load panda library
import matplotlib.pyplot as plt   # to load the matplotlib library only pyplot to ploy the graphs
%matplotlib inline                # switching to inline mode in jupyter notebook
%pylab inline
{% endhighlight %}

Then load the use case data into the data frames

{% highlight python %}
Location = r'data/india-districts-census-2011.csv'  # location where the data is stored
df = pd.read_csv(Location)                          # reading the file from the location and storing it in the dataframes
df                                                  # only to display the dataframes, to check out what data is read from the file
{% endhighlight %}

To display the list of the columns which are in cvs file

{% highlight python %}
list(df)
{% endhighlight %}

This will output the list which have all the coloums present in the cvs file 
