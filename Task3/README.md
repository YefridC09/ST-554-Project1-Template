Each group member should provide feedback on the other group members’ work. Be detailed and specific where possible. The quality of this feedback can play a part in your grade.

You can provide feedback to your group members in many different ways (live in a meeting, offline, or however else you devise) but the feedback must be documented here! 

Please replace “Feedback giver #x” with a group member’s name below and add feedback as a bulleted list below. Note: There is a pencil icon on the top right of the README file (when you are viewing the README.md file) that allows you to edit.

- Stephen Griggs
  * This looks really solid. Great job at implemented the logic for the sequential time series forecasting.
  * You correctly fetched the data and successfully created the chained filters to remove the `-200` values for `C6H6(GT)`, `CO(GT)`, `T`, `RH`, and `AH`.
  * Your approach to converting `Date` to a `pd.datetime` object and using `.groupby().mean()` successfully collapsed the data down to the required 347 rows.
  * In your `MSE2` function, using `X.iloc[:Day]` for the training set and `X.iloc[Day]` for the testing set captures the $250$ training rows and tests on the $251^{st}$ row. 
  * In `CV_error`, using `len(Y)` instead of hardcoding the final day conviently itterates over all the days except the last one.
  * Thank you for specifying the the MLR model. Maybe add the SLR model spec too.
  * I like that you've you've used type hinting and function annotations for your work.
  * In your MSE2 function, yout used reshape(1, -1) if X_test has the type `pd.Series`. The code `X.iloc[Day]` returns a Series but you can simplify your code with `X.iloc[[Day]]`. This returns a one-row DataFrame so you can drop the if/else statement and pass X_test directly into .predict().
  * I would consider spacing out some of the code in `MSE2` and putting the comments above so it's a little easier to read.


- Feedback giver #2
  + item
