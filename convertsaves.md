# School of Lust - Converting Saves
[*\~My list of walkthroughs and when they'll be updated\~*](https://www.patreon.com/maimlain)

<br>

- [Back to incest patch](https://github.com/maim-lain/schooloflust/blob/master/patreonpatch.md)  
 
---

<br>

- When transfering saves, sometimes ingame at the load game screen the transfered save will be invisible or say that it is a different save. The file number of the save you transfered corresponds to which save you need to click ingame to load the save you transfered:
  - file1.rpgsave -> Autosave
  - file2.rpgsave -> Save #1
  - file3.rpgsave -> Save #2
  - etc.

<br>
<br>

## Converting Saves:
- Find the file#.rpgsave that you want to convert in ```/www/saves``` in your old game folder
- In the incest patch game folder go to ```/www/saves```
- Open ```RPGMakerMVSaveEditor``` then ```index.html``` to bring up the tab and with it open the save you want to convert
- Select all the text and copy it into ```/www/saves/save.txt``` and then save and close the ```save.txt``` file
- Open ```Save Converter``` and select an option
- Open ```save.txt``` and select all the text and copy it
- Delete all the text in the RPGM Save Editor html tab, paste the new text, and click 'save' to download your converted save
- Put the converted save in the save folder you wish to transfer it to
- Finally copy ```config.rpgsave``` and ```global.rpgsave``` from your old save folder to your new save folder
