# P(u)shit

> a `cp` helper   

### Setup   

- Clone **pshit** wherever you want and enter.
```
git clone https://github.com/ngpfontaine/pshit.git && cd pshit
```   

- Make a new **pshit** from template.
```
cp pshit pshit-dev
```   

- Open in editor and change pathing variables with your intended paths, then save.
```
vim pshit-dev   
   
baseDir='/example/local/path'
remoteDir='/example/remote/path'
```   

- Make it executable.
```
chmod +x pshit-dev
```   

- Create a symlink to your new **pshit** in root **/bin**.
```
sudo ln -s ~/example/path/pshit-dev /bin/pshit-dev
```   

### Use   

list **help** info
`pshit-dev --help`   


