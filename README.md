# Join Epochry Lab

Welcome to **Epochry Lab**.

If you'd like to join the organization as a contributor, complete this
Git screening task. The purpose of this task is **not to test your
programming skills**, but to verify that you can use Git and GitHub
correctly, follow instructions, and submit work through a proper Pull
Request workflow.

Every applicant must complete this task before being considered for the
organization.

------------------------------------------------------------------------

# Before You Begin

Read these instructions completely before doing anything.

Most incorrect submissions happen because applicants skip steps or don't
read the instructions carefully.

You will need:

-   Git installed on your machine (`git --version` should return a
    version number)
-   A GitHub account
-   Basic knowledge of Git and GitHub
-   Ability to fork repositories, create branches, commit changes, and
    open Pull Requests

If you're new to Git, we recommend learning the basics before attempting
this task.

------------------------------------------------------------------------

# Task Instructions

## Step 1 --- Fork this Repository

Click **Fork** at the top-right of this repository.

Fork it to **your personal GitHub account**.

Do **not** work directly on the Epochry Lab repository.

## Step 2 --- Clone Your Fork

``` bash
git clone https://github.com/YOUR_USERNAME/quickstart.git
cd quickstart
```

## Step 3 --- Create Your Branch

``` bash
git checkout main
git pull origin main
git checkout -b screening/YOUR_GITHUB_USERNAME
```

## Step 4 --- Create Your Submission File

Create:

``` text
submission/YOUR_GITHUB_USERNAME.md
```

## Step 5 --- Complete Your Submission

Your file must contain:

``` md
# Name

# GitHub

# About Yourself

# Why do you want to join Epochry Lab?

# Expected Contribution

# Question
```

## Step 6 --- Commit

``` bash
git add submission/YOUR_GITHUB_USERNAME.md
git commit -m "add screening submission for YOUR_GITHUB_USERNAME"
```

## Step 7 --- Push

``` bash
git push origin screening/YOUR_GITHUB_USERNAME
```

## Step 8 --- Open a Pull Request

Open a PR to **Epochry-Lab/quickstart**.

Title:

``` text
[Application] Your Full Name
```

Description:

-   What you added
-   Why you want to join Epochry Lab

## Step 9 --- Verify

-   [ ] Branch: `screening/your-github-username`
-   [ ] PR targets `Epochry-Lab/quickstart`
-   [ ] File is inside `/submission`
-   [ ] File name is your GitHub username
-   [ ] All required sections are included

------------------------------------------------------------------------

# What We're Looking For

-   Ability to follow instructions
-   Basic Git & GitHub knowledge
-   Proper Pull Request workflow
-   Clear communication
-   Attention to detail

------------------------------------------------------------------------

# Need Help?

Open an Issue titled:

``` text
[Question] Your Name — Your Question
```

Please avoid direct messages for questions that can help everyone.

------------------------------------------------------------------------

**Welcome to Epochry Lab!**
