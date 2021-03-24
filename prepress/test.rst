Страница препресса
==========================

.. note::
   Внимание Тревога!!     


.. image:: 1.jpg

Код
~~~~~

.. code-block:: javascript   

    for (var i = 0; i < allFilesList.length; i++) {
    file = allFilesList[i];	
    if (file instanceof File && file.name.match(/\.jpg$/i)) {
	
    allFilesArr.push(decodeURI(file));

    var thumbTitle = new Thumbnail(file);
    var md = thumbTitle.synchronousMetadata;   
    var icc_title = md.read(XMPConst.NS_DC, "title");

    if (icc_title.toString().match(/[а-я]/i)) {
    iccArr.push(icc_title);
    iccAndNameArr.push(icc_title + "#" + decodeURI(file.name))
    }


Скрипты
-------
.. csv-table:: 
    :header: Скрипт, Сюжет, Статус, Программа, Разработчик, Тестрирование

    ФК Библиотека 1.0, ФК Библиотека, Используется, Indesign CC 2017, Крутиков Д., Крутиков Д.
    ДДС 1.2, ФК ДДС, Используется, Indesign CC 2017, Козьяков А., Крутиков Д.