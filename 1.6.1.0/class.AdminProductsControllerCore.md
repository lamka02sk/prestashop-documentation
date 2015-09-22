Class AdminProductsControllerCore
=====================





* Class name: AdminProductsControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminProductsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L30)


Contents
--------


### Properties

* [$_category](#property-$_category)
* [$available_tabs](#property-$available_tabs)
* [$available_tabs_lang](#property-$available_tabs_lang)
* [$default_tab](#property-$default_tab)
* [$id_current_category](#property-$id_current_category)
* [$max_file_size](#property-$max_file_size)
* [$max_image_size](#property-$max_image_size)
* [$object](#property-$object)
* [$position_identifier](#property-$position_identifier)
* [$submitted_tabs](#property-$submitted_tabs)
* [$tab_display](#property-$tab_display)
* [$tab_display_module](#property-$tab_display_module)

### Methods

* [__construct](#method-__construct)
* [_applyTaxToEcotax](#method-_applyTaxToEcotax)
* [_cleanMetaKeywords](#method-_cleanMetaKeywords)
* [_displayDraftWarning](#method-_displayDraftWarning)
* [_displayLabelField](#method-_displayLabelField)
* [_displayLabelFields](#method-_displayLabelFields)
* [_displaySpecificPriceModificationForm](#method-_displaySpecificPriceModificationForm)
* [_displayUnavailableProductWarning](#method-_displayUnavailableProductWarning)
* [_getCustomizationFieldIds](#method-_getCustomizationFieldIds)
* [_getFinalPrice](#method-_getFinalPrice)
* [_removeTaxFromEcotax](#method-_removeTaxFromEcotax)
* [_validateSpecificPrice](#method-_validateSpecificPrice)
* [addCarriers](#method-addCarriers)
* [addProductImage](#method-addProductImage)
* [ajaxPreProcess](#method-ajaxPreProcess)
* [ajaxProcessAddAttachment](#method-ajaxProcessAddAttachment)
* [ajaxProcessCheckProductName](#method-ajaxProcessCheckProductName)
* [ajaxProcessDefaultProductAttribute](#method-ajaxProcessDefaultProductAttribute)
* [ajaxProcessDeleteProductAttribute](#method-ajaxProcessDeleteProductAttribute)
* [ajaxProcessDeleteProductImage](#method-ajaxProcessDeleteProductImage)
* [ajaxProcessDeleteSpecificPrice](#method-ajaxProcessDeleteSpecificPrice)
* [ajaxProcessEditProductAttribute](#method-ajaxProcessEditProductAttribute)
* [ajaxProcessGetCategoryTree](#method-ajaxProcessGetCategoryTree)
* [ajaxProcessGetCountriesOptions](#method-ajaxProcessGetCountriesOptions)
* [ajaxProcessGetCurrenciesOptions](#method-ajaxProcessGetCurrenciesOptions)
* [ajaxProcessGetGroupsOptions](#method-ajaxProcessGetGroupsOptions)
* [ajaxProcessProductManufacturers](#method-ajaxProcessProductManufacturers)
* [ajaxProcessProductQuantity](#method-ajaxProcessProductQuantity)
* [ajaxProcessPublishProduct](#method-ajaxProcessPublishProduct)
* [ajaxProcessUpdateCover](#method-ajaxProcessUpdateCover)
* [ajaxProcessUpdateImagePosition](#method-ajaxProcessUpdateImagePosition)
* [ajaxProcessUpdatePositions](#method-ajaxProcessUpdatePositions)
* [ajaxProcessUpdateProductImageShopAsso](#method-ajaxProcessUpdateProductImageShopAsso)
* [ajaxProcessaddProductImage](#method-ajaxProcessaddProductImage)
* [checkFeatures](#method-checkFeatures)
* [checkMultishopBox](#method-checkMultishopBox)
* [checkProduct](#method-checkProduct)
* [copyFromPost](#method-copyFromPost)
* [copyImage](#method-copyImage)
* [displayPreviewLink](#method-displayPreviewLink)
* [getCarrierList](#method-getCarrierList)
* [getCombinationImagesJS](#method-getCombinationImagesJS)
* [getL](#method-getL)
* [getList](#method-getList)
* [getPackItems](#method-getPackItems)
* [getPreviewUrl](#method-getPreviewUrl)
* [getQuantities](#method-getQuantities)
* [haveThisAccessory](#method-haveThisAccessory)
* [initContent](#method-initContent)
* [initFormAssociations](#method-initFormAssociations)
* [initFormAttachments](#method-initFormAttachments)
* [initFormAttributes](#method-initFormAttributes)
* [initFormCombinations](#method-initFormCombinations)
* [initFormCustomization](#method-initFormCustomization)
* [initFormFeatures](#method-initFormFeatures)
* [initFormImages](#method-initFormImages)
* [initFormInformations](#method-initFormInformations)
* [initFormModules](#method-initFormModules)
* [initFormPack](#method-initFormPack)
* [initFormPrices](#method-initFormPrices)
* [initFormQuantities](#method-initFormQuantities)
* [initFormSeo](#method-initFormSeo)
* [initFormShipping](#method-initFormShipping)
* [initFormSuppliers](#method-initFormSuppliers)
* [initFormVirtualProduct](#method-initFormVirtualProduct)
* [initFormWarehouses](#method-initFormWarehouses)
* [initPack](#method-initPack)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [isProductFieldUpdated](#method-isProductFieldUpdated)
* [isTabSubmitted](#method-isTabSubmitted)
* [loadObject](#method-loadObject)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [processAttachments](#method-processAttachments)
* [processBulkDelete](#method-processBulkDelete)
* [processCustomizationConfiguration](#method-processCustomizationConfiguration)
* [processDelete](#method-processDelete)
* [processDeleteVirtualProduct](#method-processDeleteVirtualProduct)
* [processDuplicate](#method-processDuplicate)
* [processFeatures](#method-processFeatures)
* [processImage](#method-processImage)
* [processImageLegends](#method-processImageLegends)
* [processPosition](#method-processPosition)
* [processPriceAddition](#method-processPriceAddition)
* [processPricesModification](#method-processPricesModification)
* [processProductAttribute](#method-processProductAttribute)
* [processProductCustomization](#method-processProductCustomization)
* [processSpecificPricePriorities](#method-processSpecificPricePriorities)
* [processStatus](#method-processStatus)
* [processSuppliers](#method-processSuppliers)
* [processUpdate](#method-processUpdate)
* [processWarehouses](#method-processWarehouses)
* [recurseCategoryForInclude](#method-recurseCategoryForInclude)
* [renderForm](#method-renderForm)
* [renderKpis](#method-renderKpis)
* [renderList](#method-renderList)
* [renderListAttributes](#method-renderListAttributes)
* [setMedia](#method-setMedia)
* [updateAccessories](#method-updateAccessories)
* [updateAssoShop](#method-updateAssoShop)
* [updateDownloadProduct](#method-updateDownloadProduct)
* [updatePackItems](#method-updatePackItems)
* [updateTags](#method-updateTags)




Properties
----------


### <a name="property-$_category"></a>$_category

```php
protected mixed $_category
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L38).


### <a name="property-$available_tabs"></a>$available_tabs

```php
protected array $available_tabs = array()
```

The order in the array decides the order in the list of tab. If an element's value is a number, it will be preloaded.

The tabs are preloaded from the smallest to the highest number.

* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L50).


### <a name="property-$available_tabs_lang"></a>$available_tabs_lang

```php
protected mixed $available_tabs_lang = array()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L54).


### <a name="property-$default_tab"></a>$default_tab

```php
protected mixed $default_tab = 'Informations'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L52).


### <a name="property-$id_current_category"></a>$id_current_category

```php
protected mixed $id_current_category
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L60).


### <a name="property-$max_file_size"></a>$max_file_size

```php
protected integer $max_file_size = null
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L35).


### <a name="property-$max_image_size"></a>$max_image_size

```php
protected mixed $max_image_size = null
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L36).


### <a name="property-$object"></a>$object

```php
public \Product $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L30).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected mixed $position_identifier = 'id_product'
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L56).


### <a name="property-$submitted_tabs"></a>$submitted_tabs

```php
protected mixed $submitted_tabs
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L58).


### <a name="property-$tab_display"></a>$tab_display

```php
protected string $tab_display
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L42).


### <a name="property-$tab_display_module"></a>$tab_display_module

```php
protected mixed $tab_display_module
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L43).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminProductsControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L62)




### <a name="method-_applyTaxToEcotax"></a>_applyTaxToEcotax

```php
mixed AdminProductsControllerCore::_applyTaxToEcotax($product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2267](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L2267)


#### Arguments
* $product **mixed**



### <a name="method-_cleanMetaKeywords"></a>_cleanMetaKeywords

```php
mixed AdminProductsControllerCore::_cleanMetaKeywords($keywords)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 304](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L304)


#### Arguments
* $keywords **mixed**



### <a name="method-_displayDraftWarning"></a>_displayDraftWarning

```php
mixed AdminProductsControllerCore::_displayDraftWarning($active)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2626](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L2626)


#### Arguments
* $active **mixed**



### <a name="method-_displayLabelField"></a>_displayLabelField

```php
mixed AdminProductsControllerCore::_displayLabelField($label, $languages, $default_language, $type, $fieldIds, $id_customization_field)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3751](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L3751)


#### Arguments
* $label **mixed**
* $languages **mixed**
* $default_language **mixed**
* $type **mixed**
* $fieldIds **mixed**
* $id_customization_field **mixed**



### <a name="method-_displayLabelFields"></a>_displayLabelFields

```php
mixed AdminProductsControllerCore::_displayLabelFields($obj, $labels, $languages, $default_language, $type)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3779](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L3779)


#### Arguments
* $obj **mixed**
* $labels **mixed**
* $languages **mixed**
* $default_language **mixed**
* $type **mixed**



### <a name="method-_displaySpecificPriceModificationForm"></a>_displaySpecificPriceModificationForm

```php
mixed AdminProductsControllerCore::_displaySpecificPriceModificationForm($defaultCurrency, $shops, $currencies, $countries, $groups)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3520](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L3520)


#### Arguments
* $defaultCurrency **mixed**
* $shops **mixed**
* $currencies **mixed**
* $countries **mixed**
* $groups **mixed**



### <a name="method-_displayUnavailableProductWarning"></a>_displayUnavailableProductWarning

```php
mixed AdminProductsControllerCore::_displayUnavailableProductWarning()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 4995](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4995)




### <a name="method-_getCustomizationFieldIds"></a>_getCustomizationFieldIds

```php
mixed AdminProductsControllerCore::_getCustomizationFieldIds($labels, $alreadyGenerated, $obj)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3733](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L3733)


#### Arguments
* $labels **mixed**
* $alreadyGenerated **mixed**
* $obj **mixed**



### <a name="method-_getFinalPrice"></a>_getFinalPrice

```php
mixed AdminProductsControllerCore::_getFinalPrice($specific_price, $product_price, $tax_rate)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 3515](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L3515)


#### Arguments
* $specific_price **mixed**
* $product_price **mixed**
* $tax_rate **mixed**



### <a name="method-_removeTaxFromEcotax"></a>_removeTaxFromEcotax

```php
mixed AdminProductsControllerCore::_removeTaxFromEcotax()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L2261)




### <a name="method-_validateSpecificPrice"></a>_validateSpecificPrice

```php
mixed AdminProductsControllerCore::_validateSpecificPrice($id_shop, $id_currency, $id_country, $id_group, $id_customer, $price, $from_quantity, $reduction, $reduction_type, $from, $to, $id_combination)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1713](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1713)


#### Arguments
* $id_shop **mixed**
* $id_currency **mixed**
* $id_country **mixed**
* $id_group **mixed**
* $id_customer **mixed**
* $price **mixed**
* $from_quantity **mixed**
* $reduction **mixed**
* $reduction_type **mixed**
* $from **mixed**
* $to **mixed**
* $id_combination **mixed**



### <a name="method-addCarriers"></a>addCarriers

```php
mixed AdminProductsControllerCore::addCarriers($product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 4020](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4020)


#### Arguments
* $product **mixed**



### <a name="method-addProductImage"></a>addProductImage

```php
integer|false AdminProductsControllerCore::addProductImage(\Product $product, string $method)
```

Add or update a product image



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1771](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1771)


#### Arguments
* $product **[Product](class.ProductCore.md)** - Product object to add image
* $method **string**



### <a name="method-ajaxPreProcess"></a>ajaxPreProcess

```php
mixed AdminProductsControllerCore::ajaxPreProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1583](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1583)




### <a name="method-ajaxProcessAddAttachment"></a>ajaxProcessAddAttachment

```php
mixed AdminProductsControllerCore::ajaxProcessAddAttachment()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 546](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L546)




### <a name="method-ajaxProcessCheckProductName"></a>ajaxProcessCheckProductName

```php
mixed AdminProductsControllerCore::ajaxProcessCheckProductName()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 5005](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L5005)




### <a name="method-ajaxProcessDefaultProductAttribute"></a>ajaxProcessDefaultProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessDefaultProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1540](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1540)




### <a name="method-ajaxProcessDeleteProductAttribute"></a>ajaxProcessDeleteProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1482](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1482)




### <a name="method-ajaxProcessDeleteProductImage"></a>ajaxProcessDeleteProductImage

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteProductImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1676](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1676)




### <a name="method-ajaxProcessDeleteSpecificPrice"></a>ajaxProcessDeleteSpecificPrice

```php
mixed AdminProductsControllerCore::ajaxProcessDeleteSpecificPrice()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1162)




### <a name="method-ajaxProcessEditProductAttribute"></a>ajaxProcessEditProductAttribute

```php
mixed AdminProductsControllerCore::ajaxProcessEditProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1566](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1566)




### <a name="method-ajaxProcessGetCategoryTree"></a>ajaxProcessGetCategoryTree

```php
mixed AdminProductsControllerCore::ajaxProcessGetCategoryTree()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 456](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L456)




### <a name="method-ajaxProcessGetCountriesOptions"></a>ajaxProcessGetCountriesOptions

```php
mixed AdminProductsControllerCore::ajaxProcessGetCountriesOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 480](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L480)




### <a name="method-ajaxProcessGetCurrenciesOptions"></a>ajaxProcessGetCurrenciesOptions

```php
mixed AdminProductsControllerCore::ajaxProcessGetCurrenciesOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 496](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L496)




### <a name="method-ajaxProcessGetGroupsOptions"></a>ajaxProcessGetGroupsOptions

```php
mixed AdminProductsControllerCore::ajaxProcessGetGroupsOptions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 512](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L512)




### <a name="method-ajaxProcessProductManufacturers"></a>ajaxProcessProductManufacturers

```php
mixed AdminProductsControllerCore::ajaxProcessProductManufacturers()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2556](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L2556)




### <a name="method-ajaxProcessProductQuantity"></a>ajaxProcessProductQuantity

```php
mixed AdminProductsControllerCore::ajaxProcessProductQuantity()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4799](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4799)




### <a name="method-ajaxProcessPublishProduct"></a>ajaxProcessPublishProduct

```php
mixed AdminProductsControllerCore::ajaxProcessPublishProduct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 5068](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L5068)




### <a name="method-ajaxProcessUpdateCover"></a>ajaxProcessUpdateCover

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateCover()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1659](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1659)




### <a name="method-ajaxProcessUpdateImagePosition"></a>ajaxProcessUpdateImagePosition

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateImagePosition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1636](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1636)




### <a name="method-ajaxProcessUpdatePositions"></a>ajaxProcessUpdatePositions

```php
mixed AdminProductsControllerCore::ajaxProcessUpdatePositions()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 5028](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L5028)




### <a name="method-ajaxProcessUpdateProductImageShopAsso"></a>ajaxProcessUpdateProductImageShopAsso

```php
mixed AdminProductsControllerCore::ajaxProcessUpdateProductImageShopAsso()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1592](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1592)




### <a name="method-ajaxProcessaddProductImage"></a>ajaxProcessaddProductImage

```php
mixed AdminProductsControllerCore::ajaxProcessaddProductImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4036](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4036)




### <a name="method-checkFeatures"></a>checkFeatures

```php
mixed AdminProductsControllerCore::checkFeatures($languages, $feature_id)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1733](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1733)


#### Arguments
* $languages **mixed**
* $feature_id **mixed**



### <a name="method-checkMultishopBox"></a>checkMultishopBox

```php
mixed AdminProductsControllerCore::checkMultishopBox($field, $context)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 365](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L365)


#### Arguments
* $field **mixed**
* $context **mixed**



### <a name="method-checkProduct"></a>checkProduct

```php
mixed AdminProductsControllerCore::checkProduct()
```

Check that a saved product is valid



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L2110)




### <a name="method-copyFromPost"></a>copyFromPost

```php
mixed AdminProductsControllerCore::copyFromPost(\Product|\ObjectModel $object, string $table)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 326](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L326)


#### Arguments
* $object **[Product](class.ProductCore.md)|[Product](class.ObjectModelCore.md)**
* $table **string**



### <a name="method-copyImage"></a>copyImage

```php
void|false AdminProductsControllerCore::copyImage(integer $id_product, integer $id_image, string $method)
```

Copy a product image



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1811](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1811)


#### Arguments
* $id_product **integer** - Product Id for product image filename
* $id_image **integer** - Image Id for product image filename
* $method **string**



### <a name="method-displayPreviewLink"></a>displayPreviewLink

```php
mixed AdminProductsControllerCore::displayPreviewLink($token, $id, $name)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 5107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L5107)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-getCarrierList"></a>getCarrierList

```php
mixed AdminProductsControllerCore::getCarrierList()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 4001](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4001)




### <a name="method-getCombinationImagesJS"></a>getCombinationImagesJS

```php
mixed AdminProductsControllerCore::getCombinationImagesJS()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4885](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4885)




### <a name="method-getL"></a>getL

```php
mixed AdminProductsControllerCore::getL($key)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4982](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4982)


#### Arguments
* $key **mixed**



### <a name="method-getList"></a>getList

```php
mixed AdminProductsControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 388](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L388)


#### Arguments
* $id_lang **mixed**
* $orderBy **mixed**
* $orderWay **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-getPackItems"></a>getPackItems

```php
array AdminProductsControllerCore::getPackItems(\Product $product)
```

Get an array of pack items for display from the product object if specified, else from POST/GET values



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3360](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L3360)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-getPreviewUrl"></a>getPreviewUrl

```php
mixed AdminProductsControllerCore::getPreviewUrl(\Product $product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2853](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L2853)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-getQuantities"></a>getQuantities

```php
mixed AdminProductsControllerCore::getQuantities($echo, $tr)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminProductsController.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L277)


#### Arguments
* $echo **mixed**
* $tr **mixed**



### <a name="method-haveThisAccessory"></a>haveThisAccessory

```php
mixed AdminProductsControllerCore::haveThisAccessory($accessory_id, $accessories)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4904](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4904)


#### Arguments
* $accessory_id **mixed**
* $accessories **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminProductsControllerCore::initContent($token)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2399](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L2399)


#### Arguments
* $token **mixed**



### <a name="method-initFormAssociations"></a>initFormAssociations

```php
mixed AdminProductsControllerCore::initFormAssociations(\Product $obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3142](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L3142)


#### Arguments
* $obj **[Product](class.ProductCore.md)**



### <a name="method-initFormAttachments"></a>initFormAttachments

```php
mixed AdminProductsControllerCore::initFormAttachments($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3831](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L3831)


#### Arguments
* $obj **mixed**



### <a name="method-initFormAttributes"></a>initFormAttributes

```php
mixed AdminProductsControllerCore::initFormAttributes(\Product $product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4258](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4258)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-initFormCombinations"></a>initFormCombinations

```php
mixed AdminProductsControllerCore::initFormCombinations($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4248](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4248)


#### Arguments
* $obj **mixed**



### <a name="method-initFormCustomization"></a>initFormCustomization

```php
mixed AdminProductsControllerCore::initFormCustomization(\Product $obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3797](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L3797)


#### Arguments
* $obj **[Product](class.ProductCore.md)**



### <a name="method-initFormFeatures"></a>initFormFeatures

```php
mixed AdminProductsControllerCore::initFormFeatures(\Product $obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4742](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4742)


#### Arguments
* $obj **[Product](class.ProductCore.md)**



### <a name="method-initFormImages"></a>initFormImages

```php
mixed AdminProductsControllerCore::initFormImages(\Product $obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4172](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4172)


#### Arguments
* $obj **[Product](class.ProductCore.md)**



### <a name="method-initFormInformations"></a>initFormInformations

```php
mixed AdminProductsControllerCore::initFormInformations(\Product $product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3889](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L3889)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-initFormModules"></a>initFormModules

```php
mixed AdminProductsControllerCore::initFormModules($obj)
```

AdminProducts display hook



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4941](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4941)


#### Arguments
* $obj **mixed**



### <a name="method-initFormPack"></a>initFormPack

```php
mixed AdminProductsControllerCore::initFormPack(\Product $product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L3414)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-initFormPrices"></a>initFormPrices

```php
mixed AdminProductsControllerCore::initFormPrices(\Product $obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3213](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L3213)


#### Arguments
* $obj **[Product](class.ProductCore.md)**



### <a name="method-initFormQuantities"></a>initFormQuantities

```php
mixed AdminProductsControllerCore::initFormQuantities(\Product $obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4445](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4445)


#### Arguments
* $obj **[Product](class.ProductCore.md)**



### <a name="method-initFormSeo"></a>initFormSeo

```php
mixed AdminProductsControllerCore::initFormSeo($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3323](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L3323)


#### Arguments
* $product **mixed**



### <a name="method-initFormShipping"></a>initFormShipping

```php
mixed AdminProductsControllerCore::initFormShipping($obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3987](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L3987)


#### Arguments
* $obj **mixed**



### <a name="method-initFormSuppliers"></a>initFormSuppliers

```php
mixed AdminProductsControllerCore::initFormSuppliers(\Product $obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4601](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4601)


#### Arguments
* $obj **[Product](class.ProductCore.md)**



### <a name="method-initFormVirtualProduct"></a>initFormVirtualProduct

```php
mixed AdminProductsControllerCore::initFormVirtualProduct($product)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3449](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L3449)


#### Arguments
* $product **mixed**



### <a name="method-initFormWarehouses"></a>initFormWarehouses

```php
mixed AdminProductsControllerCore::initFormWarehouses(\Product $obj)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4687](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4687)


#### Arguments
* $obj **[Product](class.ProductCore.md)**



### <a name="method-initPack"></a>initPack

```php
mixed AdminProductsControllerCore::initPack(\Product $product)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 4912](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4912)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminProductsControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2636](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L2636)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminProductsControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1275](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1275)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminProductsControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2694](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L2694)




### <a name="method-isProductFieldUpdated"></a>isProductFieldUpdated

```php
boolean AdminProductsControllerCore::isProductFieldUpdated(string $field, integer $id_lang)
```

Check if a field is edited (if the checkbox is checked)
This method will do something only for multishop with a context all / group



* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 2245](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L2245)


#### Arguments
* $field **string** - Name of field
* $id_lang **integer**



### <a name="method-isTabSubmitted"></a>isTabSubmitted

```php
mixed AdminProductsControllerCore::isTabSubmitted($tab_name)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1931](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1931)


#### Arguments
* $tab_name **mixed**



### <a name="method-loadObject"></a>loadObject

```php
mixed AdminProductsControllerCore::loadObject($opt)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 433](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L433)


#### Arguments
* $opt **mixed**



### <a name="method-postProcess"></a>postProcess

```php
void AdminProductsControllerCore::postProcess()
```

postProcess handle every checks before saving products information



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1438](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1438)




### <a name="method-processAdd"></a>processAdd

```php
mixed AdminProductsControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1848](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1848)




### <a name="method-processAttachments"></a>processAttachments

```php
void AdminProductsControllerCore::processAttachments()
```

Attach an existing attachment to the product



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 674](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L674)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
mixed AdminProductsControllerCore::processBulkDelete()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 821](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L821)




### <a name="method-processCustomizationConfiguration"></a>processCustomizationConfiguration

```php
mixed AdminProductsControllerCore::processCustomizationConfiguration()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1210)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminProductsControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 735](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L735)




### <a name="method-processDeleteVirtualProduct"></a>processDeleteVirtualProduct

```php
mixed AdminProductsControllerCore::processDeleteVirtualProduct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 528](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L528)




### <a name="method-processDuplicate"></a>processDuplicate

```php
mixed AdminProductsControllerCore::processDuplicate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 685](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L685)




### <a name="method-processFeatures"></a>processFeatures

```php
mixed AdminProductsControllerCore::processFeatures()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1024](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1024)




### <a name="method-processImage"></a>processImage

```php
mixed AdminProductsControllerCore::processImage()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 778](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L778)




### <a name="method-processImageLegends"></a>processImageLegends

```php
mixed AdminProductsControllerCore::processImageLegends()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 5093](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L5093)




### <a name="method-processPosition"></a>processPosition

```php
mixed AdminProductsControllerCore::processPosition()
```

Overrides parent for custom redirect link



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1256](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1256)




### <a name="method-processPriceAddition"></a>processPriceAddition

```php
mixed AdminProductsControllerCore::processPriceAddition()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1108)




### <a name="method-processPricesModification"></a>processPricesModification

```php
mixed AdminProductsControllerCore::processPricesModification()
```

This function is never called at the moment (specific prices cannot be edited)



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1066](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1066)




### <a name="method-processProductAttribute"></a>processProductAttribute

```php
mixed AdminProductsControllerCore::processProductAttribute()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 891](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L891)




### <a name="method-processProductCustomization"></a>processProductCustomization

```php
mixed AdminProductsControllerCore::processProductCustomization()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1237](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1237)




### <a name="method-processSpecificPricePriorities"></a>processSpecificPricePriorities

```php
mixed AdminProductsControllerCore::processSpecificPricePriorities()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1193](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1193)




### <a name="method-processStatus"></a>processStatus

```php
mixed AdminProductsControllerCore::processStatus()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1942](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1942)




### <a name="method-processSuppliers"></a>processSuppliers

```php
mixed AdminProductsControllerCore::processSuppliers()
```

Post treatment for suppliers



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2885](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L2885)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminProductsControllerCore::processUpdate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 1960](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1960)




### <a name="method-processWarehouses"></a>processWarehouses

```php
mixed AdminProductsControllerCore::processWarehouses()
```

Post treatment for warehouses



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 3058](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L3058)




### <a name="method-recurseCategoryForInclude"></a>recurseCategoryForInclude

```php
string AdminProductsControllerCore::recurseCategoryForInclude($id_obj, array $indexedCategories, array $categories, $current, null $id_category, null $id_category_default, array $has_suite)
```

Build a categories tree



* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminProductsController.php line 2584](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L2584)


#### Arguments
* $id_obj **mixed**
* $indexedCategories **array** - Array with categories where product is indexed (in order to check checkbox)
* $categories **array** - Categories to list
* $current **mixed**
* $id_category **null** - Current category ID
* $id_category_default **null**
* $has_suite **array**



### <a name="method-renderForm"></a>renderForm

```php
string|void AdminProductsControllerCore::renderForm()
```

renderForm contains all necessary initialization needed for all tabs



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2735](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L2735)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminProductsControllerCore::renderKpis()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2478](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L2478)




### <a name="method-renderList"></a>renderList

```php
mixed AdminProductsControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2547](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L2547)




### <a name="method-renderListAttributes"></a>renderListAttributes

```php
string AdminProductsControllerCore::renderListAttributes(\Product $product, \Currency|array|integer $currency)
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4344](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4344)


#### Arguments
* $product **[Product](class.ProductCore.md)**
* $currency **[Currency](class.CurrencyCore.md)|array|integer**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminProductsControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L285)




### <a name="method-updateAccessories"></a>updateAccessories

```php
mixed AdminProductsControllerCore::updateAccessories(object $product)
```

Update product accessories



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2361](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L2361)


#### Arguments
* $product **object** - Product



### <a name="method-updateAssoShop"></a>updateAssoShop

```php
mixed AdminProductsControllerCore::updateAssoShop($id_object)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminProductsController.php line 1842](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L1842)


#### Arguments
* $id_object **mixed**



### <a name="method-updateDownloadProduct"></a>updateDownloadProduct

```php
boolean AdminProductsControllerCore::updateDownloadProduct(\Product $product, integer $edit)
```

Update product download



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2281](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L2281)


#### Arguments
* $product **[Product](class.ProductCore.md)**
* $edit **integer**



### <a name="method-updatePackItems"></a>updatePackItems

```php
boolean AdminProductsControllerCore::updatePackItems(\Product $product)
```

delete all items in pack, then check if type_product value is 2.

if yes, add the pack items from input "inputPackItems"

* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 4954](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L4954)


#### Arguments
* $product **[Product](class.ProductCore.md)**



### <a name="method-updateTags"></a>updateTags

```php
boolean AdminProductsControllerCore::updateTags(array $languages, object $product)
```

Update product tags



* Visibility: **public**
* Source: [controllers/admin/AdminProductsController.php line 2382](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminProductsController.php#L2382)


#### Arguments
* $languages **array** - Array languages
* $product **object** - Product

