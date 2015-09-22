Class AdminStockManagementControllerCore
=====================





* Class name: AdminStockManagementControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminStockManagementController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminStockManagementController.php#L30)


Contents
--------



### Methods

* [__construct](#method-__construct)
* [displayAddstockLink](#method-displayAddstockLink)
* [displayRemovestockLink](#method-displayRemovestockLink)
* [displayTransferstockLink](#method-displayTransferstockLink)
* [getList](#method-getList)
* [init](#method-init)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initToolbar](#method-initToolbar)
* [postProcess](#method-postProcess)
* [renderDetails](#method-renderDetails)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [skipActionByStock](#method-skipActionByStock)






Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminStockManagementControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminStockManagementController.php#L32)




### <a name="method-displayAddstockLink"></a>displayAddstockLink

```php
string AdminStockManagementControllerCore::displayAddstockLink(string $token, integer $id)
```

Display addstock action link



* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 1116](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminStockManagementController.php#L1116)


#### Arguments
* $token **string** - the token to add to the link
* $id **integer** - the identifier to add to the link



### <a name="method-displayRemovestockLink"></a>displayRemovestockLink

```php
string AdminStockManagementControllerCore::displayRemovestockLink(string $token, integer $id)
```

Display removestock action link



* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 1137](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminStockManagementController.php#L1137)


#### Arguments
* $token **string** - the token to add to the link
* $id **integer** - the identifier to add to the link



### <a name="method-displayTransferstockLink"></a>displayTransferstockLink

```php
string AdminStockManagementControllerCore::displayTransferstockLink(string $token, integer $id)
```

Display transferstock action link



* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 1158](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminStockManagementController.php#L1158)


#### Arguments
* $token **string** - the token to add to the link
* $id **integer** - the identifier to add to the link



### <a name="method-getList"></a>getList

```php
mixed AdminStockManagementControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)
```

AdminController::getList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 882](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminStockManagementController.php#L882)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-init"></a>init

```php
mixed AdminStockManagementControllerCore::init()
```

AdminController::init() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 785](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminStockManagementController.php#L785)




### <a name="method-initContent"></a>initContent

```php
mixed AdminStockManagementControllerCore::initContent()
```

AdminController::initContent() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 967](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminStockManagementController.php#L967)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminStockManagementControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminStockManagementController.php#L79)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminStockManagementControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 1173](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminStockManagementController.php#L1173)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminStockManagementControllerCore::initToolbar()
```

assign default action in toolbar_btn smarty var, if they are not set.

uses override to specifically add, modify or remove items

* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 748](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminStockManagementController.php#L748)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminStockManagementControllerCore::postProcess()
```

AdminController::postProcess() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 541](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminStockManagementController.php#L541)




### <a name="method-renderDetails"></a>renderDetails

```php
mixed AdminStockManagementControllerCore::renderDetails()
```





* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 808](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminStockManagementController.php#L808)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminStockManagementControllerCore::renderForm()
```

AdminController::renderForm() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminStockManagementController.php#L131)




### <a name="method-renderList"></a>renderList

```php
mixed AdminStockManagementControllerCore::renderList()
```

AdminController::renderList() override



* Visibility: **public**
* Source: [controllers/admin/AdminStockManagementController.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminStockManagementController.php#L95)




### <a name="method-skipActionByStock"></a>skipActionByStock

```php
mixed AdminStockManagementControllerCore::skipActionByStock(array $item, $is_product_variation)
```

Check stock for a given product or product attribute
and manage available actions in consequence



* Visibility: **protected**
* Source: [controllers/admin/AdminStockManagementController.php line 942](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminStockManagementController.php#L942)


#### Arguments
* $item **array** - reference to the current item
* $is_product_variation **mixed**

