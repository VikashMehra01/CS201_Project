# Team Members
Sarvan Suthar - 2023CSB1159
Vikash Kumar - 2023CSB1172
Sumit Singh Bais - 2023CSB1166

# Mentoring Teaching Assistant
Deepu Yadav

# Finding best Recruiter as a part of CS201(DSA) project.

# Project Summary
In our project, implemented entirely in C++ we used the data structure known as Trie and Max Heap.
The main reason of using C++ is to access unordered_map, which has search time Complexity of O(1).
In our Project Trie works to filter the Recruiter based on location,Industry and Experience Year,unordered_map helpful for storing Recruiter Experience Year and location wise.
And use of Max Heap to sort suitable Recruiter expected salary wise baseed on the matching percentage.


# Recruiter.txt contain the some Recruiter's detail like(Name,location,required experience year,Lower bound of offered salary,Upper bound of offered salary and required skill based on level).
So this file is needed to run the code.

# Input of the code is :- Candidate detail (such as :-Desired Industry,Location{if we want to give priority to some location},Experience Year and Skills level wise).

# Input we Tried :-
            1. Desired_Industry : Soft       (This will give result of both software     and softskill domain).

            2. location : no                  (No priority for location).

            3.Experience Year : 5

            4. Skills (level wise) : -
                        I. english : 10
                        II. japanese : 9
                        III. cpp : 9
                        IV. python : 8
                        V. java : 10

            5. Skill : q (To exit the loop of Giving Skills).

# Output we Get :- 

Expected Salary (in lpa): 50.0556 for sarvan in ropar with 5 years of experience.
Expected Salary (in lpa): 15.3333 for bob in sanfrancisco with 5 years of experience.
