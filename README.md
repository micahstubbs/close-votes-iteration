#Close Votes Iteration

An iteration on Jan Willem Tulp's [Close Votes](http://tulpinteractive.com/projects/close-votes/) project. 

This iteration is a step towards a reusable chart I hope to generalize from this [d3js](http://d3js.org/) project.

See Jan Willem's original code at this [block](http://bl.ocks.org/micahstubbs/c248e13bf367f56baf84) and this [gist](https://gist.github.com/micahstubbs/c248e13bf367f56baf84). 

####changes

+ translated some filenames and variable names from Dutch to English
+ formatted results.json for human-readibility
+ replaced some short variable names with long-form descriptive names
+ removed unused keys `"kg"`, `"ong"`, `"prov"`, from `results.json`
+ added data-driven city-selection drop-down menu to replace hard-coded html `<select></select>` and `<option></option>` elements

####planned

+ identify meaning of `"opk"` key in `results.json`
+ verify that the values in the `"chi"` array in `results.json` are [chi-squared test](http://stattrek.com/chi-square-test/independence.aspx) values calculated from `percentVote` values from the current city compared against the `percentVote` values from each other city in the dataset.



