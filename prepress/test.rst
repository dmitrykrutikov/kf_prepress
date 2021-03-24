Страница препресса
=====================================================

.. note::
   Внимание Тревога!!     

   
Код
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

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
