# Create-Formation-App

> Note: this project is currently in the proposal phase

A command-line tool that helps you bootstrap a new [Formation](https://github.com/AVsync-LIVE/Formation) project quickly and easily.

## Features
- Choose from a series of options to customize your project.
- Create a new project with a single command.
- Includes popular tools and libraries for your project.
- Choose from several different formation starter templates such as blog, personal website, admin dashboard, e-commerce, app with docking, etc
- Includes websockets, custom server, Electron (Nextron), Redux toolkit, Dockerfile and Docker Compose, Typescript, Testing Framework, PWA and Linter.

## Requirements
- Node.js v12+
- npm v6+

## Installation
```sh
npm install -g create-formation-app
```

## Usage
```sh
create-formation-app <project-name>
```

This will create a new directory with the provided project name and set up the project based on the options you have selected.

## Options
- Websockets
- Custom server
- Electron (Nextron)
- Redux toolkit
- Dockerfile and docker compose
- Choose from several different formation starter templates such as blog, personal website, admin dashboard, e-commerce, app with docking, etc
- TypeScript support
- Testing framework
- PWA (Progressive Web App) support
- Linter

## Example
```sh
create-formation-app my-app
```

This command will create a new directory named `my-app` in the current directory and set up the project with the options you have selected.

Once the project is set up, navigate to the project directory and start building your app with Formation.

```sh
cd my-app
npm run dev
```

## Note
This tool uses [create-next-app](https://github.com/zeit/create-next-app) package as a reference and modifies it to include the options specific to Formation.

## Feedback
We're always looking to improve, if you have any suggestions or issues, please open an issue on the [GitHub repository](https://github.com/yourusername/create-formation-app).

## Collaboration
If you're interested in contributing to this project, please reach out to the project
