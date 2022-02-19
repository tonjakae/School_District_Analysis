# School District Analysis using Python and Anaconda
Module 4 - Data Analytics Bootcamp
# What You're Creating
This new assignment consists of two technical analysis deliverables and a written report to present your results. You will submit the following:

* Deliverable 1: Replace ninth-grade reading and math scores
* Deliverable 2: Repeat the school district analysis
* Deliverable 3: A written report for the school district analysis (README.md)

# Deliverable 1: Replace Ninth-Grade Reading and Math Scores
Using the Pandas loc method with conditional statements and comparison and logical operators, select the ninth-grade reading and math scores for Thomas High School. Then, use the Pandas NumPy module to change the reading and math scores to NaN.
![image](https://user-images.githubusercontent.com/87340105/154779672-41c997fa-ebb1-4286-95cb-222ce30aa74c.png)

# Deliverable 2: Repeat the School District Analysis
![image](https://user-images.githubusercontent.com/87340105/154779802-f0f1bc82-cc23-4635-b7a5-c0dadee1ef76.png)
![image](https://user-images.githubusercontent.com/87340105/154779790-686af2b0-6098-4077-835c-3a3daebd4633.png)
![image](https://user-images.githubusercontent.com/87340105/154779833-fab14364-e4dd-4f07-b6cc-b8e612cba774.png)
![image](https://user-images.githubusercontent.com/87340105/154779845-ba89270d-cfa1-4896-9f51-116d086b6aa2.png)
![image](https://user-images.githubusercontent.com/87340105/154779858-2632cf12-3ed9-45c6-98a0-c581d823cf6c.png)
![image](https://user-images.githubusercontent.com/87340105/154779879-130014a8-efdb-4edc-9174-807612cacc6a.png)
![image](https://user-images.githubusercontent.com/87340105/154779908-a912dca6-bd55-4f20-b64f-82c626702623.png)
![image](https://user-images.githubusercontent.com/87340105/154779922-000468e2-75c0-4e16-8121-00c41170ba72.png)
![image](https://user-images.githubusercontent.com/87340105/154779943-d0009281-aa63-4f18-a5c5-6785a72ba649.png)
![image](https://user-images.githubusercontent.com/87340105/154779956-9545e661-6de0-49c5-9642-63bbfdc45f2f.png)
![image](https://user-images.githubusercontent.com/87340105/154779970-7b856ae1-eab3-4931-a317-fa21eb3f88d2.png)
![image](https://user-images.githubusercontent.com/87340105/154779984-a4474666-530f-4e15-8be4-00f202fa134d.png)
![image](https://user-images.githubusercontent.com/87340105/154780006-eaac3d8c-f4d9-4f04-a654-433f02a2d121.png)
![image](https://user-images.githubusercontent.com/87340105/154780021-5b004663-1fe2-488b-bdac-7647dc2a8c6e.png)
![image](https://user-images.githubusercontent.com/87340105/154782247-3963a62c-fc4a-4ffe-9371-dafb9c71af10.png)
![image](https://user-images.githubusercontent.com/87340105/154782275-ebc42502-fd5f-4441-85c9-105c5c84bd2b.png)
![image](https://user-images.githubusercontent.com/87340105/154780134-d435664e-3fe1-49de-8f01-f10918cd0730.png)
![image](https://user-images.githubusercontent.com/87340105/154780157-b5b22cb7-6003-400e-bc3a-f98d7d08f329.png)
![image](https://user-images.githubusercontent.com/87340105/154780170-ba0f2ed8-e71a-4f34-ab71-8a55d4aabae8.png)
![image](https://user-images.githubusercontent.com/87340105/154780181-9a6d8fd7-2dfe-4c88-94b4-19d3f129933a.png)
![image](https://user-images.githubusercontent.com/87340105/154780192-668eb22e-874e-4502-bec7-86e739b83eab.png)
![image](https://user-images.githubusercontent.com/87340105/154780219-a04151fc-a720-41bf-8f83-1bbb3be53b20.png)
![image](https://user-images.githubusercontent.com/87340105/154780228-e5c65828-1175-4ff1-9bf9-13185fcfaf73.png)

# Deliverable 3: A Written Report for the School District Analysis
# *Overview*
The school board has notified me that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to V. Isulaize for help. I've been asked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once I’ve replaced the math and reading scores, I will repeat the school district analysis and write up a report to describe how these changes affected the overall analysis.

# *Results*
## How is the district summary affected?
### Before scrubbed data:
* Average Math Score = 79.0
* Average Reading Score = 81.9
* % Passing Math 75
* % Passing Reading 86
* % Overall Passing 65

### After scrubbed data:
* Average Math Score = 78.9
* Average Reading Score = 81.9
* % Passing Math 74.8
* % Passing Reading 85.7
* % Overall Passing 64.9

### Key findings:
Average scores for both math and reading remained relatively flat with only a slight decrease in math. Percent of passing grades for both math and reading were again realatively flat and an overall passing percentage only dipped by one tenth of a percent.

## How is the school summary affected?

### Before scrubbed data:
The overall passing percentage for Thomas High School was at nearly 91%.

![image](https://user-images.githubusercontent.com/87340105/154782630-2944b6e0-6975-493c-884f-be7071a0d5dd.png)

### After scrubbed data:
The overall passing percentage for Thomas High School dropped to 65%

![image](https://user-images.githubusercontent.com/87340105/154782601-27956677-aaf5-4e37-b48e-2b82d57d14c9.png)

## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Removing the 9th grader' math and reading scores drastically reduced Thomas High School's academic performance when compared to the other school.

## How does replacing the ninth-grade scores affect the following:
* Math and reading scores by grade
* Scores by school spending
  * Scores by school size
  * Scores by school type
* Summary
