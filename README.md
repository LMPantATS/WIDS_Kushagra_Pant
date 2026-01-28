Exploratory Data Analysis (EDA) — WiDS Project

During WiDS, I finally started doing EDA the right way instead of just making random plots and calling it a day.

In the beginning, EDA for me mostly meant poking at single variables, checking distributions, hunting down missing values, and spotting weird data quirks. Pretty quick, I realized how easy it is to mess this up—like nuking half the dataset just because something looks “off” or spamming correlation matrices and pretending that means insight. One big shift was learning to not blindly trust correlations and to stop over-cleaning data just to make things look nice.

Outliers were a huge mindset change. My first instinct was to delete them because they were annoying. I almost removed a bunch of super high PM2.5 values before it clicked that these weren’t errors at all—they probably lined up with Diwali fireworks and stubble burning season. That honestly made me realize outliers can actually be the most interesting part of the data instead of something you sweep under the rug.

As things went on, I stopped doing EDA as a checklist and started actually asking real questions. Instead of just plotting everything against everything, I began looking at pairs that made sense and conditioning on context. Once I grouped things by month or season, the seasonality jumped out pretty clearly, and I could see how different pollutants kind of take turns being the main culprit behind AQI depending on the time of year.

The final AQI project was where all of this came together. I looked at why AQI behaves so differently in winter versus summer, compared extreme AQI days to normal ones, and tried to understand which pollutants really dominate during bad air days instead of assuming it’s always the same story. The goal wasn’t to build a fancy model—it was to slow down and squeeze some real insight out of the data before jumping ahead.

I used to plot stuff mainly to make it look presentable. Now I see EDA as the part where you actually think, question your assumptions, and poke around until something meaningful shows up. Still figuring a lot out, but I definitely feel like I got a lot better at this.
