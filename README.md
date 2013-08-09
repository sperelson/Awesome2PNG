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

I threw this class together over a few hours during a holiday. You should add caching if you want to incorporate 
it into any systems.
