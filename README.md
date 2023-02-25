
# Table of Contents

1.  [Natural Yard Project](#org5a48fbc)
    1.  [Resources](#org1fe7050)
        1.  [Emacs text editor](#org56792aa)
        2.  [Revision control](#org7b3ef26)
    2.  [Data Lists](#orgf3f2394)
    3.  [Code](#orge04496a)
    4.  [Theory](#org0577827)


<a id="org5a48fbc"></a>

# Natural Yard Project


<a id="org1fe7050"></a>

## Resources


<a id="org56792aa"></a>

### Emacs text editor

[GNU Emacs](https://www.gnu.org/software/emacs/)

How powerful Emacs can get: 

<https://www.youtube.com/watch?v=lkIicfzPBys&ab_channel=SteveYegge>

<https://www.youtube.com/watch?v=6ZWp05OW1c0>


<a id="org7b3ef26"></a>

### Revision control

[Git Revision Control](https://git-scm.com/docs/gittutorial)

[GitHub](https://github.com/)

1.  Setting up the natural-yard repository

    After creating a GitHub account, statlive, we created a new project, natural-yard. Start by clicking the green "New" button in the root level of your GitHub account.
    ![img](./gitcreate.png)
    
    On our local computer we prepared the directory, building on the github instructions for creating a new repository on the command line.
    
          ~/shared/yardproject $ git init
        Reinitialized existing Git repository in /Users/lchen/shared/yardproject/.git/
        ~/shared/yardproject $ git add README.md ApplicantInformationDatabase.csv gitcreate.png inaturalist-265817.csv tgw tgw.Rmd 
        ~/shared/yardproject $ git commit -m "initial commit"
        [trunk (root-commit) 054dd72] initial commit
         18 files changed, 23385 insertions(+)
         create mode 100644 ApplicantInformationDatabase.csv
         create mode 100644 README.md
         create mode 100644 gitcreate.png
         create mode 100644 inaturalist-265817.csv
         create mode 100644 tgw.Rmd
         create mode 100644 tgw/2022/exports/Export.csv
         create mode 100644 tgw/2022/exports/to1018.csv
         create mode 100644 tgw/2022/exports/to1112.csv
         create mode 100644 tgw/2022/exports/to1121.csv
         create mode 100644 tgw/2022/exports/to1222.csv
         create mode 100644 tgw/2022/exports/to1619.csv
         create mode 100644 tgw/2022/exports/to418.csv
         create mode 100644 tgw/2022/exports/to520.csv
         create mode 100644 tgw/2022/exports/to522.csv
         create mode 100644 tgw/2022/exports/to621.csv
         create mode 100644 tgw/2022/exports/to722.csv
         create mode 100644 tgw/2022/exports/to919.csv
         create mode 100644 tgw/2022/exports/to922.csv
        ~/shared/yardproject $ git branch -M main
        ~/shared/yardproject $ git remote add origin git@github.com:statlive/natural-yard.git
        ~/shared/yardproject $ git push -u origin main
        Enumerating objects: 23, done.
        Counting objects: 100% (23/23), done.
        Delta compression using up to 4 threads
        Compressing objects: 100% (21/21), done.
        Writing objects: 100% (23/23), 1.79 MiB | 2.58 MiB/s, done.
        Total 23 (delta 3), reused 0 (delta 0), pack-reused 0
        remote: Resolving deltas: 100% (3/3), done.        
        To github:statlive/natural-yard.git
         * [new branch]      main -> main
        branch 'main' set up to track 'origin/main'.

2.  Checking out the natural-yard repository

    You can now check out the repository with the command
    
        git clone https://github.com/statlive/natural-yard.git


<a id="orgf3f2394"></a>

## Data Lists

[Harrisonburg Permit Site](https://permits.harrisonburgva.gov/default.aspx)

[Harrisonburg Geographic Information System](https://www.harrisonburgva.gov/GIS)

[iNaturalist](https://www.inaturalist.org/)


<a id="orge04496a"></a>

## Code

Most of the commands and sources needed for working with the three lsts can be found in <./tgw.Rmd>


<a id="org0577827"></a>

## Theory

