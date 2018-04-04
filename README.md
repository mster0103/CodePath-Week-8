# CodePath-Week-8# Project 8 - Pentesting Live Targets

Time spent: 6 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: Session Hijacking/Fixation
<img src='https://github.com/mster0103/CodePath-Week-8/blob/master/Gifs/Session%20Hijacking.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

Was able to hijack the session of my mozilla browser by setting the particular session ID in chrome


Vulnerability #2: SQL Injection
<img src='https://github.com/mster0103/CodePath-Week-8/blob/master/Gifs/SQL%20Injection.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

Was able to inject SQL to sleep the webpage

## Green

Vulnerability #1: Username Enumeration
<img src='https://github.com/mster0103/CodePath-Week-8/blob/master/Gifs/Username%20Enumeration.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

When logging in with a username that exists will the responde text will be bold. If the username doesnt exists the response text isnt bold

Vulnerability #2: Cross-Site Scripting
<img src='https://github.com/mster0103/CodePath-Week-8/blob/master/Gifs/Cross-Site%20Scripting.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

Was able to send an alert script throught the feedback form


## Red

Vulnerability #1: Insecure Direct Object Reference<img src='https://github.com/mster0103/CodePath-Week-8/blob/master/Gifs/Insecure%20Direct%20Object%20Reference.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

Was able to view admin only employee info publicly by editing the id in the url

Vulnerability #2: Cross-Site Request Forgery
<img src='https://github.com/mster0103/CodePath-Week-8/blob/master/Gifs/Cross-Site%20Request%20Forgery.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

Editing an employee even with an invalid csrf_token still worked


## Notes

Took a bit too long to identify which site had which exploit

