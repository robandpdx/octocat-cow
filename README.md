# octocat-cow
An octocat for cowsay... and how to make your shell as cool as mine :)

These instructions are for Mac. Sorry, not sorry.  
Using [homebrew](https://brew.sh/)...  
Install cowsay: `brew install cowsay`  
Install figlet: `brew install figlet`  
Install lolcat: `brew install lolcat`  

Copy the octacat.cow file to...  
`/System/Volumes/Data/opt/homebrew/Cellar/cowsay/3.04_1/share/cows/`  
... or wherever the hell your cow files are.

Now test it out...  
`figlet GitHub | cowsay -n -f octocat | lolcat`  

![Screen Shot 2022-01-25 at 11 04 54 PM](https://user-images.githubusercontent.com/95243761/151118366-a6ada65b-6e21-4b39-aab2-57152a27b31b.png)

Sa-weet! Add that command to your .zshrc, or whatever shell init file you use. Profit!

Credit: This is based on https://github.com/cobyism/octocatsay
