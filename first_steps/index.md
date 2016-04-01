---
layout: page
title: First steps
---
<br>

### First steps

#### 1. Download the script and include it in your page

{% highlight javascript %}
  <head>
    <script type="text/javascript" src="http://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
  
    <link href="css/nanogallery.min.css" rel="stylesheet" type="text/css">
    <script type="text/javascript" src="jquery.nanogallery.min.js"></script>
  </head>
{% endhighlight %}
JQUERY is only to be included, if not already present in your page.

#### 2. Setup your HTML and initialize the nanoGALLERY script

{% highlight javascript %}
  <body>
    <div id="mynanogallery">
      <a href="img_01.jpg" data-ngthumb="img_01t.jpg">Title Image1</a>
      <a href="img_02.jpg" data-ngthumb="img_02ts.jpg" data-ngdesc="Image 2 description">Title Image2</a>
      <a href="img_03.jpg" data-ngthumb="img_03t.jpg" data-ngdesc="Description 3">Title Image3</a>
    </div>
    
    <script>
      $(document).ready(function () {
        $("#mynanogallery").nanoGallery({
          itemsBaseURL:'http://nanogallery.brisbois.fr/demonstration/'
        });
      });
    </script>
  </body>
{% endhighlight %}
