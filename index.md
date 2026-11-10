# DSC 180A Methodology Assignment 4

**Name:** Alyxandrea Wikarsa
**Email:** [awikarsa@ucsd.edu](mailto:awikarsa@ucsd.edu)

**Section:** D42
**Mentor:** Bijan Arbab

---

## Quarter 2 Project Brainstorm

**1. What is the most interesting topic covered in your domain this quarter?**

The most interesting topic for me is working together with the City of San Diego's Developmental Services Department (DSD) and tackling messy real-world administrative data. Our project uses historical permit review comments that, before cleanup, had 16 million entries. Free-text comments don't have a standard structure, so finding recurring problems means deciding how to group and label them. I found it interesting that one design choice in cleaning or categorizing the text can change what the "most common problem" turns out to be.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

Since we haven't actually dove into the nitty-gritty of the review comments data, I'd like to look at which kinds of review comments predict that a project will need more resubmission cycles, and what the common pitfalls are from applicants. We're trying, as best as possible, to create an apples-to-apples comparison as a baseline to categorize comments. I imagine that for similar permit applications, we could cluster the comments into issue types, such as missing documents, zoning conflicts, or code violations. Then we'd test which types are linked to longer permit-issuance times. Hopefully, the results could tell applicants which problems to fix before submitting, since those would save the most time.

**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

We spent a lot of time back-and-forth with our subject domain experts from the DSD to figure out how to tackle this problem which in nature seemed really simple. In order not to jump to conclusions of what we wanted our final deliverable to be, and the bureaucratic process of obtaining the review comments data delayed our confirmation for what kind of tool we wanted to build in the second half of the capstone project. Albeit necessary time and steps, we got most of the relevant data to start playing around and exploring in week 7, which I think could've been expedited if we were more sure and aware of the domain.

**4. What other techniques would you be interested in using in your project?**

I would like to try topic modeling or text embeddings to group review comments automatically instead of labeling them by hand. I'd also like to try survival analysis or a regression model to estimate how the number of review cycles affects total time to permit. For the applicant-facing tool, I'm interested in a simple checklist generator that uses the most common issues for a given project type, and in evaluating whether it reduces resubmissions.