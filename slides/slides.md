#[fit] Serverless Architecture Monitoring

---

# About Me

![left](~/Dropbox/profile.jpg)

* DevRel at IOpipe
* Serverless Community Podcast host
* Robotics tinkerer/contributor/author
* Austinite

---

# Big Question:
## Do we need Ops for serverless applications?

---

# Answer: Most definitely!

---

# [fit] but why?

---

# Increased abstraction = less visibility

* We can't see much by default
* If something goes wrong, how do we know what?
* Can we even tell if something's "wrong?"

---

# So with serverless, sometimes problems sneak up on us

![inline](~/Dropbox/GIFs/where-is-your-god-now.jpg)

---

# And we don't always know how to triage or debug these problems

![inline](~/Dropbox/GIFs/ignore-the-fire.gif)

---

# What do we want to observe?

* Platform health
* Code health
* Architecture health

---

# Platform Health

* Cold Starts
* CPU
* Memory
* $$$

---

# Code Health

* Runtime
* CPU/Memory Usage
* Errors

---

# Architecture Health

* Calls to outside services
* Time spent blocked
* Uptime/Downtime

---

# How do we want to observe it

* Visualizations
* Alerting
* Differentials/Summaries

---

# Visualizations

* Because you can only learn so much from logs
* Easy to read
* Ability to drill down

---

# Alerts

* Because we want to know when something's wrong!
* Alerting on several metrics if possible that cover all three categories


---

# Differentials and Summaries

These are so you can see how your app's performance changes over time, allowing you to spot problems before they get too big, or spot potential growth areas.

---

Demo: How AWS and IOpipe handle monitoring serverless architecture

---

# What next?

More and more platforms will probably start turning their focus to ops and developer experiience in 2018.

And if they don't, third party tools definitely will.

---

# Thanks for listening!

* Kassandra Perch
* kas@iopipe.com
* @nodebotanist

![inline](~/Dropbox/GIFs/carl-sagan-youre-awesome.gif)

