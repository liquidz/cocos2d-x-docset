cocos2d-x `v3.3rc0` api document

## download cocos2d-x

 * http://cocos2d-x.org/download

## fix doxygen.config

 * doxygen.config
```
PROJECT_NUMBER    = FIXME
GENERATE_DOCSET   = YES
DISABLE_INDEX     = YES
SEARCHENGINE      = NO
GENERATE_TREEVIEW = NO
```

## generate html

```
doxygen doxygen.config
```

## make docset

```
cd html
make
```

## import docset to dash

 * `Dash > Preferences > Docsets` --> `html/org.doxygen.Project.docset`

