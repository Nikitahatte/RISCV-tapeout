## VLSI System Design (VSD) Program Foundation & Tool Setup 


##  Virtual Machine Configuration requirement (linux)

| Resource   | Allocation     | Remarks                                |
|------------|----------------|----------------------------------------|
|  RAM     | 6 GB           | Sufficient fonts/assets/56c1ae1a-22e0-4dea-9a0d-f8e711e731bc" />


  
 <img width="1005" height="563" alt="image" src="https://github.com/user-attachments/assets/9a86d2d6-866d-40d3-8010-4034b19598a4" />




- Get in the terminal and listout files

<img width="936" height="477" alt="image" src="https://github.com/user-attachments/assets/8a0e5182-097f-41b7-959f-c589578f5f65" />

- Check git version and ensure git installed or not 
  
<img width="943" height="478" alt="image" src="https://github.com/user-attachments/assets/9e28315a-35b4-4a25-aec1-86ab5b7de56c" />


- Install git using this command

<img width="936" height="470" alt="image" src="https://github.com/user-attachments/assets/517f7259-44c7-4e6e-bb2c-488ef3a9053e" />

- After installation check git version

<img width="934" height="476" alt="image" src="https://github.com/user-attachments/assets/bb20bdd1-c56e-4afa-bbb4-7cb45b6f9f67" />

- Create directory with name (vsdflow)

<img width="939" height="481" alt="image" src="https://github.com/user-attachments/assets/232676a1-fcd8-446f-8974-0ea2e6cf70fc" />

- Clone this repository in vsdflow directory

<img width="1267" height="365" alt="image" src="https://github.com/user-attachments/assets/23575dff-886a-4304-bcc9-a75ea72fb3ba" />

- Yosys is downlaoded but still need installation. "ls" will list the folder we downloaded with git command.

<img width="1395" height="852" alt="image" src="https://github.com/user-attachments/assets/aa24b7fa-8a9a-4601-8e19-44a62ebf20ba" />

- Now change directory to yosys to install. But we need to use "make" command to install. Hence first "make" needs to be installed.

<img width="1308" height="442" alt="image" src="https://github.com/user-attachments/assets/83c3c6b7-2e01-4c55-aed5-d8917422d674" />

Then copy and paste this command in terminal
```
 sudo apt-get install build-essential clang bison flex \ 
 libreadline-dev gawk tcl-dev libffi-dev git \ 
 graphviz xdot pkg-config python3 libboost-system-dev \ 
 libboost-python-dev libboost-filesystem-dev zlib1g-dev 
 ```

<img width="1267" height="295" alt="image" src="https://github.com/user-attachments/assets/420d4b8d-221f-43d8-95b5-caf47ca683ab" />

- Now first "make" in same folder and then "sudo make install".

<img width="1265" height="195" alt="image" src="https://github.com/user-attachments/assets/6ec7b39d-ce1c-48b4-8645-2345aece4144" />


<img width="1263" height="194" alt="image" src="https://github.com/user-attachments/assets/ad3ee169-0a24-4a1c-9121-211b6f2fc1bc" />

- Then use this command on output

<img width="1265" height="315" alt="image" src="https://github.com/user-attachments/assets/01d62b57-af17-4c65-b19e-e1ac37e9afa8" />

- Use again make command

<img width="1267" height="593" alt="image" src="https://github.com/user-attachments/assets/cf5d188c-54df-49da-876a-24409325328a" />

<img width="1299" height="720" alt="image" src="https://github.com/user-attachments/assets/e680ff13-a683-4801-9915-7ccf5d970712" />

- After done make installation

<img width="817" height="598" alt="image" src="https://github.com/user-attachments/assets/8e700ae9-1685-41bb-9232-ef46d0fb46e0" />



<img width="813" height="592" alt="image" src="https://github.com/user-attachments/assets/75936c8c-0bd4-4f79-8c1a-fce4bebc6684" />

## iverilog Installation 

```bash
$ sudo apt-get update
$ sudo apt-get install iverilog
```
<img width="812" height="586" alt="image" src="https://github.com/user-attachments/assets/010cb897-1bc8-44ac-8dc1-2ab7dc77acbe" />



<img width="822" height="573" alt="image" src="https://github.com/user-attachments/assets/080c1e65-4de9-4ef7-a510-d3baf56e1612" />

## GTKwave Installation 
```bash
$ sudo apt-get update
```
```
$ sudo apt-get install gtkwave
```

<img width="822" height="584" alt="image" src="https://github.com/user-attachments/assets/09af93a6-5935-44e3-8aeb-6ecbb9643490" />

<img width="1001" height="794" alt="image" src="https://github.com/user-attachments/assets/acf8f8bd-e2dd-48ee-9b56-6162479d71d5" />

## Ngspice – Circuit Simulator  
## Ngspice Installation 
```bash
$ sudo apt-get update
$ sudo apt-get install ngspice
```
<img width="546" height="390" alt="image" src="https://github.com/user-attachments/assets/0cffa986-e510-4be8-bd42-6691344f4816" />

##  Installation Verification

<img width="835" height="382" alt="image" src="https://github.com/user-attachments/assets/8bd9504e-23fa-4df7-b5dc-36205edea9b6" />



 ##  Magic VLSI Installation


<img width="824" height="504" alt="image" src="https://github.com/user-attachments/assets/73672b27-996d-4e32-87cf-9e62f3524e7d" />

- Running ./congifure will output like this condition no error in any step before

<img width="779" height="513" alt="image" src="https://github.com/user-attachments/assets/de350132-9f5d-4f66-a850-d4305fbb88e9" />

- Now sysem wide install some people may get output error. Even after doing properly you may get some error or system lands to ❌ Error. One of the error I have for e.g.
   
<img width="762" height="510" alt="image" src="https://github.com/user-attachments/assets/ef881c1f-1f5f-4798-a65a-ba23b5661e78" />



- installing magic
<img width="673" height="523" alt="image" src="https://github.com/user-attachments/assets/0c68474a-a1c7-4b71-9ac1-5af50e89b644" />



##  **Installing OpenLane**
## Installation need some fix in `Makefile` else you will land to `ciel` error. 


<img width="764" height="572" alt="image" src="https://github.com/user-attachments/assets/64e58af6-b4d6-4fb9-9179-89ee544729fd" />

## Error in Make due to Sky PDK Version 
```bash
# Open the Makefile in test editor or Vim editor
# In test editor in top right corner enable `show line number`
# Change the Line number 67
export PDK_FAMILY ?= sky130
# Add a new line 68 as 
export PDK_VERSION ?= 0fe599b2afb6708d281543108caf8310912f54af 
# Also Change the Line number 115
./venv/bin/ciel enable --pdk-family $(PDK_FAMILY) $(PDK_VERSION)
#save the make file and rerun the `make` command
make pdk
make
make test
```

<img width="645" height="78" alt="Image" src="https://github.com/user-attachments/assets/fdf6192a-fc7b-4c50-a95d-3a9e97df775f" />

## Need committ changes in Makefile version 

<img width="744" height="109" alt="Image" src="https://github.com/user-attachments/assets/5e23129c-e0b4-45db-920f-31f66e863f18" />



## Make command run 

<img width="767" height="473" alt="image" src="https://github.com/user-attachments/assets/db6a7e3c-0ef6-4ff0-ad36-d78eb5c0c043" />











