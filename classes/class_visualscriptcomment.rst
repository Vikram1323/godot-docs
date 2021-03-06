:github_url: hide

.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the VisualScriptComment.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_VisualScriptComment:

VisualScriptComment
===================

**Inherits:** :ref:`VisualScriptNode<class_VisualScriptNode>` **<** :ref:`Resource<class_Resource>` **<** :ref:`Reference<class_Reference>` **<** :ref:`Object<class_Object>`

**Category:** Core

Brief Description
-----------------

A Visual Script node used to annotate the script.

Properties
----------

+-------------------------------+--------------------------------------------------------------------+---------------------+
| :ref:`String<class_String>`   | :ref:`description<class_VisualScriptComment_property_description>` | ""                  |
+-------------------------------+--------------------------------------------------------------------+---------------------+
| :ref:`Vector2<class_Vector2>` | :ref:`size<class_VisualScriptComment_property_size>`               | Vector2( 150, 150 ) |
+-------------------------------+--------------------------------------------------------------------+---------------------+
| :ref:`String<class_String>`   | :ref:`title<class_VisualScriptComment_property_title>`             | "Comment"           |
+-------------------------------+--------------------------------------------------------------------+---------------------+

Description
-----------

A Visual Script node used to display annotations in the script, so that code may be documented.

Comment nodes can be resized so they encompass a group of nodes.

Property Descriptions
---------------------

.. _class_VisualScriptComment_property_description:

- :ref:`String<class_String>` **description**

+-----------+------------------------+
| *Default* | ""                     |
+-----------+------------------------+
| *Setter*  | set_description(value) |
+-----------+------------------------+
| *Getter*  | get_description()      |
+-----------+------------------------+

The text inside the comment node.

.. _class_VisualScriptComment_property_size:

- :ref:`Vector2<class_Vector2>` **size**

+-----------+---------------------+
| *Default* | Vector2( 150, 150 ) |
+-----------+---------------------+
| *Setter*  | set_size(value)     |
+-----------+---------------------+
| *Getter*  | get_size()          |
+-----------+---------------------+

The comment node's size (in pixels).

.. _class_VisualScriptComment_property_title:

- :ref:`String<class_String>` **title**

+-----------+------------------+
| *Default* | "Comment"        |
+-----------+------------------+
| *Setter*  | set_title(value) |
+-----------+------------------+
| *Getter*  | get_title()      |
+-----------+------------------+

The comment node's title.

