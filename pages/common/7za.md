# 7za

> A file archiver with high compression ratio.
> A standalone version of `7z` with support for fewer archive types.
> More information: <https://www.7-zip.org/>.

- Archive a file or directory:

`7za a {{archive.7z}} {{path/to/file|path/to/directory}}`

- Extract an existing 7z file with original directory structure:

`7za x {{archive.7z}}`

- Archive a file or directory using a specific archive type:

`7za a -t{{zip|gzip|bzip2|tar}} {{archive.7z}} {{path/to/file|path/to/directory}}`

- List available archive types:

`7za i`

- List the contents of an archive file:

`7za l {{archive.7z}}`
