# My-Hugo-Website-2
Another Hugo Meghana Theme 
[View Website](https://haroldsumbrana.github.io/My-Hugo-Website-2/)
![hugomeghana](https://user-images.githubusercontent.com/30718575/49096589-ceed8b80-f2a5-11e8-8dd6-4396dd652c77.png)
1. hugo new site (project name)
2. cd (project name)
3 vim config.toml = edit config.toml
4. go to themes.gohugo.io = select theme to use
5. in github directory copy the github link
6. git init and then git submodule add (githubUrl) themes/(theme name)
7. copy all theme directory content by typing into compiler
cp themes/(theme name)/exampleSite/* . -r
8. go to config.toml add into front matter add
themesDir = "themes"
theme = "(theme name)"
9. go to your github repository and create a repository.
10. git remote add origin and paster your repository url.
11.  git status, git add --all, git commit -m "initial", git push -u origin master.

Deploying online:
12. type hugo in your compiler and copy
publishDir = "docs" paste it to config.toml front matter.
13 remove public directory
rm -r public
 push.

14.1 type hugo again in compiler.
14.2 git status git add --all git commit -m "rendered" and git

15. under settings Guthub Pages select master branch/docs folder.
and hit save and it will give url like this https://github.com/themefisher/timer-hugo copy the url and replace baseurl= "http:/example.org"  unto your config.toml. 

16. push changes again to your repositoty and refresh ti will take a while after the site is live and there you go.

-------------------
Some other ways.

1. hugo new site (project name)
2. cd (project name)
3 vim config.toml = edit config.toml
4. go to themes.gohugo.io = select theme to use
5. in github directory copy the github link
6. git init and then git submodule add (githubUrl) themes/(theme name)
7. copy all theme directory content by typing into compiler
cp themes/(theme name)/* . -r
8. go to config.toml add into front matter add 
theme = "(theme name)"
9. go to your github repository and create a repository.
10. git remote add origin and paster your repository url.
11.  git status, git add --all, git commit -m "initial", git push -u origin master.

Deploying online:
12. type hugo in your compiler and copy
publishDir = "docs" paste it to config.toml front matter.
13 remove public directory
rm -r public
 push.

14.1 type hugo again in compiler.
14.2 git status git add --all git commit -m "rendered" and git

15. under settings Guthub Pages select master branch/docs folder.
and hit save and it will give url like this https://github.com/themefisher/timer-hugo copy the url and replace baseurl= "http:/example.org"  unto your config.toml. 

16. push changes again to your repositoty and refresh ti will take a while after the site is live and there you go.
------



