# devTracker Contriubting

We want to make contributing to this project as easy and transparent as possible, whether it's:

* Reporting a bug
* Discussing the current state of the code
* Submitting a fix
* Proposing new features
* Becoming a maintainer

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

Please note we have a code of conduct, follow it in all your interactions with the project (see at end of this document).

## Basic Set up

* Fork repo to your github account.
* Clone repo into any directory.
* cd into the devtracker directory.
* Ensure you are running python version 3.5 or greater and that you have pip updated.
* Run the install.sh file `./install.sh`. (if you have already installed the project via pip, uninstall before running command.)
* Run `pytest` to begin as this will create the required devtrack_projects directory and allow you to verify all tests pass before working on feature or fixing bug.

See README.md for info about basic commands and usage.

### Testing

* devtracker uses [pytest](https://docs.pytest.org) for testing.
* pytest should be installed after running install.sh or can be installed using `pip install pytest`
* to run tests cd into devtracker directory and run `pytest` in the terminal.  **If tests are not run from devtracker directory some may fail.**
* Ensure any feature or bug fix has appropriate testing.

### Uninstall

run `pip3 uninstall devtracker` if you need to uninstall.

## We use GitHub

We use github to host code, to track issues and feature requests, as well as accept pull requests.

Follow this common GitHub workflow:

1. Fork the repo and create your branch from master.
2. If you've added code that should be tested, add tests.
3. If you've changed APIs, update the documentation.
4. Ensure the test suite passes.
5. Make sure your code lints.
6. Issue that pull request!

We use GitHub issues to track public bugs. Report a bug by opening a new issue!

Great Bug Reports tend to have:

* A quick summary and/or background
* Steps to reproduce
    1. Be specific!
    2. Give sample code if you can.
    3. What you expected would happen
    4. What actually happens
* Notes (possibly including why you think this might be happening, or stuff you tried that didn't work)


##License

By contributing, you agree that your contributions will be licensed under its MIT License.


# Code of Conduct

### Our Pledge

In the interest of fostering an open and welcoming environment, we as contributors and maintainers pledge to making participation in our project and our community a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, sex characteristics, gender identity and expression, level of experience, education, socio-economic status, nationality, personal appearance, race, religion, or sexual identity and orientation.

### Our Standards

Examples of behavior that contributes to creating a positive environment include:

* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

* The use of sexualized language or imagery and unwelcome sexual attention or advances
* Trolling, insulting/derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others’ private information, such as a physical or electronic address, without explicit permission
* Other conduct which could reasonably be considered inappropriate in a professional setting

### Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable behavior and are expected to take appropriate and fair corrective action in response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or reject comments, commits, code, wiki edits, issues, and other contributions that are not aligned to this Code of Conduct, or to ban temporarily or permanently any contributor for other behaviors that they deem inappropriate, threatening, offensive, or harmful.

### Scope

This Code of Conduct applies both within project spaces and in public spaces when an individual is representing the project or its community. Examples of representing a project or community include using an official project e-mail address, posting via an official social media account, or acting as an appointed representative at an online or offline event. Representation of a project may be further defined and clarified by project maintainers.

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by contacting the project team at conorsouhrada@gmail.com. All complaints will be reviewed and investigated and will result in a response that is deemed necessary and appropriate to the circumstances. The project team is obligated to maintain confidentiality with regard to the reporter of an incident. Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the Code of Conduct in good faith may face temporary or permanent repercussions as determined by other members of the project’s leadership.

### Attribution
This Code of Conduct is adapted from the Contributor Covenant, version 1.4, available at https://www.contributor-covenant.org/version/1/4/code-of-conduct.html
