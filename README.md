# Branch Test

This project is for testing branches with multiple collaborators.

The structure is based on the information in [this document](http://nvie.com/posts/a-successful-git-branching-model/).

In this document, each set of commands is given twice, first in a more concise form, then in an equivalent, but longer and more descriptive form.

Each command is shown twice, first with the syntax, then with an example.

## Initial setup

<!--First, clone the new repository from GitHub.-->
First, create a new project and publish it to GibHub. Then clone it and cd into the directory

```
git clone git@github.com:username/Project.git
cd Project
```

Once that is done, create the `develop` branch and push it to the repository. The following command creates a branch called `develop` based on `master`.

```
git branch develop master
```

Then, make `develop` the working branch.

```
git checkout develop
```

Then, push the new branch to the central repository on GitHub, so all of the collaborators can see it.

```
git push -u origin develop
```



```
git branch develop master
git checkout develop
git push -u origin develop
```


