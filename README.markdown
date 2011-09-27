Installation
------------

Double click the .clips file to install into Panic Coda.

Cheat Sheet
-----------

The Basics
==========

``tv + TAB`` -> template variable (``{{ ... }}``)

``# + TAB`` -> inline comment (``{# ... #}``)

``tt + TAB`` -> custom template tag (``{% ... %}``)

Default Django Template Tags
============================

<table>
    <tr>
        <td>``autoescape + TAB``</td>
        <td>autoescape off</td>
        <td>``{% autoescape off %} ... {% endautoescape %}``</td>
    </tr>
    <tr>
        <td>``comment + TAB``</td>
        <td>multiline comment</td>
        <td>``{% comment %} ... {% endcomment %}``</td>
    </tr>
    <tr>
        <td>``block + TAB``</td>
        <td>block</td>
        <td>``{% block ￼ %} ... {% endblock %}``</td>
    </tr>
    <tr>
        <td>``cache + TAB``</td>
        <td>cache</td>
        <td>``{% cache ￼ %} ... {% endcache %}``</td>
    </tr>
    <tr>
        <td>csrf + TAB</td>
        <td>csrf token</td>
        <td>``{% csrf_token %}``</td>
    </tr>
</table>