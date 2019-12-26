---
---
[Предисловие](uroki_intro.php.htm)
<ol>
    [Google](http://google.com)
    <li><a href="uroki_intro.php.htm">Предисловие</a></li>
{% for i in (0..31) %}{{ c | prepend: '<li><a href="urok_' | append: '.php.htm">Урок ' }}{{ c | append: '</a></li>'}}{% endfor %}
    <li><a href="urok_ER.php.htm">Эрзянь-рузонь валкске</a></li>
    <li><a href="urok_RE.php.htm">Русско-эрзянский словарь</a></li>
</ol>