![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# LAB | Pandas
<details>
  <summary>
   <h2>Learning Goals</h2>
  </summary>

  This lab allows you to practice and apply the concepts and techniques taught in class. 

  Upon completion of this lab, you will be able to:
  
- Create pandas Series objects and retrieve their attributes, such as values and index.
- Access Series objects through their items() method and by using categorical or numerical indexes.
- Manipulate Series objects using various methods, including append, concat, pop, sort_values, sort_index, or value_counts.
- Create pandas DataFrame objects and retrieve their attributes, including index, values, columns or dtypes.
- Access data in DataFrames through columns (as a dictionary or attribute) and by using loc and iloc to access rows.
- Filter and select data in DataFrames using simple comparison and logical operators
- Use various methods to explore and summarize DataFrames, such as shape, head, tail, describe, info, nunique, max, min, and mean

  <br>
  <hr> 

</details>

<details>
  <summary>
   <h2>Prerequisites</h2>
  </summary>

Before this starting this lab, you should have learnt about:

- Data types, operators and structures
- Flow control (if-else statements and loops)
- Functions
 
  <br>
  <hr> 

</details>


## Introduction

Welcome to the Pandas Lab! In this lab, you will learn how to work with pandas series and dataframes, which are powerful tools for data manipulation and analysis in Python. Pandas allows you to create, manipulate, and analyze large, complex datasets with ease, making it a valuable library for any data scientist or analyst.

During this lab, you will learn how to create pandas series and dataframes, access their attributes and values, and manipulate them using a variety of built-in methods. You will also learn how to filter and sort data and summarize and describe data. By the end of this lab, you will have a strong foundation in working with pandas series and dataframes, which you can apply to real-world data analysis problems.

<br>

**Happy coding!** :heart:


## Requirements

- Fork this repo
- Clone it to your machine

## Getting Started

Complete the challenges in the `src` directory. Follow the instructions and add your code and explanations as necessary.

## Submission

- Upon completion, run the following commands:

```bash
git add .
git commit -m "Solved lab"
git push origin master
```

- Create a Pull Request so that your TAs can check your work.


## FAQs
<details>
  <summary>I am stuck in the exercise and don't know how to solve the problem or where to start.</summary>
  <br>

  If you are stuck in your code and don't know how to solve the problem or where to start, you should take a step back and try to form a clear question about the specific issue you are facing. This will help you narrow down the problem and come up with potential solutions.


  For example, is it a concept that you don't understand, or are you receiving an error message that you don't know how to fix? It is usually helpful to try to state the problem as clearly as possible, including any error messages you are receiving. This can help you communicate the issue to others and potentially get help from classmates or online resources. 


  Once you have a clear understanding of the problem, you will be able to start working toward the solution.

  [Back to top](#faqs)

</details>


<details>
  <summary>I am unable to push changes to the repository. What should I do?</summary>
  <br>

There are a couple of possible reasons why you may be unable to *push* changes to a Git repository:

1. **You have not committed your changes:** Before you can push your changes to the repository, you need to commit them using the `git commit` command. Make sure you have committed your changes and try pushing again. To do this, run the following terminal commands from the project folder:
  ```bash
  git add .
  git commit -m "Your commit message"
  git push
  ```
2. **You do not have permission to push to the repository:** If you have cloned the repository directly from the main Ironhack repository without making a *Fork* first, you do not have write access to the repository.
To check which remote repository you have cloned, run the following terminal command from the project folder:
  ```bash
  git remote -v
  ```
If the link shown is the same as the main Ironhack repository, you will need to fork the repository to your GitHub account first and then clone your fork to your local machine to be able to push the changes.

**Note**: You should make a copy of your local code to avoid losing it in the process.

  [Back to top](#faqs)

</details>

