# msyi
Shell script for git commit emoji 🎉

## MacOS install

### Download msyi.sh file
```
$ mkdir ~/msyi
$ sudo curl -L https://raw.githubusercontent.com/hoangdv99/msyi/main/msyi.sh -o ~/msyi/msyi.sh
$ sudo chmod +x ~/msyi/msyi.sh 
```
### Create alias command to run everywhere
Open ~/.zshrc
```
$ nano ~/.zshrc
```
Add your alias
```
alias msyi="~/msyi/msyi.sh"
```
Reload shell config
```
$ source ~/.zshrc
```
Use your alias
```
$ msyi
```
