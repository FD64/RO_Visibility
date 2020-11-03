# RO Visibility Project
Things that help not lose your sight in general while playing RO ![](https://cdn.betterttv.net/emote/5c1817f6fdbdda30f11a6210/1x) 

Here I will investigate how to change the background of some text, font size, font type... and make a guide on how to apply that to the game. Unless stated otherwise, everything is pulled from the internet and all I did was put it together here.  
I wouldn't expect regular updates, I might be busy playing ![](https://cdn.betterttv.net/emote/55e66e4e5ad6221639a6bbbc/1x)

You will need **[GRFEditor]** (direct download link from https://rathena.org/board/files/file/2766-grf-editor/)

[GRFEditor]: http://www.reddit.com

Backup **every** file you modify, its much faster to move any file than redownload the whole client. Also, while GRF Editor is opening a RO file the game might not work if it needs to write to that file (downloading game updates with it open won't work and you won't notice until the download is over).  
What I have done is have a folder with every modified file so you only have to replace it if the game ever overwrites those files.

---

So far:



1. ![](https://cdn.betterttv.net/emote/5aca62163e290877a25481ad/1x) Have you ever lost track of your cursor? I've got you covered (very simple guide)

2. ![](https://cdn.betterttv.net/emote/5a0380004ebd8047f54e4c4d/1x) Is the damage text too pixelated for you? ⬆️ Read right above this line!

---

## 1. CHANGE CURSOR ##

I have put together a pack of cursors  👉 **[here](Cursors.zip)** 👈

First, extract them in a folder and see if you like any.

Second, open the data.grf from your game's folder and locate **cursors.act** and **cursors.spr**

![](https://image.prntscr.com/image/EvzFtw9BQSa8Qu-yD1AwEg.png)

Now drag the **cursors.act** and **cursors.spr** to the sprite folder, they should appear blue:

![](https://image.prntscr.com/image/r0vgsm83SyONie70sVwNlQ.png)

If you select the file and go to Image Preview you can view all the states of the cursor (opening a door, teleporting, the arrow above a clicked enemy...)  
All these images are editables (.bmp), so you can make your own by going to Sprite editor, extracting the sprite, photoshopping it and packing it again (use SPR Conview)

Thats it, now make sure your game is closed before you save the data.grf (CTRL+S)

I chose Bicolor_Red2 and it looks like this:

![](https://image.prntscr.com/image/plDCrWLBTKC62KIz6HaZwg.png)



---

## 2. HD Damage numbers ##

Download the HD damage numbers 👉 **[here](HD_Damage_numbers.zip)** 👈

First, extract it and open your GRF Editor.

Second, open the data.grf from your game's folder and locate this folder:

![](https://image.prntscr.com/image/1zaxiFbkRaSreo5cSigEaw.png)

Drag all the files here (theres 5). They should now appear blue:

![](https://image.prntscr.com/image/ShRcXqygRJWRb9b3ndD3xw.png)

Thats it, now make sure your game is closed before you save the data.grf (CTRL+S)

It looks like this in my game:

![](https://image.prntscr.com/image/0JTvTR7MQ3ytyIdfQXJEnw.png)
