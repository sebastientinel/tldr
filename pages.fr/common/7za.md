# 7za

> Solution d'archivage de fichier à haut niveau de compression.
> Version autonome de `7z` qui supporte moins de types d'archive.
> More information: <https://www.7-zip.org/>.

- Archive un fichier ou un répertoire :

`7za a {{archive.7z}} {{chemin/du/fichier|chemin/du/répertoire}}`

- Extrais une archive 7z avec la structure du répertoire :

`7za x {{archive.7z}}`

- Archive un fichier ou un répertoire en sélectionnant un type d'archive :

`7za a -t{{zip|gzip|bzip2|tar}} {{archive.7z}} {{chemin/du/fichier|chemin/du/répertoire}}`

- Liste les types d'archives disponibles :

`7za i`

- Liste le contenu d'une archive :

`7za l {{archive.7z}}`
