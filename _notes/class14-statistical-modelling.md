---
title: "Statistical Modelling"
author: "Taylor Arnold"
output: html_notebook
---



In the last class we discussed at a high level how data can be used in the
construction of persuasive arguments. In the class before that, we saw how
exploratory data analysis can be used to understand the patterns within a
dataset and to extract useful observations, graphics, and summary statistics.
Today we look at how we can extract information from data through the use of
predictive statistical models.

## Predictive Models

FiveThirtyEight also has plenty of examples of predictive models.
For example, here are several on-going sports and politics links on the site
that try to predict who will win a given sports game, win a given election, or
the estimate the current popularity of the president:

- [Club Soccer Predictions](https://projects.fivethirtyeight.com/soccer-predictions/)
- [2017-18 NBA Predictions](https://projects.fivethirtyeight.com/2018-nba-predictions/)
- [2017 NFL Predictions](https://projects.fivethirtyeight.com/2017-nfl-predictions/)
- [Are Democrats/Republicans Winning The Race For Congress?](https://projects.fivethirtyeight.com/congress-generic-ballot-polls/?ex_cid=rrpromo)
- [How (un)popular is Donald Trump?](https://projects.fivethirtyeight.com/trump-approval-ratings/)

These are continually updated as games are played and polls released. The site
includes many more such predictive models around US federal elections,
particularly during presidential elections.

Predictive models can be used as evidence within a persuasive argument just as
exploratory methods. For some examples, see:

- [Casey Affleck And Denzel Washington Are Neck And Neck In The Oscar Race (Feb. 14, 2017)](http://fivethirtyeight.com/features/casey-affleck-and-denzel-washington-are-neck-and-neck-in-the-oscar-race/)
- [Northam Heads Into Virginia Governor’s Race With A Small Lead (Nov. 6, 2017)](https://fivethirtyeight.com/features/the-virginia-governors-race-might-not-be-predictive-but-it-could-really-matter/)

What then makes predictive models different than exploratory techniques? In
my view: *exploratory methods explain the observed data; predictive models
make an explicit attempt to explain unobserved data*. The difference here is
subtle and not always clear-cut, but understanding the fundamental distinction
is important.

## Statistical/Machine Learning

We will not spend much time discussing the general task of predictive
modelling. If you are interested, here is a great 5 minute
tour of the big picture behind building predictive models:

[A Visual Introduction to Machine Learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)

I teach an entire class on this subject, *Statistical Learning*, if you are
interested in taking more statistics courses in the future.

## Statistical Inference

There is one particular type of predictive model that we will look at this
semester, which falls under the task of statistical inference. Inference has
a particular structure to it, with the following elements:

- a **population** of which we are interested in understanding; for example,
this could be all Americans over the age of 18, all UR students, or the set of
all wild chimpanzees
- a **variable of interest** that we wish to understand about the population;
this could be, for example, the average height or age of all members in a
population
- a subset of the population, know as a **sample**; for example, this could be
1000 randomly chosen households, the students in this class, or the
chimpanzees  held at a particular zoo

This set up is important in many fields. For example, medicine:

> How many heart attack patients (the  population) will survive in the next 5
> years if given the new drug Z (variable of interest)? Let's test it on 200
> heart attack patients at our hospital (sample)!

Or psychology:

> How long, on average, does it take an adult chimpanzee (population) to learn
> the optimal strategy for playing tic-tac-toe (variable of interest)? Let's
> test it on the 12 chimpanzees we have in our lab!

Statistical inference is used to take the properties observed regarding the
variable of interest in the sample and estimating properties of the
population. We will talk about this process, which is where all the
mathematics comes into statistics, but unlike "old style" statistics courses
this will only be a small part of the larger picture of learning to work with
data.

## Examples

Statistical inference is most often used in academic writing. Let's take a
look, to start, at articles from the :

-[NEJM: Browse Research](http://www.nejm.org/medical-articles/research)

You'll be able to see a summary of most articles on this page, though
generally not the entire text. The summary should be enough for our purposes.
We will all pick an article to work with. For your article, write down:

- what is the population of study?
- what is the variable(s) of interest?
- what is the sample (how many patients, how selected, ect.)?
- what were the results?

You may not understand all of the technical terms. Try to look up those that
are foreign to you, within reason.

Let's repeat with a second journal (choose an article from one and repeat
the questions above):

- [Science](http://science.sciencemag.org/)
- [Pediatric Neurology](http://www.pedneur.com/current)
- [American Journal of Political Science](https://ajps.org/ajps-articles/current-issue/)
- [Journal of Applied Psychology](http://psycnet.apa.org/PsycARTICLES/journal/apl/102/12)

We will cover in much more detail the process of statistical inference later
in the semester, but now at least we have an understanding of the approach at
a very high level.

## Summary: Where we are and where we are going

In the first two weeks of the semester we have taken a bird's eye view of the
statistical process which data is explored, modelled, and used in constructing
larger arguments about the world around us.

Next week we begin to learn the tools and techniques for ourselves: how to
collect data, how to clean it for analysis, how to visualize it  without a
fancy pre-made website, how to construct inferential models, and how to write
statistical analyses for ourselves.

