# golang

## three install methods

- Go source code
- Go standard install package
- Third party tools


## go source code

1. Download source code from [go official website](https://golang.org/doc/install/source)  
`wget source_code_url`

2. unzip the source code file  
`tar -zxf source_code_file `

3. install go
```
cd go/src
./all.bash
```

## go standard install pacakge

1. Download standard install package from [go official website](https://golang.org/dl/)  
`wget url`

2. unzip the tar.gz file  
`tar -zxf file_path -C /usr/bin`


## third party tools(apt)

```
sudo apt-get install python-software-properties
sudo add-apt-repository ppa:longsleep/golang-backports
sudo apt-get update
sudo apt-get install golang-go
```


