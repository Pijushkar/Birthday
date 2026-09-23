HOW TO ADD YOUR PHOTOS — 30 seconds
====================================

1. Copy your pictures into this folder (photos/).

2. Open index.html in any text editor and find the CONFIG section near the
   bottom (search for "EDIT EVERYTHING HERE"). Look for the  photos:  list:

     photos: [
       { src:'', caption:'our first picture together' },
       ...

3. Put your file name inside src, like this:

     { src:'photos/us-beach.jpg', caption:'that perfect evening' },

4. Save, refresh the website — done!

Tips:
- Keep captions short and sweet; they show under each photo in script font.
- Square-ish photos look best. Portrait photos also work (they get cropped nicely).
- Want more than 6 photos? Just add another line to the list. Fewer? Delete a line.
- If a photo shows a broken-image icon, recheck the file name and spelling —
  names are case-sensitive (Photo.JPG is not photo.jpg).
