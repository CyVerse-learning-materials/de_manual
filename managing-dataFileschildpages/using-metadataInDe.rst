.. include:: cyverse_rst_defined_substitutions.txt
|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


========================
Using Metadata in the DE 
========================


Metadata is data about a data or analysis file or folder that describes its contents and the context of its data. 
This can be very useful when you need to remember specific information about that file or folder in the future  — such as a tool name, version, or settings you used when submitting an analysis — or when you want to share a file and want the collaborators to understand the context of its data.

A single piece of metadata, or an **AVU**, is made up of attributes, values, and units. An *attribute**is a changeable property or characteristic of the file or folder you have selected that can be set to a *value*. For example, *length* is an **attribute** of a file, while 7 is its **value**, and *cms* is the unit.  
The metadata you enter stays with the file when you share the file or folder with others.

Just like editing any file or folder, you must either have write or own `permission <https://wiki.cyverse.org/wiki/display/DEmanual/Changing+and+Viewing+Data+Permission+Levels+in+the+DE>`_ to it in order to add, edit, or delete its metadata. You can view, copy, or save the metadata for any file or folder that has been shared with you, regardless of permission level. 
Another form of metadata that is just for your use is the ability to add `tags <https://wiki.cyverse.org/wiki/display/DEmanual/Changing+and+Viewing+Data+Permission+Levels+in+the+DE>`_ to a file or folder in the DE.

Other available options are the ability to attach multiple AVUs or metadata templates to the same file or folder, which lists the metadata on the download page that opens from a `data <https://wiki.cyverse.org/wiki/display/DEmanual/Sharing+Data+Files+Via+Public+Links>`_ link that was sent by the owner to a recipient, download a metadata template as a CSV file, and duplicate a field in a metadata template.

In addition to defining metadata within the DE, you can `read and write metadata with iCommands <https://wiki.cyverse.org/wiki/display/DS/Adding+Metadata+to+a+File+Using+iRODS+imeta+%28Metadata%29+Commands>`_. 



Adding and editing metadata in the DE
-------------------------------------

.. |helpIcon| image:: img/ContextualHelpIcon.png

To add or edit metadata to a file or folder, you must have `write or own permissions <https://pods.iplantcollaborative.org/wiki/display/DEmanual/Changing+and+Viewing+Data+Permission+Levels>`_ to the item. If saving metadata to multiple files or folders, there is a limit of 1000 items (all files within all subfolders under the parent folder) per save. If you need to save metadata to more than 1000 items, you can either save the metadata to 1000 files at a time until all files have been saved, and then delete the older folder, or use `iCommands <https://wiki.cyverse.org/wiki/display/DS/Adding+Metadata+to+a+File+Using+iRODS+imeta+%28Metadata%29+Commands>`_ to do it.


    1. In the Data window, search for the file or folder you own and to which you want to add or edit metadata. To search for a metadata attribute or value, see `Searching for Data Items <https://pods.iplantcollaborative.org/wiki/display/DEmanual/Searching+for+Data+Items>`_.

    2. Click on the three dots to the right of the file or folder name (or click the checkbox next to the item, click the **Metadata** menu, and then click **Edit/View Metadata**):

    .. image:: img/UserMetadata1.jpg

    3. **To add metadata to the data item:**

        a. Click **Add:**

            +------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
            | **Add button not enabled?**                                                                                                                                                                                                                          |
            +------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
            | If the Add button is disabled, you don't have write or own permission. Instead, you can `download it to your computer and then upload <https://wiki.cyverse.org/wiki/display/DS/Downloading+and+Uploading+Data>`_ it to your personal folder.        |
            +------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

        b. Double-click in the **New Attribute** field and enter the attribute for the data item (e.g., *length*). (Click |helpIcon| at the top right of the window to view information about attributes and values.)

        c. Tab to the **New Value** field and enter the value (e.g., 7).

        d. Tab to the **Unit** field and enter the unit (e.g., *cms*).

        .. image:: img/Metadata2.jpg

        e. Click **Save** to save the AVU.

        f. Repeat for each AVU to add.

        g. If done, click **Save**.

    4. **To edit a line of metadata:**
    
        a. Click the three dots at the right side of the item with the metadata to edit.

        b. In the Edit/View Metadata window, click the checkbox for the AVU to edit and then click **Edit**.

        c. Double-click in the field(s) to edit and make the changes.

        d. Click **Save**.

    5. **To delete a line of metadata or remove a template from a file or folder:**

        a. Click the checkbox for the AVU to delete. (Press **Shift** to select multiple rows.)

        b. Click **Delete**.

        c. If done, click **Save**.


    6. To use a metadata template, see the **Using Metadata Templates** section below.


Copying metadata to a different file or folder you own
------------------------------------------------------

.. |metadataicon| image:: img/MetadataIconAlone.gif

You can attach the metadata from any file or folder to one or more files or folders you own or to which you have been given write permissions. The same 1000-limit applies to copying metadata (see the section above).

+----------------------------------------------------------------------------------------------------------+
| **!** Any metadata in the destination file or folder will be overwritten with the newly copied metadata. |
+----------------------------------------------------------------------------------------------------------+


    1. In the Data window, click the checkbox to the left of the file or folder name with the metadata to copy.

    2. Click the **Metadata** menu and then click **Copy Metadata From**:


    .. image:: img/CopyMetadata1.jpg


    3. Either:

        - Drag and drop a file or folder from the Data window to the Copy Metadata from dialog.

        *or* 

        - Click **Add**, click the checkboxes for the destination files or folders to which you want to apply the metadata, and click **OK**.


    4. In the Copy Metadata from dialog, click **OK**.

    5. If you receive a warning message:

        - If you receive an error message that the destination file or folder contains spaces and/or special characters, select the item in the list and then click **Delete**, `rename <https://wiki.cyverse.org/wiki/display/DEmanual/Renaming+a+Data+File+or+Folder>`_ the item, and try again. See `CyVerse Curated Data Folder-Naming Guidelines <https://wiki.cyverse.org/wiki/display/DC/CyVerse+Curated+Data+Folder-Naming+Guidelines>`_ for more information.

        - If you receive a warning prompt that the metadata in the destination files or folders will be overwritten, click **Yes** to overwrite, or **No** to cancel.


    6. Click |metadataicon| and verify your metadata was copied to the file or folder.




Saving metadata from any file or folder to a separate file
----------------------------------------------------------

You can save (export) metadata from any file or folder to a new file in your personal data list.

    1. In the Data window, click the file or folder with the metadata to save.
    2. Click the **Metadata** menu and then click **Save Metadata**.
    3. In your personal data list, click the folder where you want to save the metadata file.
    4. In the **File Name** field, enter the filename for the metadata file.
    5. Click **OK**.
    6. Click |metadataicon| and verify the metadata was saved.



Importing iRODS (additional) metadata to the CyVerse metadata database in the DE
--------------------------------------------------------------------------------

Metadata that was added prior to the 2.7 release via iCommands is stored only in the iRODS metadata database after the 2.7 release. 
Although you can still read and write to it in the iRODS metadata database, you can only read it within the DE. 
To be able to write to the metadata within the DE, you must import the metadata from the old iRODS metadata in the Additional Metadata panel for the data item to the new CyVerse metadata database, which will then be displayed in the User Metadata panel.

+----------------------------------------------------------------------------------------------------------------------------------------------+
| **! This operation cannot be reversed and you will no longer be able to view or write to it using iCommands after it has been imported.**    |
+----------------------------------------------------------------------------------------------------------------------------------------------+

    1. In the Data window, click |metadataicon| to the right of the file or folder name to which the metadata was saved.
    2. Click the **Additional Metadata** panel at the bottom of the window. Metadata that was added to the file or folder and stored in the old iRODS metadata database is displayed (if none is available, the panel will not be displayed):

    .. image:: img/AdditionalMetadata.jpg

    3. Click the checkbox next to each AV to import.

    4. Click **Import to User Metadata** at the top.

    5. Click **OK** to the warning prompt that this is a one-time operation.

    6. Click **Save**. The selected metadata now appears in the **User Metadata** dialog.



Using metadata templates
------------------------

Metadata templates allow you to apply a set of predefined AVUs to a file or folder. With the 2.7 release of the DE, it is now possible to add an unlimited number of the same attribute to files and folders to which you have own or write permissions, greatly simplifying entry of metadata (e.g., if your file has multiple creators, you can add the "Creator" AVU as many times as needed). 
It also is now possible to attach more than one template to the same file or folder, to add templated or non-templated metadata to multiple files in the same or different folders at one time, and download a metadata template as a CSV file.


Applying a metadata template 
----------------------------

    .. |info| image:: img/InfoIcon.gif

    .. |plus| image:: img/MetadataTemplate-DupFieldIcon.png

    .. |minus| image:: img/MetadataTemplate-RemoveDupFieldIcon.png

    .. |download| image:: img/MetadataTemplate-DownloadIcon.png

    1. In the Data window, click the checkbox for the file or folder to which you want to add a template. (You must have `own or write permissions <https://wiki.cyverse.org/wiki/display/DEmanual/Changing+and+Viewing+Data+Permission+Levels+in+the+DE>`_ for the item.)
    2. Click on the three dots at the right of the row for the item, or click the **Metadata** menu and then click **Edit / View Metadata**.
    3. In the User Metadata window, click **Select Template**:

    .. image:: img/MetadataTemplates.png

    Note: To download the template in this window, click |download|.

    4. Select the template to use and click **OK**.

    +-------------------------------------------------------------------------------+
    | Click |info| next to the template name to view a description of the template. |
    +-------------------------------------------------------------------------------+


    The template window opens, as shown in the following example of the RNA template:

    .. image:: img/EditViewMetadataTemplate-RNA.png

    5. In the template, complete the required fields (noted with a red asterisk).

    +-----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
    | Click |info| to the left of the attribute name to learn about that field, or click **Metadata Term Guide** at the top to learn about all attributes in the template.  |
    +-----------------------------------------------------------------------------------------------------------------------------------------------------------------------+


    6. To duplicate a field, click |plus|. (Click |minus| to remove the duplicate field.)

    7. When done, click **OK**. The template's metadata attributes are added to the User Metadata dialog.

    8. Repeat for each additional template to apply to the data item.

    9. When done, click **OK**.


Downloading a metadata template
-------------------------------

    1. In the Data window, click the **Metadata** menu and then click **Download template**.

    2. Select the template and click **OK**.

    3. Click **Save file**, navigate to the desired download folder, and click **Save**.

    4. Open the zip file to view either the blank CSV file or the guide file, which describes the attributes in the file.


Adding bulk metadata to multiple files or folders
-------------------------------------------------

If you have multiple files or folders that require the same metadata attribute(s), but with different values, or multiple files that need metadata from the same metadata template, you can upload the metadata file in CSV format and apply it to all of the files or folders at the same time. 
This method can also be used to apply metadata to a single file or folder, if you already have the metadata in a comma-delimited spreadsheet. 
You can do multiple bulk metadata applications to files in the same directory or different directories. 
See a `video tutorial <https://pods.iplantcollaborative.org/wiki/display/TUT/DE%3A+Bulk+metadata+upload+video+tutorials>`_ on how to add metadata in bulk.


--------------------
If using a template:
--------------------

    1. If using a template, first download the template from the metadata window by clicking |download| next to the template, as specified above in `Downloading a Metadata Template <https://wiki.cyverse.org/wiki/display/DEmanual/Downloading+Files+and+Folders>`_.
        a. Templates can also be downloaded from **Community Data > iplantcollaborative > metadata_templates**
        b. Download the file:
            - Click the checkbox for the template to use.
            - Click the **Download** menu and then click **Simple Download**. For more information, see `Downloading Files and Folders <https://wiki.cyverse.org/wiki/display/DEmanual/Downloading+Files+and+Folders>`_.
              If more than one file format of the same template is available, select the CSV version.

    2. Open the metadata template in a text or spreadsheet editor. It will contain a single row with the attributes.

    3. Edit the template for your situation:
        - **If all of the data files are in the same folder:**
            a. Add a row for the first data file.
            b. In the first column of the first row, enter the file location in the Data Store.
            c. In the remaining columns of the first row, enter the values for each file/attribute combination.
            d. Repeat for each file.

            +---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
            | To **apply a template to a single file in bulk**, follow the steps above, but create your bulk metadata file with only two rows (one for the file and one for its attributes).  |
            +---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

            e. If desired, add additional columns to the end of the template. The metadata in the additional columns will be saved in the Data Store but will not be stored as part of the template.
            f. Save the file in **CSV** format. Make sure none of the names of the files or the parent folder include spaces or special characters.

        - **If the data files are in different folders:**
            a. Add a row for the first data file.
            b. In the first column of the first row, enter the **full path** to the file location in the Data Store.
            c. In the remaining columns in the first row, enter the values for each file/attribute combination.
            d. Repeat for each file.
            e. If desired, add additional columns to the end of the template. The metadata in the columns will be saved in the Data Store but will not be stored as part of the template.
            f. Save the file in **CSV** format. Make sure the file names or name of the parent folder do not include any spaces or special characters.

    4. Continue with **Upload and Apply Metadata**, below.

-----------------------
If not using a template
-----------------------

    1. Create a Comma Separated Value (CSV) metadata file for your situation:
        - In a text or spread sheet editor, create the first row of the CSV file. The first column of the first row can be blank or can be labeled "row" or similar. The rest of the columns of the first row should be the names of the attributes you wish to use. For best results, use unix friendly names for your attributes (no space or special characters).
    
    2. Add rows for each file or folder:
        - **If all of the data files are in the same folder**:
            a. Add a row for the first data file or folder.
            b. In the first column of the first row, enter the file or folder name in the Data Store (no need for full path).
            c. In the remaining columns of the first row, enter the values for each file/attribute combination.
            d. Repeat for each file or folder.

            +---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
            | To **apply a template to a single file in bulk**, follow the steps above, but create your bulk metadata file with only two rows (one for the file and one for its attributes).  |
            +---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

            e. Save the file in CSV format. Make sure none of the names of the files or the parent folder include spaces or special characters.

        - **If the data files are in different folders**:
            a. Add a row for the first data file.
            b. In the first column of the first row, enter the full path to the file location in the Data Store.
            c. In the remaining columns in the first row, enter the values for each file/attribute combination.
            d. Repeat for each file.
            e. Save the file in CSV format. Make sure the file names or name of the parent folder do not include any spaces or special characters.
    
    3. Continue with **Upload and Apply Metadata**, below.


-------------------------
Upload and apply metadata
-------------------------

    1. `Upload <https://wiki.cyverse.org/wiki/display/DEmanual/Uploading+and+Importing+Data+Items+Within+the+DE>`_ the metadata file to the Data Store:
        - If the first column of your metadata file contains only file names (that is, all data files are in the same folder), move the bulk metadata file to the same folder as the location of the data files.
        - If the first column of your metadata file contains the full path to each file (that is, the data files are in different folders), it does not matter where the metadata file is located on the Data Store.

    +------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
    | If you create the file directly in the DE using the built in text editor, you do not have to upload. Just be sure to save the CSV file in the correct location as specified above. |
    +------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

    2. Apply the metadata to the files:
        a. In the Data window, check the box next to the name of the folder containing the data files to which you want to apply the metadata in bulk.
        b. Click the **Metadata** menu, point to **Apply Bulk Metadata**, and then click **Select Metadata File**.
        c. Browse to the location of the bulk metadata file and select it.
        d. `Select the corresponding template <https://wiki.cyverse.org/wiki/display/DEmanual/Using+Metadata+in+the+DE#UsingMetadataintheDE-SelectTemplate>`_ from the dropdown menu.
        e. Click **Okay**.
        f. If the action was successful, you should get a notification. If there is no notification, there was an error in the process and you will need to repeat the process after confirming that your metadata file is formatted correctly.



Searching for metadata in files and folders
-------------------------------------------

For more information on searching for a metadata attribute or value, see `Searching for Data Items <https://wiki.cyverse.org/wiki/display/DEmanual/Searching+for+Data+Items>`_.


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
