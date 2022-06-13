#### What is GitHub Pages?

Websites for you and your projects. Hosted directly from your GitHub repository. Just edit, push, and your changes are live.

Ready to get started? Build your own site from scratch or generate one for your project. You get one site per GitHub account and organization, and unlimited project sites. Let's get started. User or organization site Project site Create a repository Head over to GitHub and create a new public repository named username.github.io, where username is your username (or organization name) on GitHub.

If the first part of the repository doesn't exactly match your username, it won't work, so make sure to get it right.

#### client

Clone the repository Go to the folder where you want to store your project, and clone the new repository:

Enter the project folder and add an index.html file:

```bash
git clone https://github.com/username/username.github.io
cd username.github.io
echo "Hello World" > index.html 
```

Push it

Add, commit, and push your changes:

```bash
git add --all
git commit -m "Initial commit"
git push -u origin main 
```

…and you're done! Fire up a browser and go to `https://username.github.io`.

Now that you're up and running, here are a few things you should know.

#### Blogging with Jekyll

Using Jekyll, you can blog using beautiful Markdown syntax, and without having to deal with any databases. Learn how to set up Jekyll.

#### Custom URLs

Want to use your own custom domain for a GitHub Pages site? Just create a file named CNAME and include your URL. Read more.

#### Guides

Learn how to create custom 404 pages, use submodules, and learn more about GitHub Pages.