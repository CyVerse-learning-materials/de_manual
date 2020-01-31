.. include:: cyverse_rst_defined_substitutions.txt
|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

------------------------
Searching for Data Items
------------------------

You can do a basic query for a data file or folder in the Data window search field, or create a more specific advanced one.

Advanced search features include the ability to search for included or excluded words in the file or folder name, date created or last modified, metadata attributes and values, owner, shared recipients, file size, tags, and items in the Trash. You also can . You also can save an advanced search for later reuse, and include items in the Trash folder.

Within the search query, you can use wildcards * (asterisk, which returns any character sequence) and ? (question mark returns any single character sequence) to widen your search. Note that you cannot start the query with a wildcard.

Once you have the search where you want it, you can save it as a filter name for future reuse. Saved filters are displayed at the bottom of your Navigation list under the filter name. Clicking the filter executes the search with the same settings. You can edit a filter and execute it one time only or save it as a new filter, as well as delete a filter.

Before you begin, you may want to watch a `YouTube video on advanced data search <http://www.youtube.com/watch?v=BoTYqPllZrI>`_.

+------------------------------------------------+
| **Not getting the search results you expect?** |
+------------------------------------------------+
| If you are not seeing expected search results, | 
| be aware that it may take a few minutes for any| 
| changes to a data file or folder – such as new |
| upload, delete, rename, or update – to be      |
| reflected in search results.                   |
+------------------------------------------------+

You also can search for other files and folders with the same `tag <https://wiki.cyverse.org/wiki/display/DEmanual/Using+Data+Tags+and+Tag+Descriptions>`_, as described in the section below. 


Opening the advanced search options window
------------------------------------------

.. |icon| image:: img/AdvancedSearchIcon.gif

You can customize a complex or simple query using the advanced search parameters.

1. In the Data window, open the advanced search options window by clicking |icon| next to the search field:

.. image :: img/DataAdvSearchWithTaggedWith1-9-2.png

--------------
Search options
--------------


File and folder names
---------------------

You can search for file and folder names in the Data window search field, and include or exclude file and folder names in the advanced search options window.

    1. In the Data list search field, enter at least 3 characters (case-insensitive) of the file or folder name.
       The middle section displays the number of search results returned for the query, and the name and path of each result.

    .. image:: img/SearchResultsBasicData.gif


Including or excluding specific words in the file or folder name (advanced search)
----------------------------------------------------------------------------------

    1. If necessary, click |icon| next to the search field to open the advanced search options window.
    2. To include specific words in the query, click in the **File/Folder name has the words** and enter the word(s) to include in the query.
    3. To exclude specific words in the query, click in the **File/Folder name doesn't have** field and enter the word(s) to exclude in the query.
    4. Continue adding more parameters, `save it as a filter <https://wiki.cyverse.org/wiki/display/DEmanual/Searching+for+Data+Items#SearchingforDataItems-_savedSearchFilter>`_ for future reuse, or click **Done** to execute the search. 


Metadata attributes and value (advanced search)
-----------------------------------------------

For more information on metadata attributes and values, see `Using Metadata in the DE <https://wiki.cyverse.org/wiki/display/DEmanual/Using+Metadata+in+the+DE>`_.

    1. Click |icon| next to the search field to open the advanced search options window:

    .. image:: img/AdvSearch-Metadata.jpg

    2. Click in either the **Metadata attribute has the words** field or **Metadata value has the words** field and enter the attribute or value to include in the query, and then click **Search**.

+----------------------------------------------------------------+
| To search on info-type, enter **info-type** for the attribute. |
+----------------------------------------------------------------+


File size (advanced search)
---------------------------

    1. Click |icon| next to the search field to open the advanced search options window.
    2. To search for data items by created date, click the **File size is bigger than or equal to** field and enter the size. 
    3. To define the smallest file size, click in the **File size in smaller than or equal to** field and enter the size.
    4. Change the size type (KB, MB, GB, or TB) as needed.
    5. Continue adding more parameters, `save it as a filter <https://wiki.cyverse.org/wiki/display/DEmanual/Searching+for+Data+Items#SearchingforDataItems-_savedSearchFilter>`_ for future reuse, or click **Done** to execute the search. 


Date (advanced search)
----------------------

    1. Click |icon| next to the search field to open the advanced search options window. 
    2. To search for data items by created date, click the **Created within** drop-down arrow, and select the day range.
    3. To search for data items modified data, click the **Modified within** drop-down arrow, and select the modified date.
    4. Continue adding more parameters, `save it as a filter <https://wiki.cyverse.org/wiki/display/DEmanual/Searching+for+Data+Items#SearchingforDataItems-_savedSearchFilter>`_ for future reuse, or click **Done** to execute the search.


File owner or shared recipients (advanced search)
-------------------------------------------------

    1. If necessary, click |icon| next to the search field to open the advanced search options window.
    2. To search by the item's owner, enter the user's username in the **Owned by** field.
    3. To search by users with whom the file has been shared, enter the user's username in the **Shared with** field.
    4. Continue adding more parameters, `save it as a filter <https://wiki.cyverse.org/wiki/display/DEmanual/Searching+for+Data+Items#SearchingforDataItems-_savedSearchFilter>`_ for future reuse, or click **Done** to execute the search.


Tags
----

You can search for files and folders that use the same tag or tags as other files or folders in your Data list. You can search for a single tag in the Data window, or search for a tag or multiple tags in the advanced search options window. When you search for multiple tags, any files or folders with at least one of the matching tags is displayed in the search results list.

For more information on tags, see `Using Data Tags and Tag Descriptions <https://pods.iplantcollaborative.org/wiki/display/DEmanual/Using+Data+Tags+and+Tag+Descriptions>`_.


Simple tag (Data window)
------------------------

    1. In the Data list, click the checkbox for a file or folder with the tag on which to search.
    2. In the Details panel on the right, click the orange tag to find other files and folders with a match. The list of files and folders with the same tag is displayed in the middle section.


Multiple tags (advanced search)
-------------------------------

When searching on multiple tags, you build a list of tags then execute the search. When the search is executed, the list of all files and folders containing at least one of the tags in the search list is returned. You can then view the list tags that were used.

    1. If necessary, click |icon| next to the search field to open the advanced search options window.
    2. In the **Tagged with** search field:
        a. Enter the first few characters of the first tag to find.
        b. Click the matching tag.
           The orange tag is added below the search field. If no suggestion is displayed, the tag you entered has not been used in any files or folders in your Data list.
    3. Clear the search field and repeat for each tag to include in the search.
       Each subsequent tag is added to the list below the search field. 
    4. Click **Search**.
       Any file or folder with at least one matched tag is displayed in the search results list in the middle section.
    5. Click the checkbox for each file or folder in the middle section to view its matching tag or tags in the Details section.
    6. Continue adding more parameters, `save it as a filter <https://wiki.cyverse.org/wiki/display/DEmanual/Searching+for+Data+Items#SearchingforDataItems-_savedSearchFilter>`_ for future reuse, or click **Done** to execute the search.


----

**Fix or improve this documentation:**

- On Github: |Github Repo Link|
- Send feedback: `Tutorials@CyVerse.org <Tutorials@CyVerse.org>`_
- Live chat/help: Click on the |intercom| on the bottom-right of the page for questions on documentation

----

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


.. Comment: Place Images Below This Line
   use :width: to give a desired width for your image
   use :height: to give a desired height for your image
   replace the image name/location and URL if hyperlinked


 .. |Clickable hyperlinked image| image:: ./img/IMAGENAME.png
    :width: 500
    :height: 100
 .. _CyVerse logo: http://learning.cyverse.org/

 .. |Static image| image:: ./img/IMAGENAME.png
    :width: 25
    :height: 25



.. Comment: Place URLS Below This Line

   # Use this example to ensure that links open in new tabs, avoiding
   # forcing users to leave the document, and making it easy to update links
   # In a single place in this document

   .. |Substitution| raw:: html # Place this anywhere in the text you want a hyperlink

      <a href="REPLACE_THIS_WITH_URL" target="blank">Replace_with_text</a>


.. |Github Repo Link|  raw:: html

   <a href="FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX" target="blank">Github Repo Link</a>
