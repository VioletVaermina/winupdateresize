This is a simple batch file that calls a simple diskpart script that resolves windows update error 0x80070643 by shrinking the C:/ drive by 250 Mb, deleting and then recreating the windows recovery partition with the additional space, and reassigns the necessary IDs and GPT attributes. 

-=IMPORTANT=-

This script assumes windows is installed on volume C:/ and that the recovery partition is the 4th partition on disk 0. Do not use this script if you have any sort of non-standard drive setup or multiple drives. Do not run this script multiple times as it will shrink the C:/ drive by 250 Mb every single time you run it. 

Run the shortcut as an administrator. 

<3
