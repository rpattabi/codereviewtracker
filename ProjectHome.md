# Code Review Tracker #

Code Review Tracker is a small application which scraps the code review related data from bug tracking systems, and provides a consolidated report for the usage of defect prevention analysis.

Currently Intergraph(R) JTS(R) is the only bug tracking system supported.

The reviewer should put the review comments in the following format (YAML)

```
	review_comment:
	 - my first comment
	 - my second comment
```