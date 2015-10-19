# go_work
Skeleton code,reference about the GO language

# Installation of GO with the Eclipse IDE 
- goclipse : https://github.com/GoClipse/goclipse/blob/latest/documentation/Installation.md#installation
- egit : Main Update Site: http://download.eclipse.org/egit/updates (Recommended)


# go get 
- Select,download go binaray follow to ur machine. (https://golang.org/dl/)
- tar xvf go1.5.XXXXXX /usr/local/

```sh 
cd ~/
git clone https://github.com/itmoss/go_work.git

```
# how to create a project with the Eclipse. 
- Move to workspace downloaded from github within your home. 
- `cd ~/go_work` 
- Import your exist directory go_work 
- `~/go_work/ #don't fill out your project name within path!!!!!` 
- Check your PATH 
```sh
vim ~/.bashrc
export GOPATH=$HOME/go_work
export PATH=$PATH:/usr/local/go/bin/
source ~/.bashrc
sudo apt-get install git
```
- Get source supported eclipse from open repostitories 

```sh 
go get golang.org/x/tools/cmd/oracle
go get github.com/nsf/gocode
~/go_work/bin$ sudo mv gocode /usr/local/go/bin/
~/go_work/bin$ sudo mv oracle /usr/local/go/bin/

```


- Creates your package and project 
```sh 
# your company
mkdir -p $GOPATH/src/github.com/itmoss/sample_go
#
```


- Create repository to your github location. 
```sh 
$ cd $GOPATH/src/github.com/itmoss/sample_go
$ git init
Initialized empty Git repository in /home/user/work/src/github.com/user/hello/.git/
$ git add xxxxxxxxx.go
$ git commit -m "initial commit"
git push http://github.com/itmoss/sample_go master
```

- build and debug with tool 

 
https://github.com/GoClipse/goclipse/blob/latest/documentation/UserGuide.md




# utilities of GO 
- Coplile Deamon 
go get github.com/githubnemo/CompileDaemon




