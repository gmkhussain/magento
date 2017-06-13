# Magento 2

###How to change default homepage Magento2
```
Change home page under Stores > Configuration > General > Web > Default Pages > CMS Home Page
```

###Frontend templates location
```
vendor\magento\module-theme\view\frontend\templates\html
```

### Cache location
```
1. var\cache
2. var\page_cache
```

###  Template Path Hints in Magento2
```
Store > Configuration > Advanced > Developer > Debug > Enabled Template Path Hints for Storefront > Yes
```



###Head file location for CSS and JS files
```
vendor\magento\module-theme\view\frontend\layout\default_head_blocks.xml
```

### Magento2 theme header - Welcome message
```
/public_html/vendor/magento/module-customer/view/frontend/templates/account/customer.phtml
```

###Magento2 Page link Items
```
/public_html/vendor/magento/framework/View/Element/Html
```


### Magento2 contact page * messages / content
```
\vendor\magento\module-contact\view\frontend\templates\form.phtml
\vendor\magento\module-contact\i18n\en_US.csv
```



### Magento2 default contact form location
```
/public_html/vendor/magento/module-contact/view/frontend/templates
```

### Magento2 mini search form (on header)
```
/public_html/vendor/magento/module-search/view/frontend/templates/form.mini.phtml
```


##SM Marketing Magento2
###Template configuration location
```html
admin_secured/admin/system_config/edit/section/market/
```









# Magento 1.x
### Frontend templates location

#### CSS
```
/public_html/dev.essentialbeards.com/skin/frontend/xcelance/bearded
```


#### HTML
```
/public_html/dev.essentialbeards.com/app/design/frontend/xcelance/bearded/template/page
```

### Payment form Html location
```
/public_html/dev.essentialbeards.com/app/design/frontend/base/default/template/stripe/form
```


### Current Theme Skin Url
```
<?php $this->getSkinUrl('images/my-image.jpg'); ?>
```


### Email template location
```
app/locale/[language]/email/templates/account_new.html
```

### Order Email template location
```
/app/design/frontend/xcelance/bearded/template/email/order
```
