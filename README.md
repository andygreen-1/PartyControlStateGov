# Relationship Between Party Control of State Government and Key Well-Being Metrics

This repository contains the code, final datasets, and source data files for an analysis that looks at the relationship between party control of state governments and a variety of well-being metrics at the state level.

I have used these data to create a variety of data visualizations exploring these relationships. These visualizations were published by the Georgetown Public Policy Review in a series of articles in early 2020. The links to those publications can be found [here](http://gppreview.com/2020/01/09/relationships-party-control-state-government-key-well-metrics/) and [here](http://gppreview.com/2020/02/21/growing-divide-red-states-vs-blue-states/). I am also using these data as part of an ongoing statistical analysis aimed at evaulating whether a causal relationship may exist between party control of state government and various well-being metrics.

You can find a brief summary of the files available in this repository below:

* PartyControlStateGovt.RMD: R Markdown file containing the code used to compile the datasets
* states_panel_data.csv: Panel data at the state level from 1992-2020. Includes data on which party controlled the governorship, the state house, and the state senate, as well as data on a variety of well-being metrics: median household income, poverty rate, uninsured rate, no high school diploma rate, bachelor's degree + rate, GDP per capita, and the unemployment rate.
* total_us_panel_data.csv: Panel data on the same well-being metrics for the total US
* trifectas_data.csv: Dataset where the unit of observation is a party's trifecta control of a state's government over a given period of time (e.g. Democrats' trifecta control of New Jersey from 2004-2009). Only trifectas lasting 4 years or longer are included. For each trifecta, the dataset contains the state's values on each of the well-being metrics discussed above in the first and last years of the trifecta (e.g. New Jersey's median household income in 2004 and 2009). Variables calculating the change in each metric in both absolute and percentage terms over the course of the trifecta are included. Additionally, these changes are compared to how the total US changed on these same metrics over the same period of time (e.g. New Jersey's median household income increased by \$9,502 from 2004 to 2009, while median household income increased by \$5,443 across the total US over that same period).
* Source_Data: Directory containing the source data files that were used in assembling the datasets discussed above. Information on where each dataset was downloaded from can be found in the .RMD file.
