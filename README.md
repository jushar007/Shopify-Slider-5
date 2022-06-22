# Shopify-Slider-5
Shopify dev slider free code

Go to this file

Layout > theme.liquid

Add this code in </head> tag above

{{ 'bootstrap.min.css' | asset_url | stylesheet_tag }}

add this code in </body> tag above

<script src="{{ 'bootstrap.bundle.min.js' | asset_url }}"></script><br>
<script src="{{ 'popper.min.js' | asset_url }}"></script><br>
<script src="{{ 'bootstrap.min.js' | asset_url }}"></script><br>
