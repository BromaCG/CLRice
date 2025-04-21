# CLRice
CLRice is a minimalist but reliable UNIX CLI ricing manager

It is 100% open-source, feel free to use my code for personal projects or modify my app, also, if you want to contribute to this project you may send me a pull request :)

For further understanding of the app you may want to read the entire readme or read the code itself because the code is almost full commented

## HOW IT WORKS
CLRice basically names your rice backup folder (for more explanation about the backup folder read the RUNNING AND TWEAKING chapter of the readme) and copy and paste into your user folder (~/), it is really a silly project but I really wanted to create something using CLI and I needed to manage my rices with a program, really cool

## RUNNING AND TWEAKING
As the name indicates, you should use your CLI to run the program, after completing the installation correctly you should be able to type 'clrice' into your terminal emulator and run the program with no problems

You will have to create a backup configuration of your dotfiles, usually everything is in your ~/.config, put all these files in a .config inside a backup folder, in this readme I will suppose your backup folder name is 'Catarata'
If you feel confused because of the explanation above, I will try to exemplify it by using hierarchy of folders
```
~/
    ~/.config/
    ~/Catarata/
        ~/Catarata/.config/
```


The first thing you will see after running the program is the main menu with 5 options, if it's your first time in the program I recommend you to select the 'add rice' option by typing 1 in the input, you will be redirected to the add rice menu after that, the first thing you need to do is select a name to your rice, it is just a representation of your rice to remember you of which rice it is on the other menus, after inputing its name you will have to type the path to your 'Catarata', for example, if 'Catarata is inside the user folder you have to type /home/username/Catarata/


## INSTALLATION
First, you need to clone the project to your computer using:
```
git clone github.com/BromaCG/CLRice/
```
Then, try to link the clrice python file to your path using:
```
sudo ln -s ~/CLRice/clrice ~/.local/bin/
```
And now it should be ready to execute in your terminal, try testing it by typing 'clrice' in your terminal emulator 
