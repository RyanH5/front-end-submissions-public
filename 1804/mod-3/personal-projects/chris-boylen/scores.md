### Project Scope

A good project idea should:

* Break down into logical iterations so that you can deliver a strong product on every check-in
* Be something that real people would want to use to solve a problem
* Have enough *technical* challenge to be worth your time (as opposed to a *content* challenge)

## Rubric

### Specification Adherence

- 4- - The application completes all 2 iterations above and implements one or more of the extensions.

### Code Quality

- 4 - Developer demonstrates complete understanding of React with appropriately separated components and exceptionally well refactored code.

### CSS/Design

- 3+ - Developer has made a targeted effort to make the app appealing and user friendly. Evaluator has multiple recommendations for design changes. Follows majority of the [10 Essential Usability Guidelines.](https://speckyboy.com/10-essential-web-application-usability-guidelines/)

### SASS/SCSS

- Pass - Styles are written using either SASS or SCSS

### Testing

- 4 - Every component is tested from both a unit and acceptance standpoint, all crucial functionality is tested

### PropType Implementation

- Pass - Proptype validation is implemented for any component receiving props.

### README Updates
- Pass - The README.md file has been updated with a description of the project, the team, and how to get it up and
  running
- Fail - The boilerplate README is still in place

### Code Sanitation

The output from ESLint shows…

* 4 - Zero complaints
* 3 - Five or fewer complaints
* 2 - Six to ten complaints
* 1 - More than ten complaints

### Redux Architecture

* 4: Appropriate components are wrapped in connected Redux container components. The Redux store contains all necessary application data and nothing more. All state changes are handled through Redux actions and reducers.
* 3: At least one component is not connected with Redux appropriately. Application state is mutated by more than just Redux. The Redux store is missing application data that it should be handling.
* 2: Application state is mostly outside the control of Redux. Application did not make use of Redux actions and reducers to mutate state. Components do not demonstrate a clear understanding of stateful vs. statelessness.
* 1: Application does not make use of Redux to manage state. There are little or no connected components.

### Routing

* 4: Application is a single page and uses the React Router to display appropriate components based on URL.
* 3: Application is a single page and uses the React Router but does not display the appropriate components upon navigating.
* 2: Application does not render/cannot find additional routes.
* 1: Application did not use a Router

### Workflow

- 4 - Developer(s) make many small, atomic commits that clearly document the evolution of the application and do not contain irrelevant changesets that aren't reflected by the commit message. Commit messages are concise and consistent in syntax and tense. Developer(s) effectively use git branches and pull requests when applicable to incorporate changes into the application, and are not pushing directly to master. There are no instances where the developer(s) have committed source code that should be .gitignored. There are no instances of "dead" or commented-out code and debugger statements like console.log.

- 3 - Developer(s) make many small, atomic commits that document the evolution of the application but sometimes contain irrelevant changesets and inconsistent commit messages. Developer(s) use git branches and pull requests when applicable to incorporate changes into the application, and are not pushing fresh changes directly to master. Pull requests may contain little or no code review. There may be slight instances where the developer(s) have committed source code that should be .gitignored. There may be some instances of "dead" or commented-out code and debugger statements like console.log that need to be cleaned up.

- 2 - Developer(s) make large, inconsistent commits that contain irrelevant changesets and make it difficult to follow the evolution of the application. Developer(s) rarely use git branches and frequently incorporate changes directly into master with little or no review process. There are instances of committed source code that should be .gitignored and instances of dead code and/or debugger statements.

- 1 - Developer(s) make very few commits that each cover too much responsibility and aren't indicative of how the application evolved. Branches and pull requests were not used and changesets were applied directly to master. There are many instances of committed source code that should be .gitignored and many instances of dead code and/or debugger statements.
