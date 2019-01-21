# Screen Timelapsez Translation

# Contributing

👍 🎉 Thanks for taking the time to contribute! 🎉 👍

Any contributions to this repository are most welcome. If you are planning to contribute, please take time to read this file and follow the guidelines.

## How to

#### There are quite a few ways to contribute, but following is the recommended approach.

`1. Fork this repository`

When you fork this repository you will have a personal copy of the repository where you will have complete access to edit any file. 
Edit the files you want to and commit the changes.

`2. Make a Pull request`

When you are done editing the file(s) and have commited the changes to the fork, you can now make a pull request to this repository.
You will see a Pull request option alogside compare just above the Latest commit message in your fork. 
Please beaware making a pull request to your own repository and making a pull request to this repository are two different things.
You need to click on the `Pull request button` and not the `Pull requests tab`. 

`3. Wait for the changes to get approved`

After making a Pull request you will see your pull request listed in the `Pull requests section` in the original repository.
Your changes will be reviewed and once the changes are approved they will be merged and hence will get applied to the original repository.
You might be asked to improve or make further changes, if the the commits you made could not be approved for some reason. In that case, you will need to edit the files again. 
Please note that, you do not have to make another pull request, just make the changes you are supposed to in the fork and it will get reflected in the already made pull request.


## Adding translation

This application aims to be available in multiple (as many as we can) languages. 
The task could have been achieved by using a translation tool, but in order to maintain accuracy and context, this repository provides an easy way for the contributors native to different languges to add their language to the application.

### Adding a language

To add or update a language, follow the `Step 1` of  How to section above. 
Once you have your fork ready, you can edit the required files.  

#### Adding new language 

`1. add languagename folder`



Example:

```
zh-Hant.lproj
en.lproj
es.lproj
```


#### Reference:
https://www.loc.gov/standards/iso639-2/php/code_list.php
https://www.w3schools.com/tags/ref_language_codes.asp

`2. Create a new file "Main.txt" under the folder`

```javascript
/* Class = "NSMenuItem"; title = "every 30 mins"; ObjectID = "3c0-kP-yux"; */
"3c0-kP-yux.title" = "change the language here";

/* Class = "NSTextFieldCell"; title = "TimeInterval"; ObjectID = "44a-KB-aP0"; */
"44a-KB-aP0.title" = "Intervalo de tiempo";

/* Class = "NSTextFieldCell"; title = "Autosave:"; ObjectID = "6gl-IQ-tPy"; */
"6gl-IQ-tPy.title" = "Guardar automáticamente:";
```
Notice that you are aleady given the words that you need to add translation for. Just add the translation according the main.txt given.
Please do not add any new words as the words given are the only words that the app will look for.

`3. Commit your changes and make a Pull request`

Now that you have added the translation file, you can commit the changes and make a Pull request. (Follow Step 2 of How to Section)



### Note: 
Please do not use any translation tools as it would defeat the purpose of the contribution. 