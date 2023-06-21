# LAB - Class 26

## Project: Component Based UI

### Author: Heather Holcomb | 401d53

### Problem Domain

Our application will be an API testing tool that can be run in any browser, allowing a user to easily interact with APIs in a familiar interface.

- Phase 1: Application Setup
  - Basic React Application
  - Scaffolding
  - Basic State
  - Rendering

### Links and Resources

- [GitHub Actions ci/cd](https://github.com/holcombheather/resty/actions)
- [Deployed link on codesandbox.io](https://codesandbox.io/p/github/holcombheather/resty/main?layout=%257B%2522sidebarPanel%2522%253A%2522EXPLORER%2522%252C%2522rootPanelGroup%2522%253A%257B%2522direction%2522%253A%2522horizontal%2522%252C%2522type%2522%253A%2522PANEL_GROUP%2522%252C%2522id%2522%253A%2522ROOT_LAYOUT%2522%252C%2522panels%2522%253A%255B%257B%2522type%2522%253A%2522PANEL_GROUP%2522%252C%2522direction%2522%253A%2522horizontal%2522%252C%2522id%2522%253A%2522EDITOR%2522%252C%2522panels%2522%253A%255B%257B%2522type%2522%253A%2522PANEL%2522%252C%2522panelType%2522%253A%2522TABS%2522%252C%2522id%2522%253A%2522clj4xxrxy000b3b6m052trjvd%2522%257D%255D%252C%2522sizes%2522%253A%255B100%255D%257D%252C%257B%2522type%2522%253A%2522PANEL_GROUP%2522%252C%2522direction%2522%253A%2522horizontal%2522%252C%2522id%2522%253A%2522DEVTOOLS%2522%252C%2522panels%2522%253A%255B%257B%2522type%2522%253A%2522PANEL%2522%252C%2522panelType%2522%253A%2522TABS%2522%252C%2522id%2522%253A%2522clj4xxrxy000d3b6ml1utb33r%2522%257D%255D%252C%2522sizes%2522%253A%255B100%255D%257D%255D%252C%2522sizes%2522%253A%255B50%252C50%255D%257D%252C%2522tabbedPanels%2522%253A%257B%2522clj4xxrxy000b3b6m052trjvd%2522%253A%257B%2522tabs%2522%253A%255B%257B%2522id%2522%253A%2522clj4xxrxy000a3b6mu2ilat2d%2522%252C%2522mode%2522%253A%2522permanent%2522%252C%2522type%2522%253A%2522FILE%2522%252C%2522filepath%2522%253A%2522%252FREADME.md%2522%257D%255D%252C%2522id%2522%253A%2522clj4xxrxy000b3b6m052trjvd%2522%252C%2522activeTabId%2522%253A%2522clj4xxrxy000a3b6mu2ilat2d%2522%257D%252C%2522clj4xxrxy000d3b6ml1utb33r%2522%253A%257B%2522id%2522%253A%2522clj4xxrxy000d3b6ml1utb33r%2522%252C%2522activeTabId%2522%253A%2522clj4xycuc00do3b6mpa32ns85%2522%252C%2522tabs%2522%253A%255B%257B%2522type%2522%253A%2522TASK_LOG%2522%252C%2522taskId%2522%253A%2522start%2522%252C%2522id%2522%253A%2522clj4xyac1008n3b6mbk8upibu%2522%252C%2522mode%2522%253A%2522permanent%2522%257D%252C%257B%2522type%2522%253A%2522TASK_PORT%2522%252C%2522taskId%2522%253A%2522start%2522%252C%2522port%2522%253A3000%252C%2522id%2522%253A%2522clj4xycuc00do3b6mpa32ns85%2522%252C%2522mode%2522%253A%2522permanent%2522%252C%2522path%2522%253A%2522%252F%2522%257D%255D%257D%257D%252C%2522showDevtools%2522%253Atrue%252C%2522showSidebar%2522%253Atrue%252C%2522sidebarPanelSize%2522%253A15%257D)

### Collaborators

- Referenced demo code from Class 26 lecture taught by Ryan Gallaway

### Setup

1. Clone this repo into your local environment
2. `npm i`
3. `npm start`

#### `.env` requirements (where applicable)

- `PORT` - 3001
- `DATABASE_URL` - see `.env.sample`

#### How to initialize/run your application (where applicable)

- `npm start` or `nodemon`

#### How to use your library (where applicable)

#### Features / Routes

Phase 1 Requirements
1. Convert all child components of `<App />` from classes to functions.
  - The `<App />` component serves as the container for all sub-components of this application.
  - Leave this component as a Class.
  - Make sure all base styles for `<App />` are included in a .scss imported within the App.jsx file.
  - Ensure that the `<Header />`, `<Footer />`, `<Results />` and `<Form />` components are imported using ES6 import syntax.
2. Use .scss files to style each component.
  - Each of the components use their own .scss file for styling.
3. Core application functionality should remain unchanged.
  - The `<Form />` component should:
  - Call a function onSubmit() that updates the `<App />` component via a function sent down as a prop so that the app can process the form values.
  - The `<Results />` component should show mock API results.

#### Tests
- Not required for Lab 26
- `npm test`


#### UML

![UML for Class 26](UML_class26.png)
