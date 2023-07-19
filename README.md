# fontconfig_sarasa
A set of fontconfig which help you set CJK fonts to fall back to Sarasa Gothic properly.

## Usage
1. install Sarasa Gothic fonts https://github.com/be5invis/Sarasa-Gothic
2. copy ``64-language-selector-prefer.conf`` and ``84-locale.conf`` into ``/etc/fonts/conf.d/``
3. run ``fc-cache -vv``

## Reference
https://wiki.archlinuxcn.org/wiki/%E5%AD%97%E4%BD%93%E9%85%8D%E7%BD%AE  
https://catcat.cc/post/2021-03-07/
