---
layout: tr
title: İletişim
permalink: /tr/iletisim/
---

<div class="innerContent">
    <h4>İletişim</h4>
    <table>
        <thead></thead>
        <tbody>
        {% for item in site.data.contact.list %}
        <tr>
            <td>
                <a target="_blank" href="{{item.href}}">
                {% if item.icontype == 'logo' %}
                    <i style="color:#{{item.color}}" class="{{item.icon}}"></i>
                {% else %}
                    <img style="width:18px" src="/assets/images/{{item.icon}}"/>
                {% endif %}
                &nbsp;&nbsp;&nbsp;
                {{item.name}}
                </a>
            </td>
        </tr>
        {% endfor %}
        </tbody>
    </table>
</div>