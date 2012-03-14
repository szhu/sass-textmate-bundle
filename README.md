# Sass for TextMate/Sublime Text 2

## TextMate Installation

### With git

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles/
    cd ~/Library/Application\ Support/TextMate/Bundles/
    git clone https://github.com/nathos/sass-textmate-bundle.git Sass.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'

### Without git
    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    mkdir sass-textmate-bundle.tmbundle && curl -L https://github.com/nathos/sass-textmate-bundle/tarball/master | tar xz --strip 1 -C sass-textmate-bundle.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'

## About & Credit
This was originally a fork of <https://github.com/seaofclouds/sass-textmate-bundle>, and includes the best contributions of people [throughout the network](https://github.com/nathos/sass-textmate-bundle/network).

Features include imprpoved syntax highlighting, [Zen Coding](http://code.google.com/p/zen-coding/)-style property autocompletion, and more.