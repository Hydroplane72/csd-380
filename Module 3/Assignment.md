Research “Version Control Guidelines” and write a paper on your findings. Consider the following as you research the topic:

Use at least three (3) sources for your paper. You may include your textbook, but consider that it was published in 2021.
Compare and contrast the guidelines among the three. Did you find any guidelines that are not relevant today?
Create your own list of what you consider to be the most important guidelines. Why did you select these?

# Source 1:
Name: Git - Tree Hisotry Storage Tool
Website: https://web.archive.org/web/20050811025905/http://git.or.cz/
Article Age: August 11, 2005

# Source 2:
Name: About Git
Website: https://docs.github.com/en/get-started/using-git/about-git
Article Age: Year of 2026

# Source 3:
Name: Mastering Git Versioning: The Most Reliable Strategies for Efficient Code Management
Website: https://codecarbon.com/mastering-git-versioning-the-most-reliable-strategies-for-efficient-code-management
Article Age: September 23, 2024

# Comparison of Guidelines:
To start with, I intentionally used a 20-year-old article to compare the guidelines from the early days of Git to the modern guidelines. 

The first source, the oldest, focuses on Git's technical aspects and how it works as a version control system. It emphasizes the importance of understanding Git's underlying structure and how it manages code changes. 

The second source is much more recent and focuses on the practical aspects of using Git in a collaborative environment. It also doesn't go into the technical details of how Git works; instead, it focuses on best practices for using Git effectively in a team setting. In addition, it provides examples of how to use Git commands and workflows.

The third source is older than the second one. It focuses more on best practices for using Git in a professional setting. It emphasizes things like commit messages, Branching strategies, automation, and code reviews.

# Guidelines in Article 1 not relevant today:
Given that the first article is 20 years old, a few guidelines are no longer relevant today. The most notable one I noticed first is the recommendation to use Cogito and StGIT to manage Git repositories. Both of these are tools I had never heard of before this article. Additionally, since I have to use the Wayback Machine to access the article, it is clear that it is not as relevant today as it was when it was published.

# My List of Important Guidelines:
1. Let AI write the commit message: In general, this is a great idea. AI generally does a good job summarizing the changes made in a commit, saving developers a lot of time. I have noticed that sometimes AI can be wrong; other times, though, it has spotted changes I forgot about and needed to undo.

2. Use Branches: When working with others, using branches is essential for keeping the codebase organized and avoiding conflicts. It also allows us to work on new features or bug fixes without affecting the main codebase until we are ready to merge.

3. Only create a pull request when the code is ready to be reviewed: This is important because it helps to ensure that the code being reviewed is of high quality and is ready for production. It also helps to avoid wasting time on reviewing code that is not yet complete or may have significant issues.

4. Set up CI/CD pipelines: Set up simple CI/CD pipelines to automate build, testing, and deployment processes. Don't overcomplicate it, but having some level of automation can help catch issues early and ensure code is always deployable.