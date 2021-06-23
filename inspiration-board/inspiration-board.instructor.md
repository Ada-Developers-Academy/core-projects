# Instructor: Inspiration Board

The project has three repos:

- [https://github.com/AdaGold/full-stack-inspiration-board](https://github.com/AdaGold/full-stack-inspiration-board)
- [https://github.com/AdaGold/front-end-inspiration-board](https://github.com/AdaGold/front-end-inspiration-board)
- [https://github.com/AdaGold/back-end-inspiration-board](https://github.com/AdaGold/back-end-inspiration-board)

The project description, and only the project description, lives in [the full-stack repo](https://github.com/AdaGold/full-stack-inspiration-board).

The front-end and back-end repos do **not** have any project descriptions. This is to minimize conflicting and contradictory requirements.

## About the Scaffolds

The front-end scaffold is minimal. This is to:

- Allow students to practice running `create-react-app`, since React was the most recent thing they learned
- A CRA app is more familiar to the students compared to giving them files, arguably (it's disorienting to see predefined components, for instance)
- Avoids our own repos (belonging to AdaGold and every Ada-CX org) from having another npm project to check for vulnerabilities. By asking students to `npx create-react-app` to the latest version each cohort, we
    - maximize the likeliness that the versions of everything is runnable on the student's machine
    - minimize the amount of security warnings

All three repos must be forked to Ada-CX.

The back-end scaffold was taken from my implementation, and then had the guts ripped out.
