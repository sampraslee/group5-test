# Hello Kangkungs!

This is a mini exercise for you to become familiar with Git, GitHub and the basic commands we'll be using throughout our project.

## Your mission, should you choose to accept it...

### Clone this project to your computer

First, we'll need to get a copy of all the files in this project in to your computer. We call this "cloning.".
Click the green < > Code button, then copy the HTTPS URL.

Open your terminal/command prompt (or Git Bash if you're on Windows) and run:

```
git clone [PASTE_THE_URL_HERE]
cd team-intro-project # Go into the newly cloned project folder
```

This command gets a copy of our project from GitHub onto your computer.

### Create a new branch

Before you start changing anything, create your own "branch." Think of a branch like making a copy of the project, but only for your changes. This way, you don't mess up the main project, and others can work at the same time without conflicts.

Let's create a branch named after you, e.g., `feature/your-name`.

Run this command:

```
git checkout -b feature/your-name
```

`git checkout -b` means 'create a new branch and switch to it'. Now you're working in your own safe space because apparently you young people need safe spaces.

### Show me your v-card

```
<v-row class="mt-3" align="center">
      <v-col cols="4">
        <v-card class="elevation-3 rounded-lg">
          <v-card-title>Sam</v-card-title>
          <v-card-text
            >Lorem ipsum dolor sit, amet consectetur adipisicing elit.
            Similique, doloribus?</v-card-text
          >
        </v-card>
      </v-col>
    </v-row>
```

Create a new `v-col` that contains your `v-card`. Provide your name and some random text. Save your work when you're done.

### Add & Commit your changes

You've made changes, but Git doesn't know about them yet. You need to tell Git what files you want to save (git add) and then actually save them with a message (git commit).

Run these commands:

```
git add . # Tells Git to track changes in all files
git commit -m "I've created my v-card!" # This is a message to let people know what you've changed
```

### Push your branch

You've saved your changes locally, but they're not on GitHub yet. To send your branch with your changes to GitHub, you "push" it.

Run this command:

```
git push origin feature/your-name
```

`origin` refers to the GitHub repository. `feature/your-name` is the branch you just pushed.
