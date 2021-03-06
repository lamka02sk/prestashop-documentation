Class CMSCategoryCore
=====================





* Class name: CMSCategoryCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/CMSCategory.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L28)


Contents
--------


### Properties

* [$_links](#property-$_links)
* [$active](#property-$active)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$description](#property-$description)
* [$id](#property-$id)
* [$id_cms_category](#property-$id_cms_category)
* [$id_parent](#property-$id_parent)
* [$level_depth](#property-$level_depth)
* [$link_rewrite](#property-$link_rewrite)
* [$meta_description](#property-$meta_description)
* [$meta_keywords](#property-$meta_keywords)
* [$meta_title](#property-$meta_title)
* [$name](#property-$name)
* [$position](#property-$position)
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$table](#property-$table)
* [$tables](#property-$tables)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [calcLevelDepth](#method-calcLevelDepth)
* [checkBeforeMove](#method-checkBeforeMove)
* [cleanPositions](#method-cleanPositions)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getCategories](#method-getCategories)
* [getChildren](#method-getChildren)
* [getDefinition](#method-getDefinition)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getHomeCategories](#method-getHomeCategories)
* [getLastPosition](#method-getLastPosition)
* [getLink](#method-getLink)
* [getLinkRewrite](#method-getLinkRewrite)
* [getName](#method-getName)
* [getParentsCategories](#method-getParentsCategories)
* [getRecurseCategory](#method-getRecurseCategory)
* [getSimpleCategories](#method-getSimpleCategories)
* [getSubCategories](#method-getSubCategories)
* [getTranslationsFields](#method-getTranslationsFields)
* [getUrlRewriteInformations](#method-getUrlRewriteInformations)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hideCMSCategoryPosition](#method-hideCMSCategoryPosition)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangMultishop](#method-isLangMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [recurseCMSCategory](#method-recurseCMSCategory)
* [recurseLiteCategTree](#method-recurseLiteCategTree)
* [recursiveDelete](#method-recursiveDelete)
* [save](#method-save)
* [searchByName](#method-searchByName)
* [searchByNameAndParentCMSCategoryId](#method-searchByNameAndParentCMSCategoryId)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updatePosition](#method-updatePosition)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)




Properties
----------


### <a name="property-$_links"></a>$_links

```php
protected mixed $_links = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/CMSCategory.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L71).


### <a name="property-$active"></a>$active

```php
public boolean $active = 1
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L39).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L66).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L69).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'cms_category', 'primary' => 'id_cms_category', 'multilang' => true, 'fields' => array('active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'id_parent' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'position' => array('type' => self::TYPE_INT), 'level_depth' => array('type' => self::TYPE_INT), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCatalogName', 'required' => true, 'size' => 64), 'link_rewrite' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isLinkRewrite', 'required' => true, 'size' => 64), 'description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCleanHtml'), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/CMSCategory.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L76).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L42).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L30).


### <a name="property-$id_cms_category"></a>$id_cms_category

```php
public integer $id_cms_category
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L33).


### <a name="property-$id_parent"></a>$id_parent

```php
public integer $id_parent
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L45).


### <a name="property-$level_depth"></a>$level_depth

```php
public integer $level_depth
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L51).


### <a name="property-$link_rewrite"></a>$link_rewrite

```php
public string $link_rewrite
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L54).


### <a name="property-$meta_description"></a>$meta_description

```php
public string $meta_description
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L63).


### <a name="property-$meta_keywords"></a>$meta_keywords

```php
public string $meta_keywords
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L60).


### <a name="property-$meta_title"></a>$meta_title

```php
public string $meta_title
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L57).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L36).


### <a name="property-$position"></a>$position

```php
public integer $position
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L48).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L122).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L72).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L57).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L87).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L77).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L92).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L82).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L97).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L51).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L53).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L67).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L108).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L111).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L62).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L102).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected array $webserviceParameters = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L105).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ObjectModelCore::__construct(integer $id, integer $id_lang, integer $id_shop)
```

Build object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L150)


#### Arguments
* $id **integer** - Existing object id in order to load object (optional)
* $id_lang **integer** - Required if object is multilingual (optional)
* $id_shop **integer** - ID shop for objects with multishop on langs



### <a name="method-add"></a>add

```php
mixed CMSCategoryCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L98)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 925](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L925)


#### Arguments
* $fields **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops, string $type)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 973](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L973)


#### Arguments
* $id_shops **integer|array**
* $type **string**



### <a name="method-calcLevelDepth"></a>calcLevelDepth

```php
integer CMSCategoryCore::calcLevelDepth()
```

Get the number of parent categories



* Visibility: **public**
* Source: [classes/CMSCategory.php line 292](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L292)




### <a name="method-checkBeforeMove"></a>checkBeforeMove

```php
boolean CMSCategoryCore::checkBeforeMove($id_cms_category, integer $id_parent)
```

Check if CMSCategory can be moved in another one



* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 419](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L419)


#### Arguments
* $id_cms_category **mixed**
* $id_parent **integer** - Parent candidate



### <a name="method-cleanPositions"></a>cleanPositions

```php
mixed CMSCategoryCore::cleanPositions($id_category_parent)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 580](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L580)


#### Arguments
* $id_category_parent **mixed**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 939](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L939)


#### Arguments
* $all **mixed**



### <a name="method-delete"></a>delete

```php
mixed CMSCategoryCore::delete()
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 239](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L239)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage()
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1047](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1047)




### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed CMSCategoryCore::deleteSelection($categories)
```

Delete several categories from database

return boolean Deletion result

* Visibility: **public**
* Source: [classes/CMSCategory.php line 276](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L276)


#### Arguments
* $categories **mixed**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 757](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L757)


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
* Source: [classes/ObjectModel.php line 1017](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1017)


#### Arguments
* $id **mixed**



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1081](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1081)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L272)


#### Arguments
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed ObjectModelCore::formatValue(mixed $value, integer $type, $with_quotes)
```

Format a data



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L319)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getCategories"></a>getCategories

```php
array CMSCategoryCore::getCategories(integer $id_lang, boolean $active, $order)
```

Return available categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 307](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L307)


#### Arguments
* $id_lang **integer** - Language ID
* $active **boolean** - return only active categories
* $order **mixed**



### <a name="method-getChildren"></a>getChildren

```php
mixed CMSCategoryCore::getChildren($id_parent, $id_lang, $active)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 389](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L389)


#### Arguments
* $id_parent **mixed**
* $id_lang **mixed**
* $active **mixed**



### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1184](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1184)


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
* Source: [classes/ObjectModel.php line 1261](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1261)


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
* Source: [classes/ObjectModel.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L234)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L249)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 917](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L917)


#### Arguments
* $all **mixed**



### <a name="method-getHomeCategories"></a>getHomeCategories

```php
array CMSCategoryCore::getHomeCategories(integer $id_lang, boolean $active)
```

Return main categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 384](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L384)


#### Arguments
* $id_lang **integer** - Language ID
* $active **boolean** - return only active categories



### <a name="method-getLastPosition"></a>getLastPosition

```php
mixed CMSCategoryCore::getLastPosition($id_category_parent)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 600](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L600)


#### Arguments
* $id_category_parent **mixed**



### <a name="method-getLink"></a>getLink

```php
mixed CMSCategoryCore::getLink(\Link $link)
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 453](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L453)


#### Arguments
* $link **[Link](class.LinkCore.md)**



### <a name="method-getLinkRewrite"></a>getLinkRewrite

```php
mixed CMSCategoryCore::getLinkRewrite($id_cms_category, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 435](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L435)


#### Arguments
* $id_cms_category **mixed**
* $id_lang **mixed**



### <a name="method-getName"></a>getName

```php
mixed CMSCategoryCore::getName($id_lang)
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 460](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L460)


#### Arguments
* $id_lang **mixed**



### <a name="method-getParentsCategories"></a>getParentsCategories

```php
array CMSCategoryCore::getParentsCategories(integer $id_lang)
```

Get Each parent CMSCategory of this CMSCategory until the root CMSCategory



* Visibility: **public**
* Source: [classes/CMSCategory.php line 524](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L524)


#### Arguments
* $id_lang **integer** - Language ID



### <a name="method-getRecurseCategory"></a>getRecurseCategory

```php
mixed CMSCategoryCore::getRecurseCategory($id_lang, $current, $active, $links, \Link $link, \Shop $shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L162)


#### Arguments
* $id_lang **mixed**
* $current **mixed**
* $active **mixed**
* $links **mixed**
* $link **[Link](class.LinkCore.md)**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getSimpleCategories"></a>getSimpleCategories

```php
mixed CMSCategoryCore::getSimpleCategories($id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 329](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L329)


#### Arguments
* $id_lang **mixed**



### <a name="method-getSubCategories"></a>getSubCategories

```php
array CMSCategoryCore::getSubCategories(integer $id_lang, boolean $active)
```

Return current CMSCategory childs



* Visibility: **public**
* Source: [classes/CMSCategory.php line 346](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L346)


#### Arguments
* $id_lang **integer** - Language ID
* $active **boolean** - return only active categories



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 595](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L595)


#### Arguments
* $fields_array **mixed**



### <a name="method-getUrlRewriteInformations"></a>getUrlRewriteInformations

```php
mixed CMSCategoryCore::getUrlRewriteInformations($id_category)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 605](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L605)


#### Arguments
* $id_category **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $class)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L130)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 890](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L890)


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
* Source: [classes/ObjectModel.php line 816](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L816)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-hideCMSCategoryPosition"></a>hideCMSCategoryPosition

```php
string CMSCategoryCore::hideCMSCategoryPosition(string $name)
```

Hide CMSCategory prefix used for position



* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L372)


#### Arguments
* $name **string** - CMSCategory name



### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1116](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1116)


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
* Source: [classes/ObjectModel.php line 1135](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1135)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer**



### <a name="method-isAssociatedToGroupShop"></a>isAssociatedToGroupShop

```php
boolean ObjectModelCore::isAssociatedToGroupShop(integer $id_group_shop)
```

Check if current object is associated to a group shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1003](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1003)


#### Arguments
* $id_group_shop **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 954](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L954)


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
* Source: [classes/ObjectModel.php line 1099](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1099)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1037](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1037)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 611](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L611)


#### Arguments
* $fields **mixed**
* $fields_array **mixed**
* $id_language **mixed**



### <a name="method-recurseCMSCategory"></a>recurseCMSCategory

```php
mixed CMSCategoryCore::recurseCMSCategory($categories, $current, $id_cms_category, $id_selected, $is_html)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L204)


#### Arguments
* $categories **mixed**
* $current **mixed**
* $id_cms_category **mixed**
* $id_selected **mixed**
* $is_html **mixed**



### <a name="method-recurseLiteCategTree"></a>recurseLiteCategTree

```php
array CMSCategoryCore::recurseLiteCategTree(integer $max_depth, integer $currentDepth, $id_lang, array $excluded_ids_array, \Link $link)
```

Recursive scan of subcategories



* Visibility: **public**
* Source: [classes/CMSCategory.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L129)


#### Arguments
* $max_depth **integer** - Maximum depth of the tree (i.e. 2 =&gt; 3 levels depth)
* $currentDepth **integer** - specify the current depth in the tree (don&#039;t use it, only for rucursivity!)
* $id_lang **mixed**
* $excluded_ids_array **array** - specify a list of ids to exclude of results
* $link **[Link](class.LinkCore.md)**



### <a name="method-recursiveDelete"></a>recursiveDelete

```php
mixed CMSCategoryCore::recursiveDelete($to_delete, array $id_cms_category)
```

Recursively add specified CMSCategory childs to $toDelete array



* Visibility: **protected**
* Source: [classes/CMSCategory.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L223)


#### Arguments
* $to_delete **mixed**
* $id_cms_category **array** - Parent CMSCategory ID



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L360)


#### Arguments
* $null_values **boolean**
* $autodate **boolean**



### <a name="method-searchByName"></a>searchByName

```php
array CMSCategoryCore::searchByName(integer $id_lang, string $query, boolean $unrestricted)
```

Light back office search for categories



* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 481](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L481)


#### Arguments
* $id_lang **integer** - Language ID
* $query **string** - Searched string
* $unrestricted **boolean** - allows search without lang and includes first CMSCategory and exact match



### <a name="method-searchByNameAndParentCMSCategoryId"></a>searchByNameAndParentCMSCategoryId

```php
array CMSCategoryCore::searchByNameAndParentCMSCategoryId(integer $id_lang, string $CMSCategory_name, integer $id_parent_CMSCategory)
```

Retrieve CMSCategory by name and parent CMSCategory id



* Visibility: **public**
* This method is **static**.
* Source: [classes/CMSCategory.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L506)


#### Arguments
* $id_lang **integer** - Language ID
* $CMSCategory_name **string** - Searched CMSCategory name
* $id_parent_CMSCategory **integer** - parent CMSCategory ID



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static
Remove this in 1.6 !



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1207](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1207)




### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 575](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L575)




### <a name="method-update"></a>update

```php
mixed CMSCategoryCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L110)


#### Arguments
* $null_values **mixed**



### <a name="method-updatePosition"></a>updatePosition

```php
mixed CMSCategoryCore::updatePosition($way, $position)
```





* Visibility: **public**
* Source: [classes/CMSCategory.php line 548](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/CMSCategory.php#L548)


#### Arguments
* $way **mixed**
* $position **mixed**



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 772](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L772)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 778](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L778)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 710](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L710)


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
* Source: [classes/ObjectModel.php line 649](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L649)


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
* Source: [classes/ObjectModel.php line 675](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L675)


#### Arguments
* $die **boolean**
* $error_return **boolean**


