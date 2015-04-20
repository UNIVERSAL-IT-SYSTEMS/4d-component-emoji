# 4d-component-emoji
Database of rasterised Unicode emoji on Mac and Windows.

Example
---

```
$image1:=Get_emoji_image (0x0001F300;"Windows")

$image2:=Get_emoji_image (0x0001F300;"MacOS")  //default platform

$image:=$image1/$image2

SET PICTURE TO PASTEBOARD($image)
```

![]
