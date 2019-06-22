All the projects have to issues tracked in either Github or Jira.

We were able to export the desired report from either of the platforms.

We then calculated the defect density using the following formula.

`Defect Density = Defect count/size of the release(SLOC)`

•  Defect Count is the total number of post-release defects
•  SLOC are the total number of  source lines of code (in K)

We have attached the exported report we were able to fetch from the either of the platform along with this report in the data directory. Since this is an Arithmetic computation, we have used either Microsoft Excel and/or calculator in order to achieve the best results according the source data.

For github, they have public API on, `https://api.github.com/repos/<path-to-repository>/issues` to generate the report.
For Jira, they have their own user interface to generate the reports. For which the button can be found on the top right corner of the interface.