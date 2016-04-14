---
layout: documentation
title: Options and Parameters
---

# Options

nanoGALLERY2 is highly customizable and fully adjustable to suit your needs, without coding.  

How to use options:
{% highlight javascript %}
$(document).ready(function () {
  $("#myNanoGallery").nanoGallery2({
    ...
    thumbnailHeight: 200,
    thumbnailWidth: 300,
    thumbnailAlignment: 'center',
    galleryEnableKeyboard: false,
    ...
  });
});
{% endhighlight %}

List of properties accepted by the nanoGallery2() method:   

## General settings

-----

| Property | Type | Default | Description | Script<br>Version |
| ----- | ----- | ----- | ----- | ----- |
| theme | string | 'default' |Name of the theme.<br>Note: the corresponding css-file must also be included in the html file.<br>Possible values: 'default', 'clean', 'light' or your custom one. ||
| colorScheme | string<br>object | 'none' | Gallery color scheme (breadcrumb and thumbnails).<br>Possible values: 'none', 'dark','darkRed', 'darkGreen', 'darkBlue', 'darkOrange', 'light', 'lightBackground'<br>Custom color schemes are supported. ||
| RTL | boolean | false | Sets the display direction from Right To Left (RTL). Default is from Left to Right (LTR). ||
| maxItemsPerLine	| integer |	0	| Maximum number of thumbnails per row.<br> Ignored when thumbnailWidth is 'auto'. 0 = disabled.||
| paginationDots | boolean | false | Displays dots for thumbnail pagination instead of page numbers ||
| kind | string | '' | Content storage type.<br>Possible values: '' (inline/API), 'picasa', 'flickr', 'json' ||
| hiddenAlbums | string | '' | List of hidden, including private keys. ||
| galleryRenderStep | integer | 2 | Number of lines to add when the user clicks the `more` button. ||
| galleryDisplayMode | string | 'fullContent' | Gallery display mode: `fullContent`, `pagination`, `moreButton`. ||
| galleryPaginationMode | string | 'rectangles' | What is displayed on the bottom of the gallery when pagination is enabled: `dots`, `rectangles`, `numbers`. ||



## Thumbnails

### General settings


### Advanced sizes

### Advanced effects

### 1st navigation level


## Image display


## Gallery toolbar

## Data sources

### Google Photos / Google+

### Flickr

### Self hotsted:

#### Inline method

#### API

#### nanoPhotosProvider



