# DORA Report

## Finding 1: Delivery Performance Metrics
### Description
The report discusses how quickly teams get changes into production, which tends to affect how often the project has issues. For instance, they correlated that teams that get changes to production within a day or two tend to have fewer issues than teams that take weeks or months to get changes to production. 

### My Opinion
This is a very interesting finding. If you talked to anyone straight off the street or an actual business user, they would say that the faster you can get changes to production, the more likely you are to have issues slip by. However, the faster you are forced to implement changes in production, the more likely you are to have a better process in place to ensure that the changes are tested and verified before they are released. Along with that, because you are forced to work quickly, your changes are more likely to be smaller and more manageable, and easier to test and verify. The use of feature flags and canary releases also helps mitigate the risk of issues slipping through.

### Forecast (Improve? Get Worse? Stay the Same?)
Companies that stick to a fast delivery cadence will continue to improve their processes and get better at getting changes to production quickly and safely. Companies that are slow to implement changes in production will continue to have issues, which will likely worsen over time. Along with that, I think companies that are slow to implement changes in production will likely have a harder time attracting and retaining talent, as developers want to work in an environment where they can get their changes to production quickly without having to jump through a lot of hoops. Companies that are slow to implement production changes will likely be forced to change their processes or risk going out of business. The use of AI to support testing and verification will likely help companies that are slow to deploy changes to production improve their processes and get changes to production more quickly and safely.

## Finding 2: AI Adoption
### Description
The article discusses how AI is being adopted in everyday life and how it is being used to improve efficiency. It also explains how the stigma of companies not allowing AI to be used in their processes is starting to change. 

### My Opinion
AI is a great tool for collaboration and can help make processes more efficient. However, AI is not yet a good replacement for the average developer. AI should be used to enhance developer productivity. For instance, AI can be used to help plan and design system architecture. It is not great at understanding and adhering to all the requirements and constraints of a system. There have been many times when I have seen AI generate code that is incorrect or fails to follow the requirements given to it.  

### Forecast (Improve? Get Worse? Stay the Same?)
Over time, AI will continue to get better. At some point, AI will be able to act like a full junior developer. At the same time, it isn't reliable enough yet. Some developers at my work have not touched an IDE in over 6 months now. All they do is use the GitHub Copilot App and prompt the AI to generate code for them. They then have AI review the code, create a PR, have other developers use their AIs to review the code, and then merge the code into production. I find this horrifying, but it is a glimpse into the future of software development. The difference that will keep software developers employed comes down to two things: first, the ability to read the generated code and understand what it does. Second, knowledge of requirements, constraints, and the current system, along with the current codebase, enables more accurate prompting of the AI to generate code that is correct and follows the requirements and constraints. In the future, I can see business users prompting AI to generate code for them. The issue is that they will not know the current system, codebase, requirements, and constraints to prompt the AI to generate code that will actually work the way they want it to. 

In other words, if you get asked, "Are you afraid of AI taking your job?" The answer should be "No, because while a business user can prompt AI to generate code, they are not going to be able to prompt as efficiently as a developer can."
