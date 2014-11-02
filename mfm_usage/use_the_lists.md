## Use the Lists

Each collection is split into 3 lists.  The Garbage, Existing, and Wish lists are stored in a collection.  A list is the sum of all items of a certain collection type, which match certain criteria, like you don’t want to have them, you have them, or you want to have them.  The Import list items are not stored in the collections, but have to be imported new each time from a folder or an exported list.

The Garbage list is the collection of items, which you do not want to have.  It includes also misspelled names.  The Existing list is the collection of items, which you have.  It can include also garbage items.  The Wish list is the collection of items, which you want to have.  The Wish list can include also Garbage and Existing items.  The Import list is the collection of items, which are available from an exported list or a folder on the hard disk.

If you hover the mouse over a list item a pop-up info is shown containing information about the item, like file size, file name, or resolution… What is shown depends on the how the item is scanned or if it comes from a precompiled list.

The lists are handled by selecting items and performing the desired action on them.  To select multiple items with the mouse, use the right most column (no header, quite thin and empty) and move the mouse over all items, which should be selected.

[![Lists](../images/Lists.jpg)](../images/Lists.jpg)

To add items to a list from a top level folder, drag the folder from the Windows Explorer and drop it on the list.  The add items from an exported list to a list, drag the exported list from the Windows Explorer and drop it on any list.  The pop-up info of items in the list will not be overwritten and only new items added to the list.  Only relevant unified items are added to a list when the items are read from a folder.  Unified items means that if there are more files for the same item, like a video file and a subtitle file, only one entry will be shown in the list.  MFM tries to keep the item names short to make them easier to read and to compare.  Files which are not relevant for MFM will not be shown in the lists.

All lists are drop areas, for items, for list exports and for folders.  To move items from one list to another, drag and drop items from one list to another list.  To delete items from a list, select them and press the Delete key.  Only the lists are changed, but the files still remain where they are.
If the collection type is changed or MFM closed it will ask you if you want to save any changed lists, except the Import list.

MFM uses unified item names and combines different file types, to make the processing easier.  The rules how to unify the items names can be set with regular expressions in the Setting tab.
Note:  You should organize your stuff in folders according to the collection types like Movies, Series, or Documentaries to make it easier to populate the lists.

### Garbage List
Garbage items are colored red.  The Garbage list contains all items you don’t want to have and probably don't have on any of your hard disks.  To put an item in the Garbage list can mean also that the name is spelled wrong or that it is in the wrong collection category.  It does not necessarily mean that the movie itself is garbage.  To add items to the Garbage list drag and drop items from any other list.
Note:  It the Collection Type Series is selected, only the titles of the series are shown, but not the individual files.  In order to make this work a valid Episodes Identification has to be contained in the file names.

### Existing List
Existing items are colored dark green.  The Existing list contains the items you have on your hard disks.  To add items to the Existing list drag and drop the top level folders from the Windows Explorer on the Existing list.  After a while your Existing list will get out of sync with the stuff you actual have.  To get an up to date Existing list erase all items and populate the list again with the top level folders from your hard disks.

### Wish List
Wish items are colored light green.  The Wish list contains items you want to have. To add items to the Wish list drag and drop items from the Import list on the Wish list.  After you have copied the items they will appear in the Wish list.  To clean up the Wish list, erase the Garbage and Existing items.
Note:  It the Collection Type Series is selected, only the titles of the series are shown, but not the individual files.  In order to make the work a valid Episodes Identification has to be contained in the file name.

### Import List
The Import list contains all the items, which should be processed and is a mixture of Existing, Garbage and New items, to combine with your existing collection.  To prepare the processing populate the Import list from previously saved .csv files.  Move the items to the other lists and save them for later processing. To start the actual processing the Import list has to be populated from a folder on a connected hard disk.

