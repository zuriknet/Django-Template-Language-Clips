Installation
------------

Double click the .clips file to install into Panic Coda.

Cheat Sheet
-----------

The Basics
==========

<table>
    <tr>
        <th scope="col">Trigger</th>
        <th scope="col">Name</th>
        <th scope="col">Code</th>
    </tr>
    <tr>
        <td><kbd>tv + TAB</kbd></td>
        <td>template variable</td>
        <td><code>{{ ... }}</code></td>
    </tr>
    <tr>
        <td><kbd># + TAB</kbd></td>
        <td>inline comment</td>
        <td><code>{# ... #}</code></td>
    </tr>
    <tr>
        <td><kbd>tt + TAB</kbd></td>
        <td>custom template tag</td>
        <td><code>{% ... %}</code></td>
    </tr>
</table>

Default Django Template Tags
============================

<table>
    <tr>
        <th scope="col">Trigger</th>
        <th scope="col">Name</th>
        <th scope="col">Code</th>
    </tr>
    <tr>
        <td><kbd>autoescape + TAB</kbd></td>
        <td>autoescape off</td>
        <td><code>{% autoescape off %} <i><foo></i> {% endautoescape %}</code></td>
    </tr>
    <tr>
        <td><kbd>comment + TAB</kbd></td>
        <td>multiline comment</td>
        <td><code>{% comment %} <i><foo></i> {% endcomment %}</code></td>
    </tr>
    <tr>
        <td><kbd>block + TAB</kbd></td>
        <td>block</td>
        <td><code>{% block <i><foo></i>￼ %} ... {% endblock %}</code></td>
    </tr>
    <tr>
        <td><kbd>cache + TAB</kbd></td>
        <td>cache</td>
        <td><code>{% cache ￼<i><foo></i> %} ... {% endcache %}</code></td>
    </tr>
    <tr>
        <td><kbd>csrf + TAB</kbd></td>
        <td>csrf token</td>
        <td><code>{% csrf_token %}</code></td>
    </tr>
    <tr>
        <td><kbd>cycle + TAB</kbd></td>
        <td>cycle</td>
        <td><code>{% cycle %}</code></td>
    </tr>
    <tr>
        <td><kbd>debug + TAB</kbd></td>
        <td>debug</td>
        <td><code>{% debug %}</code></td>
    </tr>
    <tr>
        <td><kbd>else + TAB</kbd></td>
        <td>else</td>
        <td><code>{% else %}</code></td>
    </tr>
    <tr>
        <td><kbd>empty + TAB</kbd></td>
        <td>empty</td>
        <td><code>{% empty %}</code></td>
    </tr>
    <tr>
        <td><kbd>endblock + TAB</kbd></td>
        <td>endblock</td>
        <td><code>{% endblock %}</code></td>
    </tr>
    <tr>
        <td><kbd>endfor + TAB</kbd></td>
        <td>endfor</td>
        <td><code>{% endfor %}</code></td>
    </tr>
    <tr>
        <td><kbd>endif + TAB</kbd></td>
        <td>endif</td>
        <td><code>{% endif %}</code></td>
    </tr>
    <tr>
        <td><kbd>extends + TAB</kbd></td>
        <td>extends</td>
        <td><code>{% extends "￼<i><foo></i>.html" %}</code></td>
    </tr>
    <tr>
        <td><kbd>filter + TAB</kbd></td>
        <td>filter</td>
        <td><code>{% filter <i><foo></i>￼ %} ... {% endfilter %}</code></td>
    </tr>
    <tr>
        <td><kbd>firstof + TAB</kbd></td>
        <td>firstof</td>
        <td><code>{% firstof ￼<i><foo></i>￼ %}</code></td>
    </tr>
    <tr>
        <td><kbd>for + TAB</kbd></td>
        <td>for</td>
        <td><code>{% for ￼<i><foo></i>￼ %} ... {% endfor %}</code></td>
    </tr>
    <tr>
        <td><kbd>forempty + TAB</kbd></td>
        <td>for ... empty</td>
        <td><code>{% for ￼<i><foo></i>￼ %} ... {% empty %} ... {% endfor %}</code></td>
    </tr>
    <tr>
        <td><kbd>if + TAB</kbd></td>
        <td>if</td>
        <td><code>{% if <i><foo></i>￼￼ %} ... {% endif %}</code></td>
    </tr>
    <tr>
        <td><kbd>ifelse + TAB</kbd></td>
        <td>if ... else</td>
        <td><code>{% if <i><foo></i>￼￼￼ %} ... {% else %} ... {% endif %}</code></td>
    </tr>
    <tr>
        <td><kbd>ifchanged + TAB</kbd></td>
        <td>ifchanged</td>
        <td><code>{% ifchanged %} ￼... {% endifchanged %}</code></td>
    </tr>
    <tr>
        <td><kbd>ifequal + TAB</kbd></td>
        <td>ifequal</td>
        <td><code>{% ifequal <i><foo></i>￼￼￼￼ %} ... {% endifequal %}</code></td>
    </tr>
    <tr>
        <td><kbd></kbd></td>
        <td></td>
        <td><code></code></td>
    </tr>
    <tr>
        <td><kbd></kbd></td>
        <td></td>
        <td><code></code></td>
    </tr>
    <tr>
        <td><kbd></kbd></td>
        <td></td>
        <td><code></code></td>
    </tr>
</table>