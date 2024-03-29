COMMENTS FOR THE AUTHOR:

There is additional documentation related to this decision letter. To access the file(s), please click the link below. You may also login to the system and click the 'View Attachments' link in the Action column.  
http://emse.edmgr.com/l.asp?i=29415&l=7UGCRKN1

Dear Authors,

We thank you for your submission, "How the R Community Creates and Curates Knowledge: A Comparative Study of Stack Overflow and Mailing Lists" to the MSR 2016 Special Issue.  Your submission was reviewed by three reviewers and we have decided to ask for a major revision to the manuscript.  Here are the main points that we ask you to address in your revision:

1.   Please improve the discussion of the implications/takeaways from the study (per Reviewer 2).
2.   All reviewers have suggestions to improve the writing by adding minor details, clarifying text, fixing grammar, defining terms and phrases (e.g. “reaching saturation”), etc.  Please see all three and make the suggested changes/additions in the text.
3.   R3 asks how results change if people who ask one question and never interact again are removed from the analysis.  Please re-run the analysis with this change and discuss the differences.
4.   Per R3’s point number 8, please check the 3 possible answers regarding R-help mailing list slowdown using your collected data or provide some explanation if this is not possible.
5.    Please update the threats to validity to include the threat regarding false positives or false negatives when merging email identities.
We look forward to receiving the revised manuscript.

Best Regards,
Chris, Romain, and Emily

-----

Reviewer #1: This is a good paper with many points for discussion among not only the R community but other online software development communities that may be struggling with maintaining communication channels in the social media age. I have attached a document with some points for improvement, clarification, and alteration. 



Reviewer #2: Online communities play a more important role in sharing knowledge in current practice. The traditional form (e.g., the mailing list) co-exists with the latest Q/A websites like stack overflow. This paper studies how knowledge is exchanged and curated on the two forms. The study is conducted from two perspectives, the shared knowledge and the participants.
As a summary, the newly added content is sufficient for the extension. This paper is well written. However, there are a few points needed to be clarified.
- The authors should explicitly mention that this is an extension of their MSR paper.
- Lack of discussion on findings described in Sections 4.4.1 and 4.4.2. What can we learn from the reported findings? Although there is a seperate discussion section (i.e., Sections 5.1.5 and 5.1.6), the two sections are just duplicate of Section 4. Findings are listed as Section 4 without deep discussions. The authors should revise Sections 5.1.5 and 5.1.6 to discuss what do their findings imply and how the R community benefits from their findings.
- Page 10, ln14, "Using the Chi-square test", could you give more details on how the test is performed. For example, what is the input of the test?
- Table 3, what the is criteria to determine 'the most significant differences', i.e., numbers in bold.
- page 16, ln 35, "find a better answer. As expected, two channels are better than one -- one channel might result in a better answer than the other". Do you have any evidence? For example, is there any difference in the rate of successfully answered questions for each type of questions?
- page 16, ln 41, "Stack Overflow ... does not provide an environment to discuss the specifics of an answer". The statement is not very accurate. Stack Overflow users can post comments under each question or each answer.
- page 7, ln13 and page 9, ln23, do Table 1 and 2 show the statistics of all data since the creation of R-help mailing list and Stack Overflow? If so, another two tables are needed to show the statistics of the data used in the study, i.e., the data collected between 2008.9 to 2013.12 and between 2008.9 to 2016.9.
- "different individuals" of R mailing list remains the same in Tables 1 and 2. Please check if there is a typo, or confirm that no new individuals use R mailing list between 2014.01 to 2016.9, or any other reason?
- page 25, ln39 and page 19, ln32, the two numbers do not match, i.e., 33% and 32%. Please correct.



Reviewer #3: This paper is an extension of the same work published at MSR 2016. The authors have extended their work in two ways. First, they include 2 more years of data from Stack Overflow and R-help mailing lists in their data sets, and they also answer two additional research questions that look at the temporal properties of participation in these forums. 

The original paper was very good, and provided some nice insights into the balance of participation across multiple forums for a single community of users. This paper extends the work, and I went through both papers side by side to identify the differences. For the most part, the text is unchanged except where the authors put in additional work to answer their two new research questions (and someone took some time to further wordsmith the abstract and introduction to tighten it up). The new material has been inserted into the right places in the paper, but its addition has not affected the authors' main message about the lessons they learned, nor did the authors redo Phase I of their analysis on the additional data. I do think it is enough to qualify for the 30% additional material "rule" for journal extensions of conference papers. 

In addition to liking the research and paper overall, here are some things I especially liked about the research and/or its writeup:

1. I like the description of the use of Cohen's Kappa metric in Section 3.1.1. This was very convincing and professional.

2. I like that the authors converted the contribution rates of SO and R-help users into posts per day in Section 4.5.2


Here are some questions and concerns I would like the authors address in a future revision of this paper. 

1. In Section 3.1, line 32, the authors say that Stack Exchange's dump file elided email addresses after September 2013. Please add the reasoning for why Stack Overflow did this. If there isn't an official answer, please speculate. 

2. The authors say they extended their data set to include October 2014 to September 2016. The data dump publicly available on the github site (referenced in footnote 4) has not been updated since February 2016. Please upload your data set publicly if you're going to reference it in a paper.

3.  The extension of two years of additional data reveals a missed opportunity. The authors did not redo Phase I with the additional data. That might have provided some insight in new kinds of questions and answers discovered by the community in later years. For example, perhaps posting questions with Instagram attachments may have become in vogue. The authors wouldn't be able to tell us.

4. In Figure 5, there's a funny bump in 2015 in the SO with score > 0 data that is not reflected in the fitted curve. What happened there? How do you explain it? It looks larger than typical natural variation. 

5. The prose in Section 4.4.1, line 28 indicates a decrease in the number of questions with score > 0, but says it may be temporary. A temporal analysis could show whether the variation is within previously expected bounds, or whether this is truly a new trend. 

6. The analysis in Section 4.4.2 about how long users participate does not consider the difference between askers and answerers. I can easily imagine a scenario where people have a single question, then go to the forum, ask their question, get an answer, and leave satisfied, never to return. I can imagine that this population is very dominant. If you pulled out those people from the analysis, what's the next largest population's behavior? Do you see people who answer questions once and leave? Please rerun these stats with that obvious class of users removed. Are the results different? That could change the authors subsequent explanation for that data point.

7. Section 4.5.2. establishes that several users are common between both channels. Where do these people come from? I would like to see the authors compare their identities to those who have contributed code to the R project. Are these the core R developers? The maintainers? 

 7.a. How does R persuade its developers to participate in the forums, if indeed it does? 

8. In Section 5.1.4. the authors speculate on why the number of posts with a positive score is decreasing. They propose 3 possible answers that are each easy to check from the authors' data. I would like to see the authors check their explanations and tell the readers how much of an effect each has on the decrease. 

9. In Section 5.1.4, line 27-31, the authors speculate that a slowdown in the R-help mailing list is due to the slowdown in StackOverflow (indicating that most questions have been asked). If this is true, it should have left a trending effect prior to Stack Overflow topic saturation in the number of R-help posts. I.e. these two figures should be linearly related. Please compute this relation and report it. If there is no relation, then the authors' explanation is probably off-base.

10. The authors go back and forth on how to explain that some participants only post once and leave the forum. In Section 5.1.5. they hedge and say that the cause isn't clear at all. I think it's completely clear re: point 6 above. This is also easily checkable. Please check and make a bolder claim.

10.a How might the participation rate distribution be explained by Lave and Wenger's theory of Legitimate Peripheral Participation? 

11. The threats to internal validity should include the email identity merging algorithm which may have incorrectly merged some individuals or left some unmerged.

