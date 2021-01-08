# About Me

## Table of Contents
- [Introduction](#introduction)
- [Projects](#introduction)
- [Hawaii Food](#hawaii-food)
- New Year's Bucket List
- Comment!!!

## Introduction
<img src="./headshot3.png" alt="Pic of me!" />

[Source (Relative Link)](./headshot.jpg)

Hey! I'm Andy Young, a second year Computer Engineering major from Honolulu, Hawaii! I've been programming as a hobby since my freshman year of high school and am lucky to have gained a lot of software and web development experiences and skills as a result. I'm very grateful to be able to pursue my passion as a career and solve all interesting problems the field has to offer.

### Projects
Since there are requirements I have to fill for this assignment, I figured I could just include a few of my projects from my resume to knock some of them down:
- [Tory Roofing](https://torystimesheet.com/)
  - Automated and digitized Tory Roofing’s employee/job management system and payroll process by developing a webapp using **Ruby on Rails** that allows foreman to submit timesheets on an intuitive mobile UI and managers to review and automatically perform the payroll every week.
- [OP.GG Search](https://chrome.google.com/webstore/detail/opgg-summoner-search/dfnoddgekoeiljeaekobnchnedoipgpc?hl=en)
   - Created a Chrome extension with **JavaScript** as a freshman in high school, which currently has 5,000+ users, that adds extra features to a League of Legends statistics website.

### Hawaii Food
Enough with the programming stuff, here are my top 5 favorite places to eat in Hawaii (this list changes frequently):
1. *Off the Hook* (Poke)
2. *Kam Bowl* (Oxtail Soup)
3. *Mitch's Fish Market* (Sashimi, Obama Approved)
4. *Giovanni's Shrimp Truck*
5. ~~*Waiola Shave Ice*~~ *Matsumoto Shave Ice*

### New Year's Bucket List
Because of how badly I've personally responded to quarantine, instead of having a list of New Year's resolutions, I have a very low-expectation bucket list that'll hopefully help push me to getting my life back together:
- [x] Attend a remote class
- [ ] Surf
- [ ] Go to the gym
- [x] Refuse to eat junk food when tempted
- [ ] Write a line of code in Haskell

### Comment!!!
Here's a wise quote:

> Code is read more often than it is written.

Not sure who said it first, but it's definitely been said and at least thousands of times by many different which makes me wonder why there is still so much bad code... Consider this snippet below, written "cleanly" by me because it takes up "such few lines", can you tell what it does?

```
dp = [0] * (target + 1)
dp[0] = 1

for i in range(1, len(dp)):
    for n in nums:
        if n <= i:
            dp[i] += dp[i - n]

return dp[target]
```

You probably can't and neither can I and I'm the one who wrote it! If there were a bug in it would you be able to find, let alone fix it? I went through a phase of over optimizing everything while not commenting, wrongly thinking that less lines of code = cleaner which bit me in the ass enough for me to stop that habit. My advice to anyone who sees this who doesn't know already is don't do what I did!