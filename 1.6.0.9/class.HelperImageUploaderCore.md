Class HelperImageUploaderCore
=====================





* Class name: HelperImageUploaderCore
* Parent class: [HelperUploader](class.HelperUploaderCore.md)
* Source: [classes/helper/HelperImageUploader.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperImageUploader.php#L27)


Contents
--------


### Properties

* [$_template](#property-$_template)

### Methods

* [__construct](#method-__construct)
* [_getFileSize](#method-_getFileSize)
* [_getServerVars](#method-_getServerVars)
* [_normalizeDirectory](#method-_normalizeDirectory)
* [checkUploadError](#method-checkUploadError)
* [getAcceptTypes](#method-getAcceptTypes)
* [getContext](#method-getContext)
* [getDropZone](#method-getDropZone)
* [getFilePath](#method-getFilePath)
* [getFiles](#method-getFiles)
* [getId](#method-getId)
* [getMaxFiles](#method-getMaxFiles)
* [getMaxSize](#method-getMaxSize)
* [getName](#method-getName)
* [getPostMaxSize](#method-getPostMaxSize)
* [getPostMaxSizeBytes](#method-getPostMaxSizeBytes)
* [getSavePath](#method-getSavePath)
* [getTemplate](#method-getTemplate)
* [getTemplateDirectory](#method-getTemplateDirectory)
* [getTemplateFile](#method-getTemplateFile)
* [getTitle](#method-getTitle)
* [getUniqueFileName](#method-getUniqueFileName)
* [getUrl](#method-getUrl)
* [isMultiple](#method-isMultiple)
* [process](#method-process)
* [render](#method-render)
* [setAcceptTypes](#method-setAcceptTypes)
* [setContext](#method-setContext)
* [setDropZone](#method-setDropZone)
* [setFiles](#method-setFiles)
* [setId](#method-setId)
* [setMaxFiles](#method-setMaxFiles)
* [setMaxSize](#method-setMaxSize)
* [setMultiple](#method-setMultiple)
* [setName](#method-setName)
* [setPostMaxSize](#method-setPostMaxSize)
* [setSavePath](#method-setSavePath)
* [setTemplate](#method-setTemplate)
* [setTemplateDirectory](#method-setTemplateDirectory)
* [setTitle](#method-setTitle)
* [setUrl](#method-setUrl)
* [setUseAjax](#method-setUseAjax)
* [upload](#method-upload)
* [useAjax](#method-useAjax)
* [validate](#method-validate)




Properties
----------


### <a name="property-$_template"></a>$_template

```php
protected mixed $_template
```





* Visibility: **protected**
* This property is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L44).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed UploaderCore::__construct($name)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Uploader.php#L37)


#### Arguments
* $name **mixed**



### <a name="method-_getFileSize"></a>_getFileSize

```php
mixed UploaderCore::_getFileSize($file_path, $clear_stat_cache)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Uploader.php#L261)


#### Arguments
* $file_path **mixed**
* $clear_stat_cache **mixed**



### <a name="method-_getServerVars"></a>_getServerVars

```php
mixed UploaderCore::_getServerVars($var)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 268](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Uploader.php#L268)


#### Arguments
* $var **mixed**



### <a name="method-_normalizeDirectory"></a>_normalizeDirectory

```php
mixed UploaderCore::_normalizeDirectory($directory)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 273](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Uploader.php#L273)


#### Arguments
* $directory **mixed**



### <a name="method-checkUploadError"></a>checkUploadError

```php
mixed UploaderCore::checkUploadError($error_code)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 193](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Uploader.php#L193)


#### Arguments
* $error_code **mixed**



### <a name="method-getAcceptTypes"></a>getAcceptTypes

```php
mixed UploaderCore::getAcceptTypes()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Uploader.php#L49)




### <a name="method-getContext"></a>getContext

```php
mixed HelperUploaderCore::getContext()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L56)




### <a name="method-getDropZone"></a>getDropZone

```php
mixed HelperUploaderCore::getDropZone()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L70)




### <a name="method-getFilePath"></a>getFilePath

```php
mixed UploaderCore::getFilePath($file_name)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Uploader.php#L54)


#### Arguments
* $file_name **mixed**



### <a name="method-getFiles"></a>getFiles

```php
mixed HelperUploaderCore::getFiles()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L98)




### <a name="method-getId"></a>getId

```php
mixed HelperUploaderCore::getId()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L84)




### <a name="method-getMaxFiles"></a>getMaxFiles

```php
mixed HelperUploaderCore::getMaxFiles()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L112)




### <a name="method-getMaxSize"></a>getMaxSize

```php
mixed UploaderCore::getMaxSize()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Uploader.php#L76)




### <a name="method-getName"></a>getName

```php
mixed HelperUploaderCore::getName()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L129)




### <a name="method-getPostMaxSize"></a>getPostMaxSize

```php
mixed HelperUploaderCore::getPostMaxSize()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L140)




### <a name="method-getPostMaxSizeBytes"></a>getPostMaxSizeBytes

```php
mixed UploaderCore::getPostMaxSizeBytes()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Uploader.php#L101)




### <a name="method-getSavePath"></a>getSavePath

```php
mixed UploaderCore::getSavePath()
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Uploader.php#L119)




### <a name="method-getTemplate"></a>getTemplate

```php
mixed HelperUploaderCore::getTemplate()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L154)




### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

```php
mixed HelperUploaderCore::getTemplateDirectory()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L168)




### <a name="method-getTemplateFile"></a>getTemplateFile

```php
mixed HelperUploaderCore::getTemplateFile($template)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L176)


#### Arguments
* $template **mixed**



### <a name="method-getTitle"></a>getTitle

```php
mixed HelperUploaderCore::getTitle()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L208)




### <a name="method-getUniqueFileName"></a>getUniqueFileName

```php
mixed UploaderCore::getUniqueFileName($prefix)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Uploader.php#L127)


#### Arguments
* $prefix **mixed**



### <a name="method-getUrl"></a>getUrl

```php
mixed HelperUploaderCore::getUrl()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L219)




### <a name="method-isMultiple"></a>isMultiple

```php
mixed HelperUploaderCore::isMultiple()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L230)




### <a name="method-process"></a>process

```php
mixed UploaderCore::process($dest)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Uploader.php#L132)


#### Arguments
* $dest **mixed**



### <a name="method-render"></a>render

```php
mixed HelperUploaderCore::render()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L235)




### <a name="method-setAcceptTypes"></a>setAcceptTypes

```php
mixed UploaderCore::setAcceptTypes($value)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Uploader.php#L43)


#### Arguments
* $value **mixed**



### <a name="method-setContext"></a>setContext

```php
mixed HelperUploaderCore::setContext($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L50)


#### Arguments
* $value **mixed**



### <a name="method-setDropZone"></a>setDropZone

```php
mixed HelperUploaderCore::setDropZone($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L64)


#### Arguments
* $value **mixed**



### <a name="method-setFiles"></a>setFiles

```php
mixed HelperUploaderCore::setFiles($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L92)


#### Arguments
* $value **mixed**



### <a name="method-setId"></a>setId

```php
mixed HelperUploaderCore::setId($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L78)


#### Arguments
* $value **mixed**



### <a name="method-setMaxFiles"></a>setMaxFiles

```php
mixed HelperUploaderCore::setMaxFiles($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L106)


#### Arguments
* $value **mixed**



### <a name="method-setMaxSize"></a>setMaxSize

```php
mixed UploaderCore::setMaxSize($value)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Uploader.php#L70)


#### Arguments
* $value **mixed**



### <a name="method-setMultiple"></a>setMultiple

```php
mixed HelperUploaderCore::setMultiple($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L117)


#### Arguments
* $value **mixed**



### <a name="method-setName"></a>setName

```php
mixed HelperUploaderCore::setName($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L123)


#### Arguments
* $value **mixed**



### <a name="method-setPostMaxSize"></a>setPostMaxSize

```php
mixed HelperUploaderCore::setPostMaxSize($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L134)


#### Arguments
* $value **mixed**



### <a name="method-setSavePath"></a>setSavePath

```php
mixed UploaderCore::setSavePath($value)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Uploader.php#L95)


#### Arguments
* $value **mixed**



### <a name="method-setTemplate"></a>setTemplate

```php
mixed HelperUploaderCore::setTemplate($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L148)


#### Arguments
* $value **mixed**



### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

```php
mixed HelperUploaderCore::setTemplateDirectory($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L162)


#### Arguments
* $value **mixed**



### <a name="method-setTitle"></a>setTitle

```php
mixed HelperUploaderCore::setTitle($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L202)


#### Arguments
* $value **mixed**



### <a name="method-setUrl"></a>setUrl

```php
mixed HelperUploaderCore::setUrl($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L213)


#### Arguments
* $value **mixed**



### <a name="method-setUseAjax"></a>setUseAjax

```php
mixed HelperUploaderCore::setUseAjax($value)
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L224)


#### Arguments
* $value **mixed**



### <a name="method-upload"></a>upload

```php
mixed UploaderCore::upload($file, $dest)
```





* Visibility: **public**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Uploader.php#L161)


#### Arguments
* $file **mixed**
* $dest **mixed**



### <a name="method-useAjax"></a>useAjax

```php
mixed HelperUploaderCore::useAjax()
```





* Visibility: **public**
* This method is defined by [HelperUploaderCore](class.HelperUploaderCore.md).
* Source: [classes/helper/HelperUploader.php line 279](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/helper/HelperUploader.php#L279)




### <a name="method-validate"></a>validate

```php
mixed UploaderCore::validate($file)
```





* Visibility: **protected**
* This method is defined by [UploaderCore](class.UploaderCore.md).
* Source: [classes/Uploader.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Uploader.php#L225)


#### Arguments
* $file **mixed**


