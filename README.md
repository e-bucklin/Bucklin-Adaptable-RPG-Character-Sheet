# Bucklin-Adaptable-RPG-Character-Sheet
This app is built with LITRPG authors in mind to help them keep track of character progression.  It is built to be unobtrusive and easy to use.  Feel free to reach out if there are other features or adaptations you would like to see in new viersions(contact:etb39@nau.edu).  If you find this app useful, consider sponsoring my work.



To all the authors using this app:

Thank you so much for the time and effort you put into your work which brings joy to so many.  Your readers love you.  Your readers are inspired by you.  I hope this makes your work a little easier and improves quality of work life.  Know that while you may be writing by yourself, you are not alone.  We all wish to help if there is anything we can do.  All you need do is ask (or even just mention as an aside at LITCon that stat tracking is tedious and anoying :P) and we will jump to try and help.  I found this project very fullfilling.  Almost 600 lines of code and love.  I hope its beneficial.  Thank you for all that you do every day.



INSTRUCTIONS:

The "save" button will create a new excel file or append an existing excel file with the entered character name as the file name.  This save will appear in the same folder     that the program .exe is stored.  When appending an existing file, it will create a new tab so users can keep track of the history of character development.

Any entry left blank will produce a blank cell in the saved Excel file

The "load" button will prompt you to select an existing excel file to load.  It will load the most recent tab information.  If you wish to go back to a previous tab, you can delete subsequent tabs.  If you wish to retain those tabs, it is recommend to move them to another excel file before deleting.



About Excel Save:

The excel save is relatively robust to changes.  When changing or adding to the excel file directly, it is recommended that the section headers(i.e. 'CHARACTERISTICS', 'SKILLS', etc.) not be changed as these are reference points for the program.

If you would like to add additional information to the excel to keep track of it, all cells to the right of the labeled cells are not read by the program and can be manipulated freely with no change to the programs load function.  Currently, the program will not copy any information to the right of the labeled cells to new sheets.  This has to be done manually if desired (note:this may be an added feature in later versions if it is desired).  Feel free to play around with the excel sheet to see how it affects the loading of the program (you won't hurt anything).



HOW TO DELETE LINES:

Currently there is no in-program method for deleting unwanted lines.  There are two options instead.
1) By deleting all entries on a line it will save to excel as blank cells.  This simply creates spacing in excel.  Note: when loaded again this will create a line with empty entries again, so it does not permenently delete a line.
2) By saving and closing the program and then deleting the undesired row in excel, you can reload the character sheet without the line. (note: when I say delete the row here I mean such that it prompts you to move the cells up.  The row must not be present upon loading for this to work.  i.e. use the actual delete button.  you could also just copy the cells below the row and move them up)
