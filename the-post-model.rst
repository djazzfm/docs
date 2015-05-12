The post model
==============

Functionalities
---------------

- multisite
- multilang
- short summary
- hierarchy
- typed
- formatted
- statufication

Fields
------

- title
- uid (slug, path, ... ?!)
- parent, prev, next (book ?!)
- author / owner
- date of post
- last editor
- date last edition
- sites (for multisite)
- content
- summary
- lang
- lid (language identifier)
- type / kind of post (article, page, wiki, ...)
- status (draft, published, protected, deleted, locked, ...)
- formatter (html, markdown, ...)

Post identifiers
----------------

A post can be identified by his id, title or uid.

- the title is not mandatory and not unique. It is usefull to identify 
  a blog article, or a book page
- the uid has to be unique through a same type and language.

Multi-language
--------------

Multilanguage is provided by the lang and lid fields :

- lang : locale, like en-us, fr-fr
- lid : provide a link between a same post for different languages.
        Must be unique for a given language.

Post format
-----------

Post model provide the "formatter" field. You can specify a formatter 
which will encode / decode your post content from / to html.

Post types
----------

Like blog_article, static_page, wiki, etc ...

Post status
-----------

Like published, closed, protected, etc ...

Post metas
==========

Meta datas are usefull when you want associate some datas to your post,
like keywords, category, or some specific post type metadatas.

For example, if your post type is a task, you can add a localisation, 
an owner, a due date, etc ...

- post
- key
- value

