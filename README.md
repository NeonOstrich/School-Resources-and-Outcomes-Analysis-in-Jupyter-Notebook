# School Resources and Outcomes Analysis

This is an assignment that I completed for the George Washington University Data Analytics Bootcamp, focused on analysis in Python using Jupyter Notebook and displaying my understanding of Pandas.


## Organization

Within this repository you will find this "README.md" file which provides an explanation of my analysis. You will also find the
folder, "PyCitySchools" which contains my Python code in a Jupyter Notebook file, as well as a "Resources" folder. The "Resources"
folder contains two documents "schools_complete.csv" and "students_complete.csv" which are used in this analysis.


## Background

Using Pandas and Jupyter Notebook, we have created a report that includes the Student and School data together in order to 
gain insights into how student scores relate to a variety of school level factors:

District Summary which summarizes key metrics about each district.

School Summary which summarizes key metrics about each school.

Highest-Performing Schools (by % Overall Passing)

Lowest-Performing Schools (by % Overall Passing)

Math Scores by Grade

Reading Scores by Grade

Scores by School Spending

Scores by School Size

Scores by School Type

<img width="1082" alt="Screen Shot 2023-03-16 at 12 35 39 PM" src="https://user-images.githubusercontent.com/119632669/225691493-1c7bb5fe-2f19-4c66-a15f-e3d01d3df893.png">

<img width="1144" alt="Screen Shot 2023-03-16 at 12 39 50 PM" src="https://user-images.githubusercontent.com/119632669/225691574-0762d1cf-bfcd-4c06-8e4d-0837d89fe0f6.png">
## Insights

One meaningful insight that can be observed in this data is that "Large Schools" (2000-5000 students) performed noticably more
poorly in Math Pass Rate (69.96%) than smaller schools (93.60%) and (93.55%). And there is a similar, though less pronounced
decrease in Reading Pass Rate for "Large Schools"(82.77%) compared to smaller schools (96.79%) and (96.10%). Together, these
disparities were amplified in the Overall Pass Rate to produce 58.28% for Large Schools and 90.62% and 89.88 for smaller schools.
This suggests that students in schools over 2000 students have a disadvantage compared to their peers in smaller institutions.

A second meaningful insight is that the lowest performing schools generally spent more per student than the highest performing
schools. This suggests that increased funding does not necessarily lead to higher academic performance, and suggests that
additional research should be done into the differential allocation of funds between schools with high and low performance.

One other very notable insight, was that Charter Schools performed consistently higher across all metrics compared to District
Schools with the most pronounced difference in Math Pass Rate with 66.55% for District Schools and 93.62% for Charter Schools,
and in Overall Pass Rate with 53.67% for District Schools and 90.43% for Charter Schools. This difference could be related to
differing sizes of these two types of schools, different allocations of funding, or the practice of some Charter Schools to 
recruit high-performing students, but would require additional research to confirm.

