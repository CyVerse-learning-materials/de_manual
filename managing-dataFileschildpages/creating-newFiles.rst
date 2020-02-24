.. include:: cyverse_rst_defined_substitutions.txt
|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


==============================
Creating New Files and Folders
==============================

You can create new **small** files and folders in your personal Data folder. File types include plain text, tabular data, R script, Perl, Python, Shell, and Markdown files. You also can create a list of files to use in HT (high-throughput) file execution.

After you create it, you can `edit <https://wiki.cyverse.org/wiki/display/DEmanual/Editing+the+Contents+of+a+File>`_ and `move <https://wiki.cyverse.org/wiki/display/DEmanual/Moving+a+Data+File+or+Folder>`_ the file or folder.


Before you begin, you may want to watch a `YouTube video on file creation, file editing, and tabular views <http://www.youtube.com/watch?v=mwaN3G2qEQs>`_.

+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| See `Using Special Characters in the DE <https://wiki.cyverse.org/wiki/display/DEmanual/Using+Special+Characters+in+the+DE>`_ for notes about file names.  |
+------------------------------------------------------------------------------------------------------------------------------------------------------------+


Creating new folders
--------------------

    1. In the Data window, select the personal folder under which you want to add the new folder.
    2. Click **File** and then click **New Folder**.
    3. Enter a unique name for the new folder and click **OK**.



Creating new files
------------------

You can create new plain text and tabular data files, as well as files using R script, Perl, Python, Shell, and Markdown. You also can create a high-throughput file list.

.. image:: img/DataFileCreate.jpg

--------------------------
NCBI SRA Submission Folder
--------------------------

You can create an NCBI SRA submission folder and then define its name and number of biosamples and libraries.

    1. In the Data window, select the personal folder under which you want to create the new submission folder. You can `move <https://wiki.cyverse.org/wiki/display/DEmanual/Moving+a+Data+File+or+Folder>`_ it later if necessary.
    2. Click **File**, click **Create**, and then click **Create NCBI SRA Submission Folder**.
    3. In the setup window, enter the project name, number of biosamples, and number of libraries.
    4. Click **OK**.


Plain text file
---------------

    1. In the Data window, select the personal folder under which you want to create the new text file. You can `move <https://wiki.cyverse.org/wiki/display/DEmanual/Moving+a+Data+File+or+Folder>`_ it later if necessary.
    2. Click **File**, point to **Create**, and then click **New Plain Text File**.
    3. In the file window, enter the text.
    4. When done, click Save, select a location in your personal folder space, enter a unique file name, and click OK.




Tabular data file
-----------------

.. |add| image:: img/NewTabDataFileIcons-AddRow.png

.. |delete| image:: img/NewTabDataFileIcons-DeleteRow.png



    1. In the Data window, select the personal folder under which you want to create the new tabular data file. You can `move <https://wiki.cyverse.org/wiki/display/DEmanual/Moving+a+Data+File+or+Folder>`_ it later if necessary.
    2. Click **File**, point to **Create**, and then click **New Tabular Data File**.

    .. image:: img/NewTabDataFile.png

    3. In the New Tabular File window, enter the number of columns, select the separator type (either comma or tab), and then click **OK**.
    4. In the Tabular View tab, enter the values for each column, and either click |add| to add a new row or |delete| to delete a row.
    5. When done, click **Save**, select a location in your personal folder space, enter a unique file name, and click **OK**.



HT analysis path list file for use in high-throughput and batch file execution
------------------------------------------------------------------------------

.. |batch| image:: img/BatchListIcon.jpg

.. |individualAnalysis| image:: img/ViewAnalysisStatusIcon.jpg


You can create a high-throughput analysis path list file for use in high-throughput and batch file execution. This allows you to feed a single file that is basically a list of up to 16 files into an app that supports a single file or single folder as input. 
The same analysis is then run **concurrently** on the first 8 files in the list, with any subsequent files queued for later submission. All files in the list must use the same parameters, and it is available for all apps in the DE, including Agave apps.

Once you have created and saved your list file by dragging the files from the Data list to the HT window, you can submit it as the input file in an analysis using any app. You can check the status of each file in the list as it is executed.

**Note:** Each path from each HT list will be paired for each job, so each HT list used in an app must have the same number of paths. For example, if each HT list has 10 paths, 10 jobs will be run.

    1. In the Data window, click **File**, point to **Create**, and then click **New HT Analysis Path List file**.
    2. In the Data window, navigate to the first file to add to the list, and then drag it to the HT window.
    3. Repeat for each file to add to the list. Remember that all files must have the same parameters when you create the analysis.
    
    4. When the high-throughput list is complete, select the folder to which you want to save the file, click Save, and enter the filename (no spaces or special characters in the filename or folder). 
        You can `move <https://wiki.cyverse.org/wiki/display/DEmanual/Moving+a+Data+File+or+Folder>`_ it later if necessary.
        The file is displayed in the selected folder with an icon |batch| to the left of the name to indicate it is a high-throughput list file (you may need to refresh the window) and may now be used in an analysis, just like any other file.
    
    5. Submit the list file as the single input file in an `analysis <https://wiki.cyverse.org/wiki/display/DEmanual/Submitting+an+Analysis>`_ in any app.
    6. To view the status of each file's progress in the analysis, click |individualAnalysis| next to the analysis name in the Analyses window.


R script, Perl script, Python script, or Shell script file
----------------------------------------------------------

    1. In the Data window, select the personal folder under which you want to create the new script file. You can `move <https://wiki.cyverse.org/wiki/display/DEmanual/Moving+a+Data+File+or+Folder>`_ it later if necessary.
    2. Click **File**, point to **Create**, and then click either **New R Script**, **New Perl Script**, **New Python Script**, or **New Shell Script**.
    3. Enter the text using the commands for the script.
    4. Click **Save**.


Markdown File
-------------

    1. In the Data window, select the personal folder under which you want to create the new Markdown file. You can `move <https://wiki.cyverse.org/wiki/display/DEmanual/Moving+a+Data+File+or+Folder>`_ it later if necessary.
    2. Click **File**, point to **Create**, and then click **New Markdown file**.
    3. Enter the text and click **Save**.




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
