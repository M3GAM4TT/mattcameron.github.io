# Hosting a Resume on GitHub Pages

## Purpose
This should explain the practical steps of how to host and format a resume using Markdown, a Markdown editor, GitHub Pages, and Jekyll. Additionally, there should be understandable links to the general principles of current Technical Writing according to Andrew Etter's book *Modern Technical Writing*.

## Prerequisites
You will need:
- A resume formatted in Markdown
- A GitHub account

## Getting Started with GitHub

1. Create a new repository on GitHub with name *username*.github.io (where *username* is your username). There are two ways that this can be done:
    -  Click the green 'New' button on the homepage   
    ![New repo](new_repo.png)   
    -  Click the '+' button located at the top right and select 'New repository'.   
    ![New repo 2](new_repo2.png)    
    - (relates to Etter's book via distributed version control, elaborate)

2. Name your resume file `index.md`. (relates to Etter's book via distributed version control, elaborate)

3. Add your resume to the root of your GitHub repository. This can be done via 'Add file' on the repository webpage:  
    ![Add File](add_file.png)    
 (relates to Etter's book via distributed version control, elaborate)

## Building your Pages site with Jekyll

4. Click over to the 'Settings' tab on your repository. Then scroll down to 'GitHub Pages' and enable it to build from your 'main' branch. (relates to Etter's book via static websites)

5. On the same page, right below the above step, there is a Theme Chooser. This will allow you to choose a Jekyll template. Click on 'Choose a theme', and select one of the given theme options.  
Note: You may want to add a custom theme, which can be done from the same place. However, this tutorial will not cover that. (relates to Etter's book via static websites)

## More Resources

1. [Markdown Tutorial](https://www.markdowntutorial.com/)

2. [Modern Technical Writing by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

3. [GitHub Pages Tutorial](https://pages.github.com/)

## Authors and Acknowledgements
I would like to thank [Matt Graham](https://twitter.com/michigangraham), the author of the Midnight Jekyll template which I used to host my resume.     
Also, I would like to thank my group: Kurt, Ronghan, and Nabeel.

## FAQs
1. "Why is Markdown better than a word processor?"
- Markdown has fewer settings and formatting options; it is simplified and at the same time standardized. As a result, everyone is able to create a similar type of documentation with a relatively small learning curve.
2. "Why is my resume not showing up?
- Make sure GitHub Pages is set up to build from your `main` branch, and that you have your resume in `index.md` located at the root of your repository. 