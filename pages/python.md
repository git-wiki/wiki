# Python

## Package Install Options


- Context: 
  - Operating system: Ubuntu 18.04

---  
  
- User space install
  - `$ pip install --user my-package`
- Global install (not recommended)
  - `$ sudo pip install my-package`
- With [`pyenv`](https://github.com/pyenv/pyenv) installed
  - `$ pip install my-package`

### Post Install

If the package is installing a shell command and you want to use it with tab completion, you need to "restart" your shell.

One option is to execute: 

```
$ exec $SHELL
```
