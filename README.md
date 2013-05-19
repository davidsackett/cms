# Simple Cms

## Requirements

- File based
  - Be nice to use Dropbox etc update
- Versioned
  - May as well use Git etc
- Files should closely align to URLs I don't want a deeply nest hierachy, files
  should be easy to find
- Formating
  - Use markdown, asciidoc etc. Also, HTML
  - Syntax highlighting
  - Avoid non-standard metadata at the top of files. We might want to stitch multiple files
    together
- Templating
  - Support rendering all images in a directory
  - Show unrecongnised files for download
  - Add features like slide shows
  - Have hierachical nav
  - Have search with markdown files and other types like word
- Editing
  - Text editor with Git or Dropbox sync
  - Online browser based editing with preview
- Integration
  - Could this be technology agnostic and allow different templates to be
    implemented in different languages. Maybe even reverse proxy functionality
- Deployment
  - Live and static deployment?

## Solution

### URL to file mapping

`/a/b/c.md` -> `[app root]/a/b/c.md`

`/a/b/` contains:
c.md
d.md

Concatenate alphabitically?

Page = directory = item in navigation

Single file will be rendered?
Would be nice to have multiple files in a directory as separate links through

How should wiki linking work?
How to link pages and templating?
