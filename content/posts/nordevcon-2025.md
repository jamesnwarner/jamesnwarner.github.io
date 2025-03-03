---
title: "nor(DEV):con 2025 - My Highlights"
date: 2025-03-03T21:00:00+00:00
# weight: 1
# aliases: ["/first"]
tags: ["conference", "leadership", "software development"]
categories: ["conference"]
author: "James Warner"
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "My highlights from nor(DEV):con (Norfolk Developers Conference) 2025."
canonicalURL: "https://jamesnwarner.github.io/posts/nordevcon-2025/"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
---

I attended [nor(DEV):con 2025](https://nordevcon.com) on Thursday 27th and Friday 28th February 2025. This was my sixth nor(DEV):con in a row, having been to every single one since 2019 and I think it's seen a shift in recent years, bringing in more speakers from further afield. Gone are the days where there were five tracks of talks. Now we only have three, but this year had some great talks.

Over the twe days, I attended **14 different talks**. In this blog post, I'll cover the highlights from some of my favourite talks at this year's event and some of my biggest takeaways.

### Talk: A11y beyond the theory: Integrating accessibility testing into your workflow by [Nhlanhla Lucky Nkosi](https://www.linkedin.com/in/lucky-nkosi)

Accessibility is important. Here are some reasons why:
- Building accessible websites and applications doesn't just help people with disabilities, it benefits every single user of your site.
- 15% of the world has some sort of digital accessibility needs and compliance is starting to become a legal requirement in some countries so engineers need to start understanding this stuff.

Lucky then started talking about how to automate accessibility testing as much as possible.
- Lighthouse, Wave and axe DevTools can help evaluate your site for accessibility, but these tools are used post-release which is too late.
- [Pa11y CI](https://github.com/pa11y/pa11y-ci) can be integrated into CI/CD pipelines to highlight accessibility issues during PR, this is something I am going to implement at work soon!
- [jest-axe](https://www.npmjs.com/package/jest-axe) is a package that can be used to write accessibility tests. I'm going to start incorporating these into any new frontend code that I write.
- Finally, I've installed [axe Accessibility Linter](https://marketplace.visualstudio.com/items?itemName=deque-systems.vscode-axe-linter) straight into VS Code already based on Lucky's recommendation!

It's worth bearing in mind that automated tests can only catch 30-40% of accessibility issues, so this doesn't replace manual testing but I look forward to making use of these tools to ease the building of accessible software. I'm fully convinced that shifting left with accessibility testing is the way to go.

### Talk: Turning Production Incidents into Systemic Wins by [Julian Wreford](https://www.linkedin.com/in/julian-wreford/)

Every single talk that I attended given by a [Gearset](https://gearset.com/) employee was a brilliant talk and Julian's was no different.

My main takeaways were:
- Having a blameless culture is essential to learning and improving when it comes to production incidents.
- Blue/green deployment is a **superpower** when things go wrong, being able to switch back to that working version is amazing.
- Investing in observability tools to allow you to understand performance issues in real time will allow you to better serve your customers.
- Developing a structure for retrospectives and holding them is necessary to learn. Make sure you dedicate time to root cause analysis and process improvement and assign small actions to individuals.


### Talk: Impostor Syndrome - a day in the life of a developer by [Patrick Boyd](https://www.linkedin.com/in/paddy-boyd/)
Patrick talked about the imposter syndrome that he felt when he started the role at his latest company and I felt this was something I could relate to. When I started in my current role at AM I felt very much the same. You're using new technology and learning new ways of doing things and these can make you feel unqualified and undeserving of the role you are in.

Patrick made some recommendations for overcoming "Imposter Syndrome" which I loved.
- Set **training goals** (courses, documentation, practice projects).
- **Talk to mentors and peers** – you’re not alone.
- **Celebrate small wins** – success compounds over time.
- **Own mistakes and learn from them** – failure is part of growth.


### Talk: Product: Uncovering the Jobs To Be Done by [Iz Wright](https://www.linkedin.com/in/isobel-wright/)
As someone who works closely with a Product Manager on a day-to-day basis, I enjoyed this talk as it allowed me to learn a little more about the role and provided me with plenty of ideas to take back to my company and team.

Iz recommended a book called **[The Mom Test by Rob Fitzpatrick](https://www.momtestbook.com/)** which I messaged my colleague with straight away.

I also learnt about the importance of asking the right questions to your customers to fully understand how they use your product and what their problems might be. I especially loved the idea of deliberately repeating what your customer just told you back to them incorrectly to make them clarify it again to extract the extra bit of information and learning.

As a software engineer, I know it is my job to deliver a solution that my customers need, and the Product Manager plays a huge part in making sure that solution is the right one.


### Talk: Ctrl+Alt+Shift: Taking Your Career from Developer to DevOps Engineer by [Luke Kittridge](https://www.linkedin.com/in/lukekittridge/)
In my role as a Lead Software Engineer at AM I have recently found myself needing the wear the DevOps hat a little more than I have ever had before.

Luke gave a brilliant talk about what it means to be a DevOps Engineer and how this differs from his previous role as a Software Developer.

His suggestions about making use of PowerShell to automate as much as possible got me thinking about how I can make better use of it and has given me some ideas to take back to my organisation. I especially loved the idea of putting together a PowerShell script to allow software developers to add secrets to Azure Key Vault vault that enforces the company's agreed naming scheme.

Luke also offered some ideas around FinOps and limiting spending costs in the cloud. This is a topic I find a little too easy to neglect. Luke suggested in his talk to add workbooks for orphaned resources. I plan to take this on board and I will look to add workbooks to our Azure infrastructure at AM soon.

### Talk: So you think you can lead a team? by [Paul Grenyer](https://www.linkedin.com/in/pgrenyer/)
Paul took us all through his journey to leading a team and what he now considers to be the four aspects of Team Leading.

My favourite point was "talk to your team every day". This feels like a simple one but if you work in a remote team this can be hard. I fully buy into the premise of it though. From my experience, when a team gets on well with each other I have seen the positive effects this has on productivity and effectiveness. You can't force people to like one another but you can create an environment where people can get to know their colleagues and know they are supported in their role.

Paul recommended the book [The New One Minute Manager](https://www.amazon.co.uk/ONE-MINUTE-MANAGER-NEW-ONE_PB-best-selling/dp/0008128049) which is already sitting in my basket on Amazon.

## Final Thoughts
nor(DEV):con is always one of the highlights of my year. 

As I've grown in my career I get different things from it. I used to come away with loads of new ideas and whilst I'm still learning new things, the conference now provides some reassurance that I am doing the right things in my role.

I'm excited to bring my learnings back to my team at AM and I plan to implement some changes. I think I'll put myself forward to give a talk next year, fingers crossed it gets accepted 🤞.