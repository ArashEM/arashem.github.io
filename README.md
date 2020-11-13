# My page

This repository contain my personal documents based on `rst` and `sphinx`.

## Dependencies

* Sphinx
* sphinx\_rtd\_theme

###  Install build dependencies on Debian

``` bash
sudo apt-get install python-pip plantuml sphinx
sudo pip install sphinx_rtd_theme
```



## Building

``` bash
    cd srcs/
    make html
```
You can find html files in `srcs/build/html`

## Deploy

My Github Page is configured to render `docs/` directory.  
So after compiling, contents of `docs/` is replaced by new build contents from `srcs/build/html`
This is done via **Git hooks** in `scripts/`.


