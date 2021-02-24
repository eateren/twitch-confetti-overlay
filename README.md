# Twitch Confetti Overlay
Let viewers drop confetti on your stream with a command in chat


# Installation Guide
1. Download the files using the green button on the top right.
1. You can download it as a zip.
1. Open the zip, and save the confetti folder somewhere on your computer.
1. Open the config.js file using Notepad.
1. Set the configuration by entering and saving the config.js file:
    1. channel - your twitch username
    1. waitTimeUser - the cooldown time in seconds per user
    1. waitTimeGlobal - the global cooldown time between confetti.  Set 0 for no global cooldown
    1. command - set the command keyword to trigger confetti.  To trigger start with !, ie: !confetti
1. Using OBS (Streamlabs, Streamelements, etc.) create a browser source for the overlay:
    1. Check off the local file box
    1. Browse for the confetti-overlay.html local file
    1. Set your width and height, I recommend 1280X720 or 1920X1080
1. Place your confetti overlay above the sources you want.
1. Type !confetti in chat (or your custom command) to make it rain!
1. Then go over to https://twitch.tv/instafluff and give him a thanks!
1. Also you can thank mathusummut for the confetti https://github.com/mathusummut
