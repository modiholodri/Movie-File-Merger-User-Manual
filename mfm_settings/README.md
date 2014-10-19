# MFM Settings

Most of the settings are regular expressions.  See the chapter Regular Expressions at the end of MFM Settings for more information.

## Nick Name
Fill in your nick name, so that it will be shown in the pop info when the mouse is hovered over an item.  It is useful to know from where an item comes when you populate your wish list from more than one source.

## Considered Files Settings
MFM only considers files which have certain extensions.  Files which are not relevant are ignored.

[![Considered Files](../images/ConsideredFiles.jpg)](../images/ConsideredFiles.jpg)

### Video Files Extension
The Video Files Extension regular expression identifies main video files.  If no main file exists also the add-on files will be ignored.  Keep the list as short as possible to speed up the file processing.  Add all wanted video file extensions separated with a vertical line “|”.

### Add-on Files Extension
The Add-on Files Extension identified add-on files like subtitles or posters.  Add-on files will be only considered if a main video file exists.  Add all wanted add-on file extensions separated with a vertical line “|”.

## Name Unification Settings
MFM tries to unify the names of items, so that they can be better read and compared.

[![Name Unification](../images/NameUnification.jpg)](../images/NameUnification.jpg)

### Cut Name Before
The Cut Name Before regular expression tells MFM what not to include in the name.  Everything after, including the match itself, will be removed from the item name.  For example the year is good to remove, because the same movie can have different years in different collections.  The disadvantage is that two different item with the same name, but a different year, will be treated as one.  This regular expression is a little bit more complicated; please consult the Regular Expression Explanation chapter for more information.

### Only Characters
The Only Characters regular expression tells MFM which characters to accept.  All other characters will be removed from the item name.  The only character regular expression has to start with “[^” and end with “]”.  All characters, which should be included in the unified item name, have to be written in the middle.

### Convert to Lower
MFM capitalizes the first letter of each word in a name by default, to make the item name easier to read.  The Convert to Lower regular expression tells MFM which words in the name to convert to lower case.  The convert to lower regular expression contains the articles between spaces “ “ separated by a vertical line “|”.

### Episodes Identification
The Episodes Identification regular expression tells MFM where to find the episode identification in the file name.  The episode identification has to contain 2 numbers of which the first number is for the season and the second number for the episode.  Episode names will be truncated after the episode identification.  Series names will be truncated before the episode identification.  The regular expression “\d+” means a number with any amount of digits.  Different episode identifications have to be separated by a vertical line “|”.

## Supporting Programs Installation Paths Settings
MFM uses just 2 programs which are called direct; TeraCopy and Media info.  Other programs, like the web browser and the media player, are launched by executing the file or http address.

[![Supporting Programs](../images/SupportingPrograms.jpg)](../images/SupportingPrograms.jpg)

Note that even when the German version of Windows 7 is installed and the “Program Files” folder is called “Programme” in the Windows explorer the paths work also with “Program Files”.  That means if the default settings are used during the installation there should be no need the change these settings.

### TeraCopy Path
The TeraCopy Path points to where you have installed TeraCopy.

### MediaInfo Path
The MediaInfo Path points to where you have installed MediaInfo.
