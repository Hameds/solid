# Solid, A theme for [Hugo](http://gohugo.io/), a framework for building websites.


## Installation

Inside the folder of your Hugo site run:

    $ cd themes
    $ git clone https://github.com/hameds/solid.git

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.



## Getting started

After installing the theme successfully it requires a just a few more steps to get your site running.


## Config File
Solid comes with several configuration options to aid in site customization. This is an example config.toml file:

```toml
theme = "solid"

[params.hero]
  img="img/browser.png"
  lead="test"
  title="test2"
  description="test3"

[params.services]
  
  [[params.services.item]]
    icon = "fa-heart-o"
    title = "Handsomely Crafted"
    linktitle="more"
    linkurl="#"
    description = "Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet nam itaque ipsam iste provident quo ipsam iste provident."

  [[params.services.item]]
    icon = "fa-flask"
    title = "Retina Ready"
    linktitle="more"
    linkurl="#"
    description = "Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet nam itaque ipsam iste provident quo ipsam iste provident."

  [[params.services.item]]
    icon = "fa-trophy"
    title = "Quality Theme"
    linktitle="more"
    linkurl="#"
    description = "Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet nam itaque ipsam iste provident quo ipsam iste provident."


[params.about]
    title="More about our agency"
    description="<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. </p>"
    linktitle="More Info"
    linkurl="#"

[params.footer]
  notetitle="About Us"
  note = "<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s.</p>"
  github = "#"
  twitter = "#"
  facebook = "#"
  linkedin = "#"
  instagram = "#"
  addresstitle="Our Bunker"
  address="<p>Some Ave, 987,<br>23890, New York,<br>United States.<br></p>"
```


### Nearly finished

In order to see your site in action, run Hugo's built-in local server.

`$ hugo server`

Now enter [`localhost:1313`](http://localhost:1313/) in the address bar of your browser.


## Contributing

If you find a bug or have an idea for a feature, feel free to use the [issue tracker](https://github.com/hameds/solid/issues) to let me know.


## TODO

- add rtl support
- make home page sections optional
- port all solid theme pages
- support more hugo features
- better documentation
- submit it to hugo themes showcase
