.. include:: cyverse_rst_defined_substitutions.txt
|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


=======================
Designing the Interface
=======================

About the Create App window
---------------------------

The Create App window consists of four distinct sections:


.. image:: img/CV_CreateApp1.jpg

    - The section on the left side contains the different app items that can be added to your interface. To add an app item, select the one to use (hover over the object name for a brief description) and drag it into position in the middle section.
    - Once dropped into a group, the properties that are available for that type are displayed in the Properties section on the right. As you add and design the argument, the Command line view section at the bottom of the window displays the commands for the object, and the middle section updates interactively to display the argument. You can also preview it to see how the whole app looks and functions.
    - The middle section is the landing place for the objects you dragged and dropped from the left section, and it updates to display how the object looks as you define it in the Details section on the right.
    - The **Details** section on the right displays all of the available properties for the selected item. As you customize the app in the Details section, the middle section updates dynamically so you can see how it will look and act.
    - The **Command line view** at the bottom contains the command-line commands for the current item's properties. As you update the properties in the Details section, the Command line view updates as well.
    - At the top of the window are icons to save the app, preview the UI or JSON script, and set the argument order.



About designing the interface
-----------------------------

Creating a new app interface is a basic process. You'll need to know how to use the tool — the executable or binary upon which the app is based. With that knowledge, you create the interface according to how you want it to be used in the DE.

An app interface in the DE is arranged in a hierarchy of two main pieces:
    
    - The framework consists of one or more **groups**. A group creates a conceptual boundary in the interface into which you add the relevant user input settings in the order and with the field names you want, as displayed when the app is viewed in the DE. For example, many DE apps have a first panel called *File Inputs*.
    - Inside each group, you add those user interface objects you need to facilitate the collection of user inputs. There are a number of different user interface objects from which to select, including input file fields, selection and checkbox fields, text and numerical input fields, and output file fields.

In the following example, we see three groups, with the **Select input data** group, as defined by the integrator, expanded:

.. image:: img/CreateApp_GroupsAnno.png


Next Steps
----------

See this section to help you design the interface:

-------------------------------------
Selecting the Tool and Naming the App
-------------------------------------

.. |BrowseButton| image:: img/BrowseButton.png

.. |CloseWindow| image:: img/CloseWindowPreviewNewApp.png

Whether creating a new app or editing an existing one, the first step in the process is selecting the tool used for the app, and entering or editing the app name and description.

    1. `Open the Create Apps window. <https://wiki.cyverse.org/wiki/display/DEmanual/Creating%2C+Copying%2C+and+Editing+DE+Apps>`_

    2. If necessary, click the **New app** (or current app name) panel header to open the section.

    .. image:: img/CreateApps-1a.png


    3. In the **Tool used** field, click |BrowseButton|, and then enter at least 3 characters of the app name.

    .. tip:: To indicate a version of your app or that this is an HPC app, you can add opening and closing parentheses in the app name.

    4. To view the attribution and description of the tool, click the app name, then click |CloseWindow| to close.

    .. tip:: Tool or version not listed? 
            Click **New Tool Request** and `request that a new tool or version be installed <https://wiki.cyverse.org/wiki/display/DEmanual/Adding+or+Requesting+a+New+Tool>`_.


    5. Select the tool and click **OK**.

    6. In the App name field, enter a unique name for the app.

    7. In the **App description** field, enter a brief description. The description will be displayed when viewing the `app information <https://wiki.cyverse.org/wiki/display/DEmanual/Viewing+App+and+Tool+Information>`_ section in the Apps list.

    8. Click **Save**.

-------------------------------
Adding and Editing App Sections
-------------------------------

Apps are built section by section. By default, the Section 1 section is created when you first create a new app. You can edit the section name, as well as add additional sections and delete sections.

    ----------------------
    Editing a section name
    ----------------------

    1. To create a new app, or copy or edit an existing one:

        - To **create a new app or workflow from scratch**, either:
    
            - Open the Apps window, click **Apps** on the toolbar for an app or **Workflow** for a workflow, and then click **Create New**.
    
                or
    
            - Click the tool name from the `Manage Tools <https://wiki.cyverse.org/wiki/display/DEmanual/Managing+Tools+in+the+DE>`_ window.
    
        - To **create your own version or edit one you already published**, select the app or workflow in the **Public Apps** folder, click either **Apps** or **Workflow**, and then click **Copy**.
    
        - To **edit an unpublished app or workflow** you are working on, select the app or workflow in your **Apps under development** folder, click either **Apps** or **Workflow**, and then click **Edit**.
    
    2. In the middle section, click the header bar for the section name to edit:


    .. image:: img/CreateAppSection.png


    3. In the Details section on the right, click in the **Section name** field and edit the section name label.

    4. Click **Save**.


    --------------------
    Adding a new section
    --------------------

    1. In the Create Apps window for the app, click and drag the Section object in the App Items section on the left to the target position in the selected group:

    .. image:: img/Createapp_AddInputGroup.png

    2. In the Details section, edit the section name label.
    3. Click **save**

    ------------------
    Deleting a section
    ------------------

    1. In the Create Apps window for the app, click the header bar of the section to delete.
    2. In the Details section, click **Delete section**:

    .. image:: img/DeleteSection.png


-------------------------------------------------------------
Adding and Deleting File and Folder Input Fields for Your App
-------------------------------------------------------------

You can add fields for multiple input files, single files, or folder input fields when creating or editing an app interface.

    -------------------
    Adding input fields
    -------------------

    --------------------------
    Step 1: Select the section
    --------------------------

    1. To create a new app, or copy or edit an existing one:

        - To **create a new app or workflow from scratch**, either:
    
            - Open the Apps window, click **Apps** on the toolbar for an app or **Workflow** for a workflow, and then click **Create New**.

             or

            - Click the tool name from the `Manage Tools <https://wiki.cyverse.org/wiki/display/DEmanual/Managing+Tools+in+the+DE>`_ window.

        - To **create your own version or edit one you already published**, select the app or workflow in the **Public Apps** folder, click either **Apps** or **Workflow**, and then click **Copy**.
        
        - To **edit an unpublished app or workflow** you are working on, select the app or workflow in your **Apps under development** folder, click either **Apps** or **Workflow**, and then click **Edit**.
    
    2. In the app, click the section header to expand the section into which you want to add the input field.


    ------------------------------------------
    Step 2: Select the input field type to add
    ------------------------------------------

    - **Multiple Input Files field**: Allows the user to select multiple files, with the ability to specify the type of file that may be added to the list, as shown:

    .. image:: img/CreateApp_MultiInputFiles.png

    - **Input File field**: Allows the user to select one input file, as shown:

    .. image:: img/CreateApp_InputFile-2.png

    - **Input Folder field**: Allows the user to select one input folder, as shown:

    .. image:: img/CreateApp_FolderSelector.png


    ---------------------------------------------------
    Step 3: Edit the Details section in the right panel
    ---------------------------------------------------

.. role:: rubric


The properties displayed in the Details panel vary according to which input type you selected.

    Click the field in the middle section to edit its properties in the Details section on the right.

    - **Selector label**: Edit the label as you want it to be displayed in the app.
    - **Argument option**: Enter the command line option according to the tool's requirements.
    - **Make this field required**: Select to require the user to select at least one input folder.
    - **Exclude this item if nothing is entered**: Click this option if you want to skip this file type when nothing is entered in the app.
    - **Tool tip text**: Enter text to inform the user about how to use the field when viewed in the app.
    - **Type of information contained in these files**: Select the type of file that can be included in the folder, or leave Unspecified to allow more than one file type.
    - **Do not pass this argument to command line**: Allows the user to select input files without including those files in the command line.
    - **Repeat "Argument option" on the command line before each filename** *:rubric:`(Multiple Input Files only)`*: Includes the select input files in the command line before each filename selected by the user.


    ------------------------
    Step 4: Preview and save
    ------------------------

    1. Click **Preview** and then click **Preview UI**.

    2. When done, close the Preview window.

    3. Click **Save**.

    ------------------------------
    Deleting file or folder fields
    ------------------------------
    .. |deleteicon| img/Createapp_DeleteArgumentIcon.png


    1. In the middle section, click in the field to delete. A blue border around it is displayed around the field:

    .. image:: img/CreateApp_DeleteCheckbox1.png

    2. Hover over the the gray |deleteicon| icon at the top right until it turns red:

    .. image:: img/CreateApp_DeleteCheckbox2.png

    3. Click the icon to complete the deletion.
    4. Click **Save**.




------------------------------
Adding List Fields to Your App
------------------------------

    -------------------
    Adding a list field
    -------------------

    You can add several different types of list fields to your app.

    





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
