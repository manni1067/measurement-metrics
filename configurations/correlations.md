We have gathered most of the data in form of csv. But there were still some data, we have had only in form of html reports which we then converted to csv using (http://convertcsv.com/html-table-to-csv.htm) tool.

We have used the Microsoft Excel for calculating all the correlations.

For calculating the Spearman correlation, we have to calcualte the rank from the data gathered. We have calculated the rank using `=RANK.AVG(B2,$B$2:$B$11,0)` function in Microsoft Excel. After calculating the rank, we can calculate the correlations by using `=CORREL(D2:D11, E2:E11)` formula.
In the formula `=CORREL(D2:D11, E2:E11)`, if we don't use the rank, the correlation becomes the Pearson coefficient.