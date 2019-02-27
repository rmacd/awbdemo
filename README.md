# AWB / asciidoc website builder demo

## Setup

In file ~/.config/awb/awb.conf

```
[awbdemo]
siteroot: /path/to/awbdemo
baseurl: http://www.example.com
asciidoc options: -a icons -a theme=flask -f /path/to/awbdemo/src/html5.conf
tidy: true
```

## Notes

On MacOS, py-configparse and py-xdg are required. Also to get AWB to behave, I had to explicitly set my
environment to use Python 3.x.
