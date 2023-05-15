# 🎉Welcome to our development team!

We are thrilled to have you on board and excited to work together. Your skills and expertise will be invaluable as we tackle new challenges and deliver innovative solutions. Our team is dedicated, collaborative, and passionate about what we do, and we believe that with your contributions, we can achieve great things.

Feel free to reach out to anyone on the team if you have questions or need assistance. We are here to support you and ensure your success in this role. Together, we will create amazing software and make a positive impact.

Once again, welcome to the team. We look forward to an incredible journey ahead!



# 🗣How to communicate

Slack is the main tool for communication. When using Slack to communicate, please keep the following in mind.


### Slack Team Communication Best Practices Guideline

1. Choose appropriate channels: Choose channels based on topics, projects, or teams to keep discussions organized. Avoid cluttering the general channel with unrelated conversations. Use the "dev-team" channel when it concerns development. Since "action-in-github" is a channel for notifying actions on GitHub, it is not necessary to use it.
    
2. Use clear and concise messages: Keep your messages brief and to the point. Avoid long paragraphs and use bullet points or numbered lists when necessary.
    
3. Utilize threads: Use threads for in-depth discussions or to respond to specific messages. This keeps the main channel clutter-free and allows focused conversations.
    
4. Mention individuals when necessary: Use @mentions to get someone's attention or involve them in a conversation. However, be mindful of not overusing mentions to prevent unnecessary distractions.
    
5. Use reactions and emojis: React to messages using emojis to acknowledge or express emotions. It adds a personal touch to communication and encourages positive interactions. I personally use "👀" this emoji to mean "I have read/confirmed this message".
    
6. Be mindful of timing: Consider time zones and availability when messaging team members. When sending time-related messages (e.g., deadlines), please specify the time zone (e.g., JPT). 
    
7. Keep discussions professional: Maintain a respectful and professional tone in all communications. Avoid offensive language, personal attacks, or any form of discrimination.
    
8. Share important updates and information: Use appropriate channels to share announcements, important updates, or relevant articles. Ensure that team members are subscribed to the relevant channels to receive essential information.
    
9. Keep noise to a minimum: Avoid unnecessary notifications or pings in channels. Use @channel or @here mentions sparingly and only when the message is important for everyone.
    
10. Use integrations and bots wisely: Explore and utilize Slack integrations and bots that can enhance team productivity, such as project management tools, code review notifications, or status updates.
    
11. Respect channel purposes: Follow the guidelines for each channel's purpose. Avoid posting unrelated or off-topic messages that can distract others.
    
12. Encourage participation and collaboration: Foster an inclusive environment where everyone feels comfortable sharing their ideas and opinions. Encourage active participation and collaboration among team members.

13. Response time and communication availability: Strive to maintain a reasonable response time to keep the development speed consistent. If you plan to take time off or won't be able to respond for an extended period (more than a day), please notify your team in advance. 



# 🧑‍💻How to develop

GitHub/Git is the main tool for development. When using GitHub/Git to develop, please keep the following in mind.


### GitHub/Git Team Development Best Practices Guideline

1. Use meaningful commit messages: Write descriptive and concise commit messages that clearly explain the changes made in the commit. This helps team members understand the purpose and impact of each change.
    
2. Follow branching strategies: Adopt a branching strategy that suits your team's workflow, such as GitFlow or GitHub Flow. Use feature branches for new features or bug fixes and create pull requests for code review before merging to the `develop` branch.
    
3. Regularly pull from the `develop` branch: Keep your local branch up to date by regularly pulling changes from the `develop` branch. This helps prevent merge conflicts and ensures you are working on the latest codebase.
    
4. Review code through pull requests: Use pull requests to facilitate code reviews. Request feedback from team members to ensure code quality, catch bugs, and promote knowledge sharing.
    
5. Maintain a clean commit history: Keep your commit history clean and organized by squashing or rebasing commits before merging to the `develop` branch. This helps maintain a clear and concise history and makes it easier to track changes over time.
    
6. Utilize issue tracking: Use GitHub's issue tracking system or other project management tools integrated with GitHub to track and prioritize tasks, enhancements, and bugs. Link commits and pull requests to related issues for better traceability.
    
7. Use meaningful branch and tag names: Use descriptive names for branches and tags that clearly indicate their purpose or the feature they represent. This helps team members quickly understand the context of a branch or tag.
    
8. Write comments and processes: Write clear and concise comments for your codebase. This helps onboard new team members and ensures consistent practices.
    
9. Utilize code review tools and integrations: Explore code review tools and integrations available on GitHub, such as code linters, automated testing frameworks, and static code analysis tools. These tools can help identify issues early in the development process.
    
10. Foster a collaborative and constructive environment: Encourage respectful and constructive code reviews and discussions. Provide feedback in a helpful manner and be open to receiving feedback from others. Collaborate and learn from each other to improve the overall code quality.


### Additional

1. Below is the Git-branch best practice we use.
   ![git-model@2x](https://github.com/Succery-dev/Onboarding/assets/54393289/77166a4b-d8e4-435a-a72f-01d4bbaf3acb)
   [Detail](https://nvie.com/posts/a-successful-git-branching-model/)

2. How to make branches

   Branch should be derived from the `develop` branch each time it is created. Each time you create a new branch, pull the `develop` branch to keep the code up-to-date.
   
   * When creating a new feature: `feature/~` (e.g. `featuer/hp-design`)
   * When fixing a bug: `fix/~` (e.g. `fix/module-not-found`)
  
3. Do not use and merge it to the `main` branch. We only use it for production.
   
   If you create a PR, make sure that the commit is going to merge into `develop` branch.
   
   I'll check the PR, so please assign me as a reviewer and let me know on the Slack.
