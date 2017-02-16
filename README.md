# P(u)shit

> a `cp` assistant      
   
   
## Setup   

- Clone **pshit** wherever you want _(_ ` ~/ ` _in this example)_ and enter directory.
```
git clone https://github.com/ngpfontaine/pshit.git ~/pshit && cd ~/pshit
```   

- Make it executable.
```
chmod +x pshit
```   

- Run setup. **(1)** You will be prompted to enter your  **base** & **target** paths. **(2)** A symlink will be created or updated from the location of **pshit** to **/bin/pshit**.
```
bash pshit --setup
```    

## Post Setup   

- **pshit** can now be run w/o using `$ bash ...`   

- Now **pshit** will copy files from your **base** > **target** path (**note:** sudo will be invoked).   

- Run ` pshit --setup ` anytime to change it's functionality.   


## Use   

Run setup to set directories.   
`bash pshit --setup` _(first time from_ **pshit** _directory)_   

`pshit --setup` _(any time after that)_   

List **help** info   
`pshit --help`   

**pshit** everything   
`pshit --all`   

---

Files in main directory   
`pshit --files`   

One file, in main directory   
`pshit index.html`   

A recursive directory in main dir   
`pshit css`   

## To-Do   

- cp & mkdir   

- add all accept prompts   

- `-y` option to bypass prompts   

- deal with subdirectories   


