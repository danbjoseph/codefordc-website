# Contributing to the Code for DC Website

Want to contribute to the Code for DC website? Awesome! We welcome pull requests from anyone who wants to help improve the project. Here are some steps to follow:

## Step 1: Create a new branch

Before you start working on a feature, it's best to create a new branch off of the `master` branch. This will allow you to work on your changes without messing with the main codebase. To create a new branch, run the following command in your terminal:
```bash
git checkout -b <your-new-branch-name>
```
Replace `<your-new-branch-name>` with the name you want to give your new branch.

## Step 2: Make changes to the code

Once you have a new branch, it's time to start making changes! Open the `Code for DC` repository in your favorite code editor or IDE, and start modifying files and adding new features. Be sure to follow our coding style guidelines (available on GitHub) so that your changes look nice and neat among the rest of the code.

## Step 3: Commit your changes

Once you've made some changes, commit them to your branch by running the following command in your terminal:
```bash
git add .
git commit -m "Your commit message goes here"
```
Be sure to include a meaningful commit message that describes what you changed and why. This will help others understand your changes when they review your PR.

## Step 4: Push your branch to your fork

Now that you have committed your changes, push them to your own fork of the `Code for DC` repository on GitHub. This will create a new remote branch with your changes. To do this, run the following command in your terminal:
```bash
git push origin <your-new-branch-name>
```
Replace `<your-new-branch-name>` with the name of your new branch.

## Step 5: Create a Pull Request

Once you have pushed your changes to your own fork, it's time to create a pull request! Go to the `Code for DC` repository on GitHub and click the "New pull request" button. Select the branch you want to merge (in this case, your new branch), add a title and description of your changes, and click "Create pull request."

## Step 6: Wait for feedback and address comments

Once you've created a pull request, it will initiate a CircleCI build that runs a series of checks on your changes. You can watch the build process in real-time on the `Code for DC` repository page. If there are any failures or issues with your code, you'll see them highlighted in the build results. Don't worry – this is a normal part of the contribution process! Just address any comments or requests from reviewers and resubmit your PR when you're ready.

## Step 7: Request a review by a project contributor

Once you've addressed all comments and issues with your pull request, you can request a review from a project contributor. Just click the "Request a review" button on the right side of the PR card, and a contributor will take a look at your changes.

## Step 8: Get merged!

Once a project contributor has reviewed your changes and approved them, they'll merge your pull request into the `master` branch! An updated version of the website will automatically be deployed, and you can see the results in action at <your-website-url>.

And that's it! With these steps, you should be able to contribute to the Code for DC website with ease. If you have any questions or get stuck at any point, feel free to ask for help in the `#codefordc-website` slack channel. Happy coding!
