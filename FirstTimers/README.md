## How to contribute to this project
Here are 3 quick and painless ways to contribute to this project:

* Add your name to the `CONTRIBUTORS.md` file
* Add a profile page to the `profiles` directory
* Create a simple "Hello, World" script in a language of your choice

Choose one or all 3, make a pull request for your work and wait for it to be merged!

## A Guide to Get Started

1. Check out [Andrei's videos on github](https://www.udemy.com/the-complete-web-developer-in-2018/learn/v4/t/lecture/8725782/) or this free how-to tutorial at http://makeapullrequest.com/.

2. On the [GitHub page for this repository](https://github.com/geekyvyas/GithubBeginners), click on the Button "Fork".

   ![fork image](https://help.github.com/assets/images/help/repository/fork_button.jpg)

3. Clone _your forked repository_ to your computer:

   ![code ui](https://docs.github.com/assets/images/help/repository/code-button.png)

    For example, run this command inside your terminal:

    ```bash
    git clone https://github.com/<your-github-username>/GithubBeginners.git
    ```

    **Replace \<your-github-username\>!**

    Learn more about [forking](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) and [cloning a repo](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).


4. Before you make any changes, [keep your fork in sync](https://www.freecodecamp.org/news/how-to-sync-your-fork-with-the-original-git-repository/) to avoid merge conflicts:

    ```bash
    git remote add upstream https://github.com/geekyvyas/GithubBeginners.git
    git pull upstream master
    ```

    If you run into a **merge conflict**, you have to resolve the conflict. There are a lot of guides online, or you can try this one by [opensource.com](https://opensource.com/article/20/4/git-merge-conflict).

5. On your computer, open your text editor, and add your name to the `CONTRIBUTORS.md` file.

6. Add the changes with `git add`, `git commit` ([write a good commit message](https://chris.beams.io/posts/git-commit/), if possible):

    ```bash
    git add CONTRIBUTORS.md
    git commit -m "Add <your-github-username>"
    ```

    **Replace \<your-github-username\>!**

7. Push your changes _to your repository_:

    ```bash
    git push origin master
    ```

8. Go to the GitHub page of _your fork_, and make a pull request:

    ![pull request image](https://help.github.com/assets/images/help/pull_requests/choose-base-and-compare-branches.png)

    Read more about pull requests on the [GitHub help pages](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

9. Wait until Zerobot or one of the maintainers merges your pull request. If there are any conflicts, you will get a notification.

* Create a new pull request from your forked repository (Click the `New Pull Request` button located at the top of your repo)
* Wait for your PR review and merge approval!
* __Star this repository__ if you had fun!

## Choose from these tasks
### 1. Add your name
Add your name to the `CONTRIBUTORS.md` file using the below convention:

```markdown
#### Name: [YOUR NAME](GitHub link)
- Place: City, State, Country
- Bio: Who are you?
- GitHub: [GitHub account name](GitHub link)
```

### 2. Add a profile page
Add a `Your_Name.md` file to the `profiles` directory. Use any combination of content and Markdown you'd like. Here is an example:

```markdown
# Your Name

### Location

Your City/Country

### Academics

Your School

### Interests

- Some Things You Like

### Development

- Inventor of the My Pillow

### Projects

- [My Project](GitHub Link) Short Description

### Profile Link

[Your Name](GitHub Link)
```

### 3. Create a `Hello, World!` Script
Add a `hello_world_yourusername.xx` script to the `scripts` directory in any language of your choice! Here is an example:

```Javascript
// LANGUAGE: Javascript
// ENV: Node.js
// AUTHOR: Alice Chuang
// GITHUB: https://github.com/AliceWonderland

console.log('Hello, World!');
```

Name the file `hello_world_yourusername.xx`. e.g., `hello_world_alicewonderland.js` or `hello_world_alicewonderland.py`.

Don't forget to include the comments as seen above. Feel free to include additional information about the language you choose in your comments too! Like a link to a helpful introduction or tutorial. 

Here is my `hello_world` example: [hello_world_alicewonderland.js](https://github.com/AliceWonderland/hacktoberfest/blob/master/scripts/hello_world_alicewonderland.js)


## Reference links
Here is a great tutorial for creating your first pull request by [Roshan Jossey](https://github.com/Roshanjossey):
[https://github.com/Roshanjossey/first-contributions](https://github.com/Roshanjossey/first-contributions)

Managing your Forked Repo: [https://help.github.com/articles/fork-a-repo/](https://help.github.com/articles/fork-a-repo/)

Syncing a Fork: [https://help.github.com/articles/syncing-a-fork/](https://help.github.com/articles/syncing-a-fork/)

Keep Your Fork Synced: [https://gist.github.com/CristinaSolana/1885435](https://gist.github.com/CristinaSolana/1885435)

Checkout this list for README examples - Awesome README [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Github-Flavored Markdown [https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)

## Additional references added by contributors
GitHub license explained [https://choosealicense.com](https://choosealicense.com)

