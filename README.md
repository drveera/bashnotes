* auto-gen TOC:
{:toc}

# bashnotes
Collection of day to day bash procedures 

[TOC]

### Convert a row to column 

```
#assuming the delimiter is tab
sed s/\\t/\\n/g file
```
