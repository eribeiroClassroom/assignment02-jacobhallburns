[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/b0B_Pv66)
# os161_base_code

Make a small change in the kernel. Re-build and boot the kernel so it shows the change that has been made. To make the change, search for the string "Put-your-group-name-here" and replace it with your name. 

See notes on building and running OS/161: 
- https://github.com/eraldoribeiro/UsingCSE4001_OS161
- https://github.com/eribeiroClassroom/notes_github/blob/main/README.md

This repository tests the kernel automatically every time new changes are pushed to the repository. Open the Actions tab to see details of the tests. The main test is implemented in the file `entrypoint.sh`. 

**Important**: Configure the kernel using the configuration file `DUMBVM`, i.e.: 
```bash
cd kern/conf/
./config DUMBVM
```




