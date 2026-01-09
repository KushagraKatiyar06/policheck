# Welcome to PoliCheck!

here it is: https://kushagrakatiyar06.github.io/policheck/

## Created by: Ben Adelman, Kushagra Katiyar, Bayan Mahmoodi

### Rankings
We included a ranking table in order to show users what specific polling companies predicted the elections (2020,2024) the best. One could look at simply the aggregated error over the two elections as the measure of this however we felt a more meticiulous approach was needed. We created our own PoliCheck score for each polling provider to measure the true accuracy of each poll. The equation for the PoliScore is $(P =(\frac{1}{ER})0.75  + (\frac{S}{max(S_n)})0.25\)$. We chose this methodolgy in order to consider both the aggregated error as well as the number of polls that were taken by each company. The error is measured inversely meaning that a lower aggregated error (ideal) leads to a higher overall score. We weighted this category at 75% due to the philosophy that accuracy should be the #1 priority when it comes to polling. We also took into consideration the relative amount of polls conducted compared to the rest of the dataset at 25%. While not as important as total error, a larger amount of polls leads to more reliable and consistent polling average. Overall, the formula used to develop our score is dynamic and changes may be made in response to future data/events.




