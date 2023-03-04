# ReactPlay Docs
Official documentation for ReactPlay 

## What is ReactPlay
`react-play` is an open-source web app that helps you learn ReactJS faster with a hands-on practice model. It is a collection of ReactJS projects you can use to learn ReactJS.

Is that all? Nope. You can also create your projects and share them with the world. The best part is that the ReactJS experts will review your project code before it gets part of the ReactPlay app. Isn't that a pure WIN-WIN?

## How to contribute to this repo?

You can contribute to this repo in several ways:
1. Write documentation for the various parts of ReactPLay
2. Suggest changes to the existing docs
3. Improve the documentation website

To contribute, you must set up this repository on your local machine. Here is a brief guide on setting up the repo on your local machine:

### 🍴 Fork and Clone the Repo
First, you need to fork the `docs` repo. You can do this by clicking the `Fork` button on the top right corner of the repo. If you are new to forking, please watch this [YouTube Guide](https://www.youtube.com/watch?v=h8suY-Osn8Q) to get started.

Once forked, click the bright green `<> Code` button and the URL.

Now open the destination directory in the terminal and execute the following command:

```bash
git clone <URL_LINK>
```
Here the `URL_LINK` is the same link you coped in the previous step.


Please change the directory after cloning the repository using the cd <folder-name> command.

### ⬆ Set Upstream
We recommend setting an upstream repo to make pulling and fetching easier. Execute the following command in the terminal:

```bash
git remote add upstream https://github.com/reactplay/docs
```

Check if the upstream has been added by executing the following command:

```bash
git remote -v
```

### 🌴 Create a branch
Ideally, you must create a separate branch for each issue you are working on. Here is how to create a new branch locally

```bash
git checkout -b <branch-name>
``` 
Keep the branch name clear and straightforward. The `-b` command switches the current branch to the newly created branch. 

You are ready to start working on the issue!

### 👨‍💻 Make changes
You need to install dependencies before you start working on the website. Make sure you are in the same directory as your repo's `package.json` and execute either of the following commands:

```bash
yarn install
```

We recommend using Yarn. But feel free to use NPM as well:
```
npm install
```

To start a local development server, enter the following command:

```bash
yarn start
````

Or, for NPM:
```bash
npm run start
```

The local development server will start on localhost:3000

### 🔒 Commit and Push
You can save your changes by committing them. Committing once you have made significant changes to the repo is recommended. Execute the following commands:

```bash
git add .
git commit -m "<massage>"
git push -u origin <branch-name>
```
The `message` should be a descriptive text defining your changes since the last commit.
The `branch-name` is the branch name you created before working on this issue.

You can create multiple commits before pushing the code.
