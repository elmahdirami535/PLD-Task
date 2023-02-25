su betty == change the current user to the user betty
whoami == prints the effective username of the current user
id == prints all the group the current user is part also there
sudo chown betty hello == to change the owner of the file hello to betty we use sudo because  we must have superuser privileges. 
touch hello == create an empthy file
chmod 114 hello == i give permission x to the owner and the group and read to the other user

r (read) == 4
w (write) == 2
x (execute) == 1 

for this project we had --x --x r-- == x 0+0+1 = 1 0+0+1=1 4+0+0=4    == 114
rwx = 4 + 2 + 1 = 7   
