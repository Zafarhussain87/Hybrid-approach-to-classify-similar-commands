# Hybrid-approach-to-classify-similar-commands

Command-line commands form a special kind of semi-natural
language. Analyzing their structure and classifying them is a useful approach
in the field of cyber security to detect anomalous commands
used by malicious actors. Without any contextual knowledge, commands’
analysis is a difficult task as similar-looking commands might be performing
different tasks, and commands with different aliases might be
performing the same tasks. To understand command-line commands’
structure and their syntactic and semantic meanings, we created a rulebased
system based on expert opinions. Using this system, we classified
command-line commands into similar and not-similar classes. This rulebased
system transformed command-line commands’ data into a binary
classified form. We trained three machine learning models (a logistic regression
document classifier, a deep learning document classifier, and a
deep learning sentence-pair classifier) to learn the set of rules created in
the rule-based system. We used Mathews Correlation Coefficient (MCC)
score for the models’ performance comparison. The logistic regression
model shows an MCC score of 0.85, whereas both the Deep Learning
(DL) models scored above 0.98. DL document classifier and DL sentencepair
classifier achieved an accuracy of 0.943 and 0.983 respectively on
unseen data. Our proposed hybrid approach solves the complex problem
of classifying semi-natural language data. This approach can be used
to create a domain-specific set of rules, and classify any semi-natural
language data into multi-classes.

# Cite as:
Hussain, Z., Nurminen, J. K., Mikkonen, T. & Kowiel, M. “Combining Rule-Based System and Machine Learning to Classify Semi-natural language Data” Intelligent Systems and Applications, 2022. Springer, Cham (Lecture Notes in Networks and Systems (LNNS); vol. 542)
