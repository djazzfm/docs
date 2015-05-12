API Provider
============

Like ajax, rest, xml-rpc, etc ...


Permissions
===========

The permission system need to be more complex than a simple perms code
(eg. can_edit, can_create, can_delete).
For a post like a blog post, a basic authenticated user who can create a
post can edit only his own posts if he is not an editor or administrator.
Plus, a user which can create and / or edit a blog post can be not 
allowed to create a wiki page.
