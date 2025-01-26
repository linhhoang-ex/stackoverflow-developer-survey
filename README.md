# Project Motivation
In May 2024, over 65,000 developers responded to an annual survey conducted by Stack Overflow about coding, the technologies and tools they use and want to learn, AI, and developer experience at work.

This project analyze data from this survey to answer the following three questions:
1. What are the most popular programming, scripting and markup languages used by professional developers?
2. What is the most popular operating system for developers?
3. What are the top paying technologies for professional developers?

# Installation
- You should install `numpy`, `pandas`, and `matplotlib` packages to run the code in `main.ipynb`.
- The data used for analysis is from [Stack Overflow's 2024 Developer Survey](https://survey.stackoverflow.co/) with more than 65K responses. You should download the dataset and put it in to the same folder before running the code.

# File Description
- `main.ipynb`: the notebook contains all codes for data wrangling and plotting
- `img/`: folder containing all visualizations of data analysis

# Results
Following are some findings from the data:

1. JavaScript is the most popular language for professional developers, followed by SQL, HTML/CSS, Python, and Typescript. For those learning to code, the three most popular languages are HTML/CSS, JavaScript, and Python, respectively.

2. Windows is the most popular operating system for professional developers, across both personal and professional use, followed by MacOS and Ubuntu.

3. The highest reported median salary is for professional developers with the following programming languages: Scala, Objective-C, F#, Clojure, and Erlang. Among those, PHP, GDScript, Visual Basic (.NET), Ada, and Prolog are reported to have the lowest median salary.

More discussion about these findings can be found in [this blog post](https://medium.com/@linhht.419/insights-from-stack-overflows-2024-annual-developer-survey-328d85289488) on Medium.

# Acknowledgement
You can check more insights drawn from the survey from [this official documentation](https://survey.stackoverflow.co/2024/) on Stack Overflow.
