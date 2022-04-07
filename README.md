# Bikesharing
  An analysis of NYC CitiBike bikesharing data from August, 2019, with Tableau
This Tableau story can be seen, in its entirety, [at this link](https://public.tableau.com/views/NYCCitiBikeAnalysischallenge_16492957034750/CustomerDescription?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
#overview
  The framework for this project was to analyze bikeshare data from CitiBike in New York City for presentation to investors looking to begin a bikeshare program in Des Moines, Iowa. While Des Moines is a long way away from the hustle and bustle of NYC, this analysis might help answer a few key questions:

  . Who uses bikeshare programs?
  . What area of a city sees the most bikeshare usage?
  . What time of day are bikes used the most and the least?
  . How much are the bikes used and by whom?
# Results
    While the demographics of Des Moines may be different from the make up of the citizenry of NYC, a cursory look at the makeup of CitiBike riders may shine light on who bikeshare might appeal to, regardless of locale.
    <img width="540" alt="nycCB_cust_descrip" src="https://user-images.githubusercontent.com/96033992/162105239-a8843288-e777-4e70-8ee2-542c0affe534.png">
    In the above image we can see that more than 3/4 of the users are Subscribers, who make regular use of the bikes and are a predictable source of income for the program. Bikeshare program users are also predominantly male, at approximately 5/8 to only about 1/4 female. The remaining 1/8 gender is unknown or undeclared.
    <img width="797" alt="nycCB_start_loc" src="https://user-images.githubusercontent.com/96033992/162105298-6391f267-7bda-4129-9a6d-15b277816f6a.png">
    The above map displays the bike stations from which recorded bike trips started. The size of the circles and darkness of the green indicate the relative number of trips started at those locations. It is apparent that the bulk of the bike trips are originating in the bustling commercial heart of Lower Manhattan, known for towering office buildings, densely packed residential skyscrapers, and entertainment venues. Bike usage is lower in the less densely packed surrounding neighborhoods.
    <img width="880" alt="nycCB_repair_time" src="https://user-images.githubusercontent.com/96033992/162105415-2faaeb99-0e80-4545-be60-2d9d4cb9da7d.png">
    This chart displays the number of bike rides initiated during each hour of the day, totaled across the entire month of August. We can see peak usage during morning rush hour and end-of-workday commute times. What is also of note is the low-usage hours between 2 AM and 5 AM. These hours would be the best times to conduct bike repairs and redistribution of bikes from full stations to less-full stations.
    <img width="521" alt="nycCB_peak_use_hours" src="https://user-images.githubusercontent.com/96033992/162105478-79b9c579-5442-4026-a746-c67b943bf186.png">
    A heatmap also helps show weekly usage patterns. Once again we can see the heavy bike usage during weekday commute times, and weekend usage is spread throughout the middle of the day. An interesting anomaly is the relatively low bike usage during Wednesday's end-of-day commute. It could be useful to explore reasons for this (system outage, Wednesday holidays in August, something less obvious?), but it could just be an arbitrary anomaly. Also, we can still see that low-usage time in the early morning hours, every day of the week.
# Summary
    In conclusion, bikeshare services are remarkably popular in busy metropolitan areas, where occupied real estate is densely packed and parking spaces may be scarce. The user base is made up mostly of male subscribers, providing regular income to the program. More outreach should be done to attract female riders, but male users seem a reliable market. And main usage seems focused around morning and evening commute times.

If I were to pursue additional lines of inquiry for analysis and visualization, given the data provided, I would explore:

  . trip starting and ending locations during morning and evening rush hour time-windows, to display the flow of traffic between neighborhoods at peak hours;
  . average trip duration, by birth year, by gender, to explore if there was any difference in male or female or un-gendered riders as they age.
