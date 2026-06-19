Read the case study presented in Chapter 13 of the course text and compose a brief summary of the main points the author made as well as the lessons learned.
# Blackboard Inc Case Study

## Main Points:

Blackboard Inc. had a major issue with Technical Debt. They had a Legacy J2EE codebase that was created in 1997. Over time, they noticed that the codebase was becoming increasingly difficult to maintain and scale. To measure the extent of the technical debt, they compared the amount of lines of code in the repository compared to the number of code commits being made. They found that as the lines of code increased, the number of commits decreased, which to them was an indication that the codebase was becoming more difficult to work with. 

At the same time they were dealing with a couple of issues that clued them into the fact that they had a technical debt problem. 
- Build , integration, and deployment processes were slow and growing more error-prone.
- Lead time for new features was increasing
- The outcome of changes was becoming worse for the customers
- Feedback took over 24 hours to reach the development team

## Lessons Learned:
- To fix this they did a dedicated effort to refactor the codebase and reduce technical debt. 
- They created "Building Blocks" which were reusable components that could be used across different parts of the application. This helped to reduce the amount of code and make it easier to maintain.
- Using Building Blocks allowed developers to focus on what they needed to accomplish rather than worrying about coupling with other parts of the codebase. This helped to improve the speed of development and reduce the likelihood of introducing new bugs.
- The Feedback loop timeline was improved
- Developers were able to write code faster and more confidently
- The overall quality of the codebase improved, which led to better outcomes for customers.