
######################
Getting Started
######################

The tool can be used in either *Object* or *Edit Face* Mode, with faces selected.

.. figure:: ../images/using_menu.jpg
    :alt: Shipwright Properties Panel

    Plating Generator in the right-click context menu.

#. Select some faces on your object.
#. Right-click in the viewport and a menu should appear.  
#. In the menu there should be a section called *Plating Generator*, which is also available from the *Mesh* menu at the top of the viewport.
#. If you want to create a new plating object and leave the original object intact in a :ref:`non-destructive way<Non Destructive Workflow>` you have the following options as a starting point:

    * :ref:`Add Plates`: Add a panel line pattern as a new object using the faces you have selected.
    * :ref:`Add Greebles`: Add greeble objects as a new object using the faces you have selected.

#. If you want to :ref:`modify the existing mesh<Destructive Workflow>` you have the following options:

    * :ref:`Add Plates to Mesh`: Add panel lines directly to your mesh.
    * :ref:`Add Greebles to Mesh`: Add greeble objects directly to your mesh.


.. |greeble| raw:: html

   <a href="https://en.wikipedia.org/wiki/Greeble" target="_blank">greeble</a>

These options are described below.

   
**********************************
Non Destructive Workflow
**********************************

If you don't want to damage your original object, these options will create a new separate object, called *\<original name\> plating*, and add a base Level of either Plates or Greebles:
   
============================
Add Plates
============================

Selecting the *Add Plates* option will automatically add a basic plating pattern in the form of a new Blender object:

.. image:: ../images/add_plates_1.gif
    :alt: Adding Plates


============================
Add Greebles
============================

Selecting the *Add Greebles* option will automatically add a set of basic greebles in the form of a new Blender object:

.. image:: ../images/add_greebles_1.gif
    :alt: Adding Greebles


==============================
Changing Properties for Object
==============================

When you have either added Plating or Greebles you can then change the object's properties using the built-in side panel available on the right hand side when the new object is selected.  If this is not visible, press the *n* key in the viewport to display Blender's properties panel, and select the *Plating Generator* side tab:

.. figure:: ../images/add_plates_2.jpg
    :alt: Plates Properties Panel

    Plates Properties Panel

These properties are descibed in more detail :ref:`here<properties>`.


   
**********************************
Destructive Workflow
**********************************

This will edit the existing object, which can be advantageous if you wish to create deeper plates or embedded greebles.  However it is more difficult to undo the operation.

.. tip:: Disappearing Panel?

   During this mode, which is a one-time operation, Blender's panel can disappears if you accidentally click outside.  You can bring it back as long as you have not performed another action by pressing *F9*.

============================
Add Plates to Mesh
============================


Selecting the *Add Plates to Mesh* option will automatically add a basic plating pattern directly on the mesh:


.. image:: ../images/add_plates_to_mesh_1.gif
    :alt: Adding Greebles


============================
Add Greebles to Mesh
============================

Selecting the *Add Greebles to Mesh* option will automatically add greebles directly on the mesh:

.. image:: ../images/add_greebles_to_mesh_1.gif
    :alt: Adding Greebles



============================
Add Panel Lines to Mesh
============================

Selecting the *Add Panel Lines to Mesh* option will automatically add panel lines using selected edges:

.. image:: ../images/add_panel_lines_to_mesh.gif
    :alt: Adding Panel Lines

This uses the same :ref:`properties` as the :ref:`Add Plates to Mesh` function


====================================================================
Changing Properties for Operation
====================================================================

You can then change the object's :ref:`properties` using the bottom left hand side panel.  You may need to expand the panel to see all the options:

.. image:: ../images/add_greebles_to_mesh_2.gif
    :alt: Properties Panel


These properties are descibed in more detail :ref:`here<properties>`.