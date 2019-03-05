# 100 Days Of Code - Log

### Day 1: Friday, March 1, 2019

**Today's Progress**: I started my rtlamr data visualization project, which I've unimaginatively 
named rtlamrvis. I've just _barely_ started the data ingestion code.

**Thoughts**: I'm very new to Python, and realized today that I know far less about working with 
dictionaries than I thought. Previously, I've coded mostly in Perl, and I keep expecting 
dicts to work the way Perl hashes do. I spent a lot of time spinning my wheels today, trying 
to figure out how to work with nested hashes. Better luck tomorrow, I hope.

**Link(s) to work**
1. [rtlamrvis](https://github.com/bcochrane/rtlamrvis)
2. [blog post](http://briancochrane.com/?p=73)


### Day 2: Saturday, March 2, 2019

**Today's Progress**: Got JSON parsing working in rtlamrvis.

**Thoughts**: I felt much better about today's coding session. Progress is still slow, but I feel I have a better handle on the basics of working with nested dictionaries, and the JSON parsing is working the way I want. I also learned how to delete keys from a dictonary. I ended up writing quite a bit more code than what's in today's commit, but I realized I was doing a bunch of unnecessary steps and was able to rearrange and simplify the code.

**Link(s) to work**
1. [rtlamrvis](https://github.com/bcochrane/rtlamrvis)
2. [blog post](http://briancochrane.com/?p=78)


### Day 3: Saturday, March 3, 2019

**Today's Progress**: I started off working on some tutorials, 
and then did another rewrite of the rtlamrvis data ingestion 
code. The resulting data structure is more complex than the previous 
list-of-dictionaries, but now the data is grouped by ID which I 
think will make it much easier to plot the data.

**Thoughts**: I find I'm still spending a lot of my time trying to 
figure out the basics, which is frustrating and doesn't make for a 
productive coding session. I may start splitting my hour of code between 
working on tutorials and continuing to work on the rtlamrvis project. I 
think that way I'll feel like these sessions are more effective.


**Link(s) to work**
1. [rtlamrvis](https://github.com/bcochrane/rtlamrvis)
2. [blog post](http://briancochrane.com/?p=82)


### Day 4: Saturday, March 4, 2019

**Today's Progress**: Successfully created a pandas DataFrame in rtlamrvis.py containing the 
rtlamr data and created line plots for individual meter IDs. Scatter plots aren't working, 
but a line plot with markers gets me what I need.

**Thoughts**: I'm really pleased that I finally had some success plotting the rtlamr data. 
It took a long time to find a pandas plotting example that I could understand. Most of the 
examples I found were either obviously not written for a beginner in mind, or assumed the 
reader would be using Jupyter notebooks. My code was executing without errors but I still 
wasn't seeing any plots...until I found that magic incantation: matplotlib.pyplot.show()


**Link(s) to work**
1. [rtlamrvis](https://github.com/bcochrane/rtlamrvis)
2. [blog post](http://briancochrane.com/?p=87)
