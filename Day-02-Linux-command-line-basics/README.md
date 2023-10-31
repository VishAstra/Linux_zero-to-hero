🍀 Exploring the Filesystem

The Linux filesystem is organized in a hierarchical tree-like structure. Some important directories include:

    / (root) — top of the filesystem hierarchy 🌳
    /home — user home directories 🏠
    /etc — system configuration files ⚙️
    /var — variable data like logs 📈
    /bin — executable binaries 💼

We can navigate this structure using commands like ls, cd, and pwd:

ls /home - list contents of /home 
cd /etc - change directory to /etc 
pwd - print working directory 

🍀 File Management

Linux provides various utilities for managing files and directories:

    mkdir - make a new directory 📁
    touch - create an empty file 📄
    rm - remove files and directories 🗑️
    mv - move or rename files and folders 🔄
    cp - copy files and folders 📦

For example:

mkdir test 
touch test/foo.txt 
rm test/foo.txt 
mv test foo 
cp -r foo bar 

🍀 Help and Documentation

    man - read reference manuals for commands 📖
    whatis - brief description of a command 📝
    help - get help for shell built-ins 🆘

For example:

man ls 
whatis rm 
help cd 

This just scratches the surface of Linux command line skills that are indispensable for DevOps engineers. We’ll continue exploring more Linux administration basics in the coming days. 🚀💻
