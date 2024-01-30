# Discord-Videos-Play-in-Browser
How to make Discord Videos Play in Browser instead of auto-downloading.

Steps:

1. Get the link for the video (you may have to click the download button top right of video imbed so that it puts the video's link in your browser which will auto-download but now you have the link to work with).
2. A Discord Video Link may look like the following:
``` html
  https://cdn.discordapp.com/attachments/1187224425452535809/1195393134738280568/original-55c1924638195b3fae89d7ea3b5e3b05.mp4?ex=65c6489c&is=65b3d39c&hm=2042fcee0a7592b2498e8a79cfa5d77176b708b8521a0ef057d5775362bc4988&
```

3. Now change the "`cdn.discordapp.com`" part of the link to any of the following entries:
``` html
media-1.discordapp.net
media-2.discordapp.net
images.discordapp.net
images-1.discordapp.net
images-2.discordapp.net
media-ext-1.discordapp.net
media-ext-2.discordapp.net
images-ext-1.discordapp.net
images-ext-2.discordapp.net
```

4. So using the above example url, it will now look like:
``` html
  https://media-1.discordapp.net/attachments/1187224425452535809/1195393134738280568/original-55c1924638195b3fae89d7ea3b5e3b05.mp4?ex=65c6489c&is=65b3d39c&hm=2042fcee0a7592b2498e8a79cfa5d77176b708b8521a0ef057d5775362bc4988&
```
OR
``` html
  https://media-ext-1.discordapp.net/attachments/1187224425452535809/1195393134738280568/original-55c1924638195b3fae89d7ea3b5e3b05.mp4?ex=65c6489c&is=65b3d39c&hm=2042fcee0a7592b2498e8a79cfa5d77176b708b8521a0ef057d5775362bc4988&
```
etc.

5. Now using the new links, you will see the video will play in your browser instead of auto-downloading!
6. Ba-boom, there you go!

***

SOURCE:

[Can we get media.discordapp.net videos to play in the browser again instead of auto-downloading?](https://www.reddit.com/r/discordapp/comments/xn4pxa/can_we_get_mediadiscordappnet_videos_to_play_in/?context=3)

