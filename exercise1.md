# Exercise 11.1

1. Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked? You can search for the answers by google.

    * For Python language, there is 'Pylint' for the linting step. It checks errors in Python code and coding styles. Next, 'PyUnit' is a library for unit-testing Python code in the testing step whether the program is working as intended. Unlike complied languages such as C++, Python, as an interpreted language, doesn't need the building step.

2. What alternatives are there to set up the CI besides Jenkins and GitHub Actions? Again, you can ask google!

    * Like GitHub Actions in GitHub, GitLab also offers their own CI/CD service. As well as, there are many other workflows providers such as CircleCI and TravisCI by using the configuration file to setup the CI/CD.

3. Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

    * I think it depends on the scale of a project as mentioned in the course material. If the scale of the project is small, it is much simpler, cheaper, faster and more efficient to use a cloud-based environment. This is because we don't need to concern about the initial setup of the environment. In addition, we can run agile development process with quick environment. On the other hand, if we plan to build a large scale system and we already have high-performed hardware, it is much more stable and sustainable to use a self-hosted environment. This is because the resources from cloud-based environments are limited or expensive when we require more powerful resources. Once we setup the CI/CD in the self-hosted environment, we can keep using it continuously.