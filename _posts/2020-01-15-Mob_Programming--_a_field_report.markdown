---
layout: post
title:  "Mob Programming - a field report"
date:   2020-01-15 14:47:28 +0100
categories: jekyll update
---

![](https://media-exp1.licdn.com/dms/image/C4D12AQFXBKCnytYwUw/article-cover_image-shrink_720_1280/0?e=1588204800&v=beta&t=zOaeBRnzulfcHTzrTp_z1CvJZKlk-2eEn6fpYqfZnHU)

As Engineering Coach at idealo I like to challenge different approaches on whether teams can benefit from them. The last two days I had the opportunity to have two sessions of Mob Programming with one team. It was very interesting and I want to share it with you.

## What is Mob Programming (in a nutshell)?

The whole team is working together at the same time on one task. There is only one computer for coding, a beamer/big monitor is used so everybody can see the code. The team members take up different roles (described below). You rotate the roles after a couple of minutes. For starters rotate every 4 minutes.

### Roles

The driver is sitting in front of the computer, she is doing the typing but makes no decisions. The (dedicated) navigator is coding with words by asking the driver to do the next steps. The rest of the group (mob) makes suggestions on how to proceed. 

Maaret Pyhäjärvi wrote a book that goes deeper into facilitating and practicing Mob Programming.

## Our setup

The team consists of four developers and a product owner (PO). One of the developers is new to the team and new to professional programming as well. All five agreed to participate in the Mob Programming.

The team chose a task to work on that was basically quite easy and well understood. 

Other than that we worked with the suggestions from Maaret Pyhäjärvi's book 'Mob Programming'. We stayed with four minutes rotation intervals for both days. About every hour we stopped for a retrospective (and a break).

## Learnings

1. Keep the session's length at a maximum of two hours. Energy level drops afterwards. Towards the end of the sessions the team got into a state of "let's keep it like this and be done". I think this is rather due to the fact that the team is new to Mob Programming and that the task was too basic than the practice of Mob Programming itself.
2. The outcome of the Mob Programming sessions was more on the learning value that the feature value. This might be highly related to the type of task you are working on.
3. The code we wrote during Mob Programming showed a tendency towards overengineered. A lot of time was spent on getting the tests into a maintainable state. I observed a lack of common mindset within the team concerning tests.
4. It is valuable to have the PO as part of the Mob Programming. In our sessions she learned about the questions and tasks the developers need to work on in order to get even a seemingly simple task done. Also it became obvious that sometimes developers need to make some small decisions that can have a huge impact (for others) that the developer is not aware of. As the PO was involved, she was able to understand the implications and talk to the concerned people about it afterwards. IMHO this can be very beneficial for transparency and avoiding strange behaviour (AKA bugs). Having the PO in the role of dedicated navigator or driver was no issue for us. We adopted the level of abstraction in our communication and were able to move forward. In fact in a total of fife hours of Mob Programming and four minute intervals there was not one interval where no code editing was done. For me that was very satisfying.
5. Overall the mood was good.

The learnings 2, 3 and 5 where gathered through a quick feedback at the end of the second session. The others through the retrospectives and my observations as facilitator.

![Feedback from mob programming sessions](img/mob_programming_feedback.png)