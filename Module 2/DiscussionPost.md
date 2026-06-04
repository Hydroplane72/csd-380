# Technical Debt
## What is technical debt?
The article Techopedia has a great definition of technical debt that I would be hard pressed to improve upon:

    "Technical debt is a concept in programming that reflects the extra work required when developers choose an easy short-term solution over the best long-term approach. Like financial debt, it incurs interest in the form of increased maintenance costs and complexity over time."

In short, tech debt is the result of taking shortcuts in software development that may save time in the short term but can (and more often than not always do) lead to more work and complications in the future.

The second article by IBM talks about how technical debt can be intentional or unintentional. To be honest though, in the end, in my experience, it doesn't matter if the technical debt was intentional or unintentional, it still has to be dealt with and can cause the same issues regardless of how it came to be.

## What is an advantage of technical debt?
The main advantage of technical debt is that it can allow developers to quickly implement features or fixes when time is of the essence. For example, if a critical bug needs to be fixed immediately, a developer might choose to implement a quick and dirty solution that resolves the issue in the short term, even if it is not the most elegant or maintainable solution. This can help to meet deadlines and keep projects moving forward.

## What is a disadvantage of technical debt?
The main disadvantage of technical debt is that it does not go away on its own and will require additional work to address in the future. If technical debt is not managed properly, it can accumulate and lead to a codebase that is difficult to maintain, understand, and extend. 

## Example of technical debt
I have a perfect example of technical debt from the main project I work on. When they first introduced a new feature to the program to allow representatives the ability to save health care provider information to be able to use in the future. They implemented this feature so the data was saved locally on the user's machine. When they later created the web version of the program, they had to rewrite this feature to save the data to an online database as well. The biggest issue, is that they never went back and updated the original local saving feature to match the new online saving feature. Meaning the desktop version of the program still has the old local save of data that was kept entirely seperate from the new online saving feature.

Over the past month, I have been working on a project to update the desktop and web versions of the program to use the same saving method, which is to save the data to an online database. It has been a lot of work to go back and update the desktop version and web version to use the same method of saving this data. There were other features added while we did this update that caused issues with the initial roll out. This is a perfect example of technical debt, where the initial decision to implement the feature in a quick and easy way (saving data locally) led to more work and complications down the line when we had to update both versions of the program to use the same saving method.


## Articles:

What is Technical Debt? - Definition from Techopedia. (n.d.). Techopedia.com. https://www.techopedia.com/definition/27913/technical-debt

‌IBM. (2025, March 27). Technical debt. Ibm.com. https://www.ibm.com/think/topics/technical-debt

‌