Maps admin section
==================

This section list the ``maps`` section and its usage in the site.


View existing Locations
-----------------------

Location of the items that appear in the map.

The existing Locations can be listed in the ``/admin/maps/location/`` URL. From this section the details of these Locations can be inspected.

And the following actions can be performed:

- View the details of the Locations.
- Filter the Locations by: status or category.
- Search the Locations by their contents.

.. image:: ../snapshots/admin--maps--location.png
   :width: 100%


Adding Locations
----------------

Adding Locations can be done from the ``/admin/maps/location/add/`` URL.

The following fields are available to create Locations:

- Name: Required. Name of the location.
- Website: Optional. Fully qualified URL to be used for this location.
- Image: Optional. Icon to be used for this location in the map.
- Status: Required. Publication status of the location.
- Position: Optional. Position of the location in a map.
- Category: Required. Category used for this location.

.. image:: ../snapshots/admin--maps--location--add.png
   :width: 100%


Unpublishing / Removing  Locations
----------------------------------

In case Locations needs unpublishing it can be done from the detail admin view by changing the ``status`` of the Locations to ``draft`` or ``removed``

.. note::
   The Locations can be browsed in the ``/admin/maps/location/`` URL.


View existing Categories
------------------------

These are the categories used for the elements that appear in the map.

The existing Categories can be listed in the ``/admin/maps/category/`` URL. From this section the details of these Categories can be inspected.

And the following actions can be performed:

- View the details of the Categories.

.. image:: ../snapshots/admin--maps--category.png
   :width: 100%


Adding Categories
-----------------

Adding Categories can be done from the ``/admin/maps/category/add/`` URL.

The following fields are available to create Categories:

- Name: Required. Name of the category.
- Slug: Required. Slug used for this category, must be unique.
- Image: Optional. Image used as an icon for the map on this category.

.. image:: ../snapshots/admin--maps--category--add.png
   :width: 100%
