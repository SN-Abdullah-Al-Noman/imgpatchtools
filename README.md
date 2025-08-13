# imgpatchtools
linux based imgpatchtools by erfanoabdi

Source: 
https://github.com/erfanoabdi/imgpatchtools

sudo apt update
sudo apt full-upgrade

sudo apt update
sudo apt install zlib1g-dev libbz2-dev libssl-dev build-essential

chmod +x ./BlockImageUpdate

./BlockImageUpdate odm.img odm.transfer.list odm.new.dat odm.patch.dat 

./BlockImageUpdate product.img product.transfer.list product.new.dat product.patch.dat 
