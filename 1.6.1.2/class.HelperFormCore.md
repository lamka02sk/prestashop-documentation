Class HelperFormCore
=====================





* Class name: HelperFormCore
* Parent class: [Helper](class.HelperCore.md)
* Source: [classes/helper/HelperForm.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L30)


Contents
--------


### Properties

* [$allow_employee_form_lang](#property-$allow_employee_form_lang)
* [$back_url](#property-$back_url)
* [$default_form_language](#property-$default_form_language)
* [$fields_form](#property-$fields_form)
* [$fields_value](#property-$fields_value)
* [$first_call](#property-$first_call)
* [$id](#property-$id)
* [$languages](#property-$languages)
* [$name_controller](#property-$name_controller)
* [$show_cancel_button](#property-$show_cancel_button)
* [$submit_action](#property-$submit_action)
* [$title](#property-$title)
* [$token](#property-$token)
* [$base_folder](#property-$base_folder)
* [$base_tpl](#property-$base_tpl)
* [$bootstrap](#property-$bootstrap)
* [$context](#property-$context)
* [$currentIndex](#property-$currentIndex)
* [$identifier](#property-$identifier)
* [$module](#property-$module)
* [$override_folder](#property-$override_folder)
* [$ps_help_context](#property-$ps_help_context)
* [$show_toolbar](#property-$show_toolbar)
* [$table](#property-$table)
* [$toolbar_btn](#property-$toolbar_btn)
* [$toolbar_scroll](#property-$toolbar_scroll)
* [$tpl](#property-$tpl)
* [$tpl_vars](#property-$tpl_vars)

### Methods

* [__construct](#method-__construct)
* [createTemplate](#method-createTemplate)
* [generate](#method-generate)
* [generateForm](#method-generateForm)
* [getFieldsRequired](#method-getFieldsRequired)
* [l](#method-l)
* [renderAdminCategorieTree](#method-renderAdminCategorieTree)
* [renderAssoShop](#method-renderAssoShop)
* [renderCategoryTree](#method-renderCategoryTree)
* [renderModulesList](#method-renderModulesList)
* [renderRequiredFields](#method-renderRequiredFields)
* [renderShopList](#method-renderShopList)
* [setTpl](#method-setTpl)




Properties
----------


### <a name="property-$allow_employee_form_lang"></a>$allow_employee_form_lang

```php
public mixed $allow_employee_form_lang = null
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L51).


### <a name="property-$back_url"></a>$back_url

```php
public mixed $back_url = '#'
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L53).


### <a name="property-$default_form_language"></a>$default_form_language

```php
public mixed $default_form_language = null
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L50).


### <a name="property-$fields_form"></a>$fields_form

```php
protected array $fields_form = array()
```





* Visibility: **protected**
* Source: [classes/helper/HelperForm.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L36).


### <a name="property-$fields_value"></a>$fields_value

```php
public array $fields_value = array()
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L39).


### <a name="property-$first_call"></a>$first_call

```php
public mixed $first_call = true
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L33).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L32).


### <a name="property-$languages"></a>$languages

```php
public mixed $languages = null
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L49).


### <a name="property-$name_controller"></a>$name_controller

```php
public mixed $name_controller = ''
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L40).


### <a name="property-$show_cancel_button"></a>$show_cancel_button

```php
public mixed $show_cancel_button = false
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L52).


### <a name="property-$submit_action"></a>$submit_action

```php
public string $submit_action
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L46).


### <a name="property-$title"></a>$title

```php
public string $title = null
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L43).


### <a name="property-$token"></a>$token

```php
public mixed $token
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L48).


### <a name="property-$base_folder"></a>$base_folder

```php
public string $base_folder
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L47).


### <a name="property-$base_tpl"></a>$base_tpl

```php
public string $base_tpl = 'content.tpl'
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L60).


### <a name="property-$bootstrap"></a>$bootstrap

```php
public mixed $bootstrap = false
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L39).


### <a name="property-$context"></a>$context

```php
public mixed $context
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L37).


### <a name="property-$currentIndex"></a>$currentIndex

```php
public mixed $currentIndex
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L29).


### <a name="property-$identifier"></a>$identifier

```php
public mixed $identifier
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L31).


### <a name="property-$module"></a>$module

```php
public \Module $module
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L44).


### <a name="property-$override_folder"></a>$override_folder

```php
public string $override_folder
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L50).


### <a name="property-$ps_help_context"></a>$ps_help_context

```php
public mixed $ps_help_context
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L34).


### <a name="property-$show_toolbar"></a>$show_toolbar

```php
public mixed $show_toolbar = true
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L36).


### <a name="property-$table"></a>$table

```php
public mixed $table = 'configuration'
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L30).


### <a name="property-$toolbar_btn"></a>$toolbar_btn

```php
public mixed $toolbar_btn
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L33).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
public mixed $toolbar_scroll = false
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L38).


### <a name="property-$tpl"></a>$tpl

```php
protected \Smarty_Internal_Template $tpl
```





* Visibility: **protected**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L55).


### <a name="property-$tpl_vars"></a>$tpl_vars

```php
public mixed $tpl_vars = array()
```





* Visibility: **public**
* This property is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L62).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HelperFormCore::__construct()
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L55)




### <a name="method-createTemplate"></a>createTemplate

```php
\Smarty_Internal_Template HelperCore::createTemplate(string $tpl_name)
```

Create a template from the override file, else from the base file.



* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L80)


#### Arguments
* $tpl_name **string** - filename



### <a name="method-generate"></a>generate

```php
mixed HelperFormCore::generate()
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L68)




### <a name="method-generateForm"></a>generateForm

```php
mixed HelperFormCore::generateForm($fields_form)
```





* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L62)


#### Arguments
* $fields_form **mixed**



### <a name="method-getFieldsRequired"></a>getFieldsRequired

```php
mixed HelperFormCore::getFieldsRequired()
```

Return true if there are required fields



* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 268](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L268)




### <a name="method-l"></a>l

```php
string HelperCore::l(mixed $string, string $class, boolean $addslashes, boolean $htmlentities)
```

use translations files to replace english expression.



* Visibility: **protected**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 299](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L299)


#### Arguments
* $string **mixed** - term or expression in english
* $class **string**
* $addslashes **boolean** - if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().
* $htmlentities **boolean** - if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)



### <a name="method-renderAdminCategorieTree"></a>renderAdminCategorieTree

```php
mixed HelperCore::renderAdminCategorieTree($translations, $selected_cat, $input_name, $use_radio, $use_search, $disabled_categories, $use_in_popup)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L119)


#### Arguments
* $translations **mixed**
* $selected_cat **mixed**
* $input_name **mixed**
* $use_radio **mixed**
* $use_search **mixed**
* $disabled_categories **mixed**
* $use_in_popup **mixed**



### <a name="method-renderAssoShop"></a>renderAssoShop

```php
string HelperFormCore::renderAssoShop($disable_shared, $template_directory)
```

Render an area to determinate shop association



* Visibility: **public**
* Source: [classes/helper/HelperForm.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/HelperForm.php#L287)


#### Arguments
* $disable_shared **mixed**
* $template_directory **mixed**



### <a name="method-renderCategoryTree"></a>renderCategoryTree

```php
string HelperCore::renderCategoryTree(array $root, array $selected_cat, string $input_name, boolean $use_radio, boolean $use_search, array $disabled_categories)
```





* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L166)


#### Arguments
* $root **array** - array with the name and ID of the tree root category, if null the Shop&#039;s root category will be used
* $selected_cat **array** - array of selected categories
            Format
                Array
                (
                     [0] =&gt; 1
                 [1] =&gt; 2
            )
                OR
            Array
            (
                 [1] =&gt; Array
                      (
                            [id_category] =&gt; 1
                            [name] =&gt; Home page
                      )
            )
* $input_name **string** - name of input
* $use_radio **boolean** - use radio tree or checkbox tree
* $use_search **boolean** - display a find category search box
* $disabled_categories **array**



### <a name="method-renderModulesList"></a>renderModulesList

```php
mixed HelperCore::renderModulesList($modules_list)
```





* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 350](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L350)


#### Arguments
* $modules_list **mixed**



### <a name="method-renderRequiredFields"></a>renderRequiredFields

```php
string HelperCore::renderRequiredFields(string $class_name, string $identifier, array $table_fields)
```

Render a form with potentials required fields



* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L318)


#### Arguments
* $class_name **string**
* $identifier **string**
* $table_fields **array**



### <a name="method-renderShopList"></a>renderShopList

```php
string HelperCore::renderShopList()
```

Render shop list



* Visibility: **public**
* This method is **static**.
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 374](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L374)




### <a name="method-setTpl"></a>setTpl

```php
mixed HelperCore::setTpl($tpl)
```





* Visibility: **public**
* This method is defined by [HelperCore](class.HelperCore.md).
* Source: [classes/helper/Helper.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/helper/Helper.php#L69)


#### Arguments
* $tpl **mixed**


