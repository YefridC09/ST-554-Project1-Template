Each group member should provide feedback on the other group members’ work. Be detailed and specific where possible. The quality of this feedback can play a part in your grade.

You can provide feedback to your group members in many different ways (live in a meeting, offline, or however else you devise) but the feedback must be documented here! 

Please replace “Feedback giver #x” with a group member’s name below and add feedback as a bulleted list below. Note: There is a pencil icon on the top right of the README file (when you are viewing the README.md file) that allows you to edit.

- Stephen Griggs
* You're most of the way there just don't forget some things!
    * Commentary on the correlation tables before the final draft.
    * Grouped numeric summaries of `C6H6` at different levels/combinations of other variables. You have the plots but the only summaries are counts.
* I would consider printing the metadata keys/attribute names to keep the notebook clean without dumping the full metadata.
* Maybe provide more interpretation on the benzene plots.
* Everything else is very strong:
* Clearly explains data origins, research questions ("electronic noses" vs. ground truth), and provides a great high-level metadata summary.
* Renaming variables is a good idea (I skipped that entirely), and counting missing values before dropping them helps reproducibility.
* Nice catch noting the massive difference in scale between the electronic sensors and the ground truth measurements.
* Starting with high-level numerical summaries sets a baseline before diving into the outcome variable.
* Effective `C6H6` Visualizations:
    * Using both distribution and temporal views is needed for interpreting time-series data
    * Averaging concentration by `Month` successfully turned an unreadable, noisy plot into something readable
    * Exploring benzene ranges by temperature with different histogram bin cutoffs showed two perspectives of the same question


- Yefrid Cordoba
  + Great job Eleanor, renaming the columns was very helpful at the begining of the document, it was easy to follow what you did.
  + I think it would be important to consider reporting the amount of data that was lost during the cleainig of missing values.
  + The relation that you want to make between temperature and benzene concentration is important, to add more weight to that part I would consider important to show the temperature over time on the same graph with benzene concentration (daily might look good, or monthly), ploting temperature on a secondary y-axis.
  + Adding a little more description of the correlations between the nose sensor readings for other gases againts benzene concentration (which are the ones that correlate better with the variable of interest). 
