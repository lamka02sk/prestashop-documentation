Class CartControllerCore
=====================





* Class name: CartControllerCore
* Parent class: [FrontController](class.FrontControllerCore.md)
* Source: [controllers/front/CartController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L27)


Contents
--------


### Properties

* [$ajax_refresh](#property-$ajax_refresh)
* [$customization_id](#property-$customization_id)
* [$id_address_delivery](#property-$id_address_delivery)
* [$id_product](#property-$id_product)
* [$id_product_attribute](#property-$id_product_attribute)
* [$php_self](#property-$php_self)
* [$qty](#property-$qty)
* [$ssl](#property-$ssl)
* [$auth](#property-$auth)
* [$authRedirection](#property-$authRedirection)
* [$cart](#property-$cart)
* [$cookie](#property-$cookie)
* [$currentCustomerGroups](#property-$currentCustomerGroups)
* [$display_column_left](#property-$display_column_left)
* [$display_column_right](#property-$display_column_right)
* [$errors](#property-$errors)
* [$guestAllowed](#property-$guestAllowed)
* [$initialized](#property-$initialized)
* [$iso](#property-$iso)
* [$link](#property-$link)
* [$maintenance](#property-$maintenance)
* [$n](#property-$n)
* [$nb_items_per_page](#property-$nb_items_per_page)
* [$orderBy](#property-$orderBy)
* [$orderWay](#property-$orderWay)
* [$p](#property-$p)
* [$restrictedCountry](#property-$restrictedCountry)
* [$smarty](#property-$smarty)
* [$ajax](#property-$ajax)
* [$content_only](#property-$content_only)
* [$context](#property-$context)
* [$controller_type](#property-$controller_type)
* [$css_files](#property-$css_files)
* [$display_footer](#property-$display_footer)
* [$display_header](#property-$display_header)
* [$js_files](#property-$js_files)
* [$json](#property-$json)
* [$php_errors](#property-$php_errors)
* [$redirect_after](#property-$redirect_after)
* [$status](#property-$status)
* [$template](#property-$template)

### Methods

* [__construct](#method-__construct)
* [addCSS](#method-addCSS)
* [addColorsToProductList](#method-addColorsToProductList)
* [addJS](#method-addJS)
* [addJquery](#method-addJquery)
* [addJqueryPlugin](#method-addJqueryPlugin)
* [addJqueryUI](#method-addJqueryUI)
* [addMedia](#method-addMedia)
* [canonicalRedirection](#method-canonicalRedirection)
* [checkAccess](#method-checkAccess)
* [checkLiveEditAccess](#method-checkLiveEditAccess)
* [display](#method-display)
* [displayAjax](#method-displayAjax)
* [displayContent](#method-displayContent)
* [displayFooter](#method-displayFooter)
* [displayHeader](#method-displayHeader)
* [displayMaintenancePage](#method-displayMaintenancePage)
* [displayRestrictedCountryPage](#method-displayRestrictedCountryPage)
* [geolocationManagement](#method-geolocationManagement)
* [getColorsListCacheId](#method-getColorsListCacheId)
* [getController](#method-getController)
* [getCurrentCustomerGroups](#method-getCurrentCustomerGroups)
* [getLayout](#method-getLayout)
* [getLiveEditFooter](#method-getLiveEditFooter)
* [getOverrideTemplate](#method-getOverrideTemplate)
* [getOverrideThemeDir](#method-getOverrideThemeDir)
* [getTemplatePath](#method-getTemplatePath)
* [getThemeDir](#method-getThemeDir)
* [init](#method-init)
* [initContent](#method-initContent)
* [initCursedPage](#method-initCursedPage)
* [initFooter](#method-initFooter)
* [initHeader](#method-initHeader)
* [initLogoAndFavicon](#method-initLogoAndFavicon)
* [isCached](#method-isCached)
* [isInWhitelistForGeolocation](#method-isInWhitelistForGeolocation)
* [isTokenValid](#method-isTokenValid)
* [isXmlHttpRequest](#method-isXmlHttpRequest)
* [myErrorHandler](#method-myErrorHandler)
* [pagination](#method-pagination)
* [postProcess](#method-postProcess)
* [process](#method-process)
* [processAllowSeperatedPackage](#method-processAllowSeperatedPackage)
* [processChangeProductAddressDelivery](#method-processChangeProductAddressDelivery)
* [processChangeProductInCart](#method-processChangeProductInCart)
* [processDeleteProductInCart](#method-processDeleteProductInCart)
* [processDuplicateProduct](#method-processDuplicateProduct)
* [processRemoveDiscounts](#method-processRemoveDiscounts)
* [productSort](#method-productSort)
* [recoverCart](#method-recoverCart)
* [redirect](#method-redirect)
* [removeCSS](#method-removeCSS)
* [removeJS](#method-removeJS)
* [removeMedia](#method-removeMedia)
* [run](#method-run)
* [setMedia](#method-setMedia)
* [setMobileMedia](#method-setMobileMedia)
* [setMobileTemplate](#method-setMobileTemplate)
* [setTemplate](#method-setTemplate)
* [smartyOutputContent](#method-smartyOutputContent)
* [useMobileTheme](#method-useMobileTheme)
* [viewAccess](#method-viewAccess)




Properties
----------


### <a name="property-$ajax_refresh"></a>$ajax_refresh

```php
protected mixed $ajax_refresh = false
```





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L38).


### <a name="property-$customization_id"></a>$customization_id

```php
protected mixed $customization_id
```





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L34).


### <a name="property-$id_address_delivery"></a>$id_address_delivery

```php
protected mixed $id_address_delivery
```





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L33).


### <a name="property-$id_product"></a>$id_product

```php
protected mixed $id_product
```





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L31).


### <a name="property-$id_product_attribute"></a>$id_product_attribute

```php
protected mixed $id_product_attribute
```





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L32).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self = 'cart'
```





* Visibility: **public**
* Source: [controllers/front/CartController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L29).


### <a name="property-$qty"></a>$qty

```php
protected mixed $qty
```





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L35).


### <a name="property-$ssl"></a>$ssl

```php
public mixed $ssl = true
```





* Visibility: **public**
* Source: [controllers/front/CartController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L36).


### <a name="property-$auth"></a>$auth

```php
public mixed $auth = false
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L43).


### <a name="property-$authRedirection"></a>$authRedirection

```php
public mixed $authRedirection = false
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L45).


### <a name="property-$cart"></a>$cart

```php
protected mixed $cart
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L34).


### <a name="property-$cookie"></a>$cookie

```php
protected mixed $cookie
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L34).


### <a name="property-$currentCustomerGroups"></a>$currentCustomerGroups

```php
protected mixed $currentCustomerGroups
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L56).


### <a name="property-$display_column_left"></a>$display_column_left

```php
public mixed $display_column_left = true
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L51).


### <a name="property-$display_column_right"></a>$display_column_right

```php
public mixed $display_column_right = true
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L52).


### <a name="property-$errors"></a>$errors

```php
public mixed $errors = array()
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L29).


### <a name="property-$guestAllowed"></a>$guestAllowed

```php
public mixed $guestAllowed = false
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L44).


### <a name="property-$initialized"></a>$initialized

```php
public mixed $initialized = false
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L54).


### <a name="property-$iso"></a>$iso

```php
public mixed $iso
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L36).


### <a name="property-$link"></a>$link

```php
protected mixed $link
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L34).


### <a name="property-$maintenance"></a>$maintenance

```php
protected mixed $maintenance = false
```





* Visibility: **protected**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L49).


### <a name="property-$n"></a>$n

```php
public mixed $n
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L41).


### <a name="property-$nb_items_per_page"></a>$nb_items_per_page

```php
public mixed $nb_items_per_page
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L58).


### <a name="property-$orderBy"></a>$orderBy

```php
public mixed $orderBy
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L38).


### <a name="property-$orderWay"></a>$orderWay

```php
public mixed $orderWay
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L39).


### <a name="property-$p"></a>$p

```php
public mixed $p
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L40).


### <a name="property-$restrictedCountry"></a>$restrictedCountry

```php
protected mixed $restrictedCountry = false
```





* Visibility: **protected**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L48).


### <a name="property-$smarty"></a>$smarty

```php
protected mixed $smarty
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L34).


### <a name="property-$ajax"></a>$ajax

```php
public boolean $ajax = false
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L75).


### <a name="property-$content_only"></a>$content_only

```php
protected string $content_only = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L70).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L35).


### <a name="property-$controller_type"></a>$controller_type

```php
public mixed $controller_type
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L81).


### <a name="property-$css_files"></a>$css_files

```php
public array $css_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L40).


### <a name="property-$display_footer"></a>$display_footer

```php
protected string $display_footer
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L65).


### <a name="property-$display_header"></a>$display_header

```php
protected boolean $display_header
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L55).


### <a name="property-$js_files"></a>$js_files

```php
public array $js_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L45).


### <a name="property-$json"></a>$json

```php
protected mixed $json = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L76).


### <a name="property-$php_errors"></a>$php_errors

```php
public array $php_errors = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L50).


### <a name="property-$redirect_after"></a>$redirect_after

```php
protected mixed $redirect_after = null
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L79).


### <a name="property-$status"></a>$status

```php
protected mixed $status = ''
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L77).


### <a name="property-$template"></a>$template

```php
protected string $template
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L60).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed FrontControllerCore::__construct()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L60)




### <a name="method-addCSS"></a>addCSS

```php
mixed FrontControllerCore::addCSS($css_uri, $css_media_type, $offset)
```

Add one or several CSS for front, checking if css files are overriden in theme/css/modules/ directory



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1053](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L1053)


#### Arguments
* $css_uri **mixed**
* $css_media_type **mixed**
* $offset **mixed**



### <a name="method-addColorsToProductList"></a>addColorsToProductList

```php
mixed FrontControllerCore::addColorsToProductList($products)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1270](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L1270)


#### Arguments
* $products **mixed**



### <a name="method-addJS"></a>addJS

```php
mixed FrontControllerCore::addJS($js_uri)
```

Add one or several JS files for front, checking if js files are overriden in theme/js/modules/ directory



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1068](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L1068)


#### Arguments
* $js_uri **mixed**



### <a name="method-addJquery"></a>addJquery

```php
void ControllerCore::addJquery($version, $folder, $minifier)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 336](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L336)


#### Arguments
* $version **mixed**
* $folder **mixed**
* $minifier **mixed**



### <a name="method-addJqueryPlugin"></a>addJqueryPlugin

```php
mixed ControllerCore::addJqueryPlugin($name, null $folder, boolean $css)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 368](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L368)


#### Arguments
* $name **mixed**
* $folder **null**
* $css **boolean**



### <a name="method-addJqueryUI"></a>addJqueryUI

```php
void ControllerCore::addJqueryUI($component, $theme, $check_dependencies)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 347](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L347)


#### Arguments
* $component **mixed**
* $theme **mixed**
* $check_dependencies **mixed**



### <a name="method-addMedia"></a>addMedia

```php
mixed FrontControllerCore::addMedia($media_uri, $css_media_type, $offset, $remove)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 990](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L990)


#### Arguments
* $media_uri **mixed**
* $css_media_type **mixed**
* $offset **mixed**
* $remove **mixed**



### <a name="method-canonicalRedirection"></a>canonicalRedirection

```php
mixed CartControllerCore::canonicalRedirection($canonicalURL)
```

This is not a public page, so the canonical redirection is disabled



* Visibility: **public**
* Source: [controllers/front/CartController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L43)


#### Arguments
* $canonicalURL **mixed**



### <a name="method-checkAccess"></a>checkAccess

```php
boolean FrontControllerCore::checkAccess()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L93)




### <a name="method-checkLiveEditAccess"></a>checkLiveEditAccess

```php
mixed FrontControllerCore::checkLiveEditAccess()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 826](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L826)




### <a name="method-display"></a>display

```php
mixed FrontControllerCore::display()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 525](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L525)




### <a name="method-displayAjax"></a>displayAjax

```php
mixed CartControllerCore::displayAjax()
```

Display ajax content (this function is called instead of classic display, in ajax mode)



* Visibility: **public**
* Source: [controllers/front/CartController.php line 317](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L317)




### <a name="method-displayContent"></a>displayContent

```php
mixed FrontControllerCore::displayContent()
```

1.4 retrocompatibility



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 521](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L521)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed FrontControllerCore::displayFooter($display)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 498](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L498)


#### Arguments
* $display **mixed**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed FrontControllerCore::displayHeader($display)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 460](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L460)


#### Arguments
* $display **mixed**



### <a name="method-displayMaintenancePage"></a>displayMaintenancePage

```php
mixed FrontControllerCore::displayMaintenancePage()
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 583](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L583)




### <a name="method-displayRestrictedCountryPage"></a>displayRestrictedCountryPage

```php
mixed FrontControllerCore::displayRestrictedCountryPage()
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 604](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L604)




### <a name="method-geolocationManagement"></a>geolocationManagement

```php
mixed FrontControllerCore::geolocationManagement($default_country)
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 658](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L658)


#### Arguments
* $default_country **mixed**



### <a name="method-getColorsListCacheId"></a>getColorsListCacheId

```php
mixed FrontControllerCore::getColorsListCacheId($id_product)
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1307](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L1307)


#### Arguments
* $id_product **mixed**



### <a name="method-getController"></a>getController

```php
mixed ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)
```

Get an instance of a controller



* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L133)


#### Arguments
* $class_name **string**
* $auth **boolean**
* $ssl **boolean**



### <a name="method-getCurrentCustomerGroups"></a>getCurrentCustomerGroups

```php
mixed FrontControllerCore::getCurrentCustomerGroups()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 939](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L939)




### <a name="method-getLayout"></a>getLayout

```php
boolean|string FrontControllerCore::getLayout()
```

Returns the layout corresponding to the current page by using the override system
Ex:
On the url: http://localhost/index.php?id_product=1&controller=product, this method will
check if the layout exists in the following files (in that order), and return the first found:
- /themes/default/override/layout-product-1.tpl
- /themes/default/override/layout-product.tpl
- /themes/default/layout.tpl



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1169](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L1169)




### <a name="method-getLiveEditFooter"></a>getLiveEditFooter

```php
mixed FrontControllerCore::getLiveEditFooter()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 835](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L835)




### <a name="method-getOverrideTemplate"></a>getOverrideTemplate

```php
boolean FrontControllerCore::getOverrideTemplate()
```

Returns the template corresponding to the current page.

By default this method return false but could easily be overridden in a specific controller

* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L1131)




### <a name="method-getOverrideThemeDir"></a>getOverrideThemeDir

```php
mixed FrontControllerCore::getOverrideThemeDir()
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1152](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L1152)




### <a name="method-getTemplatePath"></a>getTemplatePath

```php
mixed FrontControllerCore::getTemplatePath($template)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1192](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L1192)


#### Arguments
* $template **mixed**



### <a name="method-getThemeDir"></a>getThemeDir

```php
mixed FrontControllerCore::getThemeDir()
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L1147)




### <a name="method-init"></a>init

```php
mixed CartControllerCore::init()
```

Initialize cart controller



* Visibility: **public**
* Source: [controllers/front/CartController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L51)




### <a name="method-initContent"></a>initContent

```php
mixed CartControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/front/CartController.php line 307](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L307)




### <a name="method-initCursedPage"></a>initCursedPage

```php
mixed FrontControllerCore::initCursedPage()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 504](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L504)




### <a name="method-initFooter"></a>initFooter

```php
mixed FrontControllerCore::initFooter()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 806](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L806)




### <a name="method-initHeader"></a>initHeader

```php
mixed FrontControllerCore::initHeader()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 788](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L788)




### <a name="method-initLogoAndFavicon"></a>initLogoAndFavicon

```php
array FrontControllerCore::initLogoAndFavicon()
```

Return an array with specific logo and favicon,
if mobile device



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1253](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L1253)




### <a name="method-isCached"></a>isCached

```php
mixed ControllerCore::isCached($template, $cacheId, $compileId)
```





* Visibility: **protected**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 436](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L436)


#### Arguments
* $template **mixed**
* $cacheId **mixed**
* $compileId **mixed**



### <a name="method-isInWhitelistForGeolocation"></a>isInWhitelistForGeolocation

```php
mixed FrontControllerCore::isInWhitelistForGeolocation()
```





* Visibility: **protected**
* This method is **static**.
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 958](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L958)




### <a name="method-isTokenValid"></a>isTokenValid

```php
boolean FrontControllerCore::isTokenValid()
```

Check if token is valid



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 982](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L982)




### <a name="method-isXmlHttpRequest"></a>isXmlHttpRequest

```php
boolean ControllerCore::isXmlHttpRequest()
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 390](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L390)




### <a name="method-myErrorHandler"></a>myErrorHandler

```php
mixed ControllerCore::myErrorHandler($errno, $errstr, $errfile, $errline)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 444](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L444)


#### Arguments
* $errno **mixed**
* $errstr **mixed**
* $errfile **mixed**
* $errline **mixed**



### <a name="method-pagination"></a>pagination

```php
mixed FrontControllerCore::pagination($total_products)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 879](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L879)


#### Arguments
* $total_products **mixed**



### <a name="method-postProcess"></a>postProcess

```php
mixed CartControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/front/CartController.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L66)




### <a name="method-process"></a>process

```php
mixed FrontControllerCore::process()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 509](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L509)




### <a name="method-processAllowSeperatedPackage"></a>processAllowSeperatedPackage

```php
mixed CartControllerCore::processAllowSeperatedPackage()
```





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L146)




### <a name="method-processChangeProductAddressDelivery"></a>processChangeProductAddressDelivery

```php
mixed CartControllerCore::processChangeProductAddressDelivery()
```





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L125)




### <a name="method-processChangeProductInCart"></a>processChangeProductInCart

```php
mixed CartControllerCore::processChangeProductInCart()
```

This process add or update a product in the cart



* Visibility: **protected**
* Source: [controllers/front/CartController.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L180)




### <a name="method-processDeleteProductInCart"></a>processDeleteProductInCart

```php
mixed CartControllerCore::processDeleteProductInCart()
```

This process delete a product from the cart



* Visibility: **protected**
* Source: [controllers/front/CartController.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L107)




### <a name="method-processDuplicateProduct"></a>processDuplicateProduct

```php
mixed CartControllerCore::processDuplicateProduct()
```





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L159)




### <a name="method-processRemoveDiscounts"></a>processRemoveDiscounts

```php
mixed CartControllerCore::processRemoveDiscounts()
```

Remove discounts on cart



* Visibility: **protected**
* Source: [controllers/front/CartController.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/controllers/front/CartController.php#L298)




### <a name="method-productSort"></a>productSort

```php
mixed FrontControllerCore::productSort()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 852](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L852)




### <a name="method-recoverCart"></a>recoverCart

```php
mixed FrontControllerCore::recoverCart()
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1078](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L1078)




### <a name="method-redirect"></a>redirect

```php
mixed FrontControllerCore::redirect()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 513](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L513)




### <a name="method-removeCSS"></a>removeCSS

```php
mixed FrontControllerCore::removeCSS($css_uri, $css_media_type)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1058](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L1058)


#### Arguments
* $css_uri **mixed**
* $css_media_type **mixed**



### <a name="method-removeJS"></a>removeJS

```php
mixed FrontControllerCore::removeJS($js_uri)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1073](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L1073)


#### Arguments
* $js_uri **mixed**



### <a name="method-removeMedia"></a>removeMedia

```php
mixed FrontControllerCore::removeMedia($media_uri, $css_media_type)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1043](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L1043)


#### Arguments
* $media_uri **mixed**
* $css_media_type **mixed**



### <a name="method-run"></a>run

```php
mixed ControllerCore::run()
```

Start controller process (this method shouldn't be overriden !)



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L161)




### <a name="method-setMedia"></a>setMedia

```php
mixed FrontControllerCore::setMedia()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 743](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L743)




### <a name="method-setMobileMedia"></a>setMobileMedia

```php
mixed FrontControllerCore::setMobileMedia()
```

Specific medias for mobile device.

if autoload directory is present in the mobile theme, these files will not be loaded

* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 722](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L722)




### <a name="method-setMobileTemplate"></a>setMobileTemplate

```php
mixed FrontControllerCore::setMobileTemplate($template)
```

This checks if the template set is available for mobile themes,
otherwise the front template is choosen.



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1218](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L1218)


#### Arguments
* $template **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed FrontControllerCore::setTemplate($default_template)
```

This is overrided to manage is behaviour
if a customer access to the site with mobile device.



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1110](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L1110)


#### Arguments
* $default_template **mixed**



### <a name="method-smartyOutputContent"></a>smartyOutputContent

```php
mixed ControllerCore::smartyOutputContent($content)
```





* Visibility: **protected**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/Controller.php#L395)


#### Arguments
* $content **mixed**



### <a name="method-useMobileTheme"></a>useMobileTheme

```php
mixed FrontControllerCore::useMobileTheme()
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 1136](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L1136)




### <a name="method-viewAccess"></a>viewAccess

```php
boolean FrontControllerCore::viewAccess()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/controller/FrontController.php#L103)



