We have to calcualte the number of lines changed in order to calculate the maintenance effort. Since we use `git` for all the projects, we can use the different git commands in order to compute the number of lines changed.

We have created a ruby script that can generate the number of lines changed between two versions of the project from the git. The script is attached in this directory.

In the script, we just have to change the version numbers according to the project and run this script inside the project and we get the analysis on number of lines changed with resepct to all the contrinutors and the analysis can also be exported as a csv which we can use it for later analysis in Microsoft Excel.

We calculated the final results for the metric using Microsoft Excel. We already have the CSV files for all the project versions which we can use it excel and apply the formula for the effort mentioned in the report.