.. include:: cyverse_rst_defined_substitutions.txt
|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

========================================================
Sharing your App or Workflow and Editing the User Manual
========================================================

New for the 2.11 release is the ability to share unpublished Agave apps as well as DE apps you own.

There are two ways to share an app you created:

    - You can share an app or workflow with all users by making it public. Once the app is public, you can `send the URL <https://pods.cyverse.org/wiki/display/DEmanual/Viewing+App+and+Tool+Information#AppUrl>`_ to the app to a user to help them quickly find it.

    - You can share a private (unpublished) app or workflow (that is, one that is still in your Apps under development folder) with specific users and define the permissions for each user, without having to make the app public to all users. You also can unshare an unpublished app.

--------------------------------
Sharing your app with the public
--------------------------------

When you make your app public, it becomes available to other CyVerse users in the categories you select, both in the Topic and Operation tabs, or in the HPC tab (if appropriate), as well as in the My public apps category in the My Apps tab.

.. note:: All **apps in a workflow** first must be public before the workflow itself can be made public.

Can I edit a published app?
---------------------------

Just a few minor tweaks can be edited once you've published the app, all related to the GUI elements but not the main functionality: just its field labels, tool tips, descriptions of items, and the user manual. If you need to edit more than those items, you must `copy and edit the app or workflow <http://hammer.cyverse.org:8090/display/DEmanual/Creating%2C+Copying%2C+and+Editing+DE+Apps>`_, and then make it public again under a different name.

Step 1: Move your sample data files into Community Data
-------------------------------------------------------

As part of sharing your app or workflow, you must first share the sample data files so you can point to them in your submission form, which you complete in the next step.

Step 2: Publish the app and create your user manual page
--------------------------------------------------------

After your sample data files have been moved into Community Data, you complete the Public Submission Form, which then becomes the user manual for your app. Providing useful data files and entering complete information on the form helps others learn how to use your app or workflow.

    1. In the Apps window, click the **My Apps** tab.
    2. Click the **Apps under development** folder and then click the app or workflow in the right panel to make public. Note that all apps in the workflow must already be shared in Community Data before you can publish the workflow.
    3. Click the **Share** menu and then click **Make Public**. The Public Submission Form opens.
    4. Edit a unique name for the app or workflow that is easily identified by the tool and/or intent of the app.
    5. Enter a brief description (such as its uses and results) of your app.
    6. Request the categories:
        a. Click the **Operation** checkbox, click the arrow to expand the operation categories and subcategories, and select the operation categories in which you would like your app or workflow to be listed in the Operation tab.
        b. Click the **Topic** checkbox, click the arrow to expand the topic categories and subcategories, and select the topic categories in which you would like your app or workflow to be listed in the Topic tab.
           (You can `request a different category <http://hammer.cyverse.org:8090/display/DEmanual/Sharing+your+App+or+Workflow+and+Editing+the+User+Manual#SharingyourApporWorkflowandEditingtheUserManual-Categories>`_ later if you change your mind.)
    7. Click **Browse** and navigate to the Community Data folder into which you saved your sample data files in the previous section.
    8. Enter a brief description of the sample input files you used, such as the number of required files and acceptable file format.
    9. Enter a brief description of the parameters to use when running the sample data you specified in step d.
    10. Enter a brief description of the expected analysis outputs as a result of the sample data files and specified parameters.
    11. Click **Add** and enter the links to the tool (executable or binary) used for your app. For example, you want want to include a link to a paper that references your app.
    12. Click **Submit**.

The manual is saved to the DE and may be edited by the app owner, using Markdown format directly within the DE, following instructions in the next section. You can `send the URL to a public app to a user as well <https://pods.cyverse.org/wiki/display/DEmanual/Viewing+App+and+Tool+Information#AppUrl>`_.

------------------------------------------------------------------------
Sharing and unsharing an unpublished app or workflow with specific users
------------------------------------------------------------------------

You can share an unpublished DE or Agave app in your **Apps under development** folder with specified collaborators and define the level of permissions each user has to the app or workflow — much like sharing a data item. When you do so, the app name is displayed in green in the user's **Shared with me** folder, just like an app in your Apps under development folder.

    1. In the Apps window, click the **My Apps** tab.
    2. Click **Apps under development** and then click to select the app or workflow to share.
    3. Click the **Share** menu and then click **Share with Collaborators**:

    .. image:: img/Apps_ManageSharing1.jpg

    4. If you selected more than one app or workflow, click the items to share in the **Selected Apps** section.
    5. **To share the app with a user or change permission levels for the user**:
        a. Select the user from your `Collaborators list <http://adding%20and%20deleting%20users%20from%20the%20collaborators%20list%20in%20preferences/>`_.
        b. In the **Who has access** section, click the Permissions drop-down and select the permission level for the user:
        .. note:: We recommend that unless you are experienced Agave user, you set permissions for your unpublished Agave app within the DE. Because permissions are different between Agave and DE apps, this avoids possible conflicts.
        
        - **read** allows the user to use the app. This setting applies both to DE and Agave apps.
        - **write**: This setting allows the user to use, copy, and edit the app.
        - **own**: This setting allows the user to delete, share the app with other collaborators, and make the app or workflow public, in addition to the other permissions. **Use this setting with caution**.


The app is displayed with a green name in the user's Shared with me folder in the My Apps tab.


Unsharing a shared unpublished app or workflow
----------------------------------------------

    1. In your Apps under development folder on the My Apps tab, click to select the app or workflow to unshare.
    2. Click the Share menu and then click Share with Collaborators.
    3. Select the user in the Who has access section.
    4. Click |redx|.

The app is removed from the user's Shared with me folder and the user's permissions are retracted.

-----------------------------------------------------
Editing the User Manual page for your app or workflow
-----------------------------------------------------

User manuals for apps published after the 2.0 release are stored in the DE in Markdown format and may be edited within the DE.

Manuals and comments for apps or workflows that were shared prior to the 2.0 release remain in the Wiki unless you `email CyVerse Support <support@cyverse.org>`_ to request that they be moved to the DE.

.. caution::

     If you shared the app (made it public) **before the 2.0 release**, your user manual is on the CyVerse Wiki and accessible from the List of Applications page. 
     If you shared the app **after the 2.0 release**, your manual was created when you shared your app, and is available in the DE in the user manual link of the App Info section for the app. When CyVerse Support tests your app to ensure it is ready for public use, they create a copy of your manual for use in the List of Applications on the wiki, so all manuals are accessible in the same place.





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

.. |redx| image:: img/CheckmarkIcon.jpg


.. Comment: Place URLS Below This Line

   # Use this example to ensure that links open in new tabs, avoiding
   # forcing users to leave the document, and making it easy to update links
   # In a single place in this document

   .. |Substitution| raw:: html # Place this anywhere in the text you want a hyperlink

      <a href="REPLACE_THIS_WITH_URL" target="blank">Replace_with_text</a>


.. |Github Repo Link|  raw:: html

   <a href="FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX" target="blank">Github Repo Link</a>
