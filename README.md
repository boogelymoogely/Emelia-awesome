# Emelia-awesome
My Awesomewm config.
It's based on the Arcolinux config (https://github.com/arcolinux/arcolinux-awesome) but with some modifications and scripts to suit my needs. Feel free to copy it, but don't just go and use it with no modifications, unless you use Linux exactly like I do, configure it to your liking. Also, feel free to use it as a reference for your own configuration. 

------ display notice ------

If you don't have multiple monitors or you don't wish to only use one HDMI monitor, you'll probably want to delete displayfix.sh and the command to run it in rc.lua. 

------ installation ------

To install it, all you need to do is extract the files into your .config directory. 
For me, that would be /home/emelia/.config. It'll be different if you have a different username, which is highly likely, just change it accordingly. If you don't have the "awesome" directory created, no problem, just make one then copy the files into it and edit as needed. With more recent versions of my configuration, I include both Awesome and Alacritty configurations, both in your .config folder. Copy those folders into .config, so that way you have both directories $home/.config/alacritty and $home/.config/awesome. Feel free to edit the files in each of those to your liking. I also include my Dmenu config now, but customizing it isn't really necessary, just make sure you have Dmenu installed. I use it as a run launcher, so it's pretty important to my workflow. By default, it's launched with Super+Shift+D. If you do want to use my Dmenu configuration, just cd into the dmenu folder from a terminal and run "sudo make clean install". If you get an error compiling it, you probably don't have the proper dependencies.

------ distro support ------

Also, one should probably note that this is meant for an Arch-based distro. It works on Fedora 36 from my testing, and I believe I modified it slightly to work better on Pop!-OS 22.04 LTS, I released that one as well. I had some font issues for some reason, so I changed the terminal because Alacritty didn't seem to want to comply.

------ additional dependencies ------

Dependencies include (and there are probably more, but here's what additional stuff I threw in there, change it as you see fit, and remember to install dependencies for Awesome, these are just dependencies for my config specifically):
- picom
- nitrogen
- flameshot
- caffeine (not entirely necessary, but good to have for gaming)
- firefox
- kate
- pcmanfm
- alacritty
- virt-manager
- mpv
- xfce4-power-manager
- dmenu

Otherwise, this is just what I feel comfortable and enjoy using, have fun. :)

Here are some (old) screenshots of it in use, in case you're curious. 
<img width="1720" alt="image" src="https://user-images.githubusercontent.com/66752943/171455243-f2780019-3127-4759-b2df-c18b400a01a2.png">

<img width="1720" alt="image" src="https://user-images.githubusercontent.com/66752943/171454961-f43483e3-1d39-4566-96d2-3354239f445e.png">
