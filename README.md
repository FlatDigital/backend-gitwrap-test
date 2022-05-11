# Backend Interview Test
Interview test for backend engineers

## Welcome!
---
If you're reading this, it means we're interested in working with you and solving amazing and difficult problems in real-estate tech in Mexico.

This README provides the instructions to a small, self-contained test for a Backend Software Engineer position.

## What we're looking for
---
We're looking for a talented and driven backend engineer, comfortable with designing and building rigorous APIs and backend services.

This means that this test is designed to gather signal on your coding structure, the tradeoffs and decisions you make on API design. We're excited to see what you build!

## The test
---
Today, we'll be building an API wrapper around the git information of your project. We suggest creating a new repo and start working on it, the url of which is the only thing you need to send us when you're done.

The main objects we'll be dealing with are:

- Commits
- Authors
- Branches
- PRs

For the PR create endpoint, we'll ask the user for a PR title and description, and we'll give them 2 options: either save it (Status = Open), or merge it. Note that merge operations can fail due to conflicts or other reasons, so make sure you handle and show whatever error happens when merging. After a successful merge, the PR should move to a Merged status.

## Deliverables
---
We expect this test to take around 4 hours, but not significantly more (your time is very valuable!). We're giving you a week from the date you receive it to complete it and send us your repo URL, using whatever stack you feel most comfortable with. Due to this, we ask that you also provide a README with instructions for running your project, along with setup instructions (or provide a Dockerfile and a docker run instruction).

It's up to you to design how this should look code-wise, but we don't expect you to model all git objects in a DB. We're ok with reading them using a library wrapper for git like GitPython, on-demand. The only DB design required is the one for PRs.

## Grading
---
We'll grade this project according to completion percentage of the features requested, good coding style for both back and frontend. For us, good coding means:

- It's readable. We read code much more often than we write it, so it's important that we're clear on what we're doing and comment any hairy parts (which we don't really expect to have in this test!).
- It's reasonably well ordered and with a logically thought-out structure. We like to do separation of concerns, and deal with routing, DB models, serialization, etc in their own file structure / files.
- Clear, understandable variable names. No one wants to read the whole file to understand what the variable c1_2 means.

We also care about being able to run your test without significant effort on our part, so make sure you test the instructions you provide on your README.

## Bonus points
- The code has tests.
- The proyect is easy to deploy on any local enviroment.

If you come across any questions or anything we didn't cover on this README, feel free to reach out to us and we'll get you an answer as soon as possible. Happy coding!