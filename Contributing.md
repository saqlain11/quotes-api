Confused how to make a contribution? Here's how you we go about it - 
To start contributing, follow the following steps: 

**1.**  Fork [this](https://github.com/GDSC-RTU/quotes-api) repository.

**2.**  Clone your forked copy of the project.

```
git clone --depth 1 https://github.com/<your_user_name>/quotes-api.git
```

**3.** Navigate to the project directory :file_folder: .

```
cd profiles-browser-extension
```

**4.** Add a reference(remote) to the original repository.

```
git remote add upstream https://github.com/ishubham21/quotes-apt.git
```

**5.** Check the remotes for this repository.

```
git remote -v
```

**6.** Always take a pull from the upstream repository to your master branch to keep it at par with the main project(updated repository).

```
git pull upstream master
```

**7.** Create a new branch.

```
git checkout -b <your_branch_name>
```

**8.** Perfom your desired changes to the code base.

**9.** Track your changes:heavy_check_mark: .

```
git add . 
```

**10.** Commit your changes .

```
git commit -m "Relevant message"
```

**11.** Push the committed changes in your feature branch to your remote repo.

```
git push -u origin <your_branch_name>
```

**12.** To create a pull request, click on `compare and pull requests`. Please ensure you compare your feature branch to the desired branch of the repo you are suppose to make a PR to.


**13.** Add appropriate title and description to your pull request explaining your changes and efforts done.


**14.** Click on `Create Pull Request`.


**15** Voila! You have made a PR to the awesome-developer-portfolio project. Sit back patiently and relax while the your PR is reviewed.
