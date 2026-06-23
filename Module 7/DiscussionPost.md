# Telemetry
## Provide at least two (2) examples of anomaly detection tools as they apply to DevOps. Which would you recommend? Why?

### Cisco DevNet Anomaly Detection Tool
#### https://developer.cisco.com/articles/anomaly-detection-in-devops
The Cisco DevNet Detection Tool is an anomaly detection tool that is designed to help DevOps teams identify and respond to anomalies in their systems. It uses machine learning algorithms to analyze telemetry data from various sources, such as logs, metrics, and traces, to detect unusual patterns or behaviors that may indicate potential issues. This tool can be integrated into the DevOps pipeline to provide real-time monitoring and alerting for anomalies, allowing teams to quickly address problems before they impact users.

### Splunk Anomaly Detection Tool
#### https://www.splunk.com/en_us/solutions/anomaly-detection.html
This tool provides a platform for monitoring, searching, and analyzing machine-generated data. It can be used to detect anomalies in real-time by analyzing logs, metrics, and other telemetry data. Splunk's anomaly detection capabilities include statistical analysis, machine learning models, and customizable alerts to help DevOps teams identify and respond to unusual patterns or behaviors in their systems.

## My Recommendation
While Cisco does a really good job with their anomaly detection tool, I would recommend using Splunk for anomaly detection in DevOps. My main reason for this is because Splunk does a better job of providing a services that can handle full stack telemetry data, including logs, metrics, and traces. The major downside to Splunk is that it is very expensive. I also choose splunk because I use it at work for us to be notified when we are on call if something goes wrong with our systems. It is a great tool for DevOps teams to use to monitor their systems and detect anomalies in real-time.

# Anomalies
## Explain two different types of code/peer reviews. When might each be used? Why?
https://staging-graphite-splash.vercel.app/guides/modern-code-review-vs-formal-inspections

### Formal Code Review
This type of review is a structured process where developers present their code to a team of peers for evaluation. It typically involves a checklist of criteria that the code must meet, and reviewers provide feedback on aspects such as code quality, adherence to coding standards, and potential bugs. Formal code reviews are often used in larger projects or when working with critical systems where high-quality code is essential. They help ensure that the code meets organizational standards and can prevent defects from being introduced into the codebase.

Unless the code is critical, I would not recommend using a formal code review. It can be time consuming and can slow down the development process. It is best used when working on critical systems or when working on a large project with multiple developers. Even then, I have very rarely seen a formal code review used in the workplace. Most of the time, informal code reviews are used to save time and get the job done.

### Over-the-Shoulder Review
This type of review is an informal process where a developer presents their code to a peer, who reviews it in real-time. The reviewer can ask questions, provide feedback, and suggest improvements as they go through the code together. Over-the-shoulder reviews are often used in smaller teams or when working on less critical code, as they allow for quick feedback and collaboration. They can be particularly useful for mentoring junior developers or when time constraints make formal reviews impractical.

I have conducted over-the-shoulder reviews in the workplace quite often. It is my favorite way to get Junior developers up to speed on how to write code that meets the standards of the company. My style of mentoring has been describes as "throwing them in the deep end" and then helping them learn how to swim. It tends to get them at least making a small contribution to the code base. Along with this method, it helps me to understand their thought process and how they approach problem solving.

I'll be honest, I barely looked at the article for this code review discussion portion. I do code reviews all of the time at work and didn't really need to read the article to answer the question. So there is a chance the article may have some good information that I didn't talk about. :)

## References
Integrating Anomaly Detection with DevOps Processes - Anomaly detection in DevOps - Cisco DevNet. (2026). Cisco DevNet. https://developer.cisco.com/articles/anomaly-detection-in-devops

‌bhardwaj, namrata. (2025, March 11). Top Anomaly Detection Tools for 2025. Techywired. https://techywired.com/reviews/top-anomaly-detection-tools-for-2025/#1-splunk

‌Modern code review vs. formal code inspections. (2026). Graphite. https://staging-graphite-splash.vercel.app/guides/modern-code-review-vs-formal-inspections

‌