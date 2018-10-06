# The Hiland Test

## Introduction
At LawSikho we are constantly creating, renovating and optimising code with a motivation to keep our audience growing and engaged. The work of a developer is therefore challenging, demanding and exciting at the same time. Because we believe in the importance of individual choices and because we want to match the Ethics and Practices of a new member with our existing members, our recruitment process is slightly more rigorous than many other companies.

## The Recruitment Process
This test is for the role of Lead Developer PHP at LawSikho. You have cleared the first round, we are confident you would like to work with us. This is the second round for technical assesment, it involves you build something for us and help us observe and appreciate your development experience till date. Success in this round will be followed by another round of technical assessment where our Technology Manager would talk to you about development best practices. A successful assessment thereafter will be followed by an interview with our Founders. And that's all.

## The Application (The Hiland Test) Outline
This application we ask you to build might come across to you as very simple, yet, it is hugely important to us. This in effect helps us to see a sample of code written by you and observe patterns of your thought process while writing it. We call building this application ‘The Hiland Test’, named affectionately after the place ‘Hiland Park’ in Kolkata from where we started our first office.

Take this not as a coding challenge, but as your opportunity to impress upon us your skills and experience. Try and use the variety of PHP language features and practices. Show us your understanding and mastery of OOP, SOLID principles, TDD as a professional software engineer.

### Requirements of the Test
The test requires you you to create a small command-line utility to help us determine the dates on which we need to pay salaries to our employees. You are free to use any open-source packages to accomplish the task. Remember, this is not to test your algorithmic skills, but your coding style.

### Assume
We handle our payroll in the following way:
1. All our employees get a fixed sum as a monthly base salary, they might also receive an additional sum called a monthly bonus.
2. The former part i.e. the base salary is to be paid on the last date of the month. If that day is a Saturday or a Sunday, payment must be made on the Friday before that last date.
3. The latter part i.e. the monthly bonus are paid for the previous month. The bonus is always paid on the 15th day of a month. If that day is a Saturday or a Sunday, the bonus must be paid on the immediately next Wednesday.
4. You need not account for public holidays.

### Input
One can use this utility in this following manner:

```bin/run filetype filename```

1. ```filename``` is optional. This is the name of the file that can be used to store the output.
2. ```filetype``` is optional. It can be either ```csv``` or ```pdf```

### Output
1. The output of the utility should either be a CSV or a PDF file according to the input arguments.
2. The file should contain the payment dates for the next twelve months starting next month.
3. The file should contain three columns: Month name, Base Salary date, Monthly Bonus date.

### Evaluation
1. Plagiarism is unacceptable.
2. Show-off your design pattern knowledge and technical skills.
3. Readability and organising the code is of prime importance.
4. Usage of latest versions would be appreciated.

### Questions
No questions will be entertained. This Readme file is conclusive.

### Submission
1. Please do not upload it to any publicly accessible VCS, forum, etc. It might give some applicants an unfair advantage over others.
2. You can keep a readme file in your working directory, if there are any notes or explanations about the code.
3. Zip the entire content and email it to tech@lawsikho.com. Subject line must contain in this format: "OOP_LS_YOURLASTNAME_DATE"
