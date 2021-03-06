# Team 3 group project: Net Worth Tracker

A Net Worth Tracker (Manager) is an app that allows users to calculate and see their net worth over time. A user would add their assets and liabilities and the tool would allow them to easily comprehend the results.

## Project Screenshot (after Sprint 1)

![Project Dashboard Screenshot](./app_screenshot.png)

## Team Members

- Svyatoslav Semenyuk (@Prometheus3375)
- Dragos Strugar (@d11r)
- Alexey Logachev (@picroc)

## Technologies

We discussed between making a desktop app or a web application. Tradeoffs included things like privacy, platform independence, ease of use, etc. After careful consideration we decided to make a web application with a cloud-stored database. We realize that the privacy is the main aspect of our product: users do **not** want their data to be seen by anyone except themselves, so we will implement additional privacy measures.

To make a web app, it is best to use JavaScript, so we decided to use _React_ as our frontend framework to use. For the database, we will use Firebase.

## Organization

Daily meetings, retrospective, sprint planning, and sprint review are all planned and scheduled as follows:

- daily meetings at 7pm MSC every working day
- sprint planning on Monday in the mornings
- sprint review on Friday in the evenings
- sprint restrospect after each sprint review

## Running the app

Make sure you have Node.js installed on your system (along with NPM). If not, please visit [this link](https://nodejs.org/en/download/) for additional instructions. Now, install yarn if you don't have it. To see installation instructions for Yarn, please visit [this link](https://classic.yarnpkg.com/en/docs/install).

Please note that on Mondays the could should be reviewed and put on the `main` branch. However, it may not be as some of the members have full-time jobs.

After that, clone our repository, and run the following (make sure you have `yarn` in your PATH and `cd` is for UNIX, so use Windows alternative if your OS is Windows):

```
cd net-worth-tracker
yarn && yarn start
```

The local server should be up and running.

## Commit Message Conventions

For commit messages use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/). Style is the following - for new features, fixes, refactors, doc changes, testing, performance changes respectively:

```
feat: <short description in present simple here>
fix: <short description in present simple here>
refactor: <short description in present simple here>
docs: <short description in present simple here>
test: <short description in present simple here>
perf: <short description in present simple here>
```

## Code Style Conventions

They are outlined in `.eslintrc` file and will be formatted automatically by [Prettier](https://prettier.io/).

## Overviews of Sprints

This section helps us, as well as the professor, in navigating the current stage of the project. We have two [projects](https://github.com/IU-IPOD-F20/map-projects-team3/projects) created, one with user stories and one with github issues. There you can also track our progress and how far we've come.

Below is the summary in terms of Story Points and effort needed to perform different tasks.

### Sprint 1

In total this sprint required 11 story points. There were three tasks, with weights of 5, and two with weight of 3. We managed to finish all the tasks that we've set out to do. While the prototype is very basic at this point, it fulfills all the requirements that the client has defined.

![Burndown Chart Sprint #1](./burndown-charts/sprint_1.png)
