Class RijndaelCore
=====================





* Class name: RijndaelCore
* Source: [classes/Rijndael.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Rijndael.php#L28)


Contents
--------


### Properties

* [$_iv](#property-$_iv)
* [$_key](#property-$_key)

### Methods

* [__construct](#method-__construct)
* [decrypt](#method-decrypt)
* [encrypt](#method-encrypt)




Properties
----------


### <a name="property-$_iv"></a>$_iv

```php
protected mixed $_iv
```





* Visibility: **protected**
* Source: [classes/Rijndael.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Rijndael.php#L31).


### <a name="property-$_key"></a>$_key

```php
protected mixed $_key
```





* Visibility: **protected**
* Source: [classes/Rijndael.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Rijndael.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed RijndaelCore::__construct($key, $iv)
```





* Visibility: **public**
* Source: [classes/Rijndael.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Rijndael.php#L33)


#### Arguments
* $key **mixed**
* $iv **mixed**



### <a name="method-decrypt"></a>decrypt

```php
mixed RijndaelCore::decrypt($ciphertext)
```





* Visibility: **public**
* Source: [classes/Rijndael.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Rijndael.php#L49)


#### Arguments
* $ciphertext **mixed**



### <a name="method-encrypt"></a>encrypt

```php
mixed RijndaelCore::encrypt($plaintext)
```





* Visibility: **public**
* Source: [classes/Rijndael.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/Rijndael.php#L40)


#### Arguments
* $plaintext **mixed**


