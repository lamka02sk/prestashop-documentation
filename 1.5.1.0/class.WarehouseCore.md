Class WarehouseCore
=====================

Holds Stock



* Class name: WarehouseCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/stock/Warehouse.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L33)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$deleted](#property-$deleted)
* [$id](#property-$id)
* [$id_address](#property-$id_address)
* [$id_currency](#property-$id_currency)
* [$id_employee](#property-$id_employee)
* [$management_type](#property-$management_type)
* [$name](#property-$name)
* [$reference](#property-$reference)
* [$webserviceParameters](#property-$webserviceParameters)
* [$db](#property-$db)
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$get_shop_from_context](#property-$get_shop_from_context)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$id_shop_list](#property-$id_shop_list)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$table](#property-$table)
* [$tables](#property-$tables)
* [$update_fields](#property-$update_fields)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [exists](#method-exists)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAssociatedShops](#method-getAssociatedShops)
* [getCarriers](#method-getCarriers)
* [getDefinition](#method-getDefinition)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsShop](#method-getFieldsShop)
* [getNumberOfProducts](#method-getNumberOfProducts)
* [getPackWarehouses](#method-getPackWarehouses)
* [getProductLocation](#method-getProductLocation)
* [getProductWarehouseList](#method-getProductWarehouseList)
* [getQuantitiesOfProducts](#method-getQuantitiesOfProducts)
* [getShops](#method-getShops)
* [getStockValue](#method-getStockValue)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWarehouseNameById](#method-getWarehouseNameById)
* [getWarehouses](#method-getWarehouses)
* [getWarehousesByEmployee](#method-getWarehousesByEmployee)
* [getWarehousesByProductId](#method-getWarehousesByProductId)
* [getWarehousesGroupedByShops](#method-getWarehousesGroupedByShops)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getWsCarriers](#method-getWsCarriers)
* [getWsShops](#method-getWsShops)
* [getWsStockValue](#method-getWsStockValue)
* [getWsStocks](#method-getWsStocks)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isEmpty](#method-isEmpty)
* [isLangMultishop](#method-isLangMultishop)
* [isMultishop](#method-isMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [removeCarrier](#method-removeCarrier)
* [resetProductsLocations](#method-resetProductsLocations)
* [resetStockAvailable](#method-resetStockAvailable)
* [save](#method-save)
* [setCarriers](#method-setCarriers)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setFieldsToUpdate](#method-setFieldsToUpdate)
* [setProductLocation](#method-setProductLocation)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateMultishopTable](#method-updateMultishopTable)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [validateFieldsRequiredDatabase](#method-validateFieldsRequiredDatabase)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'warehouse', 'primary' => 'id_warehouse', 'fields' => array('id_address' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'reference' => array('type' => self::TYPE_STRING, 'validate' => 'isString', 'required' => true, 'size' => 45), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isString', 'required' => true, 'size' => 45), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'management_type' => array('type' => self::TYPE_STRING, 'validate' => 'isStockManagement', 'required' => true), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'deleted' => array('type' => self::TYPE_BOOL)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/stock/Warehouse.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L65).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L54).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L36).


### <a name="property-$id_address"></a>$id_address

```php
public integer $id_address
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L39).


### <a name="property-$id_currency"></a>$id_currency

```php
public integer $id_currency
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L51).


### <a name="property-$id_employee"></a>$id_employee

```php
public integer $id_employee
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L48).


### <a name="property-$management_type"></a>$management_type

```php
public \enum $management_type
```

Describes the way a Warehouse is managed



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L60).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L45).


### <a name="property-$reference"></a>$reference

```php
public string $reference
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L42).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_address' => array('xlink_resource' => 'addresses'), 'id_employee' => array('xlink_resource' => 'employees'), 'id_currency' => array('xlink_resource' => 'currencies'), 'valuation' => array('getter' => 'getWsStockValue', 'setter' => false), 'deleted' => array()), 'associations' => array('stocks' => array('resource' => 'stock', 'fields' => array('id' => array())), 'carriers' => array('resource' => 'carrier', 'fields' => array('id' => array())), 'shops' => array('resource' => 'shop', 'fields' => array('id' => array(), 'name' => array()))))
```





* Visibility: **protected**
* Source: [classes/stock/Warehouse.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L82).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L141).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L131).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L81).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L66).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L96).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L86).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L101).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L91).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L106).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected mixed $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L64).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L58).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L60).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public mixed $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L62).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L76).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L117).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L120).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L71).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L111).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L136).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ObjectModelCore::__construct(integer $id, integer $id_lang, integer $id_shop)
```

Build object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L169)


#### Arguments
* $id **integer** - Existing object id in order to load object (optional)
* $id_lang **integer** - Required if object is multilingual (optional)
* $id_shop **integer** - ID shop for objects with multishop on langs



### <a name="method-add"></a>add

```php
boolean ObjectModelCore::add(boolean $autodate, boolean $null_values)
```

Add current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L437)


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1097](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1097)


#### Arguments
* $fields **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1144](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1144)


#### Arguments
* $id_shops **integer|array**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1111](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1111)


#### Arguments
* $all **mixed**



### <a name="method-delete"></a>delete

```php
boolean ObjectModelCore::delete()
```

Delete current object from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 644](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L644)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage($force_delete)
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1270](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1270)


#### Arguments
* $force_delete **mixed**



### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 690](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L690)


#### Arguments
* $selection **array**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 890](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L890)


#### Arguments
* $field **mixed**
* $class **mixed**
* $htmlentities **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1188](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1188)


#### Arguments
* $id **mixed**



### <a name="method-exists"></a>exists

```php
boolean WarehouseCore::exists(integer $id_warehouse)
```

Checks if the given warehouse exists



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L214)


#### Arguments
* $id_warehouse **integer**



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1307](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1307)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L335)


#### Arguments
* $type **integer** - FORMAT_COMMON or FORMAT_LANG or FORMAT_SHOP
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed ObjectModelCore::formatValue(mixed $value, integer $type, $with_quotes)
```

Format a data



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L381)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Get the list of associated id_shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1173](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1173)




### <a name="method-getCarriers"></a>getCarriers

```php
array WarehouseCore::getCarriers()
```

Gets the carriers associated to the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L135)




### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1413](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1413)


#### Arguments
* $class **string** - Name of object
* $field **string** - Name of field if we want the definition of one field only



### <a name="method-getFieldByLang"></a>getFieldByLang

```php
mixed ObjectModelCore::getFieldByLang($field_name, null $id_lang)
```

Return the field value for the specified language if the field is multilang, else the field value.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1490](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1490)


#### Arguments
* $field_name **mixed**
* $id_lang **null**



### <a name="method-getFields"></a>getFields

```php
array ObjectModelCore::getFields()
```

Prepare fields for ObjectModel class (add, update)
All fields are verified (pSQL, intval.

..)

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L263)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L300)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1089](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1089)


#### Arguments
* $all **mixed**



### <a name="method-getFieldsShop"></a>getFieldsShop

```php
array ObjectModelCore::getFieldsShop()
```

Prepare fields for multishop
Fields are not validated here, we considere they are already validated in getFields() method, this
not the best solution but this is the only one possible for retro compatibility.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L286)




### <a name="method-getNumberOfProducts"></a>getNumberOfProducts

```php
integer WarehouseCore::getNumberOfProducts()
```

Gets the number of products in the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 388](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L388)




### <a name="method-getPackWarehouses"></a>getPackWarehouses

```php
integer|boolean WarehouseCore::getPackWarehouses(integer $id_product, $id_shop)
```

For a given pack, returns the warehouse it can be shipped from



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 497](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L497)


#### Arguments
* $id_product **integer**
* $id_shop **mixed**



### <a name="method-getProductLocation"></a>getProductLocation

```php
string WarehouseCore::getProductLocation(integer $id_product, integer $id_product_attribute, integer $id_warehouse)
```

For a given {product, product attribute} gets its location in the given warehouse



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L270)


#### Arguments
* $id_product **integer** - ID of the product
* $id_product_attribute **integer** - Use 0 if this product does not have attributes
* $id_warehouse **integer** - ID of the warehouse



### <a name="method-getProductWarehouseList"></a>getProductWarehouseList

```php
array WarehouseCore::getProductWarehouseList(integer $id_product, integer $id_product_attribute, integer $id_shop)
```

For a given {product, product attribute} gets warehouse list



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L290)


#### Arguments
* $id_product **integer** - ID of the product
* $id_product_attribute **integer** - Optional, uses 0 if this product does not have attributes
* $id_shop **integer** - Optional, ID of the shop. Uses the context shop id (@see Context::shop)



### <a name="method-getQuantitiesOfProducts"></a>getQuantitiesOfProducts

```php
integer WarehouseCore::getQuantitiesOfProducts()
```

Gets the number of quantities - for all products - in the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 408](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L408)




### <a name="method-getShops"></a>getShops

```php
array WarehouseCore::getShops()
```

Gets the shops associated to the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L118)




### <a name="method-getStockValue"></a>getStockValue

```php
integer WarehouseCore::getStockValue()
```

Gets the value of the stock in the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L425)




### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 722](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L722)


#### Arguments
* $fields_array **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $class)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L149)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWarehouseNameById"></a>getWarehouseNameById

```php
string WarehouseCore::getWarehouseNameById(integer $id_warehouse)
```

For a given $id_warehouse, returns its name



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 482](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L482)


#### Arguments
* $id_warehouse **integer** - Warehouse Id



### <a name="method-getWarehouses"></a>getWarehouses

```php
array WarehouseCore::getWarehouses(boolean $ignore_shop, integer $id_shop)
```

Gets available warehouses
It is possible via ignore_shop and id_shop to filter the list with shop id



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 346](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L346)


#### Arguments
* $ignore_shop **boolean** - Optional, false by default - Allows to get only the warehouses that are associated to one/some shops (@see $id_shop)
* $id_shop **integer** - Optional, Context::shop::Id by default - Allows to define a specific shop to filter.



### <a name="method-getWarehousesByEmployee"></a>getWarehousesByEmployee

```php
array WarehouseCore::getWarehousesByEmployee(integer $id_employee)
```

For a given employee, gets the warehouse(s) he/she manages



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 441](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L441)


#### Arguments
* $id_employee **integer** - Manager ID



### <a name="method-getWarehousesByProductId"></a>getWarehousesByProductId

```php
array WarehouseCore::getWarehousesByProductId(integer $id_product, integer $id_product_attribute)
```

For a given product, returns the warehouses it is stored in



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 458](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L458)


#### Arguments
* $id_product **integer** - Product Id
* $id_product_attribute **integer** - Optional, Product Attribute Id - 0 by default (no attribues)



### <a name="method-getWarehousesGroupedByShops"></a>getWarehousesGroupedByShops

```php
array WarehouseCore::getWarehousesGroupedByShops()
```

Gets warehouses grouped by shops



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 368](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L368)




### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1031](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1031)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getWebserviceParameters"></a>getWebserviceParameters

```php
mixed ObjectModelCore::getWebserviceParameters($ws_params_attribute_name)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 957](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L957)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-getWsCarriers"></a>getWsCarriers

```php
array WarehouseCore::getWsCarriers()
```

Webservice : gets the ids carriers associated to this warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 594](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L594)




### <a name="method-getWsShops"></a>getWsShops

```php
array WarehouseCore::getWsShops()
```

Webservice : gets the ids shops associated to this warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 578](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L578)




### <a name="method-getWsStockValue"></a>getWsStockValue

```php
integer WarehouseCore::getWsStockValue()
```

Webservice : gets the value of the warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 555](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L555)




### <a name="method-getWsStocks"></a>getWsStocks

```php
array WarehouseCore::getWsStocks()
```

Webservice : gets the ids stock associated to this warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 564](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L564)




### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Check if there is more than one entries in associated shop table for current entity



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1213](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1213)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1345](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1345)


#### Arguments
* $data **array**
* $id_lang **integer**



### <a name="method-hydrateCollection"></a>hydrateCollection

```php
array ObjectModelCore::hydrateCollection(string $class, array $datas, integer $id_lang)
```

Fill (hydrate) a list of objects in order to get a collection of these objects



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1364](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1364)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1126](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1126)


#### Arguments
* $id_shop **integer**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean ObjectModelCore::isCurrentlyUsed(string $table, boolean $has_active_column)
```

This method is allow to know if a entity is currently used



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1325](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1325)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isEmpty"></a>isEmpty

```php
boolean WarehouseCore::isEmpty()
```

Checks if a warehouse is empty - i.e. has no stock



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L199)




### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1225](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1225)




### <a name="method-isMultishop"></a>isMultishop

```php
mixed ObjectModelCore::isMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1220](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1220)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 738](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L738)


#### Arguments
* $fields **mixed**
* $fields_array **mixed**
* $id_language **mixed**



### <a name="method-removeCarrier"></a>removeCarrier

```php
mixed WarehouseCore::removeCarrier(integer $id_carrier, integer $id_warehouse)
```

For a given carrier, removes it from the warehouse/carrier association
If $id_warehouse is set, it only removes the carrier for this warehouse



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L186)


#### Arguments
* $id_carrier **integer** - Id of the carrier to remove
* $id_warehouse **integer** - optional Id of the warehouse to filter



### <a name="method-resetProductsLocations"></a>resetProductsLocations

```php
mixed WarehouseCore::resetProductsLocations()
```

Resets all product locations for this warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L255)




### <a name="method-resetStockAvailable"></a>resetStockAvailable

```php
mixed WarehouseCore::resetStockAvailable()
```





* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 538](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L538)




### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L425)


#### Arguments
* $null_values **boolean**
* $autodate **boolean**



### <a name="method-setCarriers"></a>setCarriers

```php
mixed WarehouseCore::setCarriers(array $ids_carriers)
```

Sets the carriers associated to the current warehouse



* Visibility: **public**
* Source: [classes/stock/Warehouse.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L162)


#### Arguments
* $ids_carriers **array**



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static
Remove this in 1.6 !



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1436](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1436)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false, langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1516](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1516)


#### Arguments
* $fields **array**



### <a name="method-setProductLocation"></a>setProductLocation

```php
boolean WarehouseCore::setProductLocation(integer $id_product, integer $id_product_attribute, integer $id_warehouse, string $location)
```

For a given {product, product attribute} sets its location in the given warehouse
First, for the given parameters, it cleans the database before updating



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/Warehouse.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/stock/Warehouse.php#L234)


#### Arguments
* $id_product **integer** - ID of the product
* $id_product_attribute **integer** - Use 0 if this product does not have attributes
* $id_warehouse **integer** - ID of the warehouse
* $location **string** - Describes the location (no lang id required)



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 706](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L706)




### <a name="method-update"></a>update

```php
boolean ObjectModelCore::update(boolean $null_values)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 529](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L529)


#### Arguments
* $null_values **boolean**



### <a name="method-updateMultishopTable"></a>updateMultishopTable

```php
boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)
```

Update a table and splits the common datas and the shop datas



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1240](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1240)


#### Arguments
* $classname **string**
* $data **array**
* $where **string**
* $specific_where **string** - Only executed for common table



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 905](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L905)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 911](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L911)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 843](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L843)


#### Arguments
* $field **string** - Field name
* $value **mixed** - Field value
* $id_lang **integer**



### <a name="method-validateFields"></a>validateFields

```php
boolean|string ObjectModelCore::validateFields(boolean $die, boolean $error_return)
```

Check for fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 776](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L776)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsLang"></a>validateFieldsLang

```php
boolean|string ObjectModelCore::validateFieldsLang(boolean $die, boolean $error_return)
```

Check for multilingual fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 805](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L805)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsRequiredDatabase"></a>validateFieldsRequiredDatabase

```php
mixed ObjectModelCore::validateFieldsRequiredDatabase($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1067](https://github.com/PrestaShop/PrestaShop/blob/1.5.1.0/classes/ObjectModel.php#L1067)


#### Arguments
* $htmlentities **mixed**


