# Contributing Guidelines

Thanks for your interest in contributing to Plagiarism Checker! Contributing to open source projects like this one are a rewarding way to learn, and build experience. Not only that, contributing is a great way to get involved with social coding. We are excited to see what amazing contributions you will make, as well as how your contributions will benefit others.

If you are new to contributing to open source projects, the process can be quite confusing. Not to worry! To help ensure both you and the community get the most out of your contributions, we've put together the following guidelines.

# Ways of Contributing

A developer can contribute in the following ways:
1. Take a look at the open issues and find one you can tackle.
2. Locate and fix bugs.
3. Ideate and implement new features.
4. Improve tooling and testing.
5. Improve the code quality.

# Ground Rules of contribution

Kindly check the [code of conduct](CODE_OF_CONDUCT.md) prior to contributing.

# How to Contribute

If you'd like to contribute, a good place to start is by searching through the issues and pull requests to see if someone else had a similar idea or question.

If you don't see your idea listed, and you think it fits into the goals of the project, you should:

1. Minor Contribution (e.g., typo fix): Open a pull request
2. Major Contribution (e.g., new feature): Start by opening an issue first. That way, other people can weigh in on the discussion and planning before you do any work.

# Steps to contribute

1. Fork the project.
2. Clone the your fork.

```bash
git clone https://github.com/<YOUR-USERNAME>/sw_frontend
```

3. Add a new remote to upstream

```bash
git remote add upstream https://github.com/Entriz/sw_frontend
```

4. Create a new branch from the current branch

```bash
git checkout -b <YOUR-NEW-BRANCH>
```

5. Work on the new branch.

6. Add or change documentation as needed.

7. Before pushing the code, pull from upstream and check if there are any conflicts. If so solve them and then push the code.

```bash
git pull --rebase upstream master
```

8. Push the code to the origin

```bash
git push origin <YOUR-NEW-BRANCH>
```

9. From your forked repository, open a new pull request to the project's development branch.

10. Once the pull request is approved and merged, you can pull the changes from upstream to your local repository and delete your extra branch(es).

Happy Coding!

## Before Submitting a PR

<em>Please do this everytime you submit a PR</em>

1. Sync your fork to keep it up-to-date with the upstream repository following the next commands or this [tutorial](https://help.github.com/articles/syncing-a-fork/). First fetch the upstream repo and its commits -commits will be stored on your local fork- and then merge changes from upstream to your local:

   ```
   $ git fetch upstream
   $ git merge upstream/master
   ```

2. Check if your changes are correct and don't break the website render by typing `npm run start`.
3. Commit the files you have changed, type:

   ```
   $ git add -A
   $ git commit -m "add a message to your commit"
   $ git push
   ```

4. Before submitting the PR, make sure to run `npm run format` on your project-directory to make the code properly formatted.
5. Commit to your repository at your github account and create a new PR. Click the _Pull Request_ tab on your fork page and then click the green button _New Pull Request_.

### PR Format

_The Pull-Request should contain the following information._

1. Fix: #issue_number
2. Feature Added/Changed
