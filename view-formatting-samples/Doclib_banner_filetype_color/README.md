![images.png](https://github.com/KuramotoYu/SPO-List-Formatting/blob/master/view-formatting-samples/Doclib_banner_filetype_color/images.png)
  
SharePoint ドキュメントライブラリに保存されたファイルの種類ごとにバナーの色付けを行います。  
ファイル名に下表のいずれかの文字が含まれている場合に色付けします。  
ファイル名に下表の文字が含まれている場合に色分けされており、拡張子以外の場所に含まれていても色付けされる点にご注意ください。  
識別する文字と色のパターンは下表の通りです。  

|識別文字|色コード|
|:-----------------|:------------------|
|.xls|#efffe0|
|.doc|#bed7ee|
|.ppt|#ffe7e0|
|.pdf|#ffb2b4|
|その他|#f3f3f3|
  
ドキュメントライブラリに必要な列は下表の通りです。  
「ファイル名」と「ファイルURL」は既定の列で、列を追加する必要はありません。
|列名|列内部名|列種類|
|:-----------------|:------------------|:------------------|
|ファイル名|FileLeafRef|既定列|
|ファイルURL|FileRef|既定列|
|TargetBlank|TargetBlank|はい/いいえ|  
  
---------------------------------------------------
  
Color the banner for each file type stored in the SharePoint DocumentLibrary.  
Color if the file name contains any of the characters in the table below.  
Note that if the file name contains characters in the table below, it will be color-coded and will be colored even if it is in a location other than the extension.  
The patterns of the characters and colors that identify are as shown in the table below.  
  
|Identification character|Color Code|
|:-----------------|:------------------|
|.xls|#efffe0|
|.doc|#bed7ee|
|.ppt|#ffe7e0|
|.pdf|#ffb2b4|
|その他|#f3f3f3|
  
The columns required for the DocumentLibrary are shown in the table below.  
"FileName" and "FileURL" are the default columns, and you do not need to add any columns.    
|File name|Internal name|Type|
|:-----------------|:------------------|:------------------|
|FileName|FileLeafRef|Default Column|
|FileURL|FileRef|Default Column|
|TargetBlank|TargetBlank|Yes/No|  
