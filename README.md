### Textmate with alternative SASS Syntax

For those of you how prefer the alternative Sass Synatx:

    .pagination
      margin: 10px 0 10px 0
      text-align: center
      font-size: 14px
      span
        color: #000
      span.disabled
        display: none
      a 
        margin: 0 1px 0 1px

### Installation

#### With git

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles/
    cd ~/Library/Application\ Support/TextMate/Bundles/
    git clone https://github.com/chrisledet/sass-bundle.git Sass.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'

#### Without git
    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget https://github.com/downloads/chrisledet/sass-bundle/Sass.tmbundle.tar.gz
    tar zxvf Sass.tmbundle.tar.gz
    rm Sass.tmbundle.tar.gz
    osascript -e 'tell app "TextMate" to reload bundles'

### About
I couldn't find a decent bundle that's updated regularly so I forked this and decided to 
maintain one for myself. Others should feel free to submit patches or whatever.

### Credit
This bundle was not created by me. It is a fork of <https://github.com/seaofclouds/sass-textmate-bundle>.
