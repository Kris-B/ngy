---
layout: documentation
title: API and callbacks
---

#  Callbacks
Callbacks and javascript helpers provide a simple mechanism to extend the capabilities of nanoGALLERY2.

| Callback | Description | Script<br>Version |
| ----- | ----- | ----- |
| fnInitGallery | Called after each gallery construction. ||
| fnThumbnailInit | Called once after one thumbnail's build. Called for each thumbnail. ||
| fnThumbnailHoverInit | Called once to initialize the thumbnail hover effect. Called for each thumbnail. ||


# API methods
```
  Usage: $('#yourElement').nanoGallery('method', options);
```

| Method | Option(s) | Description | Script<br>Version |
| ----- | ----- | ----- | ----- |
| destroy | | Removes the gallery. <br>Usage: $('#yourElement').nanoGallery('destroy');| |
| displayItem | itemID | Displays an item (album or image).<br>Usage: $('#yourElement').nanoGallery('displayItem', 'itemID');<br>- to display an album: $('#yourElement').nanoGallery('displayItem', 'albumID')<br>- to display an image: $('#yourElement').nanoGallery('displayItem', 'albumID/imageID')| |






