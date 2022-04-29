# THA: Web Interface + API application

## General instructions

We want you to create a great structure and scalable project for maintenance that respects the tests scenarios and business rules.

We also want you to write a great README file in English. We want to understand what the project is made for, how we run it and also the structure decisions you made. Think of it as a file that another software engineer will read before continuing the piece of art you created.


💡 **IMPORTANT**: you can choose any technology stack to implement this assignment. Using our stack is not a requirement in the selection process - we will consider exclusively the quality of your project (technology and product-wise) to evaluate your work.


## The challenge!

Origin is a platform that helps employees put their financial lives on track. It's been helping thousands of users to understand theirs expends and how they can better plan their future.

In order to do that, users should register information regarding their financial situation in our app. Two key pieces of information are his **annual gross income** and **average monthly costs**.

## Development Instructions

### Evaluation

Be aware that Origin will mainly take into consideration the following evaluation criteria:

- How close your page is to the mockups, both on mobile & desktop;
- How clean and organized your code is. We are looking for clear separation of back-end and front-end;
- How good your automated tests are, i.e.: qualitative over quantitative;
- If you implemented the business rules correctly.

You can use third-party libraries in case you want to.

### Business rules

Based on that information, the system should calculate a score to represent how healthy his financial life is, meaning:

- At the end of the year, the user has to pay 8% x over his annual gross income.
- If the user annual costs represents less than or is equal to 25% of his annual net compensation, his score is HEALTHY;
- If the user annual costs is greater than 25% and less than or equal 75% of his annual net compensation, his score is MEDIUM;
- If the user annual costs is greater than 75% of his annual net compensation, his score is LOW;

E.g

```
Annual Income = 1000 && Monthly Costs = 10 = HEALTHY

Annual Income = 1000 && Monthly Costs = 30 = MEDIUM

Annual Income = 1000 && Monthly Costs = 80 = LOW
```

### Presentation rules

You should create a form where the user will be able to inform his annual gross income and average monthly costs. When submitting the information, the user will be presented his financial wellness score.


🧑‍🎨 You should follow this [Figma File](https://www.figma.com/file/eysSLDJFaEgGRWqHTFVehu/Take-Home-Assignment-v3?node-id=0%3A1) for building your screens


The form should validate:

- annual income is greater than zero;
- monthly costs are greater than zero;
- inputs should allow only numbers;
- inputs are required.

## Delivery Instructions

You can share your project via Github or send a package to us. If using Github, please, make sure we can access it by making it public.