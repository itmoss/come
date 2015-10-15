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
- Excutes goclipse then create go project and check your project name whether it is above directory of workspace. 
- `~/go_work/ #don't fill out your project name!!!!!` 
- Check your PATH 
```sh
export GOPATH=$HOME/go_work
export PATH=$PATH:/usr/local/go/bin/
```

```sh 
sudo apt-get install git
#go get github.com/cihub/seelog
#go get github.com/bmizerany/pat
go get golang.org/x/tools/cmd/oracle
go get github.com/nsf/gocode
#go get golang.org/x/net/websocket
#go get golang.org/x/text
```






