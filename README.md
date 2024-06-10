# Instalação ambiente local - Dev/Windows
Documentação para ambiente DEV Local/Windows utilizando Docker

Requisitos mínimos da máquina:

 - WSL version 1.1.3.0 or later.
 - Windows 10 64-bit:
 - 64-bit processor with Second Level Address Translation (SLAT)
 - 12GB system RAM
 - Enable hardware virtualization in BIOS.
 - SMMS Server Management Studio
 
# Virtualization
Your machine must have the following features for Docker Desktop to function correctly:

# WSL 2 and Windows Home
 1. Virtual Machine Platform
  1.1.  Install WSL command
     - You can now install everything you need to run WSL with a single command. Open PowerShell or Windows Command Prompt in administrator mode by right-clicking and selecting "Run as administrator", enter the wsl --install command, then restart your machine.
<b>In PowerShell:</b>

 ```bash
wsl --install
```

 3. Windows Subsystem for Linux 

 4. Virtualization enabled in the BIOS

 5. Hypervisor enabled at Windows startup
    
![image](https://github.com/oinelsonjunior/documentation_chronos2/assets/7309691/740a673e-8d05-48e0-bed7-125f9f4f2786)

# Hyper-V
On Windows 10 Pro or Enterprise, you can also use Hyper-V with the following features enabled:

 1. Hyper-V installed and working

 2. Virtualization enabled in the BIOS

 3. Hypervisor enabled at Windows startup

![image](https://github.com/oinelsonjunior/documentation_chronos2/assets/7309691/673bbd40-2c72-42a9-a5c5-2fa6e0ba273d)



    




