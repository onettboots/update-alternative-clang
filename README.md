# update-alternative-clang

How to run ?

- clone : git clone https://github.com/onettboots/update-alternative-clang.git

- cd update-alternative-clang
- chmod +x update-alternative-clang.sh
- run it with add optional clang version and priority example i wanna add clang version 12 and 13:
- sudo ./update-alternative-clang.sh 12 120 (enter)
- sudo ./update-alternative-clang.sh 13 130 (enter) and continuesly

set up --config
- sudo update-alternatives --config clang
- sudo update-alternatives --config llvm-config

for check any settings 
- clang -v 
- opt -version

thanks !


source from here : https://gist.github.com/junkdog/70231d6953592cd6f27def59fe19e50d#file-update-alternatives-clang-sh
