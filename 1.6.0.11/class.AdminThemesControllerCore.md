Class AdminThemesControllerCore
=====================





* Class name: AdminThemesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminThemesController.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L28)


Contents
--------

### Constants

* [MAX_NAME_LENGTH](#constant-MAX_NAME_LENGTH)

### Properties

* [$check_features](#property-$check_features)
* [$check_features_version](#property-$check_features_version)
* [$className](#property-$className)
* [$img_error](#property-$img_error)
* [$table](#property-$table)
* [$toolbar_scroll](#property-$toolbar_scroll)
* [$_defaultOrderBy](#property-$_defaultOrderBy)
* [$_defaultOrderWay](#property-$_defaultOrderWay)
* [$_default_pagination](#property-$_default_pagination)
* [$_filter](#property-$_filter)
* [$_filterHaving](#property-$_filterHaving)
* [$_group](#property-$_group)
* [$_having](#property-$_having)
* [$_includeContainer](#property-$_includeContainer)
* [$_join](#property-$_join)
* [$_languages](#property-$_languages)
* [$_list](#property-$_list)
* [$_listTotal](#property-$_listTotal)
* [$_listsql](#property-$_listsql)
* [$_orderBy](#property-$_orderBy)
* [$_orderWay](#property-$_orderWay)
* [$_pagination](#property-$_pagination)
* [$_redirect](#property-$_redirect)
* [$_select](#property-$_select)
* [$_tmpTableFilter](#property-$_tmpTableFilter)
* [$_where](#property-$_where)
* [$action](#property-$action)
* [$actions](#property-$actions)
* [$actions_available](#property-$actions_available)
* [$admin_webpath](#property-$admin_webpath)
* [$allow_employee_form_lang](#property-$allow_employee_form_lang)
* [$allow_export](#property-$allow_export)
* [$base_tpl_form](#property-$base_tpl_form)
* [$base_tpl_view](#property-$base_tpl_view)
* [$bo_theme](#property-$bo_theme)
* [$bootstrap](#property-$bootstrap)
* [$boxes](#property-$boxes)
* [$breadcrumbs](#property-$breadcrumbs)
* [$bulk_actions](#property-$bulk_actions)
* [$cache_lang](#property-$cache_lang)
* [$colorOnBackground](#property-$colorOnBackground)
* [$confirmations](#property-$confirmations)
* [$content](#property-$content)
* [$controller_name](#property-$controller_name)
* [$currentIndex](#property-$currentIndex)
* [$default_form_language](#property-$default_form_language)
* [$deleted](#property-$deleted)
* [$display](#property-$display)
* [$errors](#property-$errors)
* [$explicitSelect](#property-$explicitSelect)
* [$fieldImageSettings](#property-$fieldImageSettings)
* [$fields_form](#property-$fields_form)
* [$fields_form_override](#property-$fields_form_override)
* [$fields_list](#property-$fields_list)
* [$fields_options](#property-$fields_options)
* [$fields_value](#property-$fields_value)
* [$filter](#property-$filter)
* [$filter_modules_list](#property-$filter_modules_list)
* [$helper](#property-$helper)
* [$id](#property-$id)
* [$id_object](#property-$id_object)
* [$identifier](#property-$identifier)
* [$identifier_name](#property-$identifier_name)
* [$imageType](#property-$imageType)
* [$informations](#property-$informations)
* [$is_cms](#property-$is_cms)
* [$is_prestashop_up](#property-$is_prestashop_up)
* [$lang](#property-$lang)
* [$layout](#property-$layout)
* [$list_id](#property-$list_id)
* [$list_natives_modules](#property-$list_natives_modules)
* [$list_no_link](#property-$list_no_link)
* [$list_partners_modules](#property-$list_partners_modules)
* [$list_simple_header](#property-$list_simple_header)
* [$list_skip_actions](#property-$list_skip_actions)
* [$lite_display](#property-$lite_display)
* [$logged_on_addons](#property-$logged_on_addons)
* [$meta_title](#property-$meta_title)
* [$modals](#property-$modals)
* [$modules_list](#property-$modules_list)
* [$multiple_fieldsets](#property-$multiple_fieldsets)
* [$multishop_context](#property-$multishop_context)
* [$multishop_context_group](#property-$multishop_context_group)
* [$noLink](#property-$noLink)
* [$object](#property-$object)
* [$page_header_toolbar_btn](#property-$page_header_toolbar_btn)
* [$page_header_toolbar_title](#property-$page_header_toolbar_title)
* [$path](#property-$path)
* [$position_group_identifier](#property-$position_group_identifier)
* [$position_identifier](#property-$position_identifier)
* [$required_database](#property-$required_database)
* [$required_fields](#property-$required_fields)
* [$row_hover](#property-$row_hover)
* [$shopLink](#property-$shopLink)
* [$shopLinkType](#property-$shopLinkType)
* [$shopShareDatas](#property-$shopShareDatas)
* [$show_form_cancel_button](#property-$show_form_cancel_button)
* [$show_page_header_toolbar](#property-$show_page_header_toolbar)
* [$show_toolbar](#property-$show_toolbar)
* [$show_toolbar_options](#property-$show_toolbar_options)
* [$specificConfirmDelete](#property-$specificConfirmDelete)
* [$submit_action](#property-$submit_action)
* [$tabAccess](#property-$tabAccess)
* [$tab_modules_list](#property-$tab_modules_list)
* [$template](#property-$template)
* [$token](#property-$token)
* [$toolbar_btn](#property-$toolbar_btn)
* [$toolbar_title](#property-$toolbar_title)
* [$tpl_delete_link_vars](#property-$tpl_delete_link_vars)
* [$tpl_folder](#property-$tpl_folder)
* [$tpl_form_vars](#property-$tpl_form_vars)
* [$tpl_list_vars](#property-$tpl_list_vars)
* [$tpl_option_vars](#property-$tpl_option_vars)
* [$tpl_required_fields_vars](#property-$tpl_required_fields_vars)
* [$tpl_view_vars](#property-$tpl_view_vars)
* [$translationsTab](#property-$translationsTab)
* [$warnings](#property-$warnings)
* [$ajax](#property-$ajax)
* [$content_only](#property-$content_only)
* [$context](#property-$context)
* [$controller_type](#property-$controller_type)
* [$css_files](#property-$css_files)
* [$display_footer](#property-$display_footer)
* [$display_header](#property-$display_header)
* [$js_files](#property-$js_files)
* [$json](#property-$json)
* [$php_errors](#property-$php_errors)
* [$php_self](#property-$php_self)
* [$redirect_after](#property-$redirect_after)
* [$status](#property-$status)

### Methods

* [__construct](#method-__construct)
* [_checkConfigForFeatures](#method-_checkConfigForFeatures)
* [_childValidation](#method-_childValidation)
* [_isThemeCompatible](#method-_isThemeCompatible)
* [addCSS](#method-addCSS)
* [addFiltersToBreadcrumbs](#method-addFiltersToBreadcrumbs)
* [addJS](#method-addJS)
* [addJquery](#method-addJquery)
* [addJqueryPlugin](#method-addJqueryPlugin)
* [addJqueryUI](#method-addJqueryUI)
* [addPageHeaderToolBarModulesListButton](#method-addPageHeaderToolBarModulesListButton)
* [addRowAction](#method-addRowAction)
* [addRowActionSkipList](#method-addRowActionSkipList)
* [addToolBarModulesListButton](#method-addToolBarModulesListButton)
* [afterAdd](#method-afterAdd)
* [afterDelete](#method-afterDelete)
* [afterImageUpload](#method-afterImageUpload)
* [afterUpdate](#method-afterUpdate)
* [ajaxProcessGetAddonsThemes](#method-ajaxProcessGetAddonsThemes)
* [ajaxProcessGetModuleQuickView](#method-ajaxProcessGetModuleQuickView)
* [ajaxProcessLeftMeta](#method-ajaxProcessLeftMeta)
* [ajaxProcessOpenHelp](#method-ajaxProcessOpenHelp)
* [ajaxProcessRightMeta](#method-ajaxProcessRightMeta)
* [archiveThisFile](#method-archiveThisFile)
* [beforeAdd](#method-beforeAdd)
* [beforeDelete](#method-beforeDelete)
* [beforeUpdateOptions](#method-beforeUpdateOptions)
* [checkAccess](#method-checkAccess)
* [checkDocumentation](#method-checkDocumentation)
* [checkNames](#method-checkNames)
* [checkParentClass](#method-checkParentClass)
* [checkPostedDatas](#method-checkPostedDatas)
* [checkToken](#method-checkToken)
* [checkVersionsAndCompatibility](#method-checkVersionsAndCompatibility)
* [checkXmlFields](#method-checkXmlFields)
* [copyFromPost](#method-copyFromPost)
* [copyTheme](#method-copyTheme)
* [createTemplate](#method-createTemplate)
* [display](#method-display)
* [displayAjax](#method-displayAjax)
* [displayFooter](#method-displayFooter)
* [displayHeader](#method-displayHeader)
* [displayInformation](#method-displayInformation)
* [displayModuleOptions](#method-displayModuleOptions)
* [displayNoSmarty](#method-displayNoSmarty)
* [displayRequiredFields](#method-displayRequiredFields)
* [displayWarning](#method-displayWarning)
* [downloadAddonsThemes](#method-downloadAddonsThemes)
* [extractTheme](#method-extractTheme)
* [fillModuleData](#method-fillModuleData)
* [filterTabModuleList](#method-filterTabModuleList)
* [filterToField](#method-filterToField)
* [formatHelperArray](#method-formatHelperArray)
* [formatHelperValuesArray](#method-formatHelperValuesArray)
* [generateArchive](#method-generateArchive)
* [generateXML](#method-generateXML)
* [getController](#method-getController)
* [getFieldValue](#method-getFieldValue)
* [getFieldsValue](#method-getFieldsValue)
* [getLanguages](#method-getLanguages)
* [getList](#method-getList)
* [getModules](#method-getModules)
* [getModulesList](#method-getModulesList)
* [getNativeModule](#method-getNativeModule)
* [getSelectedAssoShop](#method-getSelectedAssoShop)
* [getTemplateFormVars](#method-getTemplateFormVars)
* [getTemplateListVars](#method-getTemplateListVars)
* [getTemplateViewVars](#method-getTemplateViewVars)
* [hookModule](#method-hookModule)
* [importThemeXmlConfig](#method-importThemeXmlConfig)
* [init](#method-init)
* [initBreadcrumbs](#method-initBreadcrumbs)
* [initContent](#method-initContent)
* [initCursedPage](#method-initCursedPage)
* [initFooter](#method-initFooter)
* [initHeader](#method-initHeader)
* [initModal](#method-initModal)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initShopContext](#method-initShopContext)
* [initTabModuleList](#method-initTabModuleList)
* [initToolbar](#method-initToolbar)
* [initToolbarTitle](#method-initToolbarTitle)
* [installTheme](#method-installTheme)
* [isCached](#method-isCached)
* [isFresh](#method-isFresh)
* [isThemeInstalled](#method-isThemeInstalled)
* [isXmlHttpRequest](#method-isXmlHttpRequest)
* [jsonConfirmation](#method-jsonConfirmation)
* [jsonError](#method-jsonError)
* [l](#method-l)
* [loadObject](#method-loadObject)
* [myErrorHandler](#method-myErrorHandler)
* [postImage](#method-postImage)
* [postProcess](#method-postProcess)
* [printResponsiveIcon](#method-printResponsiveIcon)
* [processAdd](#method-processAdd)
* [processBulkAffectZone](#method-processBulkAffectZone)
* [processBulkDelete](#method-processBulkDelete)
* [processBulkDisableSelection](#method-processBulkDisableSelection)
* [processBulkEnableSelection](#method-processBulkEnableSelection)
* [processBulkStatusSelection](#method-processBulkStatusSelection)
* [processDefaultLeftColumn](#method-processDefaultLeftColumn)
* [processDefaultRightColumn](#method-processDefaultRightColumn)
* [processDelete](#method-processDelete)
* [processDeleteImage](#method-processDeleteImage)
* [processExport](#method-processExport)
* [processExportTheme](#method-processExportTheme)
* [processFilter](#method-processFilter)
* [processImportTheme](#method-processImportTheme)
* [processLeftMeta](#method-processLeftMeta)
* [processPosition](#method-processPosition)
* [processResetFilters](#method-processResetFilters)
* [processResponsive](#method-processResponsive)
* [processRightMeta](#method-processRightMeta)
* [processSave](#method-processSave)
* [processStatus](#method-processStatus)
* [processThemeInstall](#method-processThemeInstall)
* [processUpdate](#method-processUpdate)
* [processUpdateFields](#method-processUpdateFields)
* [processUpdateOptions](#method-processUpdateOptions)
* [recurseCopy](#method-recurseCopy)
* [redirect](#method-redirect)
* [refresh](#method-refresh)
* [removeCSS](#method-removeCSS)
* [removeJS](#method-removeJS)
* [renderChooseThemeModule](#method-renderChooseThemeModule)
* [renderDetails](#method-renderDetails)
* [renderExportTheme](#method-renderExportTheme)
* [renderExportTheme1](#method-renderExportTheme1)
* [renderForm](#method-renderForm)
* [renderImportTheme](#method-renderImportTheme)
* [renderKpis](#method-renderKpis)
* [renderList](#method-renderList)
* [renderModal](#method-renderModal)
* [renderModulesList](#method-renderModulesList)
* [renderOptions](#method-renderOptions)
* [renderView](#method-renderView)
* [run](#method-run)
* [setDeprecatedMedia](#method-setDeprecatedMedia)
* [setHelperDisplay](#method-setHelperDisplay)
* [setMedia](#method-setMedia)
* [setTemplate](#method-setTemplate)
* [smartyOutputContent](#method-smartyOutputContent)
* [updateAssoShop](#method-updateAssoShop)
* [updateImages](#method-updateImages)
* [updateLogo](#method-updateLogo)
* [updateOptionPsFavicon](#method-updateOptionPsFavicon)
* [updateOptionPsLogo](#method-updateOptionPsLogo)
* [updateOptionPsLogoInvoice](#method-updateOptionPsLogoInvoice)
* [updateOptionPsLogoMail](#method-updateOptionPsLogoMail)
* [updateOptionPsLogoMobile](#method-updateOptionPsLogoMobile)
* [updateOptionPsStoresIcon](#method-updateOptionPsStoresIcon)
* [updateOptionThemeForShop](#method-updateOptionThemeForShop)
* [uploadIco](#method-uploadIco)
* [uploadImage](#method-uploadImage)
* [validateField](#method-validateField)
* [validateRules](#method-validateRules)
* [viewAccess](#method-viewAccess)
* [viewDetails](#method-viewDetails)


Constants
----------


### <a name="constant-MAX_NAME_LENGTH"></a>MAX_NAME_LENGTH

```php
const MAX_NAME_LENGTH = 128
```





* Source: [controllers/admin/AdminThemesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L30).


Properties
----------


### <a name="property-$check_features"></a>$check_features

```php
public mixed $check_features = array('ccc' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_CSS_THEME_CACHE' => 0, 'PS_JS_THEME_CACHE' => 0, 'PS_HTML_THEME_COMPRESSION' => 0, 'PS_JS_HTML_THEME_COMPRESSION' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "combine, compress and cache" options.', 'tab' => 'AdminPerformance'), 'guest_checkout' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_GUEST_CHECKOUT_ENABLED' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "guest checkout" feature.', 'tab' => 'AdminPreferences'), 'one_page_checkout' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_ORDER_PROCESS_TYPE' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "one-page checkout" feature.', 'tab' => 'AdminPreferences'), 'store_locator' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_STORES_SIMPLIFIED' => 0, 'PS_STORES_DISPLAY_FOOTER' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "store locator" feature.', 'tab' => 'AdminStores'))
```

$check_features is a multidimensional array used to check [theme]/config.xml values,
and also checks prestashop current configuration if not match.



* Visibility: **public**
* This property is **static**.
* Source: [controllers/admin/AdminThemesController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L49).


### <a name="property-$check_features_version"></a>$check_features_version

```php
public mixed $check_features_version = '1.4'
```

This value is used in isThemeCompatible method. only version node with an
higher version number will be used in [theme]/config.xml



* Visibility: **public**
* This property is **static**.
* Source: [controllers/admin/AdminThemesController.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L43).


### <a name="property-$className"></a>$className

```php
public mixed $className = 'Theme'
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L103).


### <a name="property-$img_error"></a>$img_error

```php
private mixed $img_error
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L106).


### <a name="property-$table"></a>$table

```php
public mixed $table = 'theme'
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L104).


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

```php
protected mixed $toolbar_scroll = false
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L105).


### <a name="property-$_defaultOrderBy"></a>$_defaultOrderBy

```php
protected string $_defaultOrderBy = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L75).


### <a name="property-$_defaultOrderWay"></a>$_defaultOrderWay

```php
protected mixed $_defaultOrderWay = 'ASC'
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L76).


### <a name="property-$_default_pagination"></a>$_default_pagination

```php
protected integer $_default_pagination = 50
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L160).


### <a name="property-$_filter"></a>$_filter

```php
protected array $_filter
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L150).


### <a name="property-$_filterHaving"></a>$_filterHaving

```php
protected mixed $_filterHaving
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L151).


### <a name="property-$_group"></a>$_group

```php
protected string $_group
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L225).


### <a name="property-$_having"></a>$_having

```php
protected string $_having
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L228).


### <a name="property-$_includeContainer"></a>$_includeContainer

```php
protected mixed $_includeContainer = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L250).


### <a name="property-$_join"></a>$_join

```php
protected string $_join
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L219).


### <a name="property-$_languages"></a>$_languages

```php
public mixed $_languages = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L37).


### <a name="property-$_list"></a>$_list

```php
protected array $_list = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L126).


### <a name="property-$_listTotal"></a>$_listTotal

```php
protected integer $_listTotal
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L144).


### <a name="property-$_listsql"></a>$_listsql

```php
protected string $_listsql = ''
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L123).


### <a name="property-$_orderBy"></a>$_orderBy

```php
protected string $_orderBy
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L163).


### <a name="property-$_orderWay"></a>$_orderWay

```php
protected string $_orderWay
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L166).


### <a name="property-$_pagination"></a>$_pagination

```php
protected array $_pagination = array(20, 50, 100, 300, 1000)
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L157).


### <a name="property-$_redirect"></a>$_redirect

```php
protected boolean $_redirect = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L258).


### <a name="property-$_select"></a>$_select

```php
protected string $_select
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L216).


### <a name="property-$_tmpTableFilter"></a>$_tmpTableFilter

```php
protected array $_tmpTableFilter = ''
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L154).


### <a name="property-$_where"></a>$_where

```php
protected string $_where
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L222).


### <a name="property-$action"></a>$action

```php
protected mixed $action
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 248](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L248).


### <a name="property-$actions"></a>$actions

```php
protected array $actions = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L172).


### <a name="property-$actions_available"></a>$actions_available

```php
protected array $actions_available = array('view', 'edit', 'duplicate', 'delete')
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L169).


### <a name="property-$admin_webpath"></a>$admin_webpath

```php
public mixed $admin_webpath
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 291](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L291).


### <a name="property-$allow_employee_form_lang"></a>$allow_employee_form_lang

```php
public mixed $allow_employee_form_lang
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L39).


### <a name="property-$allow_export"></a>$allow_export

```php
protected mixed $allow_export = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L182).


### <a name="property-$base_tpl_form"></a>$base_tpl_form

```php
public mixed $base_tpl_form = null
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L86).


### <a name="property-$base_tpl_view"></a>$base_tpl_view

```php
public mixed $base_tpl_view = null
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L85).


### <a name="property-$bo_theme"></a>$bo_theme

```php
protected mixed $bo_theme
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L255).


### <a name="property-$bootstrap"></a>$bootstrap

```php
public mixed $bootstrap = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L42).


### <a name="property-$boxes"></a>$boxes

```php
protected array $boxes
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L210).


### <a name="property-$breadcrumbs"></a>$breadcrumbs

```php
protected mixed $breadcrumbs
```

Current breadcrumb position as an array of tab names



* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 283](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L283).


### <a name="property-$bulk_actions"></a>$bulk_actions

```php
protected array $bulk_actions
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L205).


### <a name="property-$cache_lang"></a>$cache_lang

```php
public array $cache_lang = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L185).


### <a name="property-$colorOnBackground"></a>$colorOnBackground

```php
protected mixed $colorOnBackground
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L244).


### <a name="property-$confirmations"></a>$confirmations

```php
public mixed $confirmations = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L34).


### <a name="property-$content"></a>$content

```php
public mixed $content
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L31).


### <a name="property-$controller_name"></a>$controller_name

```php
public \current $controller_name
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L275).


### <a name="property-$currentIndex"></a>$currentIndex

```php
public mixed $currentIndex
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L30).


### <a name="property-$default_form_language"></a>$default_form_language

```php
public mixed $default_form_language
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L38).


### <a name="property-$deleted"></a>$deleted

```php
protected boolean $deleted = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L237).


### <a name="property-$display"></a>$display

```php
protected mixed $display
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L249).


### <a name="property-$errors"></a>$errors

```php
public array $errors = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L94).


### <a name="property-$explicitSelect"></a>$explicitSelect

```php
protected string $explicitSelect = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L213).


### <a name="property-$fieldImageSettings"></a>$fieldImageSettings

```php
public array $fieldImageSettings = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L261).


### <a name="property-$fields_form"></a>$fields_form

```php
protected array $fields_form
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L109).


### <a name="property-$fields_form_override"></a>$fields_form_override

```php
protected \override $fields_form_override
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L112).


### <a name="property-$fields_list"></a>$fields_list

```php
protected array $fields_list
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L100).


### <a name="property-$fields_options"></a>$fields_options

```php
protected array $fields_options = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L118).


### <a name="property-$fields_value"></a>$fields_value

```php
public mixed $fields_value = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L91).


### <a name="property-$filter"></a>$filter

```php
protected boolean $filter
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L241).


### <a name="property-$filter_modules_list"></a>$filter_modules_list

```php
protected array $filter_modules_list = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L103).


### <a name="property-$helper"></a>$helper

```php
protected \Helper $helper
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L191).


### <a name="property-$id"></a>$id

```php
public integer $id = -1
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L64).


### <a name="property-$id_object"></a>$id_object

```php
protected integer $id_object
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L270).


### <a name="property-$identifier"></a>$identifier

```php
protected string $identifier = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L54).


### <a name="property-$identifier_name"></a>$identifier_name

```php
protected mixed $identifier_name = 'name'
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L55).


### <a name="property-$imageType"></a>$imageType

```php
public string $imageType = 'jpg'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L264).


### <a name="property-$informations"></a>$informations

```php
public mixed $informations = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L33).


### <a name="property-$is_cms"></a>$is_cms

```php
protected mixed $is_cms = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L230).


### <a name="property-$is_prestashop_up"></a>$is_prestashop_up

```php
protected mixed $is_prestashop_up = true
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3623](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3623).


### <a name="property-$lang"></a>$lang

```php
public boolean $lang = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L147).


### <a name="property-$layout"></a>$layout

```php
public mixed $layout = 'layout.tpl'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L41).


### <a name="property-$list_id"></a>$list_id

```php
public mixed $list_id
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L51).


### <a name="property-$list_natives_modules"></a>$list_natives_modules

```php
protected mixed $list_natives_modules = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L293).


### <a name="property-$list_no_link"></a>$list_no_link

```php
protected boolean $list_no_link = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L180).


### <a name="property-$list_partners_modules"></a>$list_partners_modules

```php
protected mixed $list_partners_modules = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L294).


### <a name="property-$list_simple_header"></a>$list_simple_header

```php
protected \define $list_simple_header
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L97).


### <a name="property-$list_skip_actions"></a>$list_skip_actions

```php
protected array $list_skip_actions = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L175).


### <a name="property-$lite_display"></a>$lite_display

```php
protected mixed $lite_display = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L178).


### <a name="property-$logged_on_addons"></a>$logged_on_addons

```php
protected mixed $logged_on_addons = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L298).


### <a name="property-$meta_title"></a>$meta_title

```php
protected mixed $meta_title
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L44).


### <a name="property-$modals"></a>$modals

```php
public mixed $modals = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 296](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L296).


### <a name="property-$modules_list"></a>$modules_list

```php
protected array $modules_list = array()
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L106).


### <a name="property-$multiple_fieldsets"></a>$multiple_fieldsets

```php
public boolean $multiple_fieldsets = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L89).


### <a name="property-$multishop_context"></a>$multishop_context

```php
public mixed $multishop_context = -1
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L277).


### <a name="property-$multishop_context_group"></a>$multishop_context_group

```php
public mixed $multishop_context_group = true
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L278).


### <a name="property-$noLink"></a>$noLink

```php
protected mixed $noLink
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L242).


### <a name="property-$object"></a>$object

```php
protected \instanciation $object
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L267).


### <a name="property-$page_header_toolbar_btn"></a>$page_header_toolbar_btn

```php
public mixed $page_header_toolbar_btn = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L288).


### <a name="property-$page_header_toolbar_title"></a>$page_header_toolbar_title

```php
public mixed $page_header_toolbar_title
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L287).


### <a name="property-$path"></a>$path

```php
public mixed $path
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L29).


### <a name="property-$position_group_identifier"></a>$position_group_identifier

```php
protected mixed $position_group_identifier
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L234).


### <a name="property-$position_identifier"></a>$position_identifier

```php
protected string $position_identifier
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L233).


### <a name="property-$required_database"></a>$required_database

```php
public mixed $required_database = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L66).


### <a name="property-$required_fields"></a>$required_fields

```php
public array $required_fields = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L188).


### <a name="property-$row_hover"></a>$row_hover

```php
protected boolean $row_hover = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L246).


### <a name="property-$shopLink"></a>$shopLink

```php
protected mixed $shopLink
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L120).


### <a name="property-$shopLinkType"></a>$shopLinkType

```php
public string $shopLinkType
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L72).


### <a name="property-$shopShareDatas"></a>$shopShareDatas

```php
public mixed $shopShareDatas = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L35).


### <a name="property-$show_form_cancel_button"></a>$show_form_cancel_button

```php
public mixed $show_form_cancel_button
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 289](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L289).


### <a name="property-$show_page_header_toolbar"></a>$show_page_header_toolbar

```php
public mixed $show_page_header_toolbar = false
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L286).


### <a name="property-$show_toolbar"></a>$show_toolbar

```php
protected boolean $show_toolbar = true
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L138).


### <a name="property-$show_toolbar_options"></a>$show_toolbar_options

```php
protected boolean $show_toolbar_options = false
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L141).


### <a name="property-$specificConfirmDelete"></a>$specificConfirmDelete

```php
protected mixed $specificConfirmDelete = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L243).


### <a name="property-$submit_action"></a>$submit_action

```php
protected \override $submit_action
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L115).


### <a name="property-$tabAccess"></a>$tabAccess

```php
public array $tabAccess
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L61).


### <a name="property-$tab_modules_list"></a>$tab_modules_list

```php
protected mixed $tab_modules_list = array('default_list' => array(), 'slider_list' => array())
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L251).


### <a name="property-$template"></a>$template

```php
public mixed $template = 'content.tpl'
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L46).


### <a name="property-$token"></a>$token

```php
public string $token
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L69).


### <a name="property-$toolbar_btn"></a>$toolbar_btn

```php
protected array $toolbar_btn = null
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L132).


### <a name="property-$toolbar_title"></a>$toolbar_title

```php
protected \define $toolbar_title
```





* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L129).


### <a name="property-$tpl_delete_link_vars"></a>$tpl_delete_link_vars

```php
public mixed $tpl_delete_link_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L80).


### <a name="property-$tpl_folder"></a>$tpl_folder

```php
public mixed $tpl_folder
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L253).


### <a name="property-$tpl_form_vars"></a>$tpl_form_vars

```php
public mixed $tpl_form_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L78).


### <a name="property-$tpl_list_vars"></a>$tpl_list_vars

```php
public mixed $tpl_list_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L79).


### <a name="property-$tpl_option_vars"></a>$tpl_option_vars

```php
public mixed $tpl_option_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L81).


### <a name="property-$tpl_required_fields_vars"></a>$tpl_required_fields_vars

```php
public mixed $tpl_required_fields_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L83).


### <a name="property-$tpl_view_vars"></a>$tpl_view_vars

```php
public mixed $tpl_view_vars = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L82).


### <a name="property-$translationsTab"></a>$translationsTab

```php
protected mixed $translationsTab = array()
```

Display modules list



* Visibility: **protected**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3675](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3675).


### <a name="property-$warnings"></a>$warnings

```php
public mixed $warnings = array()
```





* Visibility: **public**
* This property is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L32).


### <a name="property-$ajax"></a>$ajax

```php
public boolean $ajax = false
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L75).


### <a name="property-$content_only"></a>$content_only

```php
protected string $content_only = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L70).


### <a name="property-$context"></a>$context

```php
protected \Context $context
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L35).


### <a name="property-$controller_type"></a>$controller_type

```php
public mixed $controller_type
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L81).


### <a name="property-$css_files"></a>$css_files

```php
public array $css_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L40).


### <a name="property-$display_footer"></a>$display_footer

```php
protected string $display_footer
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L65).


### <a name="property-$display_header"></a>$display_header

```php
protected boolean $display_header
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L55).


### <a name="property-$js_files"></a>$js_files

```php
public array $js_files = array()
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L45).


### <a name="property-$json"></a>$json

```php
protected mixed $json = false
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L76).


### <a name="property-$php_errors"></a>$php_errors

```php
public array $php_errors = array()
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L50).


### <a name="property-$php_self"></a>$php_self

```php
public mixed $php_self
```





* Visibility: **public**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L82).


### <a name="property-$redirect_after"></a>$redirect_after

```php
protected mixed $redirect_after = null
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L79).


### <a name="property-$status"></a>$status

```php
protected mixed $status = ''
```





* Visibility: **protected**
* This property is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L77).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminThemesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L32)




### <a name="method-_checkConfigForFeatures"></a>_checkConfigForFeatures

```php
\error AdminThemesControllerCore::_checkConfigForFeatures($arrFeatures, mixed $configItem)
```

_checkConfigForFeatures



* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1956](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L1956)


#### Arguments
* $arrFeatures **mixed**
* $configItem **mixed** - will precise the attribute which not matches. If empty, will check every attributes



### <a name="method-_childValidation"></a>_childValidation

```php
mixed AdminControllerCore::_childValidation()
```

Overload this method for custom checking



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3161)




### <a name="method-_isThemeCompatible"></a>_isThemeCompatible

```php
boolean AdminThemesControllerCore::_isThemeCompatible(string $theme_dir)
```

This function checks if the theme designer has thunk to make his theme compatible 1.4,
and noticed it on the $theme_dir/config.xml file. If not, some new functionnalities has
to be desactivated



* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1900](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L1900)


#### Arguments
* $theme_dir **string** - theme directory



### <a name="method-addCSS"></a>addCSS

```php
true ControllerCore::addCSS(mixed $css_uri, string $css_media_type, integer $offset, boolean $check_path)
```

Add a new stylesheet in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L251)


#### Arguments
* $css_uri **mixed** - Path to css file, or list of css files like this : array(array(uri =&gt; media_type), ...)
* $css_media_type **string**
* $offset **integer**
* $check_path **boolean**



### <a name="method-addFiltersToBreadcrumbs"></a>addFiltersToBreadcrumbs

```php
mixed AdminControllerCore::addFiltersToBreadcrumbs()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 521](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L521)




### <a name="method-addJS"></a>addJS

```php
void ControllerCore::addJS(mixed $js_uri, boolean $check_path)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L319)


#### Arguments
* $js_uri **mixed**
* $check_path **boolean**



### <a name="method-addJquery"></a>addJquery

```php
void ControllerCore::addJquery($version, $folder, $minifier)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L372)


#### Arguments
* $version **mixed**
* $folder **mixed**
* $minifier **mixed**



### <a name="method-addJqueryPlugin"></a>addJqueryPlugin

```php
mixed ControllerCore::addJqueryPlugin($name, null $folder, boolean $css)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 404](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L404)


#### Arguments
* $name **mixed**
* $folder **null**
* $css **boolean**



### <a name="method-addJqueryUI"></a>addJqueryUI

```php
void ControllerCore::addJqueryUI($component, $theme, $check_dependencies)
```

Add a new javascript file in page header.



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 383](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L383)


#### Arguments
* $component **mixed**
* $theme **mixed**
* $check_dependencies **mixed**



### <a name="method-addPageHeaderToolBarModulesListButton"></a>addPageHeaderToolBarModulesListButton

```php
mixed AdminControllerCore::addPageHeaderToolBarModulesListButton()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1887](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1887)




### <a name="method-addRowAction"></a>addRowAction

```php
mixed AdminControllerCore::addRowAction($action)
```

Declare an action to use for each row in the list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1781](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1781)


#### Arguments
* $action **mixed**



### <a name="method-addRowActionSkipList"></a>addRowActionSkipList

```php
mixed AdminControllerCore::addRowActionSkipList($action, $list)
```

Add  an action to use for each row in the list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1790](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1790)


#### Arguments
* $action **mixed**
* $list **mixed**



### <a name="method-addToolBarModulesListButton"></a>addToolBarModulesListButton

```php
mixed AdminControllerCore::addToolBarModulesListButton()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1898](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1898)




### <a name="method-afterAdd"></a>afterAdd

```php
mixed AdminControllerCore::afterAdd($object)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3194](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3194)


#### Arguments
* $object **mixed**



### <a name="method-afterDelete"></a>afterDelete

```php
boolean AdminControllerCore::afterDelete(object $object, $oldId)
```

Called before deletion



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3189](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3189)


#### Arguments
* $object **object** - Object
* $oldId **mixed**



### <a name="method-afterImageUpload"></a>afterImageUpload

```php
boolean AdminControllerCore::afterImageUpload()
```

Check rights to view the current tab



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3210](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3210)




### <a name="method-afterUpdate"></a>afterUpdate

```php
mixed AdminControllerCore::afterUpdate($object)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3199](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3199)


#### Arguments
* $object **mixed**



### <a name="method-ajaxProcessGetAddonsThemes"></a>ajaxProcessGetAddonsThemes

```php
mixed AdminThemesControllerCore::ajaxProcessGetAddonsThemes()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1877](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L1877)




### <a name="method-ajaxProcessGetModuleQuickView"></a>ajaxProcessGetModuleQuickView

```php
mixed AdminControllerCore::ajaxProcessGetModuleQuickView()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3944](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3944)




### <a name="method-ajaxProcessLeftMeta"></a>ajaxProcessLeftMeta

```php
mixed AdminThemesControllerCore::ajaxProcessLeftMeta()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2893](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2893)




### <a name="method-ajaxProcessOpenHelp"></a>ajaxProcessOpenHelp

```php
mixed AdminControllerCore::ajaxProcessOpenHelp()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3456](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3456)




### <a name="method-ajaxProcessRightMeta"></a>ajaxProcessRightMeta

```php
mixed AdminThemesControllerCore::ajaxProcessRightMeta()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2931](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2931)




### <a name="method-archiveThisFile"></a>archiveThisFile

```php
mixed AdminThemesControllerCore::archiveThisFile($obj, $file, $server_path, $archive_path)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 855](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L855)


#### Arguments
* $obj **mixed**
* $file **mixed**
* $server_path **mixed**
* $archive_path **mixed**



### <a name="method-beforeAdd"></a>beforeAdd

```php
boolean AdminControllerCore::beforeAdd(object $object)
```

Called before Add



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3549](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3549)


#### Arguments
* $object **object** - Object



### <a name="method-beforeDelete"></a>beforeDelete

```php
boolean AdminControllerCore::beforeDelete(object $object)
```

Called before deletion



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3178](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3178)


#### Arguments
* $object **object** - Object



### <a name="method-beforeUpdateOptions"></a>beforeUpdateOptions

```php
mixed AdminControllerCore::beforeUpdateOptions()
```

Can be overriden



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3330](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3330)




### <a name="method-checkAccess"></a>checkAccess

```php
mixed AdminControllerCore::checkAccess()
```

Check if the token is valid, else display a warning page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1433](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1433)




### <a name="method-checkDocumentation"></a>checkDocumentation

```php
mixed AdminThemesControllerCore::checkDocumentation()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 796](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L796)




### <a name="method-checkNames"></a>checkNames

```php
mixed AdminThemesControllerCore::checkNames()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 780](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L780)




### <a name="method-checkParentClass"></a>checkParentClass

```php
mixed AdminThemesControllerCore::checkParentClass($name)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 742](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L742)


#### Arguments
* $name **mixed**



### <a name="method-checkPostedDatas"></a>checkPostedDatas

```php
mixed AdminThemesControllerCore::checkPostedDatas()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 838](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L838)




### <a name="method-checkToken"></a>checkToken

```php
mixed AdminControllerCore::checkToken()
```

Check for security token



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 579](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L579)




### <a name="method-checkVersionsAndCompatibility"></a>checkVersionsAndCompatibility

```php
mixed AdminThemesControllerCore::checkVersionsAndCompatibility()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 822](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L822)




### <a name="method-checkXmlFields"></a>checkXmlFields

```php
mixed AdminThemesControllerCore::checkXmlFields($xml_file)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1415](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L1415)


#### Arguments
* $xml_file **mixed**



### <a name="method-copyFromPost"></a>copyFromPost

```php
mixed AdminControllerCore::copyFromPost($object, string $table)
```

Copy datas from $_POST to object



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3221](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3221)


#### Arguments
* $object **mixed**
* $table **string** - Object table



### <a name="method-copyTheme"></a>copyTheme

```php
boolean AdminThemesControllerCore::copyTheme(string $base_theme_dir, string $target_theme_dir)
```

copy $base_theme_dir into $target_theme_dir.



* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminThemesController.php line 481](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L481)


#### Arguments
* $base_theme_dir **string** - relative path to base dir
* $target_theme_dir **string** - relative path to target dir



### <a name="method-createTemplate"></a>createTemplate

```php
\Template AdminControllerCore::createTemplate(string $tpl_name)
```

Create a template from the override file, else from the base file.



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3575](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3575)


#### Arguments
* $tpl_name **string** - filename



### <a name="method-display"></a>display

```php
mixed AdminControllerCore::display()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1490](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1490)




### <a name="method-displayAjax"></a>displayAjax

```php
mixed AdminControllerCore::displayAjax()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1469](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1469)




### <a name="method-displayFooter"></a>displayFooter

```php
mixed ControllerCore::displayFooter($display)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L212)


#### Arguments
* $display **mixed**



### <a name="method-displayHeader"></a>displayHeader

```php
mixed ControllerCore::displayHeader($display)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L207)


#### Arguments
* $display **mixed**



### <a name="method-displayInformation"></a>displayInformation

```php
mixed AdminControllerCore::displayInformation(string $msg)
```

add a info message to display at the top of the page



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1575](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1575)


#### Arguments
* $msg **string**



### <a name="method-displayModuleOptions"></a>displayModuleOptions

```php
mixed AdminControllerCore::displayModuleOptions($module, $output_type, $back)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3676](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3676)


#### Arguments
* $module **mixed**
* $output_type **mixed**
* $back **mixed**



### <a name="method-displayNoSmarty"></a>displayNoSmarty

```php
mixed AdminControllerCore::displayNoSmarty()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1465](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1465)




### <a name="method-displayRequiredFields"></a>displayRequiredFields

```php
mixed AdminControllerCore::displayRequiredFields()
```

prepare the view to display the required fields form



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3557](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3557)




### <a name="method-displayWarning"></a>displayWarning

```php
mixed AdminControllerCore::displayWarning(string $msg)
```

add a warning message to display at the top of the page



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1565](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1565)


#### Arguments
* $msg **string**



### <a name="method-downloadAddonsThemes"></a>downloadAddonsThemes

```php
mixed AdminThemesControllerCore::downloadAddonsThemes()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 509](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L509)




### <a name="method-extractTheme"></a>extractTheme

```php
mixed AdminThemesControllerCore::extractTheme($theme_zip_file, $sandbox)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1530](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L1530)


#### Arguments
* $theme_zip_file **mixed**
* $sandbox **mixed**



### <a name="method-fillModuleData"></a>fillModuleData

```php
mixed AdminControllerCore::fillModuleData($module, $output_type, $back)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3632](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3632)


#### Arguments
* $module **mixed**
* $output_type **mixed**
* $back **mixed**



### <a name="method-filterTabModuleList"></a>filterTabModuleList

```php
mixed AdminControllerCore::filterTabModuleList()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1909](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1909)




### <a name="method-filterToField"></a>filterToField

```php
mixed AdminControllerCore::filterToField($key, $filter)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1452](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1452)


#### Arguments
* $key **mixed**
* $filter **mixed**



### <a name="method-formatHelperArray"></a>formatHelperArray

```php
mixed AdminThemesControllerCore::formatHelperArray($origin_arr)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2166](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2166)


#### Arguments
* $origin_arr **mixed**



### <a name="method-formatHelperValuesArray"></a>formatHelperValuesArray

```php
mixed AdminThemesControllerCore::formatHelperValuesArray($originArr)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2187](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2187)


#### Arguments
* $originArr **mixed**



### <a name="method-generateArchive"></a>generateArchive

```php
mixed AdminThemesControllerCore::generateArchive()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 870](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L870)




### <a name="method-generateXML"></a>generateXML

```php
mixed AdminThemesControllerCore::generateXML($theme_to_export, $metas)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 932](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L932)


#### Arguments
* $theme_to_export **mixed**
* $metas **mixed**



### <a name="method-getController"></a>getController

```php
mixed ControllerCore::getController(string $class_name, boolean $auth, boolean $ssl)
```

Get an instance of a controller



* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L133)


#### Arguments
* $class_name **string**
* $auth **boolean**
* $ssl **boolean**



### <a name="method-getFieldValue"></a>getFieldValue

```php
string AdminControllerCore::getFieldValue(object $obj, string $key, integer $id_lang)
```

Return field value if possible (both classical and multilingual fields)

Case 1 : Return value if present in $_POST / $_GET
Case 2 : Return object value

* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3074](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3074)


#### Arguments
* $obj **object** - Object
* $key **string** - Field name
* $id_lang **integer** - Language id (optional)



### <a name="method-getFieldsValue"></a>getFieldsValue

```php
array AdminControllerCore::getFieldsValue(object $obj)
```

Return the list of fields value



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3024](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3024)


#### Arguments
* $obj **object** - Object



### <a name="method-getLanguages"></a>getLanguages

```php
mixed AdminControllerCore::getLanguages()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2996](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L2996)




### <a name="method-getList"></a>getList

```php
mixed AdminControllerCore::getList(integer $id_lang, string $order_by, $order_way, integer $start, integer $limit, $id_lang_shop)
```

Get the current objects' list form the database



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2739](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L2739)


#### Arguments
* $id_lang **integer** - Language used for display
* $order_by **string** - ORDER BY clause
* $order_way **mixed**
* $start **integer** - Offset in LIMIT clause
* $limit **integer** - Row count in LIMIT clause
* $id_lang_shop **mixed**



### <a name="method-getModules"></a>getModules

```php
mixed AdminThemesControllerCore::getModules($xml)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2145](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2145)


#### Arguments
* $xml **mixed**



### <a name="method-getModulesList"></a>getModulesList

```php
mixed AdminControllerCore::getModulesList($filter_modules_list)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2958](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L2958)


#### Arguments
* $filter_modules_list **mixed**



### <a name="method-getNativeModule"></a>getNativeModule

```php
array AdminThemesControllerCore::getNativeModule(integer $type)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2014](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2014)


#### Arguments
* $type **integer** - $type = 0 both native &amp; partner (default)
$type = 1 native
$type = 2 partner



### <a name="method-getSelectedAssoShop"></a>getSelectedAssoShop

```php
array AdminControllerCore::getSelectedAssoShop(string $table)
```

Returns an array with selected shops and type (group or boutique shop)



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3260](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3260)


#### Arguments
* $table **string**



### <a name="method-getTemplateFormVars"></a>getTemplateFormVars

```php
mixed AdminControllerCore::getTemplateFormVars()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2220](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L2220)




### <a name="method-getTemplateListVars"></a>getTemplateListVars

```php
mixed AdminControllerCore::getTemplateListVars()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L2131)




### <a name="method-getTemplateViewVars"></a>getTemplateViewVars

```php
mixed AdminControllerCore::getTemplateViewVars()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2151](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L2151)




### <a name="method-hookModule"></a>hookModule

```php
mixed AdminThemesControllerCore::hookModule($id_module, $module_hooks, $shop)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2418](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2418)


#### Arguments
* $id_module **mixed**
* $module_hooks **mixed**
* $shop **mixed**



### <a name="method-importThemeXmlConfig"></a>importThemeXmlConfig

```php
array|string AdminThemesControllerCore::importThemeXmlConfig(\SimpleXMLElement $xml, boolean $theme_dir)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1613](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L1613)


#### Arguments
* $xml **SimpleXMLElement**
* $theme_dir **boolean** - only used if the theme directory to import is already located on the shop



### <a name="method-init"></a>init

```php
mixed AdminThemesControllerCore::init()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L108)




### <a name="method-initBreadcrumbs"></a>initBreadcrumbs

```php
mixed AdminControllerCore::initBreadcrumbs($tab_id, $tabs)
```

Set breadcrumbs array for the controller page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 419](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L419)


#### Arguments
* $tab_id **mixed**
* $tabs **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminThemesControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1837](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L1837)




### <a name="method-initCursedPage"></a>initCursedPage

```php
void AdminControllerCore::initCursedPage()
```

initialize the invalid doom page of death



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1957](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1957)




### <a name="method-initFooter"></a>initFooter

```php
mixed AdminControllerCore::initFooter()
```

Assign smarty variables for the footer



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1965](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1965)




### <a name="method-initHeader"></a>initHeader

```php
mixed AdminControllerCore::initHeader()
```

Assign smarty variables for the header



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1583](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1583)




### <a name="method-initModal"></a>initModal

```php
mixed AdminControllerCore::initModal()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1988](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1988)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminThemesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 709](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L709)




### <a name="method-initProcess"></a>initProcess

```php
mixed AdminThemesControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2793](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2793)




### <a name="method-initShopContext"></a>initShopContext

```php
mixed AdminControllerCore::initShopContext()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2452](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L2452)




### <a name="method-initTabModuleList"></a>initTabModuleList

```php
mixed AdminControllerCore::initTabModuleList()
```

init tab modules list and add button in toolbar



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1862](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1862)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminControllerCore::initToolbar()
```

assign default action in toolbar_btn smarty var, if they are not set.

uses override to specifically add, modify or remove items

* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1340](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1340)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

```php
void AdminControllerCore::initToolbarTitle()
```

set default toolbar_title to admin breadcrumb



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 498](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L498)




### <a name="method-installTheme"></a>installTheme

```php
mixed AdminThemesControllerCore::installTheme($theme_dir, $sandbox, $redirect)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1539](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L1539)


#### Arguments
* $theme_dir **mixed**
* $sandbox **mixed**
* $redirect **mixed**



### <a name="method-isCached"></a>isCached

```php
mixed ControllerCore::isCached($template, $cacheId, $compileId)
```





* Visibility: **protected**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 472](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L472)


#### Arguments
* $template **mixed**
* $cacheId **mixed**
* $compileId **mixed**



### <a name="method-isFresh"></a>isFresh

```php
mixed AdminControllerCore::isFresh($file, $timeout)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3616](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3616)


#### Arguments
* $file **mixed**
* $timeout **mixed**



### <a name="method-isThemeInstalled"></a>isThemeInstalled

```php
mixed AdminThemesControllerCore::isThemeInstalled($theme_name)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 1595](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L1595)


#### Arguments
* $theme_name **mixed**



### <a name="method-isXmlHttpRequest"></a>isXmlHttpRequest

```php
boolean ControllerCore::isXmlHttpRequest()
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 426](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L426)




### <a name="method-jsonConfirmation"></a>jsonConfirmation

```php
mixed AdminControllerCore::jsonConfirmation($message)
```

Shortcut to set up a json success payload



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3595](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3595)


#### Arguments
* $message **mixed** - success message



### <a name="method-jsonError"></a>jsonError

```php
mixed AdminControllerCore::jsonError($message)
```

Shortcut to set up a json error payload



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3608](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3608)


#### Arguments
* $message **mixed** - error message



### <a name="method-l"></a>l

```php
string AdminControllerCore::l(mixed $string, string $class, \boolan $addslashes, boolean $htmlentities)
```

non-static method which uses AdminController::translate()



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2359](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L2359)


#### Arguments
* $string **mixed** - term or expression in english
* $class **string** - name of the class
* $addslashes **boolan** - if set to true, the return value will pass through addslashes(). Otherwise, stripslashes().
* $htmlentities **boolean** - if set to true(default), the return value will pass through htmlentities($string, ENT_QUOTES, &#039;utf-8&#039;)



### <a name="method-loadObject"></a>loadObject

```php
object|boolean AdminControllerCore::loadObject(boolean $opt)
```

Load class object using identifier in $_GET (if possible)
otherwise return an empty object, or die



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1402](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1402)


#### Arguments
* $opt **boolean** - Return an empty object if load fail



### <a name="method-myErrorHandler"></a>myErrorHandler

```php
mixed ControllerCore::myErrorHandler($errno, $errstr, $errfile, $errline)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 480](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L480)


#### Arguments
* $errno **mixed**
* $errstr **mixed**
* $errfile **mixed**
* $errline **mixed**



### <a name="method-postImage"></a>postImage

```php
boolean AdminControllerCore::postImage(integer $id)
```

Overload this method for custom checking



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3340](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3340)


#### Arguments
* $id **integer** - Object id used for deleting images



### <a name="method-postProcess"></a>postProcess

```php
mixed AdminThemesControllerCore::postProcess()
```

This functions make checks about AdminThemes configuration edition only.



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2603](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2603)




### <a name="method-printResponsiveIcon"></a>printResponsiveIcon

```php
mixed AdminThemesControllerCore::printResponsiveIcon($value)
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2837](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2837)


#### Arguments
* $value **mixed**



### <a name="method-processAdd"></a>processAdd

```php
mixed AdminThemesControllerCore::processAdd()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 550](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L550)




### <a name="method-processBulkAffectZone"></a>processBulkAffectZone

```php
mixed AdminControllerCore::processBulkAffectZone()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3525](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3525)




### <a name="method-processBulkDelete"></a>processBulkDelete

```php
boolean AdminControllerCore::processBulkDelete()
```

Delete multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3398](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3398)




### <a name="method-processBulkDisableSelection"></a>processBulkDisableSelection

```php
boolean AdminControllerCore::processBulkDisableSelection()
```

Disable multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3500](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3500)




### <a name="method-processBulkEnableSelection"></a>processBulkEnableSelection

```php
boolean AdminControllerCore::processBulkEnableSelection()
```

Enable multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3490](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3490)




### <a name="method-processBulkStatusSelection"></a>processBulkStatusSelection

```php
boolean AdminControllerCore::processBulkStatusSelection($status)
```

Toggle status of multiple items



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3510](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3510)


#### Arguments
* $status **mixed**



### <a name="method-processDefaultLeftColumn"></a>processDefaultLeftColumn

```php
mixed AdminThemesControllerCore::processDefaultLeftColumn()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2859](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2859)




### <a name="method-processDefaultRightColumn"></a>processDefaultRightColumn

```php
mixed AdminThemesControllerCore::processDefaultRightColumn()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2876](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2876)




### <a name="method-processDelete"></a>processDelete

```php
mixed AdminThemesControllerCore::processDelete()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 668](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L668)




### <a name="method-processDeleteImage"></a>processDeleteImage

```php
mixed AdminControllerCore::processDeleteImage()
```

Object Delete images



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 777](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L777)




### <a name="method-processExport"></a>processExport

```php
mixed AdminControllerCore::processExport($text_delimiter)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 794](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L794)


#### Arguments
* $text_delimiter **mixed**



### <a name="method-processExportTheme"></a>processExportTheme

```php
mixed AdminThemesControllerCore::processExportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1039](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L1039)




### <a name="method-processFilter"></a>processFilter

```php
mixed AdminControllerCore::processFilter()
```

Set the filters used for the list display



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 606](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L606)




### <a name="method-processImportTheme"></a>processImportTheme

```php
mixed AdminThemesControllerCore::processImportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1459](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L1459)




### <a name="method-processLeftMeta"></a>processLeftMeta

```php
mixed AdminThemesControllerCore::processLeftMeta()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2912](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2912)




### <a name="method-processPosition"></a>processPosition

```php
mixed AdminControllerCore::processPosition()
```

Change object position



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1111](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1111)




### <a name="method-processResetFilters"></a>processResetFilters

```php
mixed AdminControllerCore::processResetFilters($list_id)
```

Cancel all filters for this tab



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1132](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1132)


#### Arguments
* $list_id **mixed**



### <a name="method-processResponsive"></a>processResponsive

```php
mixed AdminThemesControllerCore::processResponsive()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2842](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2842)




### <a name="method-processRightMeta"></a>processRightMeta

```php
mixed AdminThemesControllerCore::processRightMeta()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2950](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2950)




### <a name="method-processSave"></a>processSave

```php
mixed AdminControllerCore::processSave()
```

Call the right method for creating or updating object



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 908](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L908)




### <a name="method-processStatus"></a>processStatus

```php
mixed AdminControllerCore::processStatus()
```

Change object status (active, inactive)



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1081](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1081)




### <a name="method-processThemeInstall"></a>processThemeInstall

```php
mixed AdminThemesControllerCore::processThemeInstall()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2446](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2446)




### <a name="method-processUpdate"></a>processUpdate

```php
mixed AdminThemesControllerCore::processUpdate()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 622](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L622)




### <a name="method-processUpdateFields"></a>processUpdateFields

```php
mixed AdminControllerCore::processUpdateFields()
```

Change object required fields



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1064](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1064)




### <a name="method-processUpdateOptions"></a>processUpdateOptions

```php
mixed AdminThemesControllerCore::processUpdateOptions()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 660](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L660)




### <a name="method-recurseCopy"></a>recurseCopy

```php
mixed AdminThemesControllerCore::recurseCopy($src, $dst)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1440](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L1440)


#### Arguments
* $src **mixed**
* $dst **mixed**



### <a name="method-redirect"></a>redirect

```php
mixed AdminControllerCore::redirect()
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 1484](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L1484)




### <a name="method-refresh"></a>refresh

```php
mixed AdminControllerCore::refresh($file_to_refresh, $external_file)
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3624](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3624)


#### Arguments
* $file_to_refresh **mixed**
* $external_file **mixed**



### <a name="method-removeCSS"></a>removeCSS

```php
mixed ControllerCore::removeCSS($css_uri, $css_media_type, $check_path)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 285](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L285)


#### Arguments
* $css_uri **mixed**
* $css_media_type **mixed**
* $check_path **mixed**



### <a name="method-removeJS"></a>removeJS

```php
mixed ControllerCore::removeJS($js_uri)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 344](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L344)


#### Arguments
* $js_uri **mixed**



### <a name="method-renderChooseThemeModule"></a>renderChooseThemeModule

```php
mixed AdminThemesControllerCore::renderChooseThemeModule()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2197](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2197)




### <a name="method-renderDetails"></a>renderDetails

```php
mixed AdminControllerCore::renderDetails()
```

Override to render the view page



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2159](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L2159)




### <a name="method-renderExportTheme"></a>renderExportTheme

```php
mixed AdminThemesControllerCore::renderExportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1365](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L1365)




### <a name="method-renderExportTheme1"></a>renderExportTheme1

```php
mixed AdminThemesControllerCore::renderExportTheme1()
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 1169](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L1169)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminThemesControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L243)




### <a name="method-renderImportTheme"></a>renderImportTheme

```php
mixed AdminThemesControllerCore::renderImportTheme()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 1713](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L1713)




### <a name="method-renderKpis"></a>renderKpis

```php
mixed AdminControllerCore::renderKpis()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2225](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L2225)




### <a name="method-renderList"></a>renderList

```php
mixed AdminThemesControllerCore::renderList()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 467](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L467)




### <a name="method-renderModal"></a>renderModal

```php
mixed AdminControllerCore::renderModal()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2028](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L2028)




### <a name="method-renderModulesList"></a>renderModulesList

```php
mixed AdminControllerCore::renderModulesList()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2042](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L2042)




### <a name="method-renderOptions"></a>renderOptions

```php
mixed AdminThemesControllerCore::renderOptions()
```

Function used to render the options for this controller



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2973](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2973)




### <a name="method-renderView"></a>renderView

```php
mixed AdminThemesControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2584](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2584)




### <a name="method-run"></a>run

```php
mixed ControllerCore::run()
```

Start controller process (this method shouldn't be overriden !)



* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L161)




### <a name="method-setDeprecatedMedia"></a>setDeprecatedMedia

```php
mixed AdminControllerCore::setDeprecatedMedia()
```





* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2315](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L2315)




### <a name="method-setHelperDisplay"></a>setHelperDisplay

```php
void AdminControllerCore::setHelperDisplay(\Helper $helper)
```

this function set various display option for helper list



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 2264](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L2264)


#### Arguments
* $helper **[Helper](class.HelperCore.md)**



### <a name="method-setMedia"></a>setMedia

```php
mixed AdminThemesControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2997](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2997)




### <a name="method-setTemplate"></a>setTemplate

```php
mixed ControllerCore::setTemplate($template)
```





* Visibility: **public**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L217)


#### Arguments
* $template **mixed**



### <a name="method-smartyOutputContent"></a>smartyOutputContent

```php
mixed ControllerCore::smartyOutputContent($content)
```





* Visibility: **protected**
* This method is defined by [ControllerCore](class.ControllerCore.md).
* Source: [classes/controller/Controller.php line 431](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/Controller.php#L431)


#### Arguments
* $content **mixed**



### <a name="method-updateAssoShop"></a>updateAssoShop

```php
mixed AdminControllerCore::updateAssoShop(integer $id_object)
```

Update the associations of shops



* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3283](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3283)


#### Arguments
* $id_object **integer**



### <a name="method-updateImages"></a>updateImages

```php
mixed AdminThemesControllerCore::updateImages($xml)
```





* Visibility: **private**
* Source: [controllers/admin/AdminThemesController.php line 2389](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2389)


#### Arguments
* $xml **mixed**



### <a name="method-updateLogo"></a>updateLogo

```php
boolean AdminThemesControllerCore::updateLogo($field_name, $logo_prefix)
```

Generic function which allows logo upload



* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 2674](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2674)


#### Arguments
* $field_name **mixed**
* $logo_prefix **mixed**



### <a name="method-updateOptionPsFavicon"></a>updateOptionPsFavicon

```php
mixed AdminThemesControllerCore::updateOptionPsFavicon()
```

Update PS_FAVICON



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2748](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2748)




### <a name="method-updateOptionPsLogo"></a>updateOptionPsLogo

```php
mixed AdminThemesControllerCore::updateOptionPsLogo()
```

Update PS_LOGO



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2629](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2629)




### <a name="method-updateOptionPsLogoInvoice"></a>updateOptionPsLogoInvoice

```php
mixed AdminThemesControllerCore::updateOptionPsLogoInvoice()
```

Update PS_LOGO_INVOICE



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2653](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2653)




### <a name="method-updateOptionPsLogoMail"></a>updateOptionPsLogoMail

```php
mixed AdminThemesControllerCore::updateOptionPsLogoMail()
```

Update PS_LOGO_MAIL



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2645](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2645)




### <a name="method-updateOptionPsLogoMobile"></a>updateOptionPsLogoMobile

```php
mixed AdminThemesControllerCore::updateOptionPsLogoMobile()
```

Update PS_LOGO_MOBILE



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2637](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2637)




### <a name="method-updateOptionPsStoresIcon"></a>updateOptionPsStoresIcon

```php
mixed AdminThemesControllerCore::updateOptionPsStoresIcon()
```

Update PS_STORES_ICON



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2661](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2661)




### <a name="method-updateOptionThemeForShop"></a>updateOptionThemeForShop

```php
mixed AdminThemesControllerCore::updateOptionThemeForShop()
```

Update theme for current shop



* Visibility: **public**
* Source: [controllers/admin/AdminThemesController.php line 2763](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2763)




### <a name="method-uploadIco"></a>uploadIco

```php
mixed AdminThemesControllerCore::uploadIco($name, $dest)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminThemesController.php line 2777](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminThemesController.php#L2777)


#### Arguments
* $name **mixed**
* $dest **mixed**



### <a name="method-uploadImage"></a>uploadImage

```php
mixed AdminControllerCore::uploadImage($id, $name, $dir, $ext, $width, $height)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3351](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3351)


#### Arguments
* $id **mixed**
* $name **mixed**
* $dir **mixed**
* $ext **mixed**
* $width **mixed**
* $height **mixed**



### <a name="method-validateField"></a>validateField

```php
mixed AdminControllerCore::validateField($value, $field)
```





* Visibility: **protected**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3309](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3309)


#### Arguments
* $value **mixed**
* $field **mixed**



### <a name="method-validateRules"></a>validateRules

```php
mixed AdminControllerCore::validateRules($class_name)
```

Manage page display (form, list.

..)

* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3089](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3089)


#### Arguments
* $class_name **mixed**



### <a name="method-viewAccess"></a>viewAccess

```php
boolean AdminControllerCore::viewAccess(boolean $disable)
```

Check rights to view the current tab



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 566](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L566)


#### Arguments
* $disable **boolean**



### <a name="method-viewDetails"></a>viewDetails

```php
mixed AdminControllerCore::viewDetails()
```

Display object details



* Visibility: **public**
* This method is defined by [AdminControllerCore](class.AdminControllerCore.md).
* Source: [classes/controller/AdminController.php line 3168](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/controller/AdminController.php#L3168)


