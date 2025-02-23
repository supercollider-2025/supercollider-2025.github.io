## {{title}}

**{{location}}**

{% if led_by|length > 1 %}
Led by:  
{% for item in led_by -%}
[{{ item }}](/bios/#{{ item|lower|replace(' ','-') }})  
{% endfor %}
{% else %}
Led by [{{ led_by[0] }}](/bios/#{{ led_by[0]|lower|replace(' ','-') }})
{% endif %}
{% if with_support_from is defined %}
With support from:  
{% for item in with_support_from -%}
[{{ item }}](/bios/#{{ item|lower|replace(' ','-') }})  
{% endfor %}
{% endif %}