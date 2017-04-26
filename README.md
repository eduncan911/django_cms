Django CMS 2.0
==============

A Django app for managing hierarchical pages of content in multiple languages, on different sites.

Django CMS handles the navigation rendering for you in multiple languages with internationalization (i18n) slugs,
and the navigation can be extended by your own models.

Pages are rendered with a template that has placeholders which get filled via plugins.
Plugins included at the moment include the following:

* Text
* Picture
* Flash
* File
* Links
* HTML Snippets

Many more are in the works.  Plugins are very easy to write and integrate with your own models.  

Screenshots
-----------

![alt text](http://github.com/digi604/django-cms-2.0/raw/master/cms/docs/screen3.png "Tree / List view")

The tree view supports full drag and drop and only shows the nodes for which you have sufficient permissions.
A traditional list view is shown instead if search or filters are activated.

![alt text](http://github.com/digi604/django-cms-2.0/raw/master/cms/docs/screen1.png "Edit view")

The edit page view. "Right-Column" and "Body" are placeholders in the default template.
If a different template were chosen, its corresponding placeholders would appear instead.

![alt text](http://github.com/digi604/django-cms-2.0/raw/master/cms/docs/screen2.png "Plugin Editor with Textplugin")

If you select a plugin you can edit it. The text plugin has the unique
capability that you can place plugins directly into the text flow. So links
inserted with the link plugin stay up-to-date even if pages are moved in the
tree and the URLs change.

Documentation and Help
----------------------


You can see the very latest documentation in the docs directory of the cms app [here](http://github.com/digi604/django-cms-2.0/tree/master/cms/docs).  Installation instructions are in the installation.md file.  Note that the
documentation is written with [Markdown](http://en.wikipedia.org/wiki/Markdown).  If
you view the files through github, they will be formatted fairly well.  Various tools are available
for converting Markdown to HTML if you wish to edit the docs, including the
[original markdown program](http://daringfireball.net/projects/markdown/) (written in Perl) and
[python-markdown](http://www.freewisdom.org/projects/python-markdown/).

You can also visit the project website at [django-cms.org](http://www.django-cms.org/)
or #django-cms on freenet IRC for more info.

For a feature comparison of all the CMS apps available for django see
[CMSComparison](http://code.djangoproject.com/wiki/CMSAppsComparison).

This is a fork of django-page-cms.
Some icons are from [http://www.famfamfam.com](http://www.famfamfam.com/)
