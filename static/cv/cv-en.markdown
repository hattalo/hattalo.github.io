---
title: Curriculum vit\u000e6
description: Curriculum Vitae
layout: cv
candidate: bruno
language: en
permalink: /cv/bruno
footer: v.2019-11-16
details_mobile: +49 170 783-0002
details_email: bruno.samueli@pm.me
details_work_eligibility : <em>Freiberufler</em>
details_availability : immediate
tags: [ cv, resume, bruno ]
---
<div class="betweenTablesTall">&#xa0;{{ page.language }}</div>
<div class="content content-table">
    <table id="details" class="pure-table pure-table-bordered cord-cv-table">
        <tbody>
            <tr class="startEntry">
                <td class="title-cell">Mobile</td>
                <td>{% assign lastidx = page.details_mobile.size | minus: 1 %}{% for i in (0..lastidx) %}{% assign c = page.details_mobile | slice: i %}{% if c == '+' or  c == '-' or  c == ' ' %}{{ c }}{% else %}{{ c | prepend: '&#x3' | append: ';' }}{% endif %}{% endfor %}</td>
                <td>&#xa0;</td>
                <td class="title-cell">E-mail</td>
                <td>{{ page.details_email }}</td>
                <td>&#xa0;</td>
                <td class="title-cell">Work Eligibility</td>
                <td>{{ page.details_work_eligibility }} {{ details_work_eligibility }}</td>
                <td>&#xa0;</td>
                <td class="title-cell">Availability</td>
                <td>{{ page.details_availability }}</td>
            </tr>
        </tbody>
    </table>

    <h4 id="role-sought">{{ site.data.cv_en.target_role.title }}: {{ site.data.cv_en.target_role.text }} - {{ author.name }} {{ page.time | date_to_xmlschema }}</h4>
</div>