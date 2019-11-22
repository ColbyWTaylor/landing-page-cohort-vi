# Git Collabotarive

To run, you must be in the website folder.

To change the directory, you can do "cd website1", then run a server using python with "python3 -m http.server 3000" (without the quotes!).

## Instructions

1. As a teacher, please create a new repository in github.com and invite your students.

2. Then, clone this repository and change the remote to your new repository
```sh
$ git clone git@github.com:breatheco-de/exercise-git-collabration.git
$ git remote set-url <the new repository>
```
3. Push everything to the new respository you have just created.
```sh
$ git push origin master
```

## Now your students can download your repository and collaborate with you

1. Pick what website you want to build with your students.

2. Each student will have to clone your new repository and develop one piece of the website you have chosee, each project is divided in pieces inside its **templates/** directory.

3. When students finish, they have to commit and push to your repository.


## Addional complementary info

The [Html-Template-Engine library](https://github.com/alesanchezr/html-template-engine) is being used as template engine for building the landing page.

