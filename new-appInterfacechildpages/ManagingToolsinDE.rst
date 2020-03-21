.. include:: cyverse_rst_defined_substitutions.txt
|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

========================
Managing Tools in the DE
========================

Discovery Environment **tools** are `Docker images <http://hammer.cyverse.org:8090/display/DEmanual/Dockerizing+Your+Tools+for+the+CyVerse+Discovery+Environment>`_ from which apps are created. There are numerous tools already available in the DE for new apps you are creating. It's easiest to just use one of those tools. However, sometimes the tool or version isn't available, so you can request installation of a new tool or create a new one yourself. If you create a new tool, it is available by default in your personal Tools list and available only for your use. You can share the tool with specific collaborators, or make it public (all tools created prior to the 2.13 release in June 2017 are public).

You can edit and delete a tool you own, as well as jump-start the creation of a new app from the Tools window.



Managing Tools
--------------

-----------------------------------
Adding a tool and Requesting a tool
-----------------------------------

See `Adding or Requesting a New Tool <http://hammer.cyverse.org:8090/display/DEmanual/Adding+or+Requesting+a+New+Tool>`_

--------------
Editing a tool
--------------

For tools you created, you can edit the tool name, description, version, and Docker Hub URL. The image name and tag are not editable after the tool has been created.

    1. In the Apps window, click **Manage Tools** at the top.
    2. Click to select the tool you own that you want to edit.
    3. Click the **Tools** menu and then click **Edit**.
    4. Change the image name, description of the tool, version, and/or Docker Hub URL as needed.
    5. When done, click **OK**.

---------------
Deleting a tool
---------------

You can delete a tool you created.

    1. In the Apps window, click **Manage Tools** at the top.
    2. Click to select the tool you own that you want to delete.
    3. Click the **Tools** menu and then click **Delete**.
    4. Click **Yes** to verify you want to delete the tool.


-----------------------------
Using a tool to create an app
-----------------------------


Once you've found the tool to use in an app you want to create, you can "jump-start" the creation of a new app right from the Tools menu.

    1. In the Apps window, click **Manage Tools** at the top.
    2. Click to select the tool to use for the new app.
    3. Click the **Tools** menu and then click **Use in app**. The Create App window opens with the tool selected.
    4. Continue to :doc:`../new-appInterface.rst` for instructions on how to create the new app.


-------------
Sharing tools
-------------

Once you have created a tool, by default, it is private and available only for your personal use. You can share it with selected collaborators or make the tool public (the default for all tools created prior to the 2.13 release). You also can edit and delete a tool you created that is in Own status. Giving Own access allows the collaborator to share, edit, and delete the tool, so grant this permission with care.

Before a new app can be created, the tool that app is based on must be made available in the DE.

----------------------------------
Sharing a tool with a collaborator
----------------------------------

    1. In the Apps window, click **Manage Tools** at the top.
    2. Click to select the tool you own that you want to share.
    3. Click the **Share** menu and then click **Share with collaborators**.
    4. Select a user in your `Collaborators <https://pods.iplantcollaborative.org/wiki/display/DEmanual/Adding+and+Deleting+Users+from+the+Collaborators+List+in+Preferences>`_ list: Click **Choose Collaborators**, select the user, click **OK**, and then click **Done**.
       To add a new collaborator, click in the search field, begin entering the user's name, and then click the user's name from the list.
    5. To change the collaborator's permission level, click the **Permissions** down arrow and change the permission.
    6. Repeat for each collaborator.
    7. Click **Done**.

------------------------------
Sharing a tool with the public
------------------------------

    1. In the Apps window, click **Manage Tools** at the top.
    2. Click to select the tool you own that you want to share with the public.
    3. Click the **Share** menu and then click **Make public**.
    4. This opens a form which you will need to fill it up and click **Submit**
    5. You will receive email notifications as the tool progresses through the process of making it public.


----------------
Unsharing a tool
----------------

    1. In the Apps window, click **Manage Tools** at the top and then click to select the tool to unshare.
    2. Click the **Share** menu and then click **Share with collaborators**.
    3. Find the collaborator and click
    4. Click  to the right of the collaborator's name.
    5. Click **Done**.


Adding or Requesting a New Tool
-------------------------------

Discovery Environment **tools** are `Docker images <http://hammer.cyverse.org:8090/display/DEmanual/Dockerizing+Your+Tools+for+the+CyVerse+Discovery+Environment>`_ from which apps are created. There are numerous tools already available in the DE for new apps you are creating. It's easiest to just use one of those tools. However, sometimes the tool or version isn't available, so you can request installation of a new tool or create a new one yourself. This page describes how to add a new tool to the DE that you created or to request that a new tool or tool version be installed in the DE. To request installation of a new tool on the Condor nodes or via some other method, contact `CyVerse Support <support@cyverse.org>`_ for more information.

If you create a new tool, it is available by default in your personal Tools list and available only for your use until you share it with a collaborator or make it public. Note that all tools created prior to the 2.13 release in June 2017 are public. You can edit and delete a tool you own, as well as jump-start the creation of a new app from the Tools window. For information on managing tools, see **Managing Tools in the DE**.

-----------------
Adding a new tool
-----------------

.. |infoicon| image:: img/InfoIcon.png

You can create a new tool.

    1. `View the list of available tools <http://hammer.cyverse.org:8090/display/DEmanual/Finding+the+List+of+Available+Tools#FindingtheListofAvailableTools-SelectTool>`_ to make sure the tool and version are not already installed. If your tool and version are not listed, you must first `Dockerize the tool <http://hammer.cyverse.org:8090/display/DEmanual/Dockerizing+Your+Tools+for+the+CyVerse+Discovery+Environment>`_ before requesting the new tool or version. **Because all tools run inside Docker containers and are installed as Docker images, you must first create the Dockerfile for the image**. See `Dockerizing Your Tools for the CyVerse Discovery Environment <http://hammer.cyverse.org:8090/display/DEmanual/Dockerizing+Your+Tools+for+the+CyVerse+Discovery+Environment>`_. It is recommended that you create a Docker image or Dockerfile for the tool before sending your request to facilitate its installation. For information on using Docker, see the `Docker website <https://www.docker.com/>`_.
    2. In the Apps window, click **Manage Tools** on the right.
    3. Click the Tools menu and then click **Add tool**:

     .. image:: img/addTool.png

        a. In the Tool Name field, enter a unique name for the tool.
        b. In the Description field, add a description. Though optional, this field will help other users know more about your tool when deciding on a tool to use when they click |infoicon| in the Tools list.
        c. In the Version field, enter the tool version.
        d. In the Image name field, enter the name of the image.
        e. In the Tag field, enter the tag (limit one tag). You may want to use the version name again, since this field shows in the Tools list.
        f. In the Dockerfile does not have an ENTRYPOINT, enter an ENTRYPOINT in the Entrypoint field. Example for a HISAT2 app: ENTRYPOINT ["/usr/bin/hisat2"]. If the Dockerfile has one, you can leave this field blank.
        g. In the Docker Hub URL field, enter the URL to the Docker hub (optional).
    
    4. Click **OK**. The tool is immediately available in your list of personal tools and you may begin using it to create a new app interface.

-------------------------------------
Requesting installation of a new tool
-------------------------------------

**Because all tools run inside Docker containers and are installed as Docker images, you must first create the Dockerfile for the image**. See `Dockerizing Your Tools for the CyVerse Discovery Environment <http://hammer.cyverse.org:8090/display/DEmanual/Dockerizing+Your+Tools+for+the+CyVerse+Discovery+Environment>`_. It is recommended that you create a Docker image or Dockerfile for the tool before sending your request to facilitate its installation. For information on using Docker, see the `Docker website <https://www.docker.com/>`_.

    1. In the DE Apps window, click **Manage Tools** on the right.
    2. Click the Tools and then **Request Tool**.
    3. In the Request New Tool Installation window:
        a. Enter the name of the tool (executable or binary).
        b. Enter a brief description of the tool as you want it to appear in the Apps window `information section <http://hammer.cyverse.org:8090/display/DEmanual/Viewing+App+and+Tool+Information>`_ for apps that use this tool.
        c. Enter the attribution for the tool, such as the person who created the tool (optional).
        d. In **How do you want to submit data for your tool's source**, do one of the following:
            
            - Click **Enter a link** and enter or paste the URL. 
            - Click **New upload** and enter a unique filename or browse to upload the file to your personal folder.
            - Click **Select from existing** and then browse to the source file location in your personal folder.
        
        e. Enter the tool's version.
        f. Select the software architecture for the tool.
        g. Specify if the file is multi-threaded. For information on threading, see `Thread (computing) <http://en.wikipedia.org/wiki/Thread_%28computing%29>`_ on the Wikipedia website.
        h. If necessary, click to expand the **Other Information** section.
        i. In the **How do you want to submit your test data** field, select either **New upload** (to upload the file to your personal Data folder) and enter a **unique** name, or **Select from existing** (to select a file that already exists in your personal Data folder), and then browse to select the first test data file.

        .. note::
            If choosing New upload, the filename must be unique.

        j. Enter instructions for how to use the tool in the Unix environment.
        k. To upload a second test data file, click **Browse** in the **How do you want to submit additional data** field and browse to select the second file.
        l. Enter any additional information that might be useful.
        m. Click **Submit**. Your request is sent to `CyVerse Support <support@cyverse.org>`_. When the new tool is installed, you will receive an email from CyVerse Support.the


---------
Next step
---------

After you receive the email notification that the new tool has been added to the Discovery Environment, you can use it to create a new app interface.


Finding the List of Available Tools
-----------------------------------

The tools — executables or binaries — that are available for use in the DE have been integrated by the CyVerse Support staff, based on user requests. Before `requesting installation of a new tool <http://hammer.cyverse.org:8090/display/DEmanual/Adding+or+Requesting+a+New+Tool>`_, you should view the list of all available tools to make sure the tool and version isn't already available in the list. You can view the name of the tool's creator, a description of the tool, and the apps that currently use the tool.

    1. In the Apps window, click the **Manage Tools** icon at the top right. 
    2. Search for a tool:
    
        - To narrow the search from all tools (default) to search only on your tools or on all public tools, click the drop-down menu at the top and then click either **All**, **Only my tools**, or **Public tools**:
        .. image:: img/ManageToolsSearchMyTools.png
        - To sort a column, click the column header and then click either **Sort Ascending** or **Sort Descending**:
        .. image:: img/SortTools.png
        - To search for a specific tool, enter the tool's name in the Search field.
    
    3. To view information about a tool and the apps that use it, click |infoicon|:
        
        a. View **tool attribution and description** on the **Tool Information** tab:
        .. image:: img/ToolAttribution.png
        b. Click the **Apps using this tool** tab to view the list of apps that use the tool:
        .. image:: img/Tool-AppsUsed.png

        .. tip::
            In this window, click |infoicon| to view information about the app, or click the app name to open the app. For more information on app info, see `Viewing App and Tool Information <http://hammer.cyverse.org:8090/display/DEmanual/Viewing+App+and+Tool+Information>`_.

            To quickly begin creating an app using the tool, click the tool name. For more information on creating new apps, see `Creating a New App Interface <http://hammer.cyverse.org:8090/display/DEmanual/Creating+a+New+App+Interface>`_.

If the tool or tool version you want to use is not available in the list, click **New Tool Request** and `complete the form <http://hammer.cyverse.org:8090/display/DEmanual/Adding+or+Requesting+a+New+Tool>`_.


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
