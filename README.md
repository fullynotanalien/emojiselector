![Screenshot](https://raw.githubusercontent.com/fullynotanalien/emojiselector/master/emoji-selector-screenshot.png)

# Why a desktop Emoji Selector?

PC/notebook users often prefer web-versions of popular chat applications that exists primarly for mobile devices. As emojis became part of our communication, PC users often see themselves visiting websites only to search and copy emojis they need to better express. 

Emoji Selector is a small GTK application that copies emojis to your clipboard so you don't have to look them up on the internet.

This software as currently is is not intended for public use as it is not complete. For now it only features the emojis I most need to talk to my girlfriend

# Compiling from source

``$ gcc `pkg-config --cflags gtk+-3.0` -o emojiSelector emojiSelector.c `pkg-config --libs gtk+-3.0` ``

# Running
`$ ./emojiSelector`


