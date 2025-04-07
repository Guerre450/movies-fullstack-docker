Making it easier for everyone
It is sometimes annoying if you forget to initiate and update your submodules. Fortunately, there are some tricks to make it easier:

git clone --recurse-submodules
This will clone a repository and also init / update any possible submodules the repository has.

git pull --recurse-submodules
This will pull the main repository and also it's submodules.

And you can make it easier with aliases:

git config --global alias.clone-all 'clone --recurse-submodules'
git config --global alias.pull-all 'pull --recurse-submodules'