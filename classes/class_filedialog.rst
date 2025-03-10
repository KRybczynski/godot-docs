:github_url: hide

.. DO NOT EDIT THIS FILE!!!
.. Generated automatically from Godot engine sources.
.. Generator: https://github.com/godotengine/godot/tree/master/doc/tools/make_rst.py.
.. XML source: https://github.com/godotengine/godot/tree/master/doc/classes/FileDialog.xml.

.. _class_FileDialog:

FileDialog
==========

**Inherits:** :ref:`ConfirmationDialog<class_ConfirmationDialog>` **<** :ref:`AcceptDialog<class_AcceptDialog>` **<** :ref:`Window<class_Window>` **<** :ref:`Viewport<class_Viewport>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

A dialog for selecting files or directories in the filesystem.

.. rst-class:: classref-introduction-group

Description
-----------

**FileDialog** is a preset dialog used to choose files and directories in the filesystem. It supports filter masks. **FileDialog** automatically sets its window title according to the :ref:`file_mode<class_FileDialog_property_file_mode>`. If you want to use a custom title, disable this by setting :ref:`mode_overrides_title<class_FileDialog_property_mode_overrides_title>` to ``false``.

.. rst-class:: classref-reftable-group

Properties
----------

.. table::
   :widths: auto

   +---------------------------------------------------+-----------------------------------------------------------------------------+------------------------------------------------------------------------------------------+
   | :ref:`Access<enum_FileDialog_Access>`             | :ref:`access<class_FileDialog_property_access>`                             | ``0``                                                                                    |
   +---------------------------------------------------+-----------------------------------------------------------------------------+------------------------------------------------------------------------------------------+
   | :ref:`String<class_String>`                       | :ref:`current_dir<class_FileDialog_property_current_dir>`                   |                                                                                          |
   +---------------------------------------------------+-----------------------------------------------------------------------------+------------------------------------------------------------------------------------------+
   | :ref:`String<class_String>`                       | :ref:`current_file<class_FileDialog_property_current_file>`                 |                                                                                          |
   +---------------------------------------------------+-----------------------------------------------------------------------------+------------------------------------------------------------------------------------------+
   | :ref:`String<class_String>`                       | :ref:`current_path<class_FileDialog_property_current_path>`                 |                                                                                          |
   +---------------------------------------------------+-----------------------------------------------------------------------------+------------------------------------------------------------------------------------------+
   | :ref:`bool<class_bool>`                           | dialog_hide_on_ok                                                           | ``false`` (overrides :ref:`AcceptDialog<class_AcceptDialog_property_dialog_hide_on_ok>`) |
   +---------------------------------------------------+-----------------------------------------------------------------------------+------------------------------------------------------------------------------------------+
   | :ref:`FileMode<enum_FileDialog_FileMode>`         | :ref:`file_mode<class_FileDialog_property_file_mode>`                       | ``4``                                                                                    |
   +---------------------------------------------------+-----------------------------------------------------------------------------+------------------------------------------------------------------------------------------+
   | :ref:`PackedStringArray<class_PackedStringArray>` | :ref:`filters<class_FileDialog_property_filters>`                           | ``PackedStringArray()``                                                                  |
   +---------------------------------------------------+-----------------------------------------------------------------------------+------------------------------------------------------------------------------------------+
   | :ref:`bool<class_bool>`                           | :ref:`mode_overrides_title<class_FileDialog_property_mode_overrides_title>` | ``true``                                                                                 |
   +---------------------------------------------------+-----------------------------------------------------------------------------+------------------------------------------------------------------------------------------+
   | :ref:`String<class_String>`                       | :ref:`root_subfolder<class_FileDialog_property_root_subfolder>`             | ``""``                                                                                   |
   +---------------------------------------------------+-----------------------------------------------------------------------------+------------------------------------------------------------------------------------------+
   | :ref:`bool<class_bool>`                           | :ref:`show_hidden_files<class_FileDialog_property_show_hidden_files>`       | ``false``                                                                                |
   +---------------------------------------------------+-----------------------------------------------------------------------------+------------------------------------------------------------------------------------------+
   | :ref:`String<class_String>`                       | title                                                                       | ``"Save a File"`` (overrides :ref:`Window<class_Window_property_title>`)                 |
   +---------------------------------------------------+-----------------------------------------------------------------------------+------------------------------------------------------------------------------------------+

.. rst-class:: classref-reftable-group

Methods
-------

.. table::
   :widths: auto

   +-------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
   | void                                      | :ref:`add_filter<class_FileDialog_method_add_filter>` **(** :ref:`String<class_String>` filter, :ref:`String<class_String>` description="" **)** |
   +-------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
   | void                                      | :ref:`clear_filters<class_FileDialog_method_clear_filters>` **(** **)**                                                                          |
   +-------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
   | void                                      | :ref:`deselect_all<class_FileDialog_method_deselect_all>` **(** **)**                                                                            |
   +-------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
   | :ref:`LineEdit<class_LineEdit>`           | :ref:`get_line_edit<class_FileDialog_method_get_line_edit>` **(** **)**                                                                          |
   +-------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
   | :ref:`VBoxContainer<class_VBoxContainer>` | :ref:`get_vbox<class_FileDialog_method_get_vbox>` **(** **)**                                                                                    |
   +-------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
   | void                                      | :ref:`invalidate<class_FileDialog_method_invalidate>` **(** **)**                                                                                |
   +-------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+

.. rst-class:: classref-reftable-group

Theme Properties
----------------

.. table::
   :widths: auto

   +-----------------------------------+------------------------------------------------------------------------------+--------------------------+
   | :ref:`Color<class_Color>`         | :ref:`file_disabled_color<class_FileDialog_theme_color_file_disabled_color>` | ``Color(1, 1, 1, 0.25)`` |
   +-----------------------------------+------------------------------------------------------------------------------+--------------------------+
   | :ref:`Color<class_Color>`         | :ref:`file_icon_color<class_FileDialog_theme_color_file_icon_color>`         | ``Color(1, 1, 1, 1)``    |
   +-----------------------------------+------------------------------------------------------------------------------+--------------------------+
   | :ref:`Color<class_Color>`         | :ref:`folder_icon_color<class_FileDialog_theme_color_folder_icon_color>`     | ``Color(1, 1, 1, 1)``    |
   +-----------------------------------+------------------------------------------------------------------------------+--------------------------+
   | :ref:`Texture2D<class_Texture2D>` | :ref:`back_folder<class_FileDialog_theme_icon_back_folder>`                  |                          |
   +-----------------------------------+------------------------------------------------------------------------------+--------------------------+
   | :ref:`Texture2D<class_Texture2D>` | :ref:`file<class_FileDialog_theme_icon_file>`                                |                          |
   +-----------------------------------+------------------------------------------------------------------------------+--------------------------+
   | :ref:`Texture2D<class_Texture2D>` | :ref:`folder<class_FileDialog_theme_icon_folder>`                            |                          |
   +-----------------------------------+------------------------------------------------------------------------------+--------------------------+
   | :ref:`Texture2D<class_Texture2D>` | :ref:`forward_folder<class_FileDialog_theme_icon_forward_folder>`            |                          |
   +-----------------------------------+------------------------------------------------------------------------------+--------------------------+
   | :ref:`Texture2D<class_Texture2D>` | :ref:`parent_folder<class_FileDialog_theme_icon_parent_folder>`              |                          |
   +-----------------------------------+------------------------------------------------------------------------------+--------------------------+
   | :ref:`Texture2D<class_Texture2D>` | :ref:`reload<class_FileDialog_theme_icon_reload>`                            |                          |
   +-----------------------------------+------------------------------------------------------------------------------+--------------------------+
   | :ref:`Texture2D<class_Texture2D>` | :ref:`toggle_hidden<class_FileDialog_theme_icon_toggle_hidden>`              |                          |
   +-----------------------------------+------------------------------------------------------------------------------+--------------------------+

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Signals
-------

.. _class_FileDialog_signal_dir_selected:

.. rst-class:: classref-signal

**dir_selected** **(** :ref:`String<class_String>` dir **)**

Emitted when the user selects a directory.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_signal_file_selected:

.. rst-class:: classref-signal

**file_selected** **(** :ref:`String<class_String>` path **)**

Emitted when the user selects a file by double-clicking it or pressing the **OK** button.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_signal_files_selected:

.. rst-class:: classref-signal

**files_selected** **(** :ref:`PackedStringArray<class_PackedStringArray>` paths **)**

Emitted when the user selects multiple files.

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Enumerations
------------

.. _enum_FileDialog_FileMode:

.. rst-class:: classref-enumeration

enum **FileMode**:

.. _class_FileDialog_constant_FILE_MODE_OPEN_FILE:

.. rst-class:: classref-enumeration-constant

:ref:`FileMode<enum_FileDialog_FileMode>` **FILE_MODE_OPEN_FILE** = ``0``

The dialog allows selecting one, and only one file.

.. _class_FileDialog_constant_FILE_MODE_OPEN_FILES:

.. rst-class:: classref-enumeration-constant

:ref:`FileMode<enum_FileDialog_FileMode>` **FILE_MODE_OPEN_FILES** = ``1``

The dialog allows selecting multiple files.

.. _class_FileDialog_constant_FILE_MODE_OPEN_DIR:

.. rst-class:: classref-enumeration-constant

:ref:`FileMode<enum_FileDialog_FileMode>` **FILE_MODE_OPEN_DIR** = ``2``

The dialog only allows selecting a directory, disallowing the selection of any file.

.. _class_FileDialog_constant_FILE_MODE_OPEN_ANY:

.. rst-class:: classref-enumeration-constant

:ref:`FileMode<enum_FileDialog_FileMode>` **FILE_MODE_OPEN_ANY** = ``3``

The dialog allows selecting one file or directory.

.. _class_FileDialog_constant_FILE_MODE_SAVE_FILE:

.. rst-class:: classref-enumeration-constant

:ref:`FileMode<enum_FileDialog_FileMode>` **FILE_MODE_SAVE_FILE** = ``4``

The dialog will warn when a file exists.

.. rst-class:: classref-item-separator

----

.. _enum_FileDialog_Access:

.. rst-class:: classref-enumeration

enum **Access**:

.. _class_FileDialog_constant_ACCESS_RESOURCES:

.. rst-class:: classref-enumeration-constant

:ref:`Access<enum_FileDialog_Access>` **ACCESS_RESOURCES** = ``0``

The dialog only allows accessing files under the :ref:`Resource<class_Resource>` path (``res://``).

.. _class_FileDialog_constant_ACCESS_USERDATA:

.. rst-class:: classref-enumeration-constant

:ref:`Access<enum_FileDialog_Access>` **ACCESS_USERDATA** = ``1``

The dialog only allows accessing files under user data path (``user://``).

.. _class_FileDialog_constant_ACCESS_FILESYSTEM:

.. rst-class:: classref-enumeration-constant

:ref:`Access<enum_FileDialog_Access>` **ACCESS_FILESYSTEM** = ``2``

The dialog allows accessing files on the whole file system.

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Property Descriptions
---------------------

.. _class_FileDialog_property_access:

.. rst-class:: classref-property

:ref:`Access<enum_FileDialog_Access>` **access** = ``0``

.. rst-class:: classref-property-setget

- void **set_access** **(** :ref:`Access<enum_FileDialog_Access>` value **)**
- :ref:`Access<enum_FileDialog_Access>` **get_access** **(** **)**

The file system access scope. See :ref:`Access<enum_FileDialog_Access>` constants.

\ **Warning:** Currently, in sandboxed environments such as Web builds or sandboxed macOS apps, FileDialog cannot access the host file system. See `godot-proposals#1123 <https://github.com/godotengine/godot-proposals/issues/1123>`__.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_property_current_dir:

.. rst-class:: classref-property

:ref:`String<class_String>` **current_dir**

.. rst-class:: classref-property-setget

- void **set_current_dir** **(** :ref:`String<class_String>` value **)**
- :ref:`String<class_String>` **get_current_dir** **(** **)**

The current working directory of the file dialog.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_property_current_file:

.. rst-class:: classref-property

:ref:`String<class_String>` **current_file**

.. rst-class:: classref-property-setget

- void **set_current_file** **(** :ref:`String<class_String>` value **)**
- :ref:`String<class_String>` **get_current_file** **(** **)**

The currently selected file of the file dialog.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_property_current_path:

.. rst-class:: classref-property

:ref:`String<class_String>` **current_path**

.. rst-class:: classref-property-setget

- void **set_current_path** **(** :ref:`String<class_String>` value **)**
- :ref:`String<class_String>` **get_current_path** **(** **)**

The currently selected file path of the file dialog.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_property_file_mode:

.. rst-class:: classref-property

:ref:`FileMode<enum_FileDialog_FileMode>` **file_mode** = ``4``

.. rst-class:: classref-property-setget

- void **set_file_mode** **(** :ref:`FileMode<enum_FileDialog_FileMode>` value **)**
- :ref:`FileMode<enum_FileDialog_FileMode>` **get_file_mode** **(** **)**

The dialog's open or save mode, which affects the selection behavior. See :ref:`FileMode<enum_FileDialog_FileMode>`.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_property_filters:

.. rst-class:: classref-property

:ref:`PackedStringArray<class_PackedStringArray>` **filters** = ``PackedStringArray()``

.. rst-class:: classref-property-setget

- void **set_filters** **(** :ref:`PackedStringArray<class_PackedStringArray>` value **)**
- :ref:`PackedStringArray<class_PackedStringArray>` **get_filters** **(** **)**

The available file type filters. For example, this shows only ``.png`` and ``.gd`` files: ``set_filters(PackedStringArray(["*.png ; PNG Images","*.gd ; GDScript Files"]))``. Multiple file types can also be specified in a single filter. ``"*.png, *.jpg, *.jpeg ; Supported Images"`` will show both PNG and JPEG files when selected.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_property_mode_overrides_title:

.. rst-class:: classref-property

:ref:`bool<class_bool>` **mode_overrides_title** = ``true``

.. rst-class:: classref-property-setget

- void **set_mode_overrides_title** **(** :ref:`bool<class_bool>` value **)**
- :ref:`bool<class_bool>` **is_mode_overriding_title** **(** **)**

If ``true``, changing the :ref:`file_mode<class_FileDialog_property_file_mode>` property will set the window title accordingly (e.g. setting :ref:`file_mode<class_FileDialog_property_file_mode>` to :ref:`FILE_MODE_OPEN_FILE<class_FileDialog_constant_FILE_MODE_OPEN_FILE>` will change the window title to "Open a File").

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_property_root_subfolder:

.. rst-class:: classref-property

:ref:`String<class_String>` **root_subfolder** = ``""``

.. rst-class:: classref-property-setget

- void **set_root_subfolder** **(** :ref:`String<class_String>` value **)**
- :ref:`String<class_String>` **get_root_subfolder** **(** **)**

If non-empty, the given sub-folder will be "root" of this **FileDialog**, i.e. user won't be able to go to its parent directory.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_property_show_hidden_files:

.. rst-class:: classref-property

:ref:`bool<class_bool>` **show_hidden_files** = ``false``

.. rst-class:: classref-property-setget

- void **set_show_hidden_files** **(** :ref:`bool<class_bool>` value **)**
- :ref:`bool<class_bool>` **is_showing_hidden_files** **(** **)**

If ``true``, the dialog will show hidden files.

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Method Descriptions
-------------------

.. _class_FileDialog_method_add_filter:

.. rst-class:: classref-method

void **add_filter** **(** :ref:`String<class_String>` filter, :ref:`String<class_String>` description="" **)**

Adds a comma-delimited file name ``filter`` option to the **FileDialog** with an optional ``description``, which restricts what files can be picked.

A ``filter`` should be of the form ``"filename.extension"``, where filename and extension can be ``*`` to match any string. Filters starting with ``.`` (i.e. empty filenames) are not allowed.

For example, a ``filter`` of ``"*.png, *.jpg"`` and a ``description`` of ``"Images"`` results in filter text "Images (\*.png, \*.jpg)".

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_method_clear_filters:

.. rst-class:: classref-method

void **clear_filters** **(** **)**

Clear all the added filters in the dialog.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_method_deselect_all:

.. rst-class:: classref-method

void **deselect_all** **(** **)**

Clear all currently selected items in the dialog.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_method_get_line_edit:

.. rst-class:: classref-method

:ref:`LineEdit<class_LineEdit>` **get_line_edit** **(** **)**

Returns the LineEdit for the selected file.

\ **Warning:** This is a required internal node, removing and freeing it may cause a crash. If you wish to hide it or any of its children, use their :ref:`CanvasItem.visible<class_CanvasItem_property_visible>` property.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_method_get_vbox:

.. rst-class:: classref-method

:ref:`VBoxContainer<class_VBoxContainer>` **get_vbox** **(** **)**

Returns the vertical box container of the dialog, custom controls can be added to it.

\ **Warning:** This is a required internal node, removing and freeing it may cause a crash. If you wish to hide it or any of its children, use their :ref:`CanvasItem.visible<class_CanvasItem_property_visible>` property.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_method_invalidate:

.. rst-class:: classref-method

void **invalidate** **(** **)**

Invalidate and update the current dialog content list.

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Theme Property Descriptions
---------------------------

.. _class_FileDialog_theme_color_file_disabled_color:

.. rst-class:: classref-themeproperty

:ref:`Color<class_Color>` **file_disabled_color** = ``Color(1, 1, 1, 0.25)``

The color tint for disabled files (when the **FileDialog** is used in open folder mode).

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_theme_color_file_icon_color:

.. rst-class:: classref-themeproperty

:ref:`Color<class_Color>` **file_icon_color** = ``Color(1, 1, 1, 1)``

The color modulation applied to the file icon.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_theme_color_folder_icon_color:

.. rst-class:: classref-themeproperty

:ref:`Color<class_Color>` **folder_icon_color** = ``Color(1, 1, 1, 1)``

The color modulation applied to the folder icon.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_theme_icon_back_folder:

.. rst-class:: classref-themeproperty

:ref:`Texture2D<class_Texture2D>` **back_folder**

Custom icon for the back arrow.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_theme_icon_file:

.. rst-class:: classref-themeproperty

:ref:`Texture2D<class_Texture2D>` **file**

Custom icon for files.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_theme_icon_folder:

.. rst-class:: classref-themeproperty

:ref:`Texture2D<class_Texture2D>` **folder**

Custom icon for folders.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_theme_icon_forward_folder:

.. rst-class:: classref-themeproperty

:ref:`Texture2D<class_Texture2D>` **forward_folder**

Custom icon for the forward arrow.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_theme_icon_parent_folder:

.. rst-class:: classref-themeproperty

:ref:`Texture2D<class_Texture2D>` **parent_folder**

Custom icon for the parent folder arrow.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_theme_icon_reload:

.. rst-class:: classref-themeproperty

:ref:`Texture2D<class_Texture2D>` **reload**

Custom icon for the reload button.

.. rst-class:: classref-item-separator

----

.. _class_FileDialog_theme_icon_toggle_hidden:

.. rst-class:: classref-themeproperty

:ref:`Texture2D<class_Texture2D>` **toggle_hidden**

Custom icon for the toggle hidden button.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
.. |bitfield| replace:: :abbr:`BitField (This value is an integer composed as a bitmask of the following flags.)`
