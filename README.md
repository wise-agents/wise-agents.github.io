# How to publish wise-agents documentation

* Fork and clone this project. Your local directory should be ```wise-agents.github.io```
* Add a remote ref to upstream, for pulling future updates. For example:
```
git remote add upstream https://github.com/wise-agents/wise-agents.github.io
```
* Be sure to fetch the website branch, you can simply use:
```
git fetch upstream
```
* Be sure to have a forked and cloned [wise-agents](https://github.com/wise-agents/wise-agents). Your local directory for wise-agents should be ```../wise-agents```
* Build wise-agents project
* from the `main` branch in ```wise-agents.github.io``` just run ```make``` it will build docs from ```../wise-agents``` and push it in a remote branch called ```website```
* go to github and create PR like this ![merge](merge.png)
* merge it
* your documentation will be shortly available at [https://wise-agents.github.io/](https://wise-agents.github.io/)
