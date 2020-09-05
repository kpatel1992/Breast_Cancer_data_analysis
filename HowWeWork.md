# Zen of Data Engineering

## Culture

_Friday Free Beer != Culture_

Tenets of good culture

- Trust (Assumption is you will do the right thing, until you break it)
- Autonomy (Exists because of trust)
- No Fear of failure 
- Collective ownership
- Free beer (Pun intended)
- You are not a resource/line item in excel spreadsheet. Hopefully you are an asset.

## Must Haves
Things that should be in place from Iteration 0/Sprint 0 (whatever floats your boat)

### Project

- CI Server running tests everytime you sneeze at the code (Hope you get the point)
- Publish test reports and coverage (Visibility)
- Infrastructure as Code (Today it is AWS, tomorrow it could be azure or gcp)
- Every commit gets deployed (Non prod to start with. Once we are mature, straight to PROD)
- Alerting (If shit hits the fan, we want to know. Pushing dirty Laundry under the carpet works at home, until it stinks)
- Follow general suggested standards of the tech/language being used. This will help us in bootstrapping new hires in a day instead of months.
- No production data in testing environments (Don't say what can go wrong...)
- No Compromise on Security.
- No compromise on quality
- Monitoring and Alerting

### Code 
- Tests (There has to be genuine reason to **not** write tests. Deadline pressure is not an acceptable excuse).
- CI server running some kind of code quality checks (depends on language)
- If it is python, this is your bible https://www.python.org/dev/peps/pep-0020/
- Small things (functions or objects), doing one thing and doing it right (Look at https://homepage.cs.uri.edu/~thenry/resources/unix_art/ch01s06.html, how well it has worked for decades)
- Again, If you can't write tests you are doing something wrong.
- Keep an eye for code smells (https://blog.codinghorror.com/code-smells/)


## Choosing tools
We will be rational is choosing tools that we use. Horses for courses, but not endup having so many that it is impossible to hire.

Most important aspect is

**Can we write tests that can run LOCALLY?**

**Can those tests run on our CI?**

Preferable answer to those questions are **YES**

## Readings
- https://norvig.com/21-days.html (this essay is a must read, not optional)
- http://steve-yegge.blogspot.com/2006/03/execution-in-kingdom-of-nouns.html
- https://www.goodreads.com/book/show/6713575-coders-at-work
- https://medium.freecodecamp.org/the-rise-of-the-data-engineer-91be18f1e603
- https://medium.com/@maximebeauchemin/functional-data-engineering-a-modern-paradigm-for-batch-data-processing-2327ec32c42a
- https://www.youtube.com/watch?v=23_1WlxGGM4
- https://www.dataengineeringpodcast.com/episode-3-defining-data-engineering-with-maxime-beauchemin/


# **KPI/OKR (s) of DET** 

- Write code that works today, tomorrow and every other day
- Write tests to prove the above
- While doing the above, keep in mind, if yout get hit by a tram, your team mates think of you because you were amazing, not because of the shit you left behind
- Teach Junior members of the team how to fish, do not feed them. If they are vegetarians/vegans, teach them how to grow veggies
- Last but not the least, Don't be a dick
- Happy Hacking
