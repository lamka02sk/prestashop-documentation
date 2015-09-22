Class ModuleGridCore
=====================





* Class name: ModuleGridCore
* This is an **abstract** class
* Parent class: [Module](class.ModuleCore.md)
* Source: [classes/module/ModuleGrid.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L27)



Properties
----------

* [$_direction](#property-$_direction)
* [$_employee](#property-$_employee)
* [$_limit](#property-$_limit)
* [$_render](#property-$_render)
* [$_sort](#property-$_sort)
* [$_start](#property-$_start)
* [$_title](#property-$_title)
* [$_totalCount](#property-$_totalCount)
* [$_values](#property-$_values)

Methods
-------
* [_displayCsv](#method-_displayCsv)
* [create](#method-create)
* [csvExport](#method-csvExport)
* [engine](#method-engine)
* [getData](#method-getData)
* [getDate](#method-getDate)
* [getLang](#method-getLang)
* [render](#method-render)
* [setEmployee](#method-setEmployee)
* [setLang](#method-setLang)




Properties
----------


### <a name="property-$_direction"></a>$_direction

    protected mixed $_direction = null





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L50)


### <a name="property-$_employee"></a>$_employee

    protected mixed $_employee





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L29)


### <a name="property-$_limit"></a>$_limit

    protected mixed $_limit





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L44)


### <a name="property-$_render"></a>$_render

    protected \ModuleGridEngine $_render





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L53)


### <a name="property-$_sort"></a>$_sort

    protected mixed $_sort = null





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L47)


### <a name="property-$_start"></a>$_start

    protected mixed $_start





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L41)


### <a name="property-$_title"></a>$_title

    protected mixed $_title





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L38)


### <a name="property-$_totalCount"></a>$_totalCount

    protected integer $_totalCount





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L35)


### <a name="property-$_values"></a>$_values

    protected array $_values = array()





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L32)


Methods
-------


### <a name="method-_displayCsv"></a>_displayCsv

    mixed ModuleGridCore::_displayCsv()





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L181)




### <a name="method-create"></a>create

    mixed ModuleGridCore::create($render, $type, $width, $height, $start, $limit, $sort, $dir)





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L67)


#### Arguments
* $render **mixed**
* $type **mixed**
* $width **mixed**
* $height **mixed**
* $start **mixed**
* $limit **mixed**
* $sort **mixed**
* $dir **mixed**



### <a name="method-csvExport"></a>csvExport

    mixed ModuleGridCore::csvExport($datas)





* Visibility: **protected**
* Source: [classes/module/ModuleGrid.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L153)


#### Arguments
* $datas **mixed**



### <a name="method-engine"></a>engine

    mixed ModuleGridCore::engine($params)





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L97)


#### Arguments
* $params **mixed**



### <a name="method-getData"></a>getData

    mixed ModuleGridCore::getData()





* Visibility: **protected**
* This method is **abstract**.
* Source: [classes/module/ModuleGrid.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L55)




### <a name="method-getDate"></a>getDate

    mixed ModuleGridCore::getDate()





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L192)




### <a name="method-getLang"></a>getLang

    mixed ModuleGridCore::getLang()





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L197)




### <a name="method-render"></a>render

    mixed ModuleGridCore::render()





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L92)




### <a name="method-setEmployee"></a>setEmployee

    mixed ModuleGridCore::setEmployee($id_employee)





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L57)


#### Arguments
* $id_employee **mixed**



### <a name="method-setLang"></a>setLang

    mixed ModuleGridCore::setLang($id_lang)





* Visibility: **public**
* Source: [classes/module/ModuleGrid.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/module/ModuleGrid.php#L62)


#### Arguments
* $id_lang **mixed**

