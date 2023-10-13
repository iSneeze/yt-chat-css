## Custom Style for Youtube Chat in OBS Studio

### Step 1: Create a new browser source 

In a scene, create a new browser source:

![](readme-imgs/obs1.png)

### Step 2: Youtube chat URL

Open your stream in your browser, click on the chat popout button and copy the URL.

![](readme-imgs/yt1.png)
![](readme-imgs/yt2.png)

### Step 3: Enter all the stuff into OBS Studio

In OBS, when creating the browser source, paste the youtube chat URL for the `URL`.

Set `Width` to something like 360 to 400. `Height` your choice, something like 720 looks nice.

Lastly, copy the CSS from this file [here](yuko-chat.css) into the `Custom CSS` field, delete the default text first.

![](readme-imgs/obs2.png)

DONE! :D


## Caveats

Unfortunately you need to set the URL for every stream, pro tip, just replace the youtube stream ID (the part after the `&v=`) thats all you need

For member streams you need to log in to your OBS browser first, if you have trouble doing that, delete the CSS out of the properties, then log in and copy it back in? idk yet whats the best solution