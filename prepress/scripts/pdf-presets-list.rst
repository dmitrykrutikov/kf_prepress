PDF пресеты
==================================================================================================

Сюжетные фотографии
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

+------------------------+--------------------+-----------------------------+
|Скрипт                  |- Сборка скриптом   |- Ручная(ой) сборка / экспорт|
|                        |- PDF пресет        |- PDF пресет                 |
+========================+====================+=============================+
|Раскладка под печать 3.1|[High Quality Print]|[High Quality Print]         |
+------------------------+--------------------+-----------------------------+
|Сюжетные календари 1.0  |[High Quality Print]|[High Quality Print]         |
+------------------------+--------------------+-----------------------------+
|Сюжетные фото 2.6       |[High Quality Print]|[High Quality Print]         |
+------------------------+--------------------+-----------------------------+
|Сюжеты Polska 1.0.2     |Polska_Lab          |Polska_Lab                   |
+------------------------+--------------------+-----------------------------+    
|Сюжетные открытки 2.2   |—                   |[High Quality Print]         |
+------------------------+--------------------+-----------------------------+
|Сюжетные магниты 1.7    |—                   |[High Quality Print]         |
+------------------------+--------------------+-----------------------------+
|Сюжетные календари 0.4  |—                   |Календари_1.3                |
+------------------------+--------------------+-----------------------------+

Сюжетные фотокниги
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

+-------------------+--------------------+----------------------+
|Сюжет              |- Сборка скриптом   |- Ручная сборка       |
|                   |- PDF пресет        |- PDF пресет          |
+===================+====================+======================+
|Арктический зоопарк|[High Quality Print]|—                     |
+-------------------+--------------------+----------------------+
|Зимняя сказка      |[High Quality Print]|—                     |
+-------------------+--------------------+----------------------+
|Пастушки           |[High Quality Print]|—                     |
+-------------------+--------------------+----------------------+
|Голуби             |—                   |Сюжетная фотокнига    |
+-------------------+--------------------+----------------------+
|Каникулы           |—                   |Сюжетная фотокнига_1.3|
+-------------------+--------------------+----------------------+
|Пианино            |—                   |Сюжетная фотокнига    |
+-------------------+--------------------+----------------------+
|Спасатели          |—                   |Сюжетная фотокнига_1.3|
+-------------------+--------------------+----------------------+

Выпускные альбомы
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

+----------------+--------------------+------------------+
|Сюжет           |- Сборка скриптом   |- Ручная сборка   |
|                |- PDF пресет        |- PDF пресет      |
+================+====================+==================+
|ФК Яркое Детство|[High Quality Print]|—                 |
+----------------+--------------------+------------------+
|ФК Библиотека   |[High Quality Print]|Сюжетная фотокнига|
+----------------+--------------------+------------------+
|ФК ДДС          |ДДС                 |—                 |
+----------------+--------------------+------------------+
|ФК Хорошее время|—                   |Сюжетная фотокнига|
+----------------+--------------------+------------------+
|- ФК Eleven     |[High Quality Print]|Сюжетная фотокнига|
|- ФК Nine       |                    |                  |  
+----------------+--------------------+------------------+

Используемые пресеты
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

[High Quality Print]
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Стандартный PDF пресет высококачественной печати. Предназначен для создания документов PDF для высококачественной печати на настольных принтерах и пробопечатных устройствах.
В этом пресете используется PDF версии 1.4, разрешение цветных изображений и изображений в градациях серого уменьшено до 300 т/д, а монохромных изображений — до 1200 т/д. 
В этой версии предусмотрено встраивание подмножеств всех шрифтов, сохранение цветов без распределения прозрачности (для типов файлов, предусматривающих изменение прозрачности).
Такие документы PDF могут быть открыты программами Acrobat 5.0 и Acrobat Reader 5.0, а также их более поздними версиями.

Сюжетная фотокнига
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

PDF пресет используется при **ручной сборке** сюжетных фотокниг и выпускных альбомов. В этом пресете используется PDF версии 1.4, разрешение изображений не уменьшается.
PDF пресет добавляет **информацию о странице** (название документа; номер страницы документа - необходим для производства) в готовый PDF. Использует **вылеты и область слага** документа.

.. figure:: /prepress/scripts/images/page-info.png
   :align: center

   Информация о странице: название документа — **Untitled-1**, номер страницы — **24**

.. code-block:: none
   :linenos:
   :emphasize-lines: 1, 3, 26, 27, 28, 30, 37, 41, 46, 49, 51
   
   PDF Preset: Сюжетная фотокнига

   Compatibility: Acrobat 5 (PDF 1.4)

   Standards Compliance: None

   General
       Pages: All
       Spreads: Off
       View: Default
       Layout: Default
       Full Screen: Off
       Generate Thumbnails: Off
       Optimize PDF: Off
       Create Acrobat Layers: N/A
       Export Layers: Visible and Printable Layers
       Include Bookmarks: Off
       Include Hyperlinks: Off
       Export Nonprinting Objects: Off
       Export Visible Guides and Baseline Grids: Off
       Create Tagged PDF: Off
       Interactive Elements: Do Not Include

   Compression
       Color Images
           No Sampling Change
           for images above: 450 ppi
           Compression: Automatic
           Tile Size: N/A
           Quality: Maximum

   Marks and Bleeds
       Crop Marks: Off
       Bleed Marks: Off
       Registration Marks: Off
       Color Bars: Off
       Page Information: On
       Page Mark Type: Default
       Weight: 0.25 pt
       Offset: 2,117 mm
       Use Document Bleed Settings: On
       Bleed Top: 3 mm
       Bleed Bottom: 3 mm
       Bleed Inside: 3 mm
       Bleed Outside: 3 mm
       Include Slug Area: On

   Output
       Color Conversion: No Color Conversion
       Destination: N/A
       Profile Inclusion Policy: Don't Include Profiles

    
Сюжетная фотокнига_1.3
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------    

PDF пресет используется при **ручной сборке** сюжетных фотокниг. Основан на пресете `Сюжетная фотокнига`_. В этом пресете используется **PDF версии 1.3**. Transparency Flattener Preset: **[High Resolution].**

.. code-block:: none
   :linenos:
   :emphasize-lines: 1, 3, 12
   
   PDF Preset: Сюжетная фотокнига_1.3

   Compatibility: Acrobat 4 (PDF 1.3)

   Standards Compliance: None

   Advanced
       Subset Fonts Below: 100%
       Omit PDF: Off
       Omit EPS: Off
       Omit Bitmap Images: Off
       Transparency Flattener Preset: [High Resolution]
       Ignore Spread Overrides: Off
       Display Title: File Name
       Language: English: USA

    
ДДС
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------   

PDF пресет для скрипта **ДДС 1.2**. В этом пресете используется **PDF версии 1.3**, разрешение изображений не уменьшается. Transparency Flattener Preset: **[High Resolution].**

.. code-block:: none
   :linenos:
   :emphasize-lines: 1, 3, 26, 27, 28, 30, 49, 51, 58

   PDF Preset: ДДС

   Compatibility: Acrobat 4 (PDF 1.3)
   
   Standards Compliance: None
   
   General
       Pages: All
       Spreads: Off
       View: Default
       Layout: Default
       Full Screen: Off
       Generate Thumbnails: Off
       Optimize PDF: Off
       Create Acrobat Layers: N/A
       Export Layers: Visible and Printable Layers
       Include Bookmarks: Off
       Include Hyperlinks: Off
       Export Nonprinting Objects: Off
       Export Visible Guides and Baseline Grids: Off
       Create Tagged PDF: Off
       Interactive Elements: Do Not Include
   
   Compression
       Color Images
           No Sampling Change
           for images above: 450 ppi
           Compression: Automatic
           Tile Size: N/A
           Quality: Maximum
   
   Marks and Bleeds
       Crop Marks: Off
       Bleed Marks: Off
       Registration Marks: Off
       Color Bars: Off
       Page Information: Off
       Page Mark Type: Default
       Weight: 0.25 pt
       Offset: 2,117 mm
       Use Document Bleed Settings: Off
       Bleed Top: 0 mm
       Bleed Bottom: 0 mm
       Bleed Left: 0 mm
       Bleed Right: 0 mm
       Include Slug Area: Off
   
   Output
       Color Conversion: No Color Conversion
       Destination: N/A
       Profile Inclusion Policy: Don't Include Profiles
   
   Advanced
       Subset Fonts Below: 100%
       Omit PDF: Off
       Omit EPS: Off
       Omit Bitmap Images: Off
       Transparency Flattener Preset: [High Resolution]
       Ignore Spread Overrides: Off
       Display Title: File Name
       Language: English: USA

Polska_Lab
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------   
       
PDF пресет для скрипта **Сюжеты Polska 1.0.2**. Основан на пресете `[High Quality Print]`_. PDF пресет **конвертирует** изображения документа в профиль **Coated FOGRA39(ISO 12647-2:2004)**.

.. code-block:: none
   :linenos:
   :emphasize-lines: 1, 3, 8, 9, 10

   PDF Preset: Polska_Lab

   Compatibility: Acrobat 5 (PDF 1.4)

   Standards Compliance: None

   Output
       Color Conversion: Convert to Destination (Preserve Numbers)
       Destination: Coated FOGRA39 (ISO 12647-2:2004)
       Profile Inclusion Policy: Don't Include Profiles
