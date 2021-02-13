# Contributing to VSCode SFTP Revived

- [Contributing to VSCode SFTP Revived](#contributing-to-vscode-sftp-revived)
  - [Ground rules](#ground-rules)
  - [Your first contribution](#your-first-contribution)
  - [Submitting a contribution](#submitting-a-contribution)
  - [How to report a bug](#how-to-report-a-bug)
  - [How to suggest a feature or enhancement](#how-to-suggest-a-feature-or-enhancement)
  - [Code review process](#code-review-process)
  - [Commits and writing commit messages](#commits-and-writing-commit-messages)
  - [Style guide](#style-guide)

Thank you for considering contributing to VSCode SFTP Revived!  We need all the help we can get to get
this tool up and running for the first release.

Following these guidelines helps to communicate that you respect the time of the developers managing
and developing this open source project.  In return, they will do everything they can with the time
they have to address your issue, assess changes, and help you finalize your pull requests.

VSCode SFTP Revived is a fork from the [VSCode SFTP plugin](https://github.com/liximomo/vscode-sftp.git) 
by [liximomo](https://github.com/liximomo).  We love to receive contributions from our community.
There are many ways to contribute, from writing tutorials or blog posts, improving the documentation,
submitting bug reports and feature requests or writing code which can be incorporated into VSCode
SFTP Revived itself.

Please do not open pull requests for code style changes.  When changing, adding, or removing code,
keep the original style intact.  This includes the use of autoformatters like 
[Prettier](https://github.com/prettier/prettier).

## Ground rules

Responbilities:

- Ensure all unit tests pass when open pull requests on the code base.
- Create issues for any major changes and enhancements that you wish to make.  Discuss things
transparently and get community feedback.
- Be welcoming to newcomers and encourage new contributors.

## Your first contribution

Not sure where to begin contributing to VSCode SFTP Revived?  You can start by looking through the
beginner and help-wanted issues.  These may include small code changes or documentation updates.

If you are completely new to contributing to open source, here are a couple of tutorials for making 
your first pull request:

- [Make a pull request](http://makeapullrequest.com)
- [First timers only](http://www.firsttimersonly.com)
- [How to contribute to an open source project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)

If a maintainer asks you to rebase your PR, they're saying that a lot of code has changed, and that
you need to update your branch so it's easier to merge with a `git rebase develop {your-branch}`.

At this point you are ready to make changes.  Feel free to ask for help!

## Submitting a contribution

Try not to open huge code PRs.  They are difficult to review, maintain, and easy for bugs to
get through.  Small, incremental changes are safer and cleaner.

For all contributions:

1. Create your own fork of the code.
2. Create a branch off of the "develop" branch in your fork.
3. Make your changes in your branch on your fork.
4. If it is a **code change**, add, update, or remove unit tests if necessary and make sure all other unit tests pass.
5. Open a pull request against the upstream project's develop branch.

The pull request should have a description of what changed that just isn't a summary of your commit messages.
You don't need to be overly descriptive on the pull request, but it should at least answer the following
questions:

1. What was the issue being fixed?
2. Why was it needed?
3. How was it fixed?

## How to report a bug

When filing an issue, make sure to answer these five questions:

1. Which version of VSCode are you using?
2. Which version of the plugin are you using?
3. What do your configuration files for VSCode SFTP Revived look like?
4. What have you tried to find a solution to your problem?
5. What do the debug logs say?
6. Is your question clear, descriptive, and to-the-point?

## How to suggest a feature or enhancement

The VSCode SFTP Revived project's philosophy is to provide a well-maintained and working SFTP
plugin for VSCode.

If you find yourself wishing for a feature that doesn't exist in VSCode SFTP Revived, you are probably
not alone.  There are bound to be others out there with similar needs.  Open an issue on our
issues list on GitHub which describes the feature you would like to see, why you need it, and how
it should work.

## Code review process

The repository owner (TomaisLeannan) looks at all pull requests on a daily basis, but this doesn't mean
that he will merge it the same day you open your PR.  Feedback may be requested, or a discussion may 
ensue.  Sometimes it takes awhile to review large PRs.  After feedback has been given we expect responses
within two weeks.  After two weeks we may close the pull request if it isn't showing any activity.  You can
always reopen it after the two week period without penalty.

## Commits and writing commit messages

Commits should be as small as possible.  Don't open your PR until your code is completely working,
but you are welcome to perform commits as often as you'd like.  All PRs are merged with a merge commit.

Don't worry about writing overly detailed commit messages.  Keep them to 72 characters in length at most.
The following command is what we usually use to write commit messages, although you can use your
preferred method.

`git commit -m "A brief description of what changed"`

## Style guide

Try to keep the code style the same as liximomo wrote it.  If you can't or have a suggestion for improvement,
open an issue and we can start a discussion.  Just remember to keep style consistent throughout the code.
It's confusing for others to see different syntax for the same thing in the same codebase, which is common when
multiple people work on the same project.
