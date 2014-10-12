# Collection Organization

There are different ways how to organize your collection.  Some people have no organization at all and that’s the worst case.  Most people have a basic separation between movies or documentaries and series and that’s already better.  There is simply no best way how to organize your collection; it depends on your personal preferences.  MFM is designed so that it browses also through subfolders and that the organization structure doesn’t matter that much.  However, it is pretty important to keep your collections as clean as possible on your hard disks.  Below are some suggestions, which make your life easier, especially if your collection gets bigger and bigger.

## Do’s and Don’ts
Below listed are some recommendations based on my experience, so if something goes against your preferences just ignore it.

### My Dos

* Do separate your video files according to what they are.  Movies, series, documentaries...
* Do use correct names.  Get them from an internet database.
* Do put the year in the movie files names after the actual movie name.
* Do put the series name, the season and the episode number in the file names.
* Do combine split video files.  Use AVI Mux GUI.
* Convert DVD files to single video files.  Use MakeMKV.
* Do delete some videos if you run out of space.  That increases the quality of your collection and saves
you the money to buy a new hard disk.
* Do use your friend’s hard disk to make a back up of your good videos.

### My Don’ts

* Don’t include video format information in the names.  It can be seen when using a database program like PVD or MediaInfo.
* Don’t make too many subfolders.
* Don’t keep any files not needed, like the torrent files.
* Don’t keep videos with bad quality.
* Don’t keep videos with burned in subtitles.
* Don’t keep movies in format 4:3 if they should be at least 16:9.  Or at least move them in a folder for bad quality movies.
* Don’t rename you files manually.  Use FileBot.
* Don’t keep not used subtitle files.  If needed they can be download again.
* Don’t keep your videos in zip or rar files.  Videos are already compressed and normally cannot be compressed more.
* Don’t worry too much that you will lose a file, most likely you can get it again.

## General Organization

Make top level folders for My Documentaries, My Movies, and My Series.  To add “My” in front of the collection types has the advantage that all collections are beside each other on the hard disk, even if you put other stuff on there.  “My” could be also replaced with your nick name or similar.  Put movies, series and documentaries in their own top level folders.  A good idea is also to make a My Garbage folder and put all movies in there which you probably will delete, but you are not sure for now, because maybe some other people like them.  If you later run out of space and need more to put on new stuff, you just have to delete the files in My Garbage without thinking too much what to delete during that stressful time.  You can make a folder structure on lower levels as you like and there is no limit to the number of subfolders you can make.

To avoid distributing stuff with bad quality or stuff which is simply not good, I recommend that you delete real crap immediately, since probably nobody wants to have it anyway.

If you have more than one hard disk, implement the same structure on every hard disk.  That way, if one of your hard disks dies, you lose only a part of each collection, but not a complete collection.  Then there is also no need to move stuff around all the time and if a hard disk is full you just buy a new one and put your stuff on there.  If you have an old hard disk, or a hard disk, which seems to be breaking down soon, you could put all the stuff on there, which you like least or with just acceptable quality.  If the sick hard disk then breaks down the average quality of your collections, will immediately improve a lot...

If you have a messed up folder structure where video files and other files (poster, torrent files...) are mixed together you can move out important files (video and subtitles) with MFM.  MFM does not touch other files, so that you can review if there is any important file left in the messed up “empty” folder structure.  Check the file names before moving the files, because sometimes files in folders are not named according to the content.  If you drop the top level folder into MFM you can see the list of all files and scan that one for strange names.  If nothing important is left just delete the whole folder structure.

If you have multiple files for the same movie, like cd1 and cd2, then they should be combined using AVI Mux GUI.  If the files are still in the DVD structure you can use MakeMKV to convert them to a single video files.  Both programs are more or less as fast as if the movie is just copied.  The limit is how fast your computer can read and write to the hard disks.  To speed up the processing it is better to convert the files from one hard disk to another.

To make the comparison as easy as possible some basic naming guide lines should be followed.  FileBot is good to get the correct names from internet databases and rename your movies and series.  If the names are that strange that FileBot cannot find them on the internet File Renamer Basic can be used to fix them so that FileBot can find them and make them 100% correct.  If you share your collection with your friends it is important to have the same names for the same stuff, otherwise they will be treated as different videos by MFM.

### Movies
A movie is a video telling a fictive story by the use of actors or a story or event recorded by a camera as a set of moving images and shown in a theatre or on television; a motion picture.  Movies should be only actual movies and not be confused with Documentaries or Series.  Even if a movie is based on a real story it is no documentary.  Some sample movies are...

![Movies](https://raw.githubusercontent.com/Modi777/Movie-File-Merger/master/Manuals/Movies.jpg)

When the name of a movie is processed, it is reduced according to certain criteria to ease the matching of the movies.  MFM tries to cleanup Movie names, by cutting them of before the year, in the files name.  If no year is found it is tried to clean up the name according to some other criteria.  However, the better the naming of the files is that better MFM works.

The recommended naming format for movies is…

`Movie Title` (`year`)
![Movies Format](https://raw.githubusercontent.com/Modi777/Movie-File-Merger/master/Manuals/MovieFormat.jpg)
The important thing is that the year is immediately after the name.  If round brackets are used or not is not that important and the main reason is readability.

I would recommend having no subfolders for each movie.  If you want to can separate your movies somehow according to genres, but the challenge with this implementation is that all movies are of more than one genre, like action comedy or a romance drama.  To get a good overview of all the stuff you have you can use a database program like the Personal Video Database.  PVD can download information from the IMDb.  With PVD you can mark you movies as seen and filter or sort them according to many criteria.

### Documentaries
A documentary is video that is telling a more real story by the use of presenters or a movie or a television program that provides a factual record or report.  Documentaries are treated like movies concerning the item names.  Some sample Documentaries are...

![Documentaries](https://raw.githubusercontent.com/Modi777/Movie-File-Merger/master/Manuals/Documentaries.jpg)

There is no recommended format concerning the documentaries.  Depending on the documentation, either Movie format or Series format can be applied.

![Documentaries Format](https://raw.githubusercontent.com/Modi777/Movie-File-Merger/master/Manuals/DocumentariesFormat.jpg)
### Series
Series are a video collection telling a fictive story in multiple parts or episodes by the use of actors.  Series are set of related television programs, esp. of a specified kind: "a new drama series".  Some sample Series are...

![Series](https://raw.githubusercontent.com/Modi777/Movie-File-Merger/master/Manuals/Series.jpg)

The Series collection is treated, different from the Movies collection.  Items in the Garbage or Wish list are even reduced further, to the Series title.  The Existing and Import lists contain also the episode identifier.  The episode title is removed after the episode identifier, to enable better matching of the episodes.

The recommended naming formats for episodes are…

`Series Name` S`Season Number`E`Episode Number` `Episode Title`

The series should be in a folder for the each series and sub-folders for each season.

![Series Format](https://raw.githubusercontent.com/Modi777/Movie-File-Merger/master/Manuals/SeriesFormat.jpg)
### Miscellaneous
Use this collection for any video of any kind.  It is opened as default.  The Miscellaneous collection is treated like the Movies collection concerning the unified item names.  It can be also used as temporarily collection to clean up your collections.

### Adult and Clips
An Adult video is telling a fictive story by the use of special actors, which should not be watched by persons under 18 years.  The Adult collection is treated like the Movies collection concerning the unified item names.
A clip is a short video telling the story of a song by using dancers.  The Clips collection is treated like the Movies collection concerning the unified item names.

## Clean Up Programs

## FileBot to Rename Movies and Series

You can find more information about FileBot on http://www.filebot.net.  FileBot is the ultimate tool for organizing and renaming your movies, TV shows or anime, and music well as downloading subtitles and artwork. It's smart and just works.

Use FileBot to rename movies or series to their standard names.  It is important that series have good names and episode identifiers.  Similarly it is important that movies have good name, so that the list can be matched as good as possible.

![FileBot](https://raw.githubusercontent.com/Modi777/Movie-File-Merger/master/Manuals/FileBot.jpg)

Just drop the series folder of movies in the left list, right click match, and select The TVDB.  After FileBot found the title in the online database, click on Rename.  If FileBot asks you to validate the name, do so, and click continue.

## File Renamer Basic to Fix Serious Naming Problems

You can find more information on http://www.sherrodcomputers.com/products_filerenamer.cfm.  File Renamer was developed to easily and quickly rename multiple files at once.  With this program, you can rename entire directories and sub-directories of files/Images/Photos at once with a powerful preview and with multiple tools. It was designed to be easy to use yet powerful enough to handle some of the most complex tasks.  File Renamer is also perfect for renaming digital pictures. Select the pictures you want to rename, choose the new file name scheme, apply, you're done!  -  It's that easy!

Use File Renamer Basic to fix serious problems with you file name, like for example if the Series name is missing in front of the episodes.

![FileRenamer](https://raw.githubusercontent.com/Modi777/Movie-File-Merger/master/Manuals/FileRenamer.jpg)

## AVI Mux GUI to Combine Videos Split Over More Files
You can find more information on http://www.alexander-noe.com/video/amg.  AVI-Mux GUI is an application that allows to combine several video, audio or subtitle files into one file, without size restriction, allowing configuring properties of the output file to a deeper level than usual for such applications.

Use AVI Mux GUI to combine movies that are split in two CDs or more.  Drop the files in the top list and select all files in the list.  AVI Mux GUI can only combine files with the same format and resolution.

![AVIMuxGUI](https://raw.githubusercontent.com/Modi777/Movie-File-Merger/master/Manuals/AVIMuxGUI.jpg)

## MakeMKV to Convert DVDs to Single Files

You can find more information on http://www.makemkv.com.  MakeMKV is your one-click solution to convert video that you own into free and patents-unencumbered format that can be played everywhere. MakeMKV is a format converter otherwise called "transcoder".  It converts the video clips from proprietary (and usually encrypted) disc into a set of MKV files, preserving most information but not changing it in any way.  The MKV format can store multiple video/audio tracks with all meta-information and preserve chapters.  There are many players that can play MKV files nearly on all platforms, and there are tools to convert MKV files to many formats, including DVD and Blu-ray discs.

Use MakeMKV to convert your DVDs to single MKV files.  If movies are stored in the DVD structure as the single VOB files, MFM will not work.

![MakeMKV](https://raw.githubusercontent.com/Modi777/Movie-File-Merger/master/Manuals/MakeMKV.jpg)

