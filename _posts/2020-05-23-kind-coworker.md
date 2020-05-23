---
layout: post
title:  "How to be a kind coworker"
date:   2020-05-23 11:26:52 -0400
categories: jekyll update
---

Based on my mistakes. 

- Don't merge code Friday afternoon just before a long weekend. Ya even though you think it is all tested and never going to break.

- Don't tag people over the weekend on slack/git reviews. I mean there is a working day around the corner.

- Write meaningful error logs. Don't stop at `Something went wrong`

- If you introduce an abstraction, please go ahead and change it all the places that abstraction can be used. And if there 2 or fewer instances then probably it is not worth abstracting yet. 

- PRs are not very obvious, esp when the code change is like 500 lines. Explain in simple words. Put in a simple diagram if that helps.

- Comments are necessary even with tests. Tests don't explain why are you processing only lines starting with a number. People maintaining code after you will thank you.

- Don't call anything fixed until there is merged PR for it. (Even if it was creating a database/ setting up VM/ cleaning disk space document the steps if you cant automate it.)

- Jira/Trello is great to communicate progress, not everything has to have a ticket. If you see a bug or an opportunity to make something better please go ahead and do it. A ticket is not needed, who introduced is not important.

- It is ok to say "I have no idea please explain".  

- Don't ask a question because you know the answer. 

- When you ask a question, don't start thinking about the next question. Instead, listen. 

- Always assume good intent. Assume there is something you are missing when you don't understand.

- When you say something is wrong, please say why and give examples. Just saying _wrong_ is never useful. 

- When you say `I don't like doing it that way`, please explain what are the pain points of it. Just saying not a fan of it goes on to say "ya ok but I want to do it my way not your way."