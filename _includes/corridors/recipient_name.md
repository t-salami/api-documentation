{% if include.recipient_type == 'business' %}
  {% capture recipient_name %}"name": "Company name"{% endcapture %}
{% elsif include.recipient_type == 'individual' %}
  {% capture recipient_name %}"first_name": "First",
  "last_name": "Last"{% endcapture %}
{% endif %}
