Class OrderControllerCore
=====================





* Class name: OrderControllerCore
* Parent class: [ParentOrderController](class.ParentOrderControllerCore.md)
* Source: [controllers/front/OrderController.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/OrderController.php#L28)


Contents
--------


### Properties

* [$step](#property-$step)
* [$nbProducts](#property-$nbProducts)
* [$php_self](#property-$php_self)
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
* [$redirect_after](#property-$redirect_after)
* [$status](#property-$status)
* [$template](#property-$template)

### Methods

* [__construct](#method-__construct)
* [_assignAddress](#method-_assignAddress)
* [_assignCarrier](#method-_assignCarrier)
* [_assignPayment](#method-_assignPayment)
* [_assignSummaryInformations](#method-_assignSummaryInformations)
* [_assignWrappingAndTOS](#method-_assignWrappingAndTOS)
* [_checkFreeOrder](#method-_checkFreeOrder)
* [_processCarrier](#method-_processCarrier)
* [_setDefaultCarrierSelection](#method-_setDefaultCarrierSelection)
* [_updateMessage](#method-_updateMessage)
* [addCSS](#method-addCSS)
* [addJS](#method-addJS)
* [addJquery](#method-addJquery)
* [addJqueryPlugin](#method-addJqueryPlugin)
* [addJqueryUI](#method-addJqueryUI)
* [autoStep](#method-autoStep)
* [canonicalRedirection](#method-canonicalRedirection)
* [checkAccess](#method-checkAccess)
* [display](#method-display)
* [displayContent](#method-displayContent)
* [displayFooter](#method-displayFooter)
* [displayHeader](#method-displayHeader)
* [displayMaintenancePage](#method-displayMaintenancePage)
* [displayRestrictedCountryPage](#method-displayRestrictedCountryPage)
* [geolocationManagement](#method-geolocationManagement)
* [getController](#method-getController)
* [getCurrentCustomerGroups](#method-getCurrentCustomerGroups)
* [getLayout](#method-getLayout)
* [getLiveEditFooter](#method-getLiveEditFooter)
* [getOverrideTemplate](#method-getOverrideTemplate)
* [init](#method-init)
* [initContent](#method-initContent)
* [initCursedPage](#method-initCursedPage)
* [initFooter](#method-initFooter)
* [initHeader](#method-initHeader)
* [isInWhitelistForGeolocation](#method-isInWhitelistForGeolocation)
* [isTokenValid](#method-isTokenValid)
* [isXmlHttpRequest](#method-isXmlHttpRequest)
* [pagination](#method-pagination)
* [postProcess](#method-postProcess)
* [preProcess](#method-preProcess)
* [process](#method-process)
* [processAddress](#method-processAddress)
* [processAddressFormat](#method-processAddressFormat)
* [processCarrier](#method-processCarrier)
* [productSort](#method-productSort)
* [recoverCart](#method-recoverCart)
* [redirect](#method-redirect)
* [run](#method-run)
* [setDefaultCarrierSelection](#method-setDefaultCarrierSelection)
* [setMedia](#method-setMedia)
* [setNoCarrier](#method-setNoCarrier)
* [setTemplate](#method-setTemplate)
* [validateDeliveryOption](#method-validateDeliveryOption)
* [viewAccess](#method-viewAccess)




Properties
----------


### <a name="property-$step"></a>$step

```php
public mixed $step
```





* Visibility: **public**
* Source: [controllers/front/OrderController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/OrderController.php#L30).


### <a name="property-$nbProducts"></a>$nbProducts

```php
public mixed $nbProducts
```





* Visibility: **public**
* This property is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/ParentOrderController.php#L41).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self = 'order'
```





* Visibility: **public**
* This property is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/ParentOrderController.php#L39).


### <a name="property-$ssl"></a>$ssl

```php
public mixed $ssl = true
```





* Visibility: **public**
* This property is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/ParentOrderController.php#L38).


### <a name="property-$auth"></a>$auth

```php
public mixed $auth = false
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L44).


### <a name="property-$authRedirection"></a>$authRedirection

```php
public mixed $authRedirection = false
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L46).


### <a name="property-$cart"></a>$cart

```php
protected mixed $cart
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L35).


### <a name="property-$cookie"></a>$cookie

```php
protected mixed $cookie
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L35).


### <a name="property-$currentCustomerGroups"></a>$currentCustomerGroups

```php
protected mixed $currentCustomerGroups
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L57).


### <a name="property-$display_column_left"></a>$display_column_left

```php
public mixed $display_column_left = true
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L52).


### <a name="property-$display_column_right"></a>$display_column_right

```php
public mixed $display_column_right = true
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L53).


### <a name="property-$errors"></a>$errors

```php
public mixed $errors = array()
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L30).


### <a name="property-$guestAllowed"></a>$guestAllowed

```php
public mixed $guestAllowed = false
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L45).


### <a name="property-$initialized"></a>$initialized

```php
public mixed $initialized = false
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L55).


### <a name="property-$iso"></a>$iso

```php
public mixed $iso
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L37).


### <a name="property-$link"></a>$link

```php
protected mixed $link
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L35).


### <a name="property-$maintenance"></a>$maintenance

```php
protected mixed $maintenance = false
```





* Visibility: **protected**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L50).


### <a name="property-$n"></a>$n

```php
public mixed $n
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L42).


### <a name="property-$nb_items_per_page"></a>$nb_items_per_page

```php
public mixed $nb_items_per_page
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L59).


### <a name="property-$orderBy"></a>$orderBy

```php
public mixed $orderBy
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L39).


### <a name="property-$orderWay"></a>$orderWay

```php
public mixed $orderWay
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L40).


### <a name="property-$p"></a>$p

```php
public mixed $p
```





* Visibility: **public**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L41).


### <a name="property-$restrictedCountry"></a>$restrictedCountry

```php
protected mixed $restrictedCountry = false
```





* Visibility: **protected**
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L49).


### <a name="property-$smarty"></a>$smarty

```php
protected mixed $smarty
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L35).


### <a name="property-$ajax"></a>$ajax

```php
public boolean $ajax = false
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L71).


### <a name="property-$content_only"></a>$content_only

```php
protected string $content_only = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L66).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L36).


### <a name="property-$controller_type"></a>$controller_type

```php
public mixed $controller_type
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L77).


### <a name="property-$css_files"></a>$css_files

```php
public array $css_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L41).


### <a name="property-$display_footer"></a>$display_footer

```php
protected string $display_footer
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L61).


### <a name="property-$display_header"></a>$display_header

```php
protected boolean $display_header
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L51).


### <a name="property-$js_files"></a>$js_files

```php
public array $js_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L46).


### <a name="property-$json"></a>$json

```php
protected mixed $json = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L72).


### <a name="property-$redirect_after"></a>$redirect_after

```php
protected mixed $redirect_after = null
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L75).


### <a name="property-$status"></a>$status

```php
protected mixed $status = ''
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L73).


### <a name="property-$template"></a>$template

```php
protected string $template
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L56).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed FrontControllerCore::__construct()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L61)




### <a name="method-_assignAddress"></a>_assignAddress

```php
mixed OrderControllerCore::_assignAddress()
```

Address step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 308](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/OrderController.php#L308)




### <a name="method-_assignCarrier"></a>_assignCarrier

```php
mixed OrderControllerCore::_assignCarrier()
```

Carrier step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/OrderController.php#L323)




### <a name="method-_assignPayment"></a>_assignPayment

```php
mixed OrderControllerCore::_assignPayment()
```

Payment step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 338](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/OrderController.php#L338)




### <a name="method-_assignSummaryInformations"></a>_assignSummaryInformations

```php
mixed ParentOrderControllerCore::_assignSummaryInformations()
```





* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 268](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/ParentOrderController.php#L268)




### <a name="method-_assignWrappingAndTOS"></a>_assignWrappingAndTOS

```php
mixed ParentOrderControllerCore::_assignWrappingAndTOS()
```





* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 432](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/ParentOrderController.php#L432)




### <a name="method-_checkFreeOrder"></a>_checkFreeOrder

```php
boolean ParentOrderControllerCore::_checkFreeOrder()
```

Check if order is free



* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/ParentOrderController.php#L156)




### <a name="method-_processCarrier"></a>_processCarrier

```php
mixed ParentOrderControllerCore::_processCarrier()
```





* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/ParentOrderController.php#L200)




### <a name="method-_setDefaultCarrierSelection"></a>_setDefaultCarrierSelection

```php
\number ParentOrderControllerCore::_setDefaultCarrierSelection(array $carriers)
```

Decides what the default carrier is and update the cart with it



* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 528](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/ParentOrderController.php#L528)


#### Arguments
* $carriers **array**



### <a name="method-_updateMessage"></a>_updateMessage

```php
mixed ParentOrderControllerCore::_updateMessage($messageContent)
```





* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/ParentOrderController.php#L168)


#### Arguments
* $messageContent **mixed**



### <a name="method-addCSS"></a>addCSS

```php
mixed FrontControllerCore::addCSS($css_uri, $css_media_type)
```

Add one or several CSS for front, checking if css files are overriden in theme/css/modules/ directory



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 887](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L887)


#### Arguments
* $css_uri **mixed**
* $css_media_type **mixed**



### <a name="method-addJS"></a>addJS

```php
mixed FrontControllerCore::addJS($js_uri)
```

Add one or several JS files for front, checking if js files are overriden in theme/js/modules/ directory



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 910](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L910)


#### Arguments
* $js_uri **mixed**



### <a name="method-addJquery"></a>addJquery

```php
void ControllerCore::addJquery($version, $folder, $minifier)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 292](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L292)


#### Arguments
* $version **mixed**
* $folder **mixed**
* $minifier **mixed**



### <a name="method-addJqueryPlugin"></a>addJqueryPlugin

```php
void ControllerCore::addJqueryPlugin($name, $folder)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L323)


#### Arguments
* $name **mixed**
* $folder **mixed**



### <a name="method-addJqueryUI"></a>addJqueryUI

```php
void ControllerCore::addJqueryUI($component, $theme, $check_dependencies)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L303)


#### Arguments
* $component **mixed**
* $theme **mixed**
* $check_dependencies **mixed**



### <a name="method-autoStep"></a>autoStep

```php
mixed OrderControllerCore::autoStep()
```

Order process controller



* Visibility: **public**
* Source: [controllers/front/OrderController.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/OrderController.php#L218)




### <a name="method-canonicalRedirection"></a>canonicalRedirection

```php
mixed FrontControllerCore::canonicalRedirection($canonical_url)
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 595](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L595)


#### Arguments
* $canonical_url **mixed**



### <a name="method-checkAccess"></a>checkAccess

```php
boolean FrontControllerCore::checkAccess()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L80)




### <a name="method-display"></a>display

```php
mixed FrontControllerCore::display()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 502](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L502)




### <a name="method-displayContent"></a>displayContent

```php
mixed FrontControllerCore::displayContent()
```

1.4 retrocompatibility - will be removed in 1.6



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 498](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L498)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed FrontControllerCore::displayFooter($display)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 470](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L470)


#### Arguments
* $display **mixed**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed FrontControllerCore::displayHeader($display)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 436](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L436)


#### Arguments
* $display **mixed**



### <a name="method-displayMaintenancePage"></a>displayMaintenancePage

```php
mixed FrontControllerCore::displayMaintenancePage()
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 571](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L571)




### <a name="method-displayRestrictedCountryPage"></a>displayRestrictedCountryPage

```php
mixed FrontControllerCore::displayRestrictedCountryPage()
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 587](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L587)




### <a name="method-geolocationManagement"></a>geolocationManagement

```php
mixed FrontControllerCore::geolocationManagement($default_country)
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 622](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L622)


#### Arguments
* $default_country **mixed**



### <a name="method-getController"></a>getController

```php
mixed ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)
```

Get an instance of a controller



* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L127)


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
* Source: [classes/controller/FrontController.php line 837](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L837)




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
* Source: [classes/controller/FrontController.php line 991](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L991)




### <a name="method-getLiveEditFooter"></a>getLiveEditFooter

```php
mixed FrontControllerCore::getLiveEditFooter()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 730](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L730)




### <a name="method-getOverrideTemplate"></a>getOverrideTemplate

```php
boolean FrontControllerCore::getOverrideTemplate()
```

Returns the template corresponding to the current page.

By default this method return false but could easily be overridden in a specific controller

* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 974](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L974)




### <a name="method-init"></a>init

```php
mixed OrderControllerCore::init()
```

Initialize order controller



* Visibility: **public**
* Source: [controllers/front/OrderController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/OrderController.php#L36)




### <a name="method-initContent"></a>initContent

```php
mixed FrontControllerCore::initContent()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 420](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L420)




### <a name="method-initCursedPage"></a>initCursedPage

```php
mixed FrontControllerCore::initCursedPage()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 481](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L481)




### <a name="method-initFooter"></a>initFooter

```php
mixed FrontControllerCore::initFooter()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 722](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L722)




### <a name="method-initHeader"></a>initHeader

```php
mixed FrontControllerCore::initHeader()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 702](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L702)




### <a name="method-isInWhitelistForGeolocation"></a>isInWhitelistForGeolocation

```php
mixed FrontControllerCore::isInWhitelistForGeolocation()
```





* Visibility: **protected**
* This method is **static**.
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 856](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L856)




### <a name="method-isTokenValid"></a>isTokenValid

```php
boolean FrontControllerCore::isTokenValid()
```

Check if token is valid



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 874](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L874)




### <a name="method-isXmlHttpRequest"></a>isXmlHttpRequest

```php
boolean ControllerCore::isXmlHttpRequest()
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 346](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L346)




### <a name="method-pagination"></a>pagination

```php
mixed FrontControllerCore::pagination($nbProducts)
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 776](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L776)


#### Arguments
* $nbProducts **mixed**



### <a name="method-postProcess"></a>postProcess

```php
mixed FrontControllerCore::postProcess()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 400](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L400)




### <a name="method-preProcess"></a>preProcess

```php
mixed FrontControllerCore::preProcess()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 416](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L416)




### <a name="method-process"></a>process

```php
mixed FrontControllerCore::process()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 486](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L486)




### <a name="method-processAddress"></a>processAddress

```php
mixed OrderControllerCore::processAddress()
```





* Visibility: **public**
* Source: [controllers/front/OrderController.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/OrderController.php#L244)




### <a name="method-processAddressFormat"></a>processAddressFormat

```php
mixed OrderControllerCore::processAddressFormat()
```





* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/OrderController.php#L202)




### <a name="method-processCarrier"></a>processCarrier

```php
mixed OrderControllerCore::processCarrier()
```

Carrier step



* Visibility: **protected**
* Source: [controllers/front/OrderController.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/OrderController.php#L288)




### <a name="method-productSort"></a>productSort

```php
mixed FrontControllerCore::productSort()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 749](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L749)




### <a name="method-recoverCart"></a>recoverCart

```php
mixed FrontControllerCore::recoverCart()
```





* Visibility: **protected**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 929](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L929)




### <a name="method-redirect"></a>redirect

```php
mixed FrontControllerCore::redirect()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 490](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L490)




### <a name="method-run"></a>run

```php
mixed ControllerCore::run()
```

Start controller process (this method shouldn't be overriden !)



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/Controller.php#L149)




### <a name="method-setDefaultCarrierSelection"></a>setDefaultCarrierSelection

```php
\number ParentOrderControllerCore::setDefaultCarrierSelection(array $carriers)
```

Decides what the default carrier is and update the cart with it



* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 493](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/ParentOrderController.php#L493)


#### Arguments
* $carriers **array**



### <a name="method-setMedia"></a>setMedia

```php
mixed ParentOrderControllerCore::setMedia()
```





* Visibility: **public**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/ParentOrderController.php#L134)




### <a name="method-setNoCarrier"></a>setNoCarrier

```php
mixed ParentOrderControllerCore::setNoCarrier()
```

Set id_carrier to 0 (no shipping price)



* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 476](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/ParentOrderController.php#L476)




### <a name="method-setTemplate"></a>setTemplate

```php
mixed FrontControllerCore::setTemplate($default_template)
```

This is overrided to manage is behaviour



* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 957](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L957)


#### Arguments
* $default_template **mixed**



### <a name="method-validateDeliveryOption"></a>validateDeliveryOption

```php
mixed ParentOrderControllerCore::validateDeliveryOption(array $delivery_option)
```

Validate get/post param delivery option



* Visibility: **protected**
* This method is defined by [ParentOrderControllerCore](class.ParentOrderControllerCore.md).
* Source: [controllers/front/ParentOrderController.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/controllers/front/ParentOrderController.php#L256)


#### Arguments
* $delivery_option **array**



### <a name="method-viewAccess"></a>viewAccess

```php
boolean FrontControllerCore::viewAccess()
```





* Visibility: **public**
* This method is defined by [FrontControllerCore](class.FrontControllerCore.md).
* Source: [classes/controller/FrontController.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/controller/FrontController.php#L90)



