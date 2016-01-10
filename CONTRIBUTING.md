# Contributing to Zatobo Development

Interested in [Zatobo](https://zatobo.wordpress.com) and want to get involved?
Wow! Well there's plenty of ways you can help!

Please take a moment to review this document in order to make the contribution
process easy for you and us.

Following these guidelines helps to communicate that you respect the time of
the developers managing and developing project (who knows, you might [become one](#devteam)). In return,
they will probably reciprocate that respect.


## Using the issue tracker

The [issue tracker](https://github.com/zatobo/zatobo_dev/issues) is
the preferred channel for [bug reports](#bugs), [features requests](#features)
and [submitting pull requests](#pull-requests), but please respect the following
restrictions:

* **do not** derail or troll issues. Keep the discussion on topic and
  respect the opinions of others.

* **do not** open issues or pull requests regarding here regarding problems or
repository that is set up for your project.  Check [this link](http://github.com/zatobo/zatobo_dev/placeholder.rm)
for getting help.


<a name="bugs"></a>
## Bug reports

A bug is a _demonstrable problem_ that is caused by the code in the repository.
Good bug reports are extremely helpful - thank you!  Of course... in Ver. 0.0.1
we don't have code.  So this is more likely to be a problem you find with using
Zatobo.

Guidelines for bug reports:

1. **Use the GitHub issue search** &mdash; check if the issue has already been
   reported.

2. **Check if the issue has been fixed** &mdash; try to reproduce it using the
   latest `master` or development branch in the repository.

3. **Isolate the problem** &mdash; ideally create a [reduced test
   case](https://css-tricks.com/reduced-test-cases/) and a live example.

A good bug report shouldn't leave developers needing to bother you for more
information. Please try to be as detailed as possible in your report. What is
your environment? What steps will reproduce the issue?  Any thoughts on the cause
All these details will help people to fix any potential bugs.

Example:

> Short and descriptive example bug report title
>
> A summary of the issue and the browser/OS/publishing software environment in which 
>it occurs. If
>suitable, include the steps required to reproduce the bug.
>
> 1. This is the first step
> 2. This is the second step
> 3. etc.
>
> Screenshots can be very helpful!
>
> Any other information you want to share that is relevant to the issue being
> reported. This might include the file and lines that you found as
> causing the bug, and any potential solutions you might have found.


<a name="features"></a>
## Feature requests

Feature requests are welcome. But please think about whether your idea
fits with the scope and aims of the project.  *You* need to make a strong
case to convince the project developers of the merits of including this feature. Please
provide as much detail and context as possible.


<a name="pull-requests"></a>
## Pull requests

Good pull requests - patches, improvements, new features - are a fantastic
help. They should remain focused in scope and avoid containing unrelated
commits.

###Please ask first
before embarking on any significant pull request, otherwise you risk spending 
a lot of time working on something that the project's developers might not want
to merge into the project.

Please adhere to the coding conventions used throughout a project (indentation,
accurate comments, etc.) and any other requirements.

Adhering to the following process is the best way to get your work
included in the project:

1. [Fork](https://help.github.com/articles/fork-a-repo/) the project, clone your
   fork, and configure the remotes:

   ```bash
   # Clone your fork of the repo into the current directory
   git clone https://github.com/<your-username>/zatobo_dev.git
   # Navigate to the newly cloned directory
   cd zatobo_dev
   # Assign the original repo to a remote called "upstream"
   git remote add upstream https://github.com/zatobo/zatobo_dev.git
   ```

2. If you cloned a while ago, get the latest changes from upstream:

   ```bash
   git checkout master
   git pull upstream master
   ```

3. Create a new topic branch (off the main project development branch) to
   contain your feature, change, or fix:

   ```bash
   git checkout -b <topic-branch-name>
   ```

4. Commit your changes in logical chunks. Adhere to these [git commit
   message guidelines](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
   Or it could take more time to figure out what is going on and your pull might be ignored. Use Git's
   [interactive rebase](https://help.github.com/articles/about-git-rebase/)
   feature to tidy up your commits before creating your pull request.

5. Locally merge (or rebase) the upstream development branch into your topic branch:

   ```bash
   git pull [--rebase] upstream master
   ```

6. Push your topic branch up to your fork:

   ```bash
   git push origin <topic-branch-name>
   ```

7. [Open a Pull Request](https://help.github.com/articles/using-pull-requests/)
    with a clear title and description.

**IMPORTANT**: By submitting a patch, you agree to allow the project
owners to license your work under the terms of the [license attached to the project](license.txt)

<a name="devteam"></a>
## Joining the Team
We are looking for your help! Are you a developer or designer interested in getting more involved with this project?  Well then [contact us](mailto: mail.zatobo@gmail.com)!  We are small but always growing and looking for people excited about the project.
