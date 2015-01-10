#PROJECT TITLE
[Funded by Biomedical Research Centre](http://core.brc.iop.kcl.ac.uk): http://core.brc.iop.kcl.ac.uk

*Institution: NIHR Maudsley Biomedical Research Centre For Mental Health and Dementia Unit (Denmark Hill), at The Institute of Psychiatry, Psychology & Neuroscience (IoPPN), Kings College London* 

Author(s):

Release Version:

## Please use this template for BRC projects
We are going to try and have some consistent branding on BRC-MH projects. Please use this template project as stub for your work, see the instructions below.

*NOTE* You need a GitHub account and to be a member of the KHP-Informatics Repo (via invite).

1) clone this template repo.

    $ git clone git@github.com:KHP-Informatics/BRC-U_git_template.git

2) Delete the .git in BRC-U_git_template folder, so you can start from scratch.

    $ rm -rf ./BRC-U_git_template/.git
   
3) Rename the BRC-U_git_template/ folder to your chosen name:

    $ mv BRC-U_git_template <New-Repository-Name> 

4) Create a project in GitHub **+New Repository** button with "**New-Repository-Name**" to act as your remote. Now we want to specify to our local git repository what the remote repository on Github is. In your top level folder (i.e. New-Repository-Name/ ):
    
    $ cd New-Repository-Name/
    $ git init
    $ git remote add <remote URL>
    # NOTE: you can get the remote URL from your newly created github project (the ssh_ git@github.com:KHP-Informatics/New-Repository-Name.git url if you want passwordless access or https https://github.com/KHP-Informatics/New-Repository-Name.git url will require a password) 
 
5) Edit this README.md with the relevant information to your project.
    If you are not familiar with markdown see: [git markdown](https://guides.github.com/features/mastering-markdown/)

6) create your first commit
    $ git add .
    $ git commit -m "First Commit"
    $ git push origin master

7) Copy in any further files, code etc. then *git add*, *git commit* and *git push* as above to send any new commits to the GitHub remote.

    
   
![Kings Health Partners](figures/brc-u-logos/KHP_M_oneline_descriptor_strapline_hr_CMYK-e1409244956134.jpg)
