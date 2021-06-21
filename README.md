# Overview of analysis
- The purpose of this analysis was to determine the temperature trends for the months of June and December to see if the weather would allow a surf shop to be economically viable all year. Furthermore, this module as a whole was used to instruct the student how to use SQL data through Python, how to clean and untangle messy data, and how to build apps using Flask.


## Results

- The descriptive statistics for June and December are presented respectively:

june_temps.png
![](data:image/png;base64,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)
