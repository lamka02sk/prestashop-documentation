Class SearchCore
=====================





* Class name: SearchCore
* Source: [classes/Search.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Search.php#L94)


Contents
--------



### Methods

* [find](#method-find)
* [getAttributes](#method-getAttributes)
* [getFeatures](#method-getFeatures)
* [getProductsToIndex](#method-getProductsToIndex)
* [getTags](#method-getTags)
* [indexation](#method-indexation)
* [removeProductsSearchIndex](#method-removeProductsSearchIndex)
* [sanitize](#method-sanitize)
* [saveIndex](#method-saveIndex)
* [searchTag](#method-searchTag)
* [setProductsAsIndexed](#method-setProductsAsIndexed)






Methods
-------


### <a name="method-find"></a>find

```php
mixed SearchCore::find($id_lang, $expr, $page_number, $page_size, $order_by, $order_way, $ajax, $use_cookie, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Search.php#L177)


#### Arguments
* $id_lang **mixed**
* $expr **mixed**
* $page_number **mixed**
* $page_size **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $ajax **mixed**
* $use_cookie **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getAttributes"></a>getAttributes

```php
mixed SearchCore::getAttributes($db, $id_product, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 367](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Search.php#L367)


#### Arguments
* $db **mixed**
* $id_product **mixed**
* $id_lang **mixed**



### <a name="method-getFeatures"></a>getFeatures

```php
mixed SearchCore::getFeatures($db, $id_product, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 384](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Search.php#L384)


#### Arguments
* $db **mixed**
* $id_product **mixed**
* $id_lang **mixed**



### <a name="method-getProductsToIndex"></a>getProductsToIndex

```php
mixed SearchCore::getProductsToIndex($total_languages, $id_product, $limit, $weight_array)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Search.php line 399](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Search.php#L399)


#### Arguments
* $total_languages **mixed**
* $id_product **mixed**
* $limit **mixed**
* $weight_array **mixed**



### <a name="method-getTags"></a>getTags

```php
mixed SearchCore::getTags($db, $id_product, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 355](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Search.php#L355)


#### Arguments
* $db **mixed**
* $id_product **mixed**
* $id_lang **mixed**



### <a name="method-indexation"></a>indexation

```php
mixed SearchCore::indexation($full, $id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 475](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Search.php#L475)


#### Arguments
* $full **mixed**
* $id_product **mixed**



### <a name="method-removeProductsSearchIndex"></a>removeProductsSearchIndex

```php
mixed SearchCore::removeProductsSearchIndex($products)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 657](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Search.php#L657)


#### Arguments
* $products **mixed**



### <a name="method-sanitize"></a>sanitize

```php
mixed SearchCore::sanitize($string, $id_lang, $indexation, $iso_code)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Search.php#L96)


#### Arguments
* $string **mixed**
* $id_lang **mixed**
* $indexation **mixed**
* $iso_code **mixed**



### <a name="method-saveIndex"></a>saveIndex

```php
mixed SearchCore::saveIndex($queryArray3)
```

$queryArray3 is automatically emptied in order to be reused immediatly



* Visibility: **protected**
* This method is **static**.
* Source: [classes/Search.php line 672](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Search.php#L672)


#### Arguments
* $queryArray3 **mixed**



### <a name="method-searchTag"></a>searchTag

```php
mixed SearchCore::searchTag($id_lang, $tag, $count, $pageNumber, $pageSize, $orderBy, $orderWay, $useCookie, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Search.php line 683](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Search.php#L683)


#### Arguments
* $id_lang **mixed**
* $tag **mixed**
* $count **mixed**
* $pageNumber **mixed**
* $pageSize **mixed**
* $orderBy **mixed**
* $orderWay **mixed**
* $useCookie **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-setProductsAsIndexed"></a>setProductsAsIndexed

```php
mixed SearchCore::setProductsAsIndexed($products)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Search.php line 665](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Search.php#L665)


#### Arguments
* $products **mixed**


