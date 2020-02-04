.. include:: cyverse_rst_defined_substitutions.txt
|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

--------------------------------------------------
Using the Data Edit menu to edit files and folders
--------------------------------------------------

There are several different ways you can edit files and folders. You can `rename <https://wiki.cyverse.org/wiki/display/DEmanual/Renaming+a+Data+File+or+Folder>`_ a file or folder;
`edit <https://wiki.cyverse.org/wiki/display/DEmanual/Editing+the+Contents+of+a+File>`_ a file you own; add, edit, and retract `comments <https://wiki.cyverse.org/wiki/display/DEmanual/Viewing%2C+Adding%2C+and+Retracting+Data+Comments>`_; 
edit a file's `info-type <https://wiki.cyverse.org/wiki/display/DEmanual/Editing+a+File%27s+Info-Type>`_; move a file or folder; and add or edit `metadata <https://wiki.cyverse.org/wiki/display/DEmanual/Using+Metadata+in+the+DE>`_.


.. image:: img/Data-EditMenu.jpg


Editing the Contents of a File
------------------------------

You can edit a **one-page** plain text or tabular data (CSV, TSV) file that you own, both in the file view and in the Tabular View. **In order to do so, you adjust the Page Size (KB) slider until all of the data is displayed on one page.**


**If the file is too large, you can:**

   - **Create a copy of the file** by `downloading <https://wiki.cyverse.org/wiki/display/DEmanual/Downloading+Files+and+Folders>`_ the file, editing it as needed, and then `uploading <https://wiki.cyverse.org/wiki/display/DEmanual/Uploading+and+Importing+Data+Items+Within+the+DE>`_ it into the DE as a new file.

   - **Copy a large file** in the Data Store using the iCommands command line utility. For more information, see `Using iCommands <https://pods.iplantcollaborative.org/wiki/display/DS/Using+iCommands>`_.

   1. In the Data window, `search <https://wiki.cyverse.org/wiki/display/DEmanual/Searching+for+Data+Items>`_ for the file or folder. You may want to `add the Path column <https://wiki.cyverse.org/wiki/display/DEmanual/Uploading%2C+Importing%2C+Downloading%2C+Sharing%2C+Editing%2C+Searching+Data+Files+in+the+DE#Uploading,Importing,Downloading,Sharing,Editing,SearchingDataFilesintheDE-pathcolumn>`_ to view the path. 

      +--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
      | To perform an advanced query, such as including or excluding wors in a file or folder name, searching for metadata attribute or value, file size range, created or modified date, owner, shared recipient, or tag, see `Searching for Data Items <https://wiki.cyverse.org/wiki/display/DEmanual/Searching+for+Data+Items>`_.  |
      +--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

   2. Click the chekbox for the file you own.

   3. Click **Edit** and then click **Edit File**.

      When you first open the file, the **Page Size (KB) slider** by default is at the far left position, more than one page is displayed in the page navigation (unless the file is very small), the Save button is not enabled, and Not Editable is displayed.

      .. image:: img/EditTextFile1.png

   4. Drag the Page Size (KB) slider until the page navigation at the bottom displays 1 of 1.

      .. image:: img/EditTextFile2.png

      Once page 1 of 1 is displayed, the file becomes editable. If the file still is not editable, youn either don't have Own permissions to the file, the file is not an editable text file, or it is too large.

   
   5. Edit the file.
   6. When done, click **Save**.

--------------------------
Editing a File's Info-type
--------------------------

.. |removeIcon| image:: img/RemoveInfoTypeIcon.gif

When a file is imported or uploaded, it is auto-assigned an info-type to identify the type of data it contains. You can change or assign the info-type for a file you own or to which you have write `permissions <https://wiki.cyverse.org/wiki/display/DEmanual/Sharing+Data+Files+and+Folders>`_. 
File-type auto-detection is available mfor text files, including .bam, .csv, .fasta, .fastq, .fa, .fq, .nwk, .newick, .phylip, .tsv, and more.

+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| The automatic info-type assignment is an asynchronous process that is dependent on other requests in the queue, which may cause a delay until the info-type is assigned. You can manually assign the info-type immediately, if necessary. |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

   1. In the Data window, click the file you own. The Info-Type row in the details section on the right displays the current info-type, if any. 

   2. **To define or change the info-type:**

       a. Either click **Select** (if the info-type has not yet been defined) or click the current info-type in the Details section on the right, or click the **Edit** menu and then click **Edit Information Type**.

       b. In the **Select Type** drop-down list, select the info-type to use.

      +------------------------------------------------------------------------------------------------------------------------------------+
      | **File type not in the list?**                                                                                                     |
      +------------------------------------------------------------------------------------------------------------------------------------+
      | If your file type is not in the list, email `CyVerse Support <support@cyverse.org>`_ with the sample file to be added to the list. |
      +------------------------------------------------------------------------------------------------------------------------------------+



       c. Click **OK**.

   3. **To remove the info-type**, click |removeIcon| next to the Info-Type displayed in the Details section. 





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
