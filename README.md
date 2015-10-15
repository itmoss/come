# come
Skeleton code,reference about the GO language

# Installation of GO with the Eclipse IDE 
- goclipse : https://github.com/GoClipse/goclipse/blob/latest/documentation/Installation.md#installation
- egit : Main Update Site: http://download.eclipse.org/egit/updates (Recommended)

# go get 
- Set GOPATH (go_work) 
- Move directory to go_work/src

```sh 
- go get github/itmoss/come 
```
# how get a project with the Eclipse. 
- Creates workspace within your home. 
- `~/go_work` 
- Move to goclipse then create go project and check your project name whether it is above directory of workspace. 
- `~/go_work/ #don't fill out your project name!!!!!` 
- Check your PATH 
```sh
export GOPATH=$HOME/go_work
export PATH=$PATH:/usr/local/go/bin/
```

```sh 
go get github.com/cihub/seelog
go get github.com/bmizerany/pat
go get golang.org/x/tools/cmd/oracle
go get github.com/nsf/gocode
go get golang.org/x/net/websocket
go get golang.org/x/text

cd /home/jaster/go_work/src/github.com/itmoss

git clone https://github.com/itmoss/MOSSD.git

```






