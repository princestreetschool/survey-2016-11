Introduction
============

In October and November 2016, [Prince Street Home and School](http://princestreetschool.ca/) opened up a process for consulting the school community to gain insights and comments about our school to contribute to the [school review process](https://www.princeedwardisland.ca/en/information/education-early-learning-and-culture/school-review-better-learning-all). The consultation included the following elements:

* Discussion at October and November Home and School meetings.
* A clear-language explanation of the school review process and our consultation plan.
* A survey, available online and in hard copy.
* A suggestion box available in the school office.
* An email address open for comments in the language of the sender’s choice.
* Encouragement from Home and School members for their friends and neighbours to take part in the discussion.

We had 55 responses to our survey about Prince Street School and the school review process. There were no separate comments: all respondents chose to use the survey (online or hard copy) to submit their comments.

A detailed summary of the survey, with notes, [is available on the Home and School website](http://princestreetschool.ca/content/report-school-review-process).

This respository contains CSV files of the survey response data to allow for further analysis by others, and reflects a belief by the Home & School in the value of open data.

Data Files Available
====================

questions.csv
-------------

This file ontains the text of the 10 survey questions as presented to respondents. For example, the text of the first question was *How are you connected to Prince Street Elementary School? (Please select all that apply.)*:

	"Question Number","Question"
	1,"How are you connected to Prince Street Elementary School? (Please select all that apply.)"

responserate.csv
----------------

This file contains data on the response rate for each question. It is related to questions.csv by the *Question* column. For example, you will find, in part:

	"Question,"Response","Count"
	1,"answered question",55
	1,"skipped question",0
	
This indicates that for question number 1, 55 respondents answered the question and 0 skipped it.

1.csv through 10.csv 
--------------------

These files contain data about the responses to each question; each file is named for its question.  For example, in the file 1.csv you will see, in part:

	"Answer Options","Response Percent","Response Count"
	"I am a Prince Street student",1.8,1

The indicates that 1.8% of respondents -- 1 respondent -- selected the option "I am a Prince Street student" for this first question. 

Note that for question 10, file **10.csv**, the only data provided is the response rate, as many of the responses contained personally-identifying information; a summary of the comments [is available on the Home and School website](http://princestreetschool.ca/content/report-school-review-process).

Comments or Questions
=====================

If you have comments or questions about the data here, please contact the Prince Street Home & School Association by email at [princestreethomeandschool@gmail.com](mailto:princestreethomeandschool@gmail.com).