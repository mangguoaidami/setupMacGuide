# get start for Mac.
> init apps
1、install Xcode\ VS Code\ StarVPN \ Color Note \ iterm2 \VirtualBox \ Genymotion \ Chrome ...
2、install Nodejs.
3、install yarn.
4、install HomeBrew.
5、yarn global add gulp\react-native-cli
6、yarn global add expo-cli

图片转换
```
brew install imagemagick gs
```

JDK

```
brew tap caskroom/versions
brew cask install java8
```

```
brew cask install charles
```


## Android

```
export ANDROID_HOME=/Users/fdhuang/Library/Android/sdk
export PATH=$PATH:$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools
```

## Git Config

1、Config line

```
git config --global user.email "h@phodal.com"
git config --global user.name "Phodal HUANG"
```
## Git branch
2、Renaming a branch (rename the local branch to the new name)
```
git branch -m <old_name> <new_name> 
```
3、delete the old branch on remote - where <remote> is eg. origin
```
git push <remote> --delete old_name
```

4、 push the new branch to remote   
```      
git push <remote> new_name
```

5、get remote branch
如果用命令行，运行 git fetch，可以将远程分支信息获取到本地，再运行 如下行，就可以将远程分支映射到本地命名为local-branchname  的一分支。 
```
git checkout -b local-branchname origin/remote_branchname  
```
## Git URL
Git change remote URL
```
git remote set-url origin http://git.ruizhan.com/zhangjie/OneSightOA_And.git
```

# React-Native
> tab skill.

1、react-native components\ 
[Class](https://stackoverflow.com/questions/43648440/how-to-call-a-function-from-another-class-in-react-native)


2、[父组件传递子组件状态：](https://stackoverflow.com/questions/43313158/react-native-passing-props-between-components-and-componentwillmount-method)


3、[子组件传父组件：](https://stackoverflow.com/questions/44875787/pass-state-from-child-to-parent-component-in-react-native)


4、[If show:](https://stackoverflow.com/questions/30266831/hide-show-components-in-react-native)


# 前端整体知识体系学习
[1\前端九部](https://www.yuque.com/fe9/basic/)