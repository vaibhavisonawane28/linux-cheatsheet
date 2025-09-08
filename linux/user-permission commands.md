 # Linux User & Permission Commands.

👤 User Management
- whoami → Show current logged-in user  
- id → Show user ID and group ID  
- adduser username → Add a new user  
- passwd username → Set / change password  
- su username → Switch user  
- exit → Log out from current user session  

 🔑 Permission Management
- ls -l → Show permissions of files  
- chmod 755 file.txt → Change file permissions (owner: rwx, group: r-x, others: r-x)  
- chmod u+x file.sh → Give execute permission to user  
- chown user file.txt → Change file owner  
- chgrp group file.txt → Change file group ownership  

 📝 Permission Types
- `r` → Read  
- `w` → Write  
- `x` → Execute  
- Example: `-rw-r--r--`  
  - Owner = read, write  
  - Group = read  
  - Others = read  
