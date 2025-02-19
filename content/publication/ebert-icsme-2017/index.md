---
title: "Confusion Detection in Code Reviews"
date: 2017-09-01
publishDate: 2020-10-09T09:34:38.566537Z
authors: [admin, fernando-castor, nicole-novielli, alexander-serebrenik]
publication_types: ["1"]
abstract: "Code reviews are an important mechanism for assuring quality of source code changes. Reviewers can either add general comments pertaining to the entire change or pinpoint concerns or shortcomings about a specific part of the change using inline comments. Recent studies show that reviewers often do not understand the change being reviewed and its context.Our ultimate goal is to identify the factors that confuse code reviewers and understand how confusion impacts the efficiency and effectiveness of code review(er)s. As the first step towards this goal we focus on the identification of confusion in developers' comments. Based on an existing theoretical framework categorizing expressions of confusion, we manually classify 800 comments from code reviews of the Android project. We observe that confusion can be reasonably well-identified by humans: raters achieve moderate agreement (Fleiss' kappa 0.59 for the general comments and 0.49 for the inline ones). Then, for each kind of comment we build a series of automatic classifiers that, depending on the goals of the further analysis, can be trained to achieve high precision (0.875 for the general comments and 0.615 for the inline ones), high recall (0.944 for the general comments and 0.988 for the inline ones), or substantial precision and recall (0.696 and 0.542 for the general comments and 0.434 and 0.583 for the inline ones, respectively). These results motivate further research on the impact of confusion on the code review process. Moreover, other researchers can employ the proposed classifiers to analyze confusion in other contexts where software development-related discussions occur, such as mailing lists."
featured: false
publication: "*2017 IEEE International Conference on Software Maintenance and Evolution (ICSME)*"
tags: ["code review", "confusion", "machine learning"]
doi: "10.1109/ICSME.2017.40"
---
