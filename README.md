# clearzoomgifs
Clears all gifs and media automatically saved on your MacBook by the zoom app

#open your terminal app and paste this apple script. 


```
tell application "Finder"
delete file "Macintosh HD:Users:username:Library:Application Support:zoom.us:data"
end tell
```

#Replace username with the name of the user whose file you want to delete and filename with the name of the file you want to remove.
