you won't able to read shit man download it i'm too lazy to edit it honstly :)


$author = "(moscow)"
$date = "23/4/2022"
$copyright = @CopyRight All rights recived to (Moscow) @2022
=================================================================


[+] [Solution]
===============
[1] install the Sleuthkit toolset
	==> apt install sleuthkit
[2] scan the disk tables
	==> mmls disk.img
[3] you should notice that there's something weird in the last partetion so let's scan it up
	==> fls -o [start] disk.img
[4] oh shit there's root let's get it
	==> fls -o [start] disk.img [id]
[5] my_folder ? are you kiding me?
	==> fls -o [start] disk.img [folder id]
[6] oh here's our guy 
	==> icat -o [start] disk.img [flag id]



