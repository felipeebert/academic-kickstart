---
title: "A Comparative Analysis Between Information Flow Control Tools for Java-written systems"
date: 2021-09-01
publishDate: 2021-08-24T09:12:17.924890Z
authors: ["G. Porto", rodrigo-andrade, admin]
publication_types: ["1"]
abstract: "Information Flow Control (IFC) tools are a common way to analyze source code with the goal to find confidentiality or integrity violations for sensitive information. Therefore, to correctly protect such information (e.g., passwords), it is important to choose the most suitable tool for each target software system. In this context, we evaluate precision, recall, and accuracy for three open-source IFC tools for Java written systems. We also check whether these tools are useful to protect sensitive information of real systems. First, we execute these tools against test cases of the SecuriBench Micro benchmark built for this purpose. Then, we run three selected IFC tools (JOANA, PIDGIN, and Flowdroid) to assess whether they are able to detect violations for rules we define considering each real system. Our results show that JOANA and PIDGIN overcome FlowDroid regarding precision, recall, and accuracy. Furthermore, the execution of JOANA and PIDGIN allow us to find eight confidentiality and integrity violations for the target systems. We registered these violations as issues on those projects. Our results also demonstrate that JOANA is faster than PIDGIN. At last, we provide some discussion for developers on which IFC tool fits better when dealing with sensitive information in software systems."
featured: false
publication: "*The 15th Brazilian Symposium on Software Components, Architectures and Reuse (SBCARS)*"
tags: ["information-flow control", "sensitive information", "confidentiality", "integrity"]
doi: "https://doi.org/10.1145/3483899.3483901"
---
