# Accordion-descritption-product-with-metafield
Snippet for iterate across a metafield namespace and create an accordion in the product page (Shopify)

### Usage

Add jquery if needed

For example before closest head tag :

```
.....
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script> 
</head>
```

Include the liquid snippet where you want accordion, for example :

```
<div class="product-single__description rte">
  {{ product.description }}
  {% include 'product-details-metafield' %}
</div>
```
