---
title: "An Exploratory Study on Exception Handling Bugs in Java Programs"
date: 2015-08-01
publishDate: 2020-10-09T09:34:38.575614Z
authors: [admin, fernando-castor, alexander-serebrenik]
publication_types: ["2"]
abstract: "Most mainstream programming languages provide constructs to throw and to handle exceptions. However, several studies argue that exception handling code is usually of poor quality and that it is commonly neglected by developers. Moreover, it is said to be the least understood, documented, and tested part of the implementation of a system. Nevertheless, there are very few studies that analyze the actual exception handling bugs that occur in real software systems or that attempt to understand developers' perceptions of these bugs. In this work we present an exploratory study on exception handling bugs that employs two complementary approaches: a survey of 154 developers and an analysis of 220 exception handling bugs from the repositories of Eclipse and Tomcat.

Only 27% of the respondents claimed that policies and standards for the implementation of error handling are part of the culture of their organizations. Moreover, in 70% of the organizations there are no specific tests for the exception handling code. Also, 61% of the respondents stated that *no* to *little* importance is given to the documentation of exception handling in the design phase of the projects with which they are involved. In addition, about 40% of the respondents consider the quality of exception handling code to be either *good* or *very good* and only 14% of the respondents consider it to be *bad* or *very bad*. Furthermore, the repository analysis has shown (with statistical significance) that exception handling bugs are ignored by developers less often than other bugs. We have also observed that while overly general *catch* blocks are a well-known bad smell related to exceptions, bugs stemming from these *catch* blocks are rare, even though many overly general *catch* blocks occur in the code. Furthermore, while developers often mention empty *catch* blocks as causes of bugs they have fixed in the past, we found very few bug reports caused by them. On top of that, empty *catch* blocks are frequently used as part of bug fixes, including fixes for exception handling bugs.

Based on our findings, we propose a classification of exception handling bugs and their causes. The proposed classification can be used to assist in the design and implementation of test suites, to guide code inspections, or as a basis for static analysis tools."
featured: false
publication: "*Journal of Systems and Software (JSS)*"
tags: ["Bugs", "Exception handling", "Repository mining"]
url_pdf: "http://dx.doi.org/10.1016/j.jss.2015.04.066"
doi: "10.1016/j.jss.2015.04.066"
---
