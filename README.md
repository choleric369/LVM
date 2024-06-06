# Project 1 - LVM (Google Drive)

Platform: Virtual box
OS: Linux
Concepts: LVM (Logical Volume Management), file system, HDD formatting.

# Why this project?
Through this project, our key take aways are usage of virtual box, concept of virtualization /hypervisors, usage of some important Linux commands, file system and memory management.

LVM originates because of volume management. Let’s say, you have 10GB of data and your storage disk typically HDD, Has the capacity to store 5GB. 

# How are we goin to store the data?
Either split the data into two halves and store in two different storage devices or buy HDD with 10GB (or) More capacity and write the data into it. But costs increase and we are wasting our resource (Already 5GB HDD exists). Let’s reiterate data structures for a simple solution i.e, storing data in two devices. 

# Why am I referring to data structures?

That’s where LVM originated from “LINKED LIST”.

The trick is to trick your computer to feel two different hard disks connected to the pc as one. You link two HDD’S by using a mount point. We are all set.

# “What do we need to mount two HDD's (memory devices) together"?

File systems, the two HDD’S should be of some file system. 
Step 1 Make them into same file system.
Step 2 Format the HDD
Step 3 Mount the HDD’S on PC & Connect them together.

# Future Scope:
•	Create a UI to allocate memory for each of the users, The google drive procedure.
•	Get to know more about the ports automate the disk formatting, mounting onto the PC and connecting them together.
•	Automation of the whole procedure.
•	Allocation/ Deallocation of list of the memory to different users
•	Configure “Ports” on connecting a physical memory to the server based on port and connected device type run a script.
