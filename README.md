## Brackets HTML Templates extension, updated

Brackets extension that will insert a chosen HTML template into the current file. Currently this will overwrite the current content of the file so it should be used on new, empty files. If there is content, a small warning is displayed.

Templates are based on generic HTML for specific doctypes or example HTML file for frameworks. The HTML for the frameworks is based on whatever example file is provided with the download of that framework. Some adjustment will likely be needed for new projects, such as file/folder locations and whatnot.

### Usage

Create a new file. Select "HTML Templates" under the Edit Menu. A modal will appear presenting different HTML template options. Choosing one will insert that HTML into the current file.

### Source, updates, & changes

Forked from [Travis Almand’s Brackets HTML Templates](https://github.com/talmand/Brackets-HTML-Templates) extension, updated, & extended. Broadly, these are the changes that I’ve made:

* HTML5 template updated
* Bootstrap 3 template updated to current version (3.3.7), with full CDN support
* Bootstrap 4 template added, with full CDN support
* Foundation 6 template added (6.4.3)
* Skeleton template updated to current version (2.0.4)<sup id="skeleton">[1](#fn1)</sup>
* HTML5 Boilerplate template updated to current version (6.0.1)
* Materialize template updated to current version (0.100.2)

### Warning

As stated above, this extension *will* overwrite the contents of the current file if any exists.

### Notes

<b id="fn1">1</b>. The [original Skeleton](http://getskeleton.com/) is a dead project; it has been forked & that project is actively being developed. Check out the [website](https://skeleton-framework.github.io/), [GitHub](skeleton-framework), or a [sample template](https://github.com/skeleton-framework/skeleton-framework/wiki/Getting-Started). [↩](#skeleton)
