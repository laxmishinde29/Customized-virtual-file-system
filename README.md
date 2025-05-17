### **📁 Customised Virtual File System (CVFS)**

## 📌 Project Overview
• Customised Virtual File System (CVFS) is a simulation of a simplified file system built from scratch to emulate core file system behaviors.

• It demonstrates file manipulation, storage logic, and system-level interactions similar to UNIX/Linux systems.

• It is a simulation of a simple file system that mimics core file operations like open, read, write, and close.

• It demonstrates how files are managed internally by the OS using inodes, file tables, and directory structures. 

• In this Project we create all Data Structure which required for File Subsystem as Inode, Inode Table, File Table, UAREA, User File Descripter(UFDT), Super Block, Disk Inode List Block, Data Block, Boot Block etc.

• Known as customized virtual files system:-

Customised : Because its designed is dependent on the users requirement

Virtual : Because it is used in the RAM.

File System : Way of storing and retriving the files.

## **⚙️ Technologies Used**
• Language: C / C++
 
• OS: Linux

## 🔧 Important System calls of File subsystems :

create() : It is used to create new regular file.
open() : It is used to open existing file.
close() : It is used to close already opened file.
read() : It isused to read the data from file.
write() : It is used to write data into the file
lseek() : It is used to change the offset of the file.
stat() : It is used to display information of file using name.
truncate() : It is used to Remove all the data from file

## Diagramatic representation file System Layout on Hard disk :

![File-System-Layout](https://github.com/user-attachments/assets/972a8acf-c24e-4dab-9da6-643e871e7c68)

## Diagramatic representation of internal implimantation of file system :

![File-System-Layout-on-RAM](https://github.com/user-attachments/assets/ac185321-a2bf-4cac-a9e5-728ade04a6ea)

## Final layout of program :

![Final Diagram](https://github.com/user-attachments/assets/380f2ffd-d523-42ee-b4ef-78b7afdab4bc)

# output :

![cvfs1](https://github.com/user-attachments/assets/481777ba-6cdc-4287-8f14-7bd3bf895fee)

![cvfs2](https://github.com/user-attachments/assets/636b3927-9dae-4c04-806c-3c0736d0ee28)

