# Dependency Scanning

## Article 1
Bottner, L., Hermann, A., Eppler, J., Thüm, T., & Kargl, F. (2023). Evaluation of Free and Open Source Tools for Automated Software Composition Analysis. https://doi.org/10.1145/3631204.3631862

## Article 2
https://docs.github.com/en/code-security/concepts/supply-chain-security/dependency-review

## What is it?
Dependency scanning is the process of reviewing your code dependencies to identify vulnerabilities. Generally, a 3rd-party package provider will find a vulnerability in their code. They will then fix the code and release a new version without the vulnerability. Depending on the provider and the severity of the issue, they may mark the old version as unsafe, unlist it, or wait until they have a new version with the fix before notifying users. What this then does is notify users on a vulnerable version to upgrade or stop using it when the scan runs.

## When should it be used?
Dependency scanning should be performed regularly across the entire company codebase. In reality, that is just a use of resources that will create noise and add more work to the backlog of many teams. Ideally, teams would receive an alert about a new vulnerability in their software and update it to the latest version as soon as possible.

To give you an example of why this is not really practical for most companies, I will share some very broad stats about the codebase for my work. The first thing to acknowledge is that programs have been added over the last 60 years there are thousands of programs that my work supports. Each has approximately 10-25 dependencies. Of those thousands of programs, about 100 are actually being actively worked on in a given month. The other 900+ apps are working just fine without us poking them. Even if it only took 30 minutes to update every project the company supports for just a single new vulnerability. You would still be looking at close to 8.5 hours straight of just upgrades. Also, that 30 minutes doesn't account for the fact that the company's entire codebase is over 5TB in size. That would be one massive hard drive you have or really fast internet to be constantly downloading and updating that code.

## Why should it be used?
Code scanning should be used to find critical and high-profile vulnerabilities. Updating a package because it has a Log4Shell dependency is different than upgrading just because the newest version was just released today. In other words, if it ain't broke, don't fix it (most of the time).

## What tools are available?
The most popular tool I know of is GitHub Dependency scanning. We have been transitioning to using it at work mainly because of its ability to automatically create pull requests with dependency updates to fix the issue.

Another one is Coverity. This is a tool we are getting away from at my work. In general, it is a good tool; the issue is that, in an enterprise environment, it is difficult to maintain the program and keep everything up to date. It also doesn't do great with Git repositories (granted, my work used custom stuff for ours, so that it could be different with newer versions).
https://www.blackduck.com/static-analysis-tools-sast/coverity.html