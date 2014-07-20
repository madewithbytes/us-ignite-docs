Snippets admin section
======================

This section list the ``snippets`` section and its usage in the site. The snippets are used across the site to render small dynamic blocks of HTML.

.. note::
   The snippets are used in conjunction with the templates of the site. They rely on an unique key to determine where they should be rendered, if they are not implemented in the templates they are unusable.


View existing Snippets
----------------------

The existing Snippets can be listed in the ``/admin/snippets/snippet/`` URL. From this section the details of these Snippets can be inspected.

And the following actions can be performed:

- View the details of the Snippets.
- Filter the Snippets by: status, is featured?, creation date.
- Search the Snippets by their contents.

.. image:: ../snapshots/admin--snippets--snippet.png
   :width: 100%


Adding Snippets
---------------

Adding Snippets can be done from the ``/admin/snippets/snippet/add/`` URL.

.. note::
   The snippets are used in conjunction with the templates of the site. They rely on an unique key to determine where they should be rendered, if they are not implemented in the templates they are unusable.


Editing existing Snippets
-------------------------

The following fields are available to create Snippets:

- Name: Required. Name of the snippet.
- Status: Required. Publication status of the snippet.
- Slug: Required. Keyword used to render this snippet of content.
- Body: Optional. HTML content of the snippet.
- URL: Optional. URL to link the snippet.
- URL text: Optional. Text to be used in conjunction with the URL
- Image: Optional. Image to acompany the content.

.. image:: ../snapshots/admin--snippets--snippet--add.png
   :width: 100%


Snippet: profile-welcome
------------------------

Text only used to welcome users when they login and access their profiles.

.. image:: ../snapshots/dashboard.png
   :width: 100%



Snippet: blog-sidebar
---------------------

Featured box in the right handside of the blog to list featured content.

.. image:: ../snapshots/blog.png
   :width: 100%


Snippet: welcome-email
----------------------

Text used to send the welcome email to the users.


Snippet: home-box
-----------------

Featured snippet for the box above the fold in the homepage.

.. image:: ../snapshots/home.png
   :width: 100%

Snippet: featured
-----------------

Featured snippet for the orange box in the homepage next to: developers, partners and community leaders.

.. image:: ../snapshots/home.png
   :width: 100%


