<p align="center">
    <img src="./intro-01/resources/header.png" >
</p>

# Openathon - Angular

Welcome to a new version of **Openathon - Angular** where we will have the opportunity to discover, in a practical way, the possibilities offered by this leading framework in the **market**.

> This is an updated version to 2023 for the Openathon edition organized for the **Accenture Technology Custom Software Engineering** in Spain that took place in 2019.

- [Openathon - Angular](#openathon---angular)
  - [The target application: Open Events](#the-target-application-open-events)
  - [Labs](#labs)
  - [Prerequisites](#prerequisites)
    - [1. Visual Studio Code](#1-visual-studio-code)
    - [2. Node.js](#2-nodejs)
    - [3. Angular CLI](#3-angular-cli)
    - [4. Angular DevTools](#4-angular-devtools)

## The target application: Open Events

**Open Events** is a solution that will allow us to register and retrieve the different technology events that are interesting for the **CSE Communities**.

The **Front-end** component will be developed using **Angular**. We are going to learn step by step during the next laboratories not only Angular theory but general **Architecture Good Practices** and **Main Principles**.

We will finish with a fully working web app using mocked data.

Open Events **functionalities**:

- Landing page: Intro and description. Shortcuts.
- Menu
  - Home
  - Events
    - See events
      - List (with filters as last, location…)
      - Event page selected with details
    - Find events (filters)
    - Create event (with categories)
    - Delete event
    - Edit event
    - Your events (as organizer)
  - Login-Register
    - Register page
    - Login page
  - Profile
    - See profile
    - Edit profile
    - Delete profile

And a simple navigation map would be:<br/>

<p align="center">
    <img src="./intro-01/resources/nav-map.png" width="700">
</p>

## Labs

This Openathon is divided in the following theory and laboratories:

| Lab                   | Title                                                   |
| --------------------- | ------------------------------------------------------- |
| [Intro 01](/intro-01) | What is Angular                                         |
| [Intro 02](/intro-02) | Main Principles, Solid Practices and Code Quality       |
| [Lab 1](/lab-01)      | Starting a New Angular Project                          |
| [Lab 2](/lab-02)      | Angular Basics                                          |
| [Lab 3](/lab-03)      | Routing Basics                                          |
| [Lab 4](/lab-04)      | Services                                                |
| [Lab 5](/lab-05)      | Routing 2 and CRUD                                      |
| [Lab 6](/lab-06)      | Central State management                                |
| [Lab 7](/lab-07)      | Style and Deploy (extra bonus optional for code ninjas) |

## Prerequisites

### 1. Visual Studio Code

**Visual Studio Code** is a source code editor with support for debugging, embedded Git control, syntax highlighting, intelligent code completion, snippets, and code refactoring.

[Click here](https://code.visualstudio.com/) to download and install.

### 2. Node.js

**Node.js** is a free, open source server environment that runs on various platforms (Windows, Linux, Unix, Mac OS X, etc.) using the JavaScript runtime built on Chrome's V8 JavaScript engine.

[Click here](https://nodejs.org/en/download/) to download and install an active LTS or maintenance LTS version.

This will also install **npm**, the package manager for Node.js and the world's largest software registry.

### 3. Angular CLI

Open your terminal or command prompt and run:

```sh
npm install -g @angular/cli
```

**Angular CLI** is a command-line interface tool used to initialize, develop, scaffold, and maintain Angular applications.

[Click here](https://cli.angular.io/) to know more.

> Depending on your computer and operating system, some dependencies will not be installed and you can get warnings during installation process. In the same terminal or a new one run:
>
> ```sh
> ng v
> ```
>
> If everything is fine, a list of Angular CLI and Node version should appear.

### 4. Angular DevTools

**Angular DevTools** is a browser extension that provides debugging and profiling capabilities for Angular applications. Angular DevTools supports Angular v12 and later when compiled with the [optimization configuration option](https://angular.io/guide/workspace-config#optimization-configuration) disabled (`{optimization:false}`).

[Click here](https://chrome.google.com/webstore/detail/angular-devtools) to download and install in your Chrome browser

[Start here: What is Angular](./boring-theory-1)
