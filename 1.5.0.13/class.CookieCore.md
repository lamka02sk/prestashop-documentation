Class CookieCore
=====================





* Class name: CookieCore
* Source: [classes/Cookie.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L28)


Contents
--------


### Properties

* [$_cipherTool](#property-$_cipherTool)
* [$_content](#property-$_content)
* [$_domain](#property-$_domain)
* [$_expire](#property-$_expire)
* [$_iv](#property-$_iv)
* [$_key](#property-$_key)
* [$_modified](#property-$_modified)
* [$_name](#property-$_name)
* [$_path](#property-$_path)

### Methods

* [__construct](#method-__construct)
* [__get](#method-__get)
* [__isset](#method-__isset)
* [__set](#method-__set)
* [__unset](#method-__unset)
* [_setcookie](#method-_setcookie)
* [exists](#method-exists)
* [getDomain](#method-getDomain)
* [getFamily](#method-getFamily)
* [getName](#method-getName)
* [isLogged](#method-isLogged)
* [isLoggedBack](#method-isLoggedBack)
* [logout](#method-logout)
* [makeNewLog](#method-makeNewLog)
* [mylogout](#method-mylogout)
* [setExpire](#method-setExpire)
* [unsetFamily](#method-unsetFamily)
* [update](#method-update)
* [write](#method-write)




Properties
----------


### <a name="property-$_cipherTool"></a>$_cipherTool

```php
protected array $_cipherTool
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L46).


### <a name="property-$_content"></a>$_content

```php
protected array $_content
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L31).


### <a name="property-$_domain"></a>$_domain

```php
protected array $_domain
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L40).


### <a name="property-$_expire"></a>$_expire

```php
protected array $_expire
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L37).


### <a name="property-$_iv"></a>$_iv

```php
protected array $_iv
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L52).


### <a name="property-$_key"></a>$_key

```php
protected array $_key
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L49).


### <a name="property-$_modified"></a>$_modified

```php
protected mixed $_modified = false
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L54).


### <a name="property-$_name"></a>$_name

```php
protected array $_name
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L34).


### <a name="property-$_path"></a>$_path

```php
protected array $_path
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L43).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CookieCore::__construct($name, $path, $expire)
```

Get data if the cookie exists and else initialize an new one



* Visibility: **public**
* Source: [classes/Cookie.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L62)


#### Arguments
* $name **mixed** - Cookie name before encrypting
* $path **mixed**
* $expire **mixed**



### <a name="method-__get"></a>__get

```php
string CookieCore::__get($key)
```

Magic method wich return cookie data from _content array



* Visibility: **public**
* Source: [classes/Cookie.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L113)


#### Arguments
* $key **mixed** - key wanted



### <a name="method-__isset"></a>__isset

```php
boolean CookieCore::__isset($key)
```

Magic method which check if key exists in the cookie



* Visibility: **public**
* Source: [classes/Cookie.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L124)


#### Arguments
* $key **mixed** - key wanted



### <a name="method-__set"></a>__set

```php
mixed CookieCore::__set($key, $value)
```

Magic method wich add data into _content array



* Visibility: **public**
* Source: [classes/Cookie.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L135)


#### Arguments
* $key **mixed** - key desired
* $value **mixed** - value corresponding to the key



### <a name="method-__unset"></a>__unset

```php
mixed CookieCore::__unset($key)
```

Magic method wich delete data into _content array



* Visibility: **public**
* Source: [classes/Cookie.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L152)


#### Arguments
* $key **mixed** - key wanted



### <a name="method-_setcookie"></a>_setcookie

```php
mixed CookieCore::_setcookie($cookie)
```

Setcookie according to php version



* Visibility: **protected**
* Source: [classes/Cookie.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L287)


#### Arguments
* $cookie **mixed**



### <a name="method-exists"></a>exists

```php
boolean CookieCore::exists()
```

Check if the cookie exists



* Visibility: **public**
* Source: [classes/Cookie.php line 362](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L362)




### <a name="method-getDomain"></a>getDomain

```php
mixed CookieCore::getDomain()
```





* Visibility: **protected**
* Source: [classes/Cookie.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L82)




### <a name="method-getFamily"></a>getFamily

```php
mixed CookieCore::getFamily($origin)
```

Get a family of variables (e.g. "filter_")



* Visibility: **public**
* Source: [classes/Cookie.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L327)


#### Arguments
* $origin **mixed**



### <a name="method-getName"></a>getName

```php
String CookieCore::getName()
```





* Visibility: **public**
* Source: [classes/Cookie.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L351)




### <a name="method-isLogged"></a>isLogged

```php
boolean CookieCore::isLogged($withGuest)
```

Check customer informations saved into cookie and return customer validity



* Visibility: **public**
* Source: [classes/Cookie.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L166)


#### Arguments
* $withGuest **mixed**



### <a name="method-isLoggedBack"></a>isLoggedBack

```php
boolean CookieCore::isLoggedBack()
```

Check employee informations saved into cookie and return employee validity



* Visibility: **public**
* Source: [classes/Cookie.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L184)




### <a name="method-logout"></a>logout

```php
mixed CookieCore::logout()
```

Delete cookie
As of version 1.5 don't call this function, use Customer::logout() or Employee::logout() instead;



* Visibility: **public**
* Source: [classes/Cookie.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L199)




### <a name="method-makeNewLog"></a>makeNewLog

```php
mixed CookieCore::makeNewLog()
```





* Visibility: **public**
* Source: [classes/Cookie.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L232)




### <a name="method-mylogout"></a>mylogout

```php
mixed CookieCore::mylogout()
```

Soft logout, delete everything links to the customer
but leave there affiliate's informations.

As of version 1.5 don't call this function, use Customer::mylogout() instead;

* Visibility: **public**
* Source: [classes/Cookie.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L213)




### <a name="method-setExpire"></a>setExpire

```php
mixed CookieCore::setExpire(integer $expire)
```

Set expiration date



* Visibility: **public**
* Source: [classes/Cookie.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L102)


#### Arguments
* $expire **integer** - Expiration time from now



### <a name="method-unsetFamily"></a>unsetFamily

```php
mixed CookieCore::unsetFamily($origin)
```





* Visibility: **public**
* Source: [classes/Cookie.php line 341](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L341)


#### Arguments
* $origin **mixed**



### <a name="method-update"></a>update

```php
mixed CookieCore::update($nullValues)
```

Get cookie content



* Visibility: **public**
* Source: [classes/Cookie.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L243)


#### Arguments
* $nullValues **mixed**



### <a name="method-write"></a>write

```php
mixed CookieCore::write()
```

Save cookie with setcookie()



* Visibility: **public**
* Source: [classes/Cookie.php line 308](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Cookie.php#L308)



