# Hosting a Resume on GitHub Pages

## Purpose
This should explain the practical steps of how to host and format a resume using Markdown, a Markdown editor, GitHub Pages, and Jekyll. Additionally, there should be understandable links to the general principles of current Technical Writing according to Andrew Etter's book *Modern Technical Writing*.

## Prerequisites
You will need:
- A resume formatted in Markdown
- A GitHub account

## Getting Started with GitHub

1. Create a new repository on GitHub with name *username*.github.io, where *username* is your username. This can be done via the green 'New' button on the homepage, or via the '+' button next to your profile picture in the top right and selecting 'New repository'. (relates to Etter's book via distributed version control, elaborate)

2. Name your resume file `index.md`. 

3. Add your resume to the root of your GitHub repository. This can be done via 'Add file' on the webpage of the repository or by cloning the repository and adding the file via a commit. 
    - If you want to use the second option, you will have to do a few more things.
    - Go to the folder where you want to store your project and clone the repository by running a `git clone` command.  
    For example, 
        <pre> git clone https://github.com/<i>username</i>/<i>username</i>.github.io         </pre>
        where *username* is your username.
    - Add your `index.md` file to the project folder.
    - Enter the folder from your terminal, add the file via commit, and push the changes.
    For example,
            <pre>cd <i>username</i>.github.io
        git add -all
        git commit -m "Initial commit"
        git push -u origin main </pre>

## Building your Pages site and Jekyll

4. Click over to the 'Settings' tab on your repository, then scroll down to 'GitHub Pages' and enable it to build from your 'main' branch.

5. On the same page, immediately below the above step, there is a Theme Chooser which allows you to 'Choose a theme' from given Jekyll templates. Select this, and choose one of the given theme options.  
Note: You may want to add a custom theme, which can be done from the same place. However, this tutorial will not cover that.

## More Resources

1. [Markdown Tutorial](https://www.markdowntutorial.com/)

2. [Modern Technical Writing by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

3. [GitHub Pages Tutorial](https://pages.github.com/)

## Authors and Acknowledgements

## FAQs
1. "Why is Markdown better than a word processor?"
- Markdown has fewer settings and formatting options; it is simplified and at the same time standardized. As a result, everyone is able to create a similar type of documentation with a relatively small learning curve.
2. "Why is my resume not showing up?
- Have you tried ...?