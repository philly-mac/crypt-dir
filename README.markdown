### Small script to allow management of encrypted directories on a linux file system

- You will need to install ecryptfs
- Assumnes all your encryoted directories are located in /home/private/your_username/*
- Will mount the directories to /home/your_username/directoy_to_be_mounted

Command and options

crypt-dir [ list | setup | teardown | mount | umount ] [ directory ]

- list     - list all directories that could be mounted, and says whethere or not they are mounted
- setup    - create a new directory in the encrypted location, ready to be mounted
- teardown - removes an empty directory in the encrypted location
- mount    - mounts and unencrypts a directory from the encrypted location
- umount   - unmounts a mount and encrypted directory
