# Train Splash Theme
Before Starting I want to give credits to respective owners:
- Video is free licensed go give like to them: https://www.pexels.com/video/train-traveling-on-the-mountainside-in-winter-3563083/
- Bottom left sticker is from: https://giphy.com/stickers/pudgypenguins-house-laundry-maid-PTLbcRjuiEHmIX7mA2
- Bottom right sticker is from: https://giphy.com/stickers/gun-jinzhan-sophia-gR6uO0IYic3ii1HSOa
- Middle sticker is from: https://giphy.com/stickers/capybara-capybaras-thecapycode-sbW2AUZLt98WoenLSl
- Top right sticker is from: https://giphy.com/stickers/pudgypenguins-huh-question-interesting-YGbY1MY31PIFoQQTt7
- Top left sticker is from: https://giphy.com/stickers/loading-cargando-lauraarpaz-rIqUQgjJa5v7Z0gSmD
- Thanks to Canva platform for giving me free video editing solution. No install, working from browser, no fuss, perfect output.
- Thanks to [nikp123/minecraft-plymouth-theme](https://github.com/nikp123/minecraft-plymouth-theme) for showing how to do stuff(I used his code for displaying messages from boot.).
- Thanks to plymouth program for making this possible for us.
- **If you are owner of any of these and want me to remove your work, mail me from: edoko192@gmail.com or open an issue in github, codeberg. I will take those claims very seriously and remove your work asap. Thank you for your work.**


This is my plymouth theme. It is designed for 1920x1080 pixel devices but appearently looks good in smaller scales too. For upper scales, Sorry bud, If you open an issue I will give it a try though, but Since I don't have those devices; I can't test it, it's up to you to testing and using it.

# Preview
Here is how it looks it from vm. Notice that **vm has lower scaling** so full scaled video are not rendered here.  This is intentional, because with scaling it takes too long to render. OS starts before plymouth splash are showing itself.  (gif takes long time to load)
![preview](preview.gif)

This is what full scaled video looks like. This is also how video rendered in my device. Notice that down below video are not a full bootsplash video but it is the background video.(gifs take long time to load :P)
![MyLinuxBootsplash](MyLinuxBootsplash.gif)

# Installing
Install plymouth from your distro. copy `TrainSplash` folder to `/usr/share/plymouth/themes` and tell plymouth to set this as default theme(`plymouth-set-default-theme -R TrainSplash`). Reboot and its yours.

# Closing thoughts
I can make this theme so much better, add effects, make loading bar better, modernize ui etc etc. But there is no reason for me to do it now because only user of this theme are me and I am pretty happy with current state of the theme. If other people starts using this and they want me to modernize ui, I will do that, thanks.
I think I made a good bootsplash for myself. For owners of this assets, if you are using linux and want me to make a theme for you , I will gladly do that for you and make it even better than this. Thanks for reading and have a nice day. 