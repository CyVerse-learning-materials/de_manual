.. include:: cyverse_rst_defined_substitutions.txt
|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

============================
Creating a New App Interface
============================


Creating a New App Interface
----------------------------

Each app in the DE is built on one tool (executable or binary), but each tool can have more than one app interface. 
You can create your own app interface, or workflow based on a sequence of different apps, for the tool you want, right within the DE, using the WYSIWYG (What You See Is What You Get) interface. 
This interface allows you to drag and drop items into the interface.

If you're new to this process, you may want to watch the YouTube video, `Creating and Modifying Apps: Customizing your tools <http://www.youtube.com/watch?v=yTcqH-6wB-Q&feature=em-uploademail>`_.

----------------------------------------------------------------------
Step 1: Complete the steps for Dockerizing your tool for use in the DE
----------------------------------------------------------------------

All tools are now Dockerized so they run faster and more efficiently in the DE. For instructions on how to do so, see `Dockerizing Your Tools for the CyVerse Discovery Environment <https://wiki.cyverse.org/wiki/display/DEmanual/Dockerizing+Your+Tools+for+the+CyVerse+Discovery+Environment>`_. 
For steps on creating a new tool or requesting installation of a new tool, see NEED

-----------------------------------------------------------------------------
Step 2: Decide how you want to create the app and open the Create Apps window
-----------------------------------------------------------------------------

Before you begin, you might want to `search the list of available tools <https://wiki.cyverse.org/wiki/display/DEmanual/Finding+the+List+of+Available+Tools>`_ to see if the tool (executable or binary) you want to use for your app interface is available in the DE. 
If the tool or tool version you want to use is not listed, you must first `request that the tool be installed <https://wiki.cyverse.org/wiki/display/DEmanual/Adding+or+Requesting+a+New+Tool>`_.

The first step in creating a new app interface for an available tool is deciding which method you want to use to create the interface. 
There are three ways in which you can create an interface for a tool that is available for use in the DE:

    - **Copy and edit an existing app:** This method is useful if you want to create a similar app based on the same tool or if you want to see how someone else created theirs.
    - **Edit an app in your Apps under development folder:** Use this method to change settings for an app you created that is still in your Apps under development folder (because it has not yet been shared, you can still edit it). This is a useful way to create different variants of your app for different uses, as well as fine-tune or change settings and layout.
    - **Create a new app from scratch:** This method allows you to create an app from the beginning with no preconceived notion.
    - You also can "jump-start" your new app by clicking to select the tool name in the `Manage Tools <https://wiki.cyverse.org/wiki/display/DEmanual/Managing+Tools+in+the+DE>`_ window.


To learn how to use each of these methods, see `Creating, Copying, and Editing DE Apps <https://wiki.cyverse.org/wiki/display/DEmanual/Creating%2C+Copying%2C+and+Editing+DE+Apps>`_.

-----------------------
Step 3: Select the tool
-----------------------

Select the tool and version to use and then enter the app's name and description. For more information, see `Selecting the Tool and Naming the App <https://wiki.cyverse.org/wiki/display/DEmanual/Selecting+the+Tool+and+Naming+the+App>`_.


-----------------------------------------
Step 4: Design the interface for your app
-----------------------------------------

This is the meat and potatoes of creating the app interface. There are a number of different field types you can add to the interface. You can customize field names, specify the number and type of input files, add descriptive text, and much more. 
As you move through the process, it is a good idea to preview the app and test it out to make sure it's doing what you want to do and looking how you want it to look. 
Remember to save frequently. 
Once saved, your app is available in your **Apps under development** workspace folder, where you can edit it at any time. 
For more information, see `Designing the Interface <https://wiki.cyverse.org/wiki/display/DEmanual/Designing+the+Interface>`_.

--------------------
Step 5: Test the app
--------------------

Once you've finished designing and saved the app, it is immediately available in your **Apps under development** folder. 
From there, you can test it — see how it works, which fields are required, how it functions — and then edit it some more if you like and try it out on some analyses. 
In short, this is the time to put yourself in a new user's shoes and make sure your app is useful to users and a good example of your work.

Remember: Once you've shared the app, you won't be able to edit the app again; you can `edit the user manual <https://wiki.cyverse.org/wiki/display/DEmanual/Sharing+your+App+or+Workflow+and+Editing+the+User+Manual>`_ at any time. Now's the time to make sure it really works and works well.


----------------------
Step 6: Share your app
----------------------

After you're sure the app is the way you want it, you can `publish <https://pods.iplantcollaborative.org/wiki/display/DEmanual/Sharing+your+App+or+Workflow+and+Editing+the+User+Manual#Publish>`_ it and create the user manual page to help CyVerse users learn how to use it, or keep it unpublished and `share it with selected users <https://pods.iplantcollaborative.org/wiki/display/DEmanual/Sharing+your+App+or+Workflow+and+Editing+the+User+Manual#ShareApp>`_.

----------------
Need assistance?
----------------

If you have problems or need assistance, you can `submit feedback <https://wiki.cyverse.org/wiki/display/DEmanual/Providing+Feedback+and+Getting+Help+with+the+Discovery+Environment>`_ right within the DE.




Creating a New App Interface Quick Start
----------------------------------------

----------------------------------------
Creating a New App Interface Quick Start
----------------------------------------

You can easily create a new interface for a DE app directly within the Discovery Environment. There are three ways in which you can `create or edit an app <https://wiki.cyverse.org/wiki/display/DEmanual/Creating%2C+Copying%2C+and+Editing+DE+Apps>`_ for use in the Discovery Environment:

    - **Copy and edit an existing app**: This method is useful if you want to create a similar app based on the same tool, if you want to see how someone else created their app, or if you just want to play with how to create or edit a tool interface.
    - **Create a new app interface from scratch**: This method allows you to create an app interface from the beginning with no preconceived notion. This is the most frequently used method.
    - **Edit an app interface you created**: Use this method to change settings in an app you created. This is a useful way to create different variants of your app for different uses, as well as to fine-tune or change settings and layout.

You can define the app's arguments, settings, and layout. Once the app is to your satisfaction, it is immediately available in your DE personal workspace, where you can use it to run analyses, or share it with the user community.

The main steps to creating a new app are:

    1. Click **Apps** to open the Apps window.
    2. `Select the method <https://wiki.cyverse.org/wiki/display/DEmanual/Creating%2C+Copying%2C+and+Editing+DE+Apps>`_ to use for creating the app – whether creating a new app from scratch, copying an existing app, or editing a public app.
    3. `Search for the tool <https://wiki.cyverse.org/wiki/display/DEmanual/Finding+the+List+of+Available+Tools>`_ (executable or binary) to use for your app interface.

    .. tip:: **Tool not there?**
        If the tool and version you want to use for your app interface is not in the list, you will need to `request that it be installed <https://wiki.cyverse.org/wiki/display/DEmanual/Adding+or+Requesting+a+New+Tool>`_.

    4. Enter basic information about your app.
    5. Specify the parameters (arguments) that define the functionality and appearance for your app.
    6. `Preview the app <https://wiki.cyverse.org/wiki/display/DEmanual/Previewing+the+App+and+JSON>`_ and test your app to verify that it looks and functions the way you want it to.
    7. `Save <https://wiki.cyverse.org/wiki/display/DEmanual/Saving+the+App>`_.
    8. Open the app in your Workspace **Apps under development** folder and test.
    9. If necessary, edit the app and preview again, repeating until the app is to your satisfaction, and then save.
    10. When you want to share it with other users, edit the documentation page for your app and then `submit it for public use <https://wiki.cyverse.org/wiki/display/DEmanual/Sharing+your+App+or+Workflow+and+Editing+the+User+Manual>`_ so other users can use your app for their analyses.

For more information on creating and editing DE apps, please see the related Table of Contents in the left pane.



Creating, Copying, and Editing DE Apps
--------------------------------------

Before you begin, you might want to `search the list of available tools <https://wiki.cyverse.org/wiki/display/DEmanual/Finding+the+List+of+Available+Tools>`_ to see if the tool and version you want to use for your app interface is available in the DE. 
If it is not listed, you must first `Dockerize the tool <https://wiki.cyverse.org/wiki/display/DEmanual/Dockerizing+Your+Tools+for+the+CyVerse+Discovery+Environment>`_ and then `request that the tool be installed <https://wiki.cyverse.org/wiki/display/DEmanual/Adding+or+Requesting+a+New+Tool>`_.

You can either create a new app from scratch, copy a public app, or edit an app in your Apps under Development folder (an app that you haven't shared with the public yet). 
Most people jump right in by creating a new app.

If you don't want to start from scratch, a useful tip is to copy an app in the Public Apps folder, then make any changes you want to that app–perhaps using a different version of the tool, or changing the name of a field–and then save to a new app name to make a totally new app.

You also can `create a new workflow <https://wiki.cyverse.org/wiki/pages/viewpage.action?pageId=8391828>`_.


----------
Main Steps
----------

.. |ForumsIcons| image:: img/de/ForumsIcons.png

    1. To create a new app, or copy or edit an existing one:
        - To **create a new app or workflow from scratch**, either:
             - Open the Apps window, click **Apps** on the toolbar for an app or **Workflow** for a workflow, and then click **Create New**.
                
             or

             - Click the tool name from the `Manage Tools <https://wiki.cyverse.org/wiki/display/DEmanual/Managing+Tools+in+the+DE>`_ window.
        - To **create your own version or edit one you already published**, select the app or workflow in the **Public Apps** folder, click either **Apps** or **Workflow**, and then click **Copy**.
        - To **edit an unpublished apP or workflow** you are working on, select the app or workflow in your **Apps under development** folder, click either **Apps** or **Workflow**, and then click **Edit**.
    2. `Create or edit the app interface <https://wiki.cyverse.org/wiki/display/DEmanual/Creating+a+New+App+Interface>`_ according to how you want to work.
    3. Save the changes. The app now is listed in your Apps under development folder. From there, you can test it and try it out. If you want to share it with the public, you can `submit it for public use <https://wiki.cyverse.org/wiki/display/DEmanual/Sharing+your+App+or+Workflow+and+Editing+the+User+Manual>`_. If you have additional questions or want to see questions other users have asked, click |ForumsIcons| at the top right of the screen to open `Ask CyVerse <http://ask.iplantcollaborative.org/questions/>`_.

You may want to begin by reading `Creating a New App Interface <https://wiki.cyverse.org/wiki/display/DEmanual/Creating+a+New+App+Interface>`_.


.. toctree::
    new-appInterfacechildpages/designingInterface.rst
    new-appInterfacechildpages/PreviewAppJson.rst






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
