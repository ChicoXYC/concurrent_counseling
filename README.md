# Appendix A. Source code for analysis
 
This appendix contains three codebooks that were used for data manipulation and analysis. Each codebook was summarized and outlined in this document and the corresponding codebook.

Note: ipynb is the file extension for Jupyter Notebooks. You can open ipynb files with Microsoft Visual Studio Code. You can download Microsoft Visual Studio Code here: https://code.visualstudio.com/

Codebook 1 - attention_score_calculation.ipynb 

This code codebook was used to calculate the attention score for each session
Input: aggregated data with metadata of conversations from the system
Output: dataset with attention score

Codebook 2 – concurrent_outcome.ipynb

This code codebook serves multiple purposes:
- Join downstream outcomes from the post-session survey, premature departure table and attention score data
- Comparisons between non-concurrent sessions with concurrent sessions
- Comparisons within groups of concurrent sessions
- Explore optimal attention score on downstream outcomes

Codebook 3 – regression_analysis.ipynb

This code codebook serves multiple purposes:
- Join counselors' role and login time and calculate their accumulative hours on duty when handling that particular session
- Exclude outliers with missing login time
- Regression analysis on attention score, counselor's roles, counselor's accumulative hours on duty, users’ visiting hours and downstream outcomes