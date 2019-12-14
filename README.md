# discord-pink-kotori
**READ IN RAW FOR PROPER FORMATTING**
WORKS AS OF 2019.12.13 21:32

UPDATE 12/13: now works on browser

For browser, copy everything in the css file and upload to a style editor like 'custom style scripts' inside the style - CSS box. Then, add this in the same space. if you press ctrl-I and scroll down, you should be able to see the words colored (that means it has been applied.

.bg-h5JY_x {
background-image: url();
background-repeat: no-repeat;
background-position: right;
background-size: cover; 
}

You can change the picture inside the URL() to whatever you like.


Theme for BetterDiscord (Pink) with any picture (kotori is stock)
The modifications are as follow: The main interface is transparent, so that the app body can contain an image of your choice. Active channels are white, with unread channels pink (color matched with unread dots) muted channels are gray. I haven't touched the friend colors either, so they stay gray.

First, you will need to download Bandaged Better Discord (https://rauenzi.github.io/BetterDiscordApp/)
Then, download my theme (.theme.css file) into the themes folder (C:\Users\*yourusername*\AppData\Roaming\BetterDiscord\themes)
Go into your Discord, and at the bottom of your settings, you should find a label "Themes" in which you should be able to enable my theme.
Final step is to copy paste the following into "Custom CSS" in the Discord settings:

.bg-h5JY_x {
background-image: url();
}

You can put whatever image link you want between the url. 
You can also edit the .theme.css file with notepad, using inspect element (ctrl + i) to find the name of the things you want to modify.

Note that this code is developed from the universal theme fixer, but I can't find the original post. 

**Edit**
For bigger images, you can use the following: (image is welcome employer from girls' frontline)

.theme-dark {
background-image: url(https://i.imgur.com/UZk22dv.jpg);
background-repeat: no-repeat;
background-position: center;
background-size: cover; 
}

this will automatically resize and center your image no matter how you size your window.

~~*Edit 2* : I think there the ".app {" part should be removed from the main file, it should be easier to change background urls in the better discord app itself, no? So people can change the background and test it without messing with the .theme.css file, which is hidden in layers of folders~~

**Edit 3: URL is Lucia holding hands
Emoji jumboable makes emotes bigger 
(number)rem is the size, change 5 to 4 or 3 if it's too big :D**

.theme-dark {
background-image: url(https://i.imgur.com/UZk22dv.jpg);
background-repeat: no-repeat;
background-position: center;
background-size: cover; 
}
.emoji.jumboable{
    height:5rem;
    width:5rem;
}
