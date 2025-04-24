# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
# Name : SASINTHAR P
# Reg No : 212223230199
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```bash
lsblk
```

```bash
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```

```bash
mmls ~/disk.img
```
```bash
sudo ls -lh disk.img
```
```bash
strings disk.img | less

```

## OUTPUT:
![Screenshot 2025-04-22 170957](https://github.com/user-attachments/assets/8758a960-8b9c-41cb-becd-f44def653266)

![Screenshot 2025-04-22 171008](https://github.com/user-attachments/assets/eb43876f-a202-461a-9265-89e4ea36b4ca)

![image](https://github.com/user-attachments/assets/1fc8e81f-12c1-4927-92ca-a4a0a500950e)

![Screenshot 2025-04-22 171038](https://github.com/user-attachments/assets/92658b19-6e77-4be4-b84b-767fae44c7aa)

![image](https://github.com/user-attachments/assets/4aff8fc4-e59c-475e-bdb2-658f15c67c50)

## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.
