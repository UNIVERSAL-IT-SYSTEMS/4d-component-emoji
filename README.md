# 4d-tips-emoji
Database of rasterised Unicode emoji on Mac and Windows.

Example
---

Pass starting code-point, ending code-point, thumbnail size, image size. 
```
TRUNCATE TABLE([Emoji])

PAUSE INDEXES([Emoji])

  //Miscellaneous Symbols and Pictographs
Create_emoji_images (0x0001F300;0x0001F5FF;32;1024)

RESUME INDEXES([Emoji])
```
