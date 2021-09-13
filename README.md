# stock-analysis
# VBA Challenge 
## Overview of Project
### Purpose 
The purpose of this project is to help Steve research and analysis which green energy company would be best for his parents to invest in as his first clients. They are leaning towards DQ so, using VBA, we will determine if their plan to go with DQ is the right move. 
### Results
2017 and 2018 had wildly different results. 2017 was the more successful year with one tiny exception, TERP. Though TERP, while not in the green, does improve the next year. Unfortunately, we cannot say that about most of the tickers in 2018.  ENPH and RUN would be the two that should be investigated rather that DQ as the not only grew in Total Daily Value in a year but also grew in returns. 

![2017 png](https://user-images.githubusercontent.com/88864493/133023288-34aae532-7c66-4f65-a81a-9f8e9d95362a.jpg)
![2018 png](https://user-images.githubusercontent.com/88864493/133023292-15963431-f881-438c-bcf9-fc37dd5cf191.jpg)

Due to the refactor code being more efficient, the run time for both dropped as well. When using the original code, I got 0.578 for 2017 as a run time and 0.559 for 2018 as a run time. Using the refactored code I was able to shave off 0.039 for 2017 and 0.043 for 2018.

![VBA_Challenge_2017 png](https://user-images.githubusercontent.com/88864493/133023311-e76e4296-1297-443f-b723-93f0f3561cf6.jpg)
![VBA_Challenge_2018 png](https://user-images.githubusercontent.com/88864493/133023326-fd9aeb06-385c-4dd8-b3e5-f020e826900d.jpg)


## Summary
### What are the advantages or disadvantages of refactoring code?
The advantage of refactoring the code is that it combines all the separate codes we started with and now with that one code, you can do everything at the same time. As a society, we look for the most efficient ways to complete tasks. Refactoring the code allowed me to consolidate and organize what we needed all with the possible touch of a button.  A disadvantage is that it takes time to refactor the code to allow all working parts function to create output information. This can be an issue if something is time sensitive or even if the code breaks. Both require time you might not have. 

### How do these pros and cons apply to refactoring the original VBA script?
The pros and cons apply to the original script because they could be heavy factors in whether you choose to refactor or not. An example would be, if your code is reliable, refactoring might not be the way to go because you know the original code won’t break. But to counter that, if the original code buggy to begin with, it could resolve that. 
