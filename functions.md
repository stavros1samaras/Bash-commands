## Functions
#### To create a function
- Navigate to your home directory:
```bash 
cd ~
```
- Edit (or create) the .bash_profile file:
```bash
nano .bash_profile
```
- write:
```bash
myFirstFunction(){ 
    echo "hello I am the first function!" 
}
```
- Save press: `control + x`
- Agree press: `Y`
- Name the file, press: ` Enter ` or set the name

Once completed, you can simply type "myFirstFunction" in any new terminal session to run myFirstFunction instantly.

If you want to run the function immedietly in the curent terminal run:
```bash
source .bash_profile
```
