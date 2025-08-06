# About

This is a minimalistic personal webpage built with [Hugo](https://gohugo.io/). The live site is available at [tylonghuang.com](https://www.tylonghuang.com).

![](/img/preview.png "Desktop and Mobile Preview")

## Page Features

✔ Minimalist

✔ Responsive

✔ Performant

✔ Privacy-friendly

## Usage

In case you are interested in using this yourself or in developing this further, clone or fork this repo. To get the theme as a submodule, run:
```
$ git clone --recurse-submodules
$ cd personal-page
```
To update the theme, run:
```
$ git submodule update --recursive --remote
```
Once you have set everything up, you can run the following to test the page locally:
```
$ hugo server -t researcher -w -D
```
In case there is an error, make sure that you have the latest Hugo version. You can update Hugo with Chocolatey by running:
```
$ choco upgrade hugo-extended -y
```

## Credit

... goes to all the contributors of [hugo-researcher](https://github.com/ojroques/hugo-researcher).
