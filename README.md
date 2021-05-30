# stock-analysis
Module 2 Challenge

## Overview of Project:
  ### Stock market analysis with code refactoring
  For this challenge, I refactored the original script to help Steve provide stock analysis for thousands of data using looping and conditional statements. Refactoring the code also improved the performance and speed of the code execution.
  
## Results:
  Total numbers of rows are the same for 2017 and 2018 dataset. However, there is a slight difference of speed performance which is shown on figure 1 for 2017 and figure 2 for 2018. There are also more positive returns under 2017 dataset compared to 2018 dataset.
  
  In addition, the refactored script had a faster execution time against the original script, which can be seen in figure 3 and 4. This is due to the use of variant arrays for three output columns which are being called inside nested loops shown in figure 5. In this way, three output arrays will be looped through the same function.
  
  ![Figure 1](https://user-images.githubusercontent.com/83877498/120116363-ce276000-c155-11eb-8807-9dff2fdfe1b0.png)
  
  **Figure 1:** Stock Analysis of 2017 dataset with execution time of the original script
  
  ![Figure 2](https://user-images.githubusercontent.com/83877498/120116417-0b8bed80-c156-11eb-9fce-4b7193249420.png)
  
  **Figure 2:** Stock Analysis of 2018 dataset with execution time of the original script
  
  ![Figure 3](https://user-images.githubusercontent.com/83877498/120116440-252d3500-c156-11eb-8281-43f064aed941.png)
  
  **Figure 3:** Stock Analysis of 2017 dataset with execution time of the refactored script
  
  ![Figure 4](https://user-images.githubusercontent.com/83877498/120116457-38d89b80-c156-11eb-9c4a-587b4fa1abc3.png)
  
  **Figure 4:** Stock Analysis of 2018 dataset with execution time of the refactored script
  
  ![Figure 5](https://user-images.githubusercontent.com/83877498/120116468-4f7ef280-c156-11eb-8d34-5bfa00b8edc0.png)
  
  **Figure 5:** Three output arrays under nested loops from refactored script
  
 ## Summary:
  ### Advantages and disadvantages of refactoring code
     - One of the advantages of refactoring code is to improve the performance of a script which we have completed on this challenge. 
     - Also, it will make the code more efficient, maintainable and eliminate repeated function. 
     - However, some disadvantages of refactoring are the amount of time it takes, errors, and it may also lead to logic confusion.
  
  ### Pros and cons apply to refactoring the original VBA script
     - For pros, refactored script is easier to understand and it can effortlessly find the bugs.
     - Cons are that it may create additional errors and can change the logic or output of the original script.
  
  





