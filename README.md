# SDS291Project
SDS 291: Multiple Regressions - Group Project

# Project
Technical Report
Your technical report will be an annotated R Markdown file (.Rmd) that contains your R code, interspersed with explanations of what the code is doing, and what it tells you about the problem.

# Content
You should not need to present all of the R code that you wrote throughout the process of working on this project. Rather, the technical report should contain the minimal set of R code that is necessary to understand your results and findings in full. If you make a claim, it must be justified by explicit calculation. A knowledgeable reviewer should be able to compile your .Rmd file without modification, and verify every statement that you have made. All of the R code necessary to produce your figures and tables must appear in the technical report. In short, the technical report should enable a reviewer to reproduce your work in full.

# Tone
This document should be written for peer reviewers, who comprehend statistics at least as well as you do. You should aim for a level of complexity that is more statistically sophisticated than an article in the Science section of The New York Times, but less sophisticated than an academic journal. [Chance magazine might provide a good example.] For example, you may use terms that that you will likely never see in the Times (e.g. bootstrap), but should not dwell on technical points with no obvious ramifications for the reader (e.g. reporting F-statistics). Your goal for this paper is to convince a statistically-minded reader (e.g. a student in this class, or a student from another school who has taken multiple regression) that you have addressed an interesting research question in a meaningful way. Even a reader with no background in statistics should be able to read your paper and get the gist of it.

# Format
Your technical report should follow this basic format:

# Abstract:
A short, one paragraph explanation of your project. The abstract should not consist of more than 5 or 6 sentences, but should relate what you studied and what you found. It need only convey a general sense of what you actually did. The purpose of the abstract is to give a prospective reader enough information to decide if they want to read the full paper.

# Introduction:
An overview of your project. In a few paragraphs, you should explain clearly and precisely what your research question is, why it is interesting, and what contribution you have made towards answering that question. You should give an overview of the specifics of your model, but not the full details. Most readers never make it past the introduction, so this is your chance to hook the reader, and is in many ways the most important part of the paper!

# Data: 
Abrief description of your data set. What variables are included? Where did they come from? What are units of measurement? What is the population that was sampled? How was the sample collected? You should also include some basic univariate analysis.

# Results:
An explanation of what your model tells us about the research question. You should interpret coefficients in context and explain their relevance. What does your model tell us that we didn’t already know before? You may want to include negative results, but be careful about how you interpret them. For example, you may want to say something along the lines of: “we found no evidence that explanatory variable x is associated with response variable y,” or “explanatory variable x did not provide any additional explanatory power above what was already conveyed by explanatory variable z.” On other hand, you probably shouldn’t claim: “there is no relationship between x and y.”

# Conclusion: 
A summary of your findings and a discussion of their limitations. First, remind the reader of the question that you originally set out to answer, and summarize your findings. Second, discuss the limitations of your model, and what could be done to improve it. You might also want to do the same for your data. This is your last opportunity to clarify the scope of your findings before a journalist misinterprets them and makes wild extrapolations! Protect yourself by being clear about what is not implied by your research.

Additional Thoughts
The technical report is not simply a dump of all the R code you wrote during this project. Rather, it is a narrative, with technical details, that describes how you addressed your research question. You should not present tables or figures without a written explanation of the information that is supposed to be conveyed by that table or figure. Keep in mind the distinction between data and information. Data is just numbers, whereas information is the result of analyzing that data and digesting it into meaningful ideas that human beings can understand. Your technical report should allow a reviewer to follow your steps from converting data into information. There is no limit to the length of the technical report, but it should not be longer than it needs to be. You will not receive extra credit for simply describing your data ad infinitum. For example, simply displaying a table with the means and standard deviations of your variables is not meaningful. Writing a sentence that reiterates the content of the table (e.g. “the mean of variable x was 34.5 and the standard deviation was 2.8…”) is equally meaningless. What you should strive to do is interpret these values in context (e.g. “although variables x1 and x2 have similar means, the spread of x1 is much larger, suggesting…”).

You should present figures and tables in your technical report in context. These items should be understandable on their own, in the sense that they have understandable titles, axis labels, legends, and captions. Someone glancing through your technical report should be able to make sense of your figures and tables without having to read the entire report. That said, you should also include a discussion of what you want the reader to learn from your figures and tables.

Your report should be submitted via email as an R Markdown (.Rmd) file and the corresponding rendered output (.html) file.

# Presentation
An effective oral presentation is an integral part of this project. One of the objectives of this class is to give you experience conveying the results of a technical investigation to a non-technical audience in a way that they can understand. Whether you choose to stay in academia or pursue a career in industry, the ability to communicate clearly is of paramount importance. As a data analyst, the burden of proof is on you to convince your audience that what you are saying is true. If your audience (who may very well be less knowledgeable about statistics than you are) cannot understand your results or their interpretations, then the technical merit of your project is irrelevant.

You will make a ~10-minute oral presentation to the class. You should make (good) slides. Your goal should be to convey to your audience a clear understanding of your research question, along with a basic understanding of your model, and how well it addresses the research question you posed. You should not tell us everything that you did, or show a bunch of models that didn’t work well. After hearing your talk, each student in the class should be able to answer:

What was your project about?

What kind of model did you build?

How well did it work?

You should prepare electronic slides for your talk. PowerPoint is fine, but you might also want to consider Google Presentation, Beamer (LaTeX), or alternative, non-linear presentation software like Prezi. Use your creativity! One thing you should not do is walk us through your calculations in RStudio.

You will need to submit your slides before your presentation, but you should also bring the slides on a flash drive as a backup. You will not be able to hook up your laptop to the computer in SR 301.

