# OpenType Feature Bundle for TextMate/Sublime Text

This covers Adobe’s [OpenType Feature File Specification](http://partners.adobe.com/public/developer/opentype/afdko/topic_feature_file_syntax.html) used by the AFDKO. As well as syntax highlighting, there are also a couple of snippets for creating features, tables etc.

## Installation

### Sublime Text (with Package Control)

1. Package Control: Install Package `OpenType Feature Bundle`
2. Restart Sublime Text

### TextMate (using git)

1. Make a new bundles folder `mkdir -p ~/Library/Application\ Support/TextMate/Bundles`
2. Open the new folder `cd ~/Library/Application\ Support/TextMate/Bundles`
3. Clone to your new folder `git clone git://github.com/brew/opentype-feature-bundle.git "opentype-feature-bundle.tmbundle"`
4. Reload TextMate Bundles `osascript -e 'tell app "TextMate" to reload bundles'`

### More!

Kenneth Ormandy maintains an [Atom package](https://github.com/kennethormandy/opentype-feature-bundle) that supports the Atom text editor.

My thanks to [Tal Leming](http://www.typesupply.com/) for contributing some snippets and keywords before this became a Github project.

I'm more than happy to accept pull requests!
