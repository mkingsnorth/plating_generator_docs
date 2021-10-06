##########################
Update/Copy/Select
##########################

If you want to:

* Change the face selection for the generated plates
* Copy the plates you already have to a new area on the object
* Get the selection you used to create the plating object

You have the following options:

.. image:: ../images/opts_update_selection.jpg
  :alt: Updating the selection used to generate plates.

*********************************
Update Selection
*********************************

.. figure:: ../images/updating_selection.gif
  :alt: Updating the selection used to generate plates.

  Updating the selection used to generate plates.


This will update the plating object to change to a different set of faces on a mesh.

.. image:: ../images/update_plating_sel_for.jpg
  :alt: Updating the selection for...

#. On the main object you are creating plate objects from, select a new set of faces you wish to change to in Face Edit Mode.  This can also be existing faces you have changed.
#. Right-click and select *Plating Generator -> Update Plating Selection For:*.
#. In the menu that appears, select the plating object you wish to update.
#. The plating object you have selected should automatically update to use the new face selection.


*********************************
Copy Plating
*********************************

.. figure:: ../images/updating_selection_copy.gif
  :alt: Updating the selection used to generate plates.

  Copying a plating object to a new selection area.

This will copy a plating object to a new set of faces on the object.

.. image:: ../images/copy_plating_sel_for.jpg
  :alt: Copy plating from...

#. On the main object you are creating plate objects from, select a new set of faces in Face Edit Mode.
#. Right-click and select *Plating Generator -> Copy Plating From:*.
#. In the menu that appears, select the plating object you wish to update.
#. The plating object you have selected should automatically be copied and pointed to use the new face selection.

*********************************
Select Faces for Plates
*********************************

.. figure:: ../images/get_selection.gif
  :alt: Getting the plating selection for a plating object.

  Getting the plating selection for a plating object.

When in Face Edit mode on the main object, this will get the selection for a plating object associated with it.

.. image:: ../images/updating_selection_get.jpg
  :alt: Copy plating from...

#. On the main object you are creating plate objects from, right-click and select *Plating Generator -> Select Faces For:*.
#. In the menu that appears, select the plating object you wish to get the face selection for.
#. The main object should update its face selection to the faces that are associated with the selected plating object.