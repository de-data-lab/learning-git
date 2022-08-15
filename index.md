---
title: Home
layout: template
---

# Welcome!

Welcome to the Data Lab! To begin your journey, please add yourself as one of the awesome fellows on this website.

# How to add yourself

**Prerequisite**: You need to be added as a member of the repo.

## Go to our GitHub repo and Clone it to your local

You can go to the <a href="{{ site.github.repository_url }}" target="_blank"> GitHub repo</a> and clone the repository to your local machine.

## Open an issue on the repo

Open a GitHub issue on the repo to tell everyone that you are adding yourself.

A rule of thumb for a good issue:

1. A descriptive title
2. A comment that describes what you are doing
3. An assignee

Example:

<img src="https://user-images.githubusercontent.com/17035406/184680715-d8ba6e8e-7bb6-4683-bd6e-988f4c32367a.png">

## Create a development branch

You can create a development branch for your issue. Some ways to do so:

1. On the issue page that you created, you can click "Create a branch": <img src="https://user-images.githubusercontent.com/17035406/184681078-746f40da-5cda-45ab-94a7-31bb11089cd5.png">

2. On your local environment, you can create a branch (`git branch nami/17-add-nami` then `git checkout -b nami/17-add-nami`)

## Create your profile

The profile page is saved in the repo's `/profiles` folder. In that folder, you will find the `_template.md` file for the template for your profile.

1. Copy the `_template.md` file and rename it as your name (e.g., `nami.md`).
2. Edit your `.md` file and save it under the `/profiles` directory.
3. Hack to add image: You can add a profile image by copy-pasting any image file to a GitHub comment area. Then you can use the generated URL in your Markdown file

   ![image](https://user-images.githubusercontent.com/17035406/184685098-d86be806-df65-4394-bd06-44742eb0b56e.png)

## Committing and pushing to remote

You can make commits as you edit the file. Then push your branch to remote (`git push`).

## Open a pull request

Now that you have pushed your development branch to the remote, you are ready to open a pull request. (A **request** for the main branch to **pull changes** from your development branch.)

1. Go to the GitHub repository --> "Pull requests" --> "New pull request"
2. Write the tile for the pull request, preferably starting with a present verb (e.g., "Add Nami as one of the awesome fellows")
3. Write the comment for the pull request
4. Assign a reviewer (another fellow)

## Review another person's pull request

Once you receive an invitation to review another person's pull request, go to the pull request and review changes.

1. Go to "Files changed" tab:

   ![image](https://user-images.githubusercontent.com/17035406/184683933-e0de0bd5-95e2-408c-b508-17abc06ae8d7.png)

2. Review the code
3. If everything looks ok, click "Review changes", write comments, check "Approve", and submit review:

   ![image](https://user-images.githubusercontent.com/17035406/184684017-4b191515-90e5-4828-b872-f2f6daa38041.png)

## Merge your approved pull request

Once you get your pull request approved, you can merge your own pull request. Go to your pull request on GitHub, and click "Merge pull request"
