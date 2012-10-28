sogou_hotwords_yong
===================

A script automatically update yong's local vocabulary with sogou's hot words(网络流行新词)


HOWTO
===================

1. Modify your yong.ini, add dicts=/mb/hotwords.txt to section [pinyin]
which results something like this:

[pinyin]
name=拼音
engine=libmb.so
arg=mb/pinyin.txt
overlay=mb/pinyin.ini
dicts=mb/hotwords.txt

2. Add the script to system's autostart list
