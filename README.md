This challenge is divided by 9 sections: 

Before starting with the different sections, notice that two database was provided, so these two databases is combined together so we can have the school data complete DataFrame

District Summary

The district summary section allows us to get the difference result like the total budget for the schools, count the school’s name by unique value, count the total number of schools, having the average score for math and reading, having the average of student who pass the math and reading and then create a summary DataFrame for this section.

School Summary

In this part, base on the provided data  get the type by considering the of the school and the name as well, then provide the number of student per school, the budget for each school, the per capita per school, the average score for math and reading, a overall result per school where math and reading score is 70 or higher, provide and display in our table  the result for passing and math score combine. Provide a table for the passing rate for all school, then display a DataFrame to summarize the result for this section
Highest-Performing Schools (by % Overall Passing)

We were asking in this section to display a table that sort the schools by the highest score 

Bottom Performing Schools (By % Overall Passing)

Is this section we were asking to display to sort by the bottom performance passing rate

Math Scores by Grade

In this math section we have to provide a separate data by the different grade, get the mean per schools and select only the math score, then create a DataFrame that will display the result by math score by grade 

Reading Score by Grade

In this section we were asking to repeat the same process of the math score, but for the reading score and display the reading score by grade

Scores by School Spending

In this section we were asking to establish a bin where we are going to display a DataFrame base on school spending, but before we copy the summary per school DataFrame, then using the pd.cut function to categorize the result,  group by the average score per student, and create a new DataFrame call spending summary to display the data.

Scores by School Size

In this section we will use the same process above, but consider the score by school size as index to have display the DataFrame considering the school size by small, Medium and large 

Scores by School Type

In this section we created a group by to get the score by type of school, the create a DataFrame to display the average math, average reading, passing math, passing reading and overall passing per school

conclusion

base on the result of the Dataframe the type summary, we constate that the Charter school have a better results than the District school.
