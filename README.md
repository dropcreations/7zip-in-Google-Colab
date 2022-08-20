# 7zip-in-Google-Colab
Compress and uncompress archives in Google Colab using 7-Zip archive manager.

<a href="https://colab.research.google.com/github/dropcreations/7zip-in-Google-Colab/blob/main/7zip-in-Google-Colab.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/></a>
<br>
* Click on the "Open in Colab" button to open this notebook in google colab

## __Compress Files and Folders__

* Create **zip, tar, 7z, gz, bz2, xz, wim** files.
* If you want you can add **password** or **split** the archive.
* If you want to save archive in **another** location **uncheck** `saveToSourceLocation`.

## __Uncompress Files__

* To **list content** of the file, use `viewFile`. ***Uncheck this after viewing the content***.
* Can also extract **splited** archives.
* `saveToSourceLocation`: Extracts files to source location.
* If you want to extract files from archive **without using directory names**, uncheck `directoryNames`.
> * NOTE : ***Don't uncheck*** `directoryNames` at normal use.
>
>  ![directory_names](https://raw.githubusercontent.com/dropcreations/Essential-Google-Colab-Notebook/main/cell_logos/directory_names.png) ![without_directory_names](https://raw.githubusercontent.com/dropcreations/Essential-Google-Colab-Notebook/main/cell_logos/without_directory_names.png)
>
> * Without `directoryNames`, extracts files as **2nd figure**.
