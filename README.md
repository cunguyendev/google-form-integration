# Google Form Integration - Grow

Create a site with Grow

Author: Vu Nguyen &lt;[nguyendaivu73.qb@gmail.com](nguyendaivu73.qb@gmail.com)&gt;

Deploy to Netlify: [https://google-form-integration-app.netlify.app/](https://google-form-integration.netlify.app/)

## Requirements

- [Node](https://nodejs.org/en/) &gt;=12.0.0 / [npm](https://www.npmjs.com/) &gt;=6.9.0
  - Recommend installing with [nvm](https://github.com/creationix/nvm)
- [Grow](https://grow.io) &gt;=0.8.27

## Getting Started

Step by step to run this app in your local

## Running the development server

Prior to starting the development server, you may have to install dependencies used by your project. The `grow install` command walks you through this and tries to set up your environment for you.

The `grow run` command starts your development server. You can make changes to your project files and refresh to see them reflected immediately.

```
grow install
grow run
```

## Building

You can use the `grow build` command to build your whole site to the `build` directory. This is a good way to test and verify the generated code.

```
grow build
```

## Staging

Once you are ready to share your changes with your team, you can stage your workspace to an access-controlled web server. Running the below command will build your site and deploy it, and then provide you with a link to the staging environment.

```
grow stage
```

_You can update the source structures to follow your patterns._

_Note: Live-reload is not supported_
