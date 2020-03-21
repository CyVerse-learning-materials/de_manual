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
