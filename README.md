<p align="center">
  <h1 align="center"><a href="https://codeforaustralia.github.io/seechange/">SeeChange (aka. Civic Makers Climate-Change) Project</a></h1>

  <p align="center">
    An awesome README to tell you everything you need to know about this project.
  </p>
</p>

## Table of Contents

- [About the Project](#about-the-project)
- [Built With](#built-with)
- [Getting Started](#getting-started)
- [Accessing the Application](#accessing-the-application)
- [How to Deploy the Application](#how-to-deploy-the-application)
- [Contributing](#contributing)
- [Asking for help](#asking-for-help)
- [Project Conventions](#project-conventions)
- [Contributors](#contributors)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

<!-- ABOUT THE PROJECT -->

## About The Project

This is a website that will inform visitors about the following:

- Why act on climate change now?
- What you can do about it?
- Why you should get all your friends and family to help too.
- Timeline of significant climate-change related events (including related Australian Parliament Motions/Bills/Divisions).
- Which Members of Parliament (MP) voted for/against motions/bills/divisions.
- MP statistics of their previous voting record and a measure of how accountable they are of keeping their promises.
- Contact forms to MPs to influence their future decisions.
- How to share the above information with others.

<!-- GETTING STARTED -->

## Getting Started

Follow the instructions below to set up your local development environment.

The instructions will guide you to deploy two services locally:

0. Open a command line interface (Terminal on mac or equivalent on windows)

   - Tip: For a linux/mac experience on Windows, you can download https://cmder.net/.

1. If you are a MAC user, please install Xcode using the following command

```
xcode-select --install
```

2. Install nvm, a version manager for node.js (for more information see: https://github.com/nvm-sh/nvm)

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.0/install.sh | bash

export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm

nvm --version

```

3. Clone the project source code.

```
git clone https://github.com/CodeforAustralia/seechange.git
```

4. Navigate into the project directory.

```
cd seechange
```

5. Install node using nvm:

```
nvm install
nvm use
```

6. Double check you are using the right version of node by typing the following command. the version number should match the version number mentioned in [.nvmrc](./.nvmrc) file:

```
$ cat .nvmrc
14.15.1

$ node --version
v14.15.1
```

7. To start up the client service run npm install

```
npm install
```

run npm start

```
npm start
```

8. Go to http://localhost:3000/ . You should see a short welcome message if the app is running.

## Accessing the Application

The application is currently hosted on [Github Pages](https://codeforaustralia.github.io/seechange/).

On your local development instance, enter `http://localhost:3000` into any web-browser to view the app.

## How to deploy the application

The application is currently hosted on [Github Pages](https://codeforaustralia.github.io/seechange/).

To deploy the app to Github Pages, run the following commands:

```
npm run deploy
```

The command will perform the following actions:

1. build the react app (using `npm run build`)
2. push the build artifacts to the `gh-pages` branch

This repo has been set up to serve the content in `gh-pages` branch on Github Pages

The [`gh-pages` tool](https://create-react-app.dev/docs/deployment/#github-pages) was used to ease the deployment of this app.

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
2. Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
3. Push to the Branch (`git push origin feature/AmazingFeature`).
4. Open a Pull Request (PR).
5. After 1-2 approvals, the PR will be merged.

## Asking for Help

- Please ask on our slack channel [#civic-makers-climatechange-dev](https://app.slack.com/client/T02A8KY38/C01DALXS62K) if you:
  - have any questions regarding any of the tasks in our [Trello board](https://trello.com/b/ZXaIkclp)
  - have any questions relating to the development of the climate change app
  - need help with a task you are working on from the [Trello board](https://trello.com/b/ZXaIkclp)
  - have any other questions/proposals you'd like to put to the dev team
- please be patient with our response, as most of us are only working on this in our spare time
- If you like to find out more about what everyone is working on, please come to our weekly Wednesday evening catchups to meet the team! Please ask on [#civic-makers-climatechange](https://app.slack.com/client/T02A8KY38/C01CXCQPF8V) slack channel to get an invite.
- Some of the dev folk will usually hang around after the catchup to discuss on outstanding issues and do some remote pair/mob programming. But if the timing doesn't work for you, don't fret, please ask on [#civic-makers-climatechange-dev](https://app.slack.com/client/T02A8KY38/C01DALXS62K) to arrange a more suitable time to pair!

## Project Conventions

- [React functional components](https://programmingwithmosh.com/react/react-functional-components/) (with hooks)
- [camelCase](https://techterms.com/definition/camelcase) for function/method names.

## Contributors

- [hqtan](https://github.com/hqtan)
- [k7n4n5t3w4rt](https://github.com/k7n4n5t3w4rt)
- [izzypeskett](https://github.com/izzypeskett)
- [mcyph](https://github.com/mcyph)
- [VasaviGannena](https://github.com/VasaviGannena)
- [Amutha37](https://github.com/Amutha37)
- [rjkr007](https://github.com/rjkr007)
- [mishfish123](https://github.com/mishfish123)
- [mansisheth13](https://github.com/mansisheth13)
- [annemariejayatilake](https://github.com/annemariejayatilake)
- [AVu120](https://github.com/AVu120)

## Contact

### Emails

- Esther (project manager) - esther.semo@gmail.com
<!-- Rest TBD -->

<!-- ACKNOWLEDGEMENTS -->

## Acknowledgements

- [Code for Australia](https://codeforaustralia.org/)
