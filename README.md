transmogrifier
==============

PNG to ANSI color converter

Install this globally and you'll have access to the `transmogrify` command anywhere on your system.

```shell
npm install -g transmogrifier
```

```shell
Usage: transmogrify <filename> [-f] [-h]

Help: transmogrify draws a png to your console.
Options:
	-f --fit	Fit the image to the console size.
	-h --help	Renders this message.
```

```shell
transmogrify imgs/wow.png
```

![wow](https://raw.githubusercontent.com/Picturelife/transmogrifier/master/imgs/example.png)

Save the output too!
```shell
transmogrify imgs/wow.png > doge

cat doge
```
