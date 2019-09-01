# Week 2

## Weekly Goals

1. Use all of week 1's skills (don't underestimate the importance of this)
2. Break one class into two classes that work together, while maintaining test coverage
3. Unit test classes in isolation using mocking
4. Explain some basic OO principles and tie them to high level concerns (e.g. ease of change)
5. Review another person's code and give them meaningful feedback

#### Plans to achieve:

1. Continue using strict TDD process, which involves understanding of OOP, testing etc. Continue to request feedback for pairing, improving each day
2. Use Oyster Card challenge as opportunity to split and refactor classes (e.g. Card class methods moved into Journey class)
3. When refactoring classes, use RSpec mocking to eliminate cross-class dependencies when testing, making sure unit tests are isolated
4. Complete all OO practicals set in the week2 of week_outlines
5. Go through peer code review and complete Google Form for airport challenge

#### Evidence:

1. 
  - TDD practices continued in both weekly and weekend challenges (Oyster card and Takeaway)
  - Continued debugging systematically to make tests pass as part of TDDing new programs
  - Improved understanding of OOP by refactoring, using dependency injection, understanding polymorphism etc.
  - Paired each afternoon with someone different, and received very positive feedback!
2. 
  - [Forwarding & Polymorphism examples](https://github.com/DanGyi23/Object-Oriented-Design)
  - [Oystercard challenge](https://github.com/DanGyi23/oystercard-1) - examples of forwarding and dependency injection demonstrated here.
3. Oyster card challenge demonstrates this really well; individual class spec files reference only the subject or mocked classes. [Complete repo here](https://github.com/DanGyi23/oystercard-1)
4.
  - [Forwarding & Polymorphism examples](https://github.com/DanGyi23/Object-Oriented-Design)
  - [Takeaway Challenge](https://github.com/DanGyi23/takeaway-challenge) - this repo contains code written to mimic a takeaway delivery service, complete with text message confirmation using Twilio API. Followed SRP to make sure the classes were lean and easy to understand.
5. Completed this on Tuesday 27th Aug - held by Makers

## Daily Goals

#### Tuesday 27th August
- GOAL: Review another person's code
- PLAN: Complete code review with peers, give and receive feedback on airport challenge
- EVIDENCE: Completed this on Tuesday 27th Aug - held by Makers

#### Wednesday 28th August
- GOAL: Break one class into two classes, maintaining unit test parity
- PLAN: Use Oyster Card challenge as opportunity to refactor some Card class methods into Journey class methods
- EVIDENCE: Worked with Ben to refactor into 2 new classes - Journey and Journey_Log - ensuring SRP. Repo [here](https://github.com/ben-zeng/oystercard)

#### Thursday 29th August
- GOAL: Understand class delegation
- PLAN: Attend delegation workshop and complete some of the practicals from this week's skills-workshop repo
- EVIDENCE: [Oystercard challenge](https://github.com/DanGyi23/oystercard-1) - many delegation examples here

#### Friday 30th August
- GOAL: Understand class polymorphism
- PLAN: Attend polymorphism workshop and practice using the week2 OOP practicals
- EVIDENCE: [Polymorphism example](https://github.com/DanGyi23/Object-Oriented-Design)

## Reflection


### Question 1

*Did you meet all of your goals to the standard you set at the start of the week?*

- Almost, I only didn't complete some of the OOP practicals concerning refactoring, though I feel like this will come with more practice and as the challenges become more complex. At least I understand the principles that the exercises were designed to demonstrate/test


### Question 2

*What would you change/improve moving forward?*


**Technical:**
- Follow TDD processes slightly more strictly, as it clearly saves time in the long run, especially with more complex code
- Understand RSpec method stubbing implementation and syntax a little better. I had to rely heavily on Google/examples
- Attend more process workshops at Makers

**Personal:**
- Try not to finish everything - there's too much to complete and my learning was compromised at times by being too concerned with completion rather than the process
- Spend more time understanding a problem/feature before starting to write code. I found that it meant I had to refactor less, and interdependencies were easier to map out 
