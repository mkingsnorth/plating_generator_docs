######################
Plating Properties
######################


.. figure:: ../../images/properties_panel_plates.jpg
    :alt: Main Control Panel

    Main properties panel for the plating effect.

**********************************
General Properties
**********************************

.. figure:: ../../images/plating_level_props.jpg
    :alt: Main Control Panel

    Plating General Properties

* **Level Color**: Color to denote level for organisational purposes.  Has no direct effect on object.
* **Level Name**: The name of the :ref:`Level<Levels>` for these properties.
* **Enabled Checkbox**: Whether the :ref:`Level<Levels>` is activated or not.
* **Plates/Greebles**: Whether we are creating Plates or Greebles.
* **Minimum Face Area**: the minimum size of the face to apply the effect to.  Good for avoiding small areas of an object.

**********************************
Plating Pattern
**********************************

.. figure:: ../../images/pattern_type_props.jpg
    :alt: Platng Pattern Props


Configure how the plating pattern is created.

* **Pattern Type**: Choose between:

    * **Generated**: Automatically generate a hull plating pattern by selecting intersecting edge loops. The following options apply:
  
        * **Random Seed**: generate a different selection based on the whole number given here.

        * **Amount**: the amount of plate cuts generated.
  
        * **Subdivisions**: this will subdivide the selected faces before applying the plates. 

    * **Ruby Dragon**: Automatically generate a hull plating pattern by randomly selecting faces and walking arounf the mesh. The following options apply:
  
        * **Random Seed**: generate a different selection based on the whole number given here.

        * **Percentage**: The amount of grooves to add.
  
        * **Subdivisions**: this will subdivide the selected faces before applying the plates. 
  

    * **Selected Edges**: Use the edges that have been already selected.
  
    * **Triangular**: Similar to Generated, with added triangular accents added randomly to the grooves. Additional properties:

        * **Triangles Random Seed**: Change where triangular parts of the grooves are added independent to the main random seed.

        * **Amount of triangles**: As a percentage, how many triangles are added to the standard pattern.