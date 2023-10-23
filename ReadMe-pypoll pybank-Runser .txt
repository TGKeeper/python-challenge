README - Runser


##HOMEWORK - module 3##


First off, I am well aware--or at least I became aware a little before 6pm today--that I was not supposed to use pandas for this assignment.  I was so excited after the teeth-pulling experience with VBA that I only had to do a silly readme file & figure out 1 or 2 things right before the deadline, so of course it figures I did the assignment completely wrong. It honestly didn't occur to me once that the two python modules were supposed to be discrete, and if I read anything in the instructions requiring me to use Visual Studio I certainly didn't clock it. So considering that I don't have any non-panda homework to turn in, here we are. 


##PyPoll##

The code I wrote for the PyBank homework was all based on a panda I called budgetDF. This allowed me to manipulate & imagine the data as a standard table complete with the use of structured references. I had some trouble at the end with figuring out how to print just the found line without headers or data type info so I resolved it by googling through a ton of almost entirely worthless posts. Again, forgive me for complaining here but I need to complain somewhere, but it would really be fantastic if every douchebag online could *just answer the question posed*. Not, "whY doN't yOu dO it liKe tHis??", or "Here's how you do it in a completely unrelated program that I personally prefer & you didn't ask about," or answering a different question than the one posed.  I can't tell if I'm reading the ramblings of a bunch of idiot savants, would-be politicians, or shit-positing 12-year-olds. StackOverflow is the worst offender & here all this time I thought it just sucked for Excel questions. What an ignorant optimist I was.  So I did look through quite a few posts there & of all the approaches that looked promising, 100% of them didn't work. 

I had trouble with the "too many indexers" error because I kept trying to treat a series as a dataframe.  A completely random webpage, https://discuss.datasciencedojo.com/t/what-is-the-method-to-find-the-maximum-value-in-each-row-of-a-dataframe/996, put me onto the .idmax() function that fixed the issue. Otherwise, I went over the homeworks (yes, the #wrong# homeworks apparently) to refresh myself on loc/ .iloc/ finding just the rows for 1 candidate, just specific rows & columns, etc. 

I did do something funny with the how many months within the data question because I  didn't know if it meant "how many different months," because it's obviously 12, like any financial statement, or if the real question was "how many different sample days were included in the data," which is 86.  So I answered both, 1 with unique() & 1 by importing datetime & approaching it like I would in Excel: by extracting month names from the dates.  I followed instructions here from another random page: https://pynative.com/python-string-to-datetime-strptime/.  
     
There is probably still some nonsense code in there I forgot to delete or comment out. 


##PyBank##

This code does many of the same types of filtering and referencing as what I wrote for PyBank does, and I had the same issues. Once I was able to figure out how to do it in PyPoll, I copied it over to PyBank. I approached them the same way thus they are structured & behave the same way. 

Ditto for forgotten nonsense code.