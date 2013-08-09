Awesome2PNG
===========

Generate PNG glyphs from the Font Awesome TTF on the server using PHP.

Why
---

Generating glyphs from the vector source on the server is very useful when you want to support devices 
that do not have nice web browsers, such as low-end feature phones, but still want the power to generate 
a variety of glyph sizes and colours.

Background
----------

A colleague and I were talking and he mused about how nice it would be to have access to all the Font 
Awesome glyphs from within our feature phone portal sites. The conversation didn't last long, but the general 
idea for a server-side renderer was conceived.

I threw this class together over a few hours during a holiday. When I incorporate it into our larger system, I 
will modify it slightly to add caching to files. I wouldn't use this class without adding caching first.

It is definitely not finished in that you will have to modify it to make it fit into any projects.


