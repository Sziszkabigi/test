# test
smart_pension_test

Task:
1. Write a program that:
a. Receives a log file as an argument (webserver.log is provided) e.g.: ./<parse> webserver.log
b. Returns the following:
> list of webpages with most page views ordered from most pages views to less page views e.g.:
/home 90 visits /index 80 visits etc...
> list of webpages with most unique page views also ordered e.g.:
/about/2 8 unique views /index 5 unique views etc...

Solution:

How To Use the program:
- need to run this in command line./parse webserver.log 

and after it can show the solution:

---
task1
---
/about/2 90 visits
/contact 89 visits
/index 82 visits
/about 81 visits
/help_page/1 80 visits
/home 78 visits

---
task2
---
/help_page/1 23 unique views
/contact 23 unique views
/home 23 unique views
/index 23 unique views
/about/2 22 unique views
/about 21 unique views

My work:

First I use the set methods so after I open the file I always can work with the uniqe wievs.
