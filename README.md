# freetype

How to add freetype2 to your project

```
mulle-sde dependency add https://gitlab.freedesktop.org/freetype/freetype/-/archive/VER-2-10-4/freetype-VER-2-10-4.tar.gz
mulle-sde dependency set freetype aliases Debug=freetyped,Release=freetype
mulle-sde dependency mark freetype no-header
mulle-sde dependency mark -e freetype only-liftheaders
mulle-sde dependency mark freetype no-inplace
```

Notes freetype headers need to be dispensed to be findable. Also the built libraries have different names, for Debug and Release.
