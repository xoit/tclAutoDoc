# tclAutoDoc
An auto document system to generate manual, presentation and etc from the code itself.
Use Tcl as programming lanuage to well support IC industry.

## How to Use
Load the sh to define some environment variable and create some alias commands to your shell.

In the shell script, you must define some seach paths, where program can find your code source.

And document output directory, you can even put this whole directory to one sub directory of your website, so that all the document can be accessed via web.

    source tclautodoc.sh
    tclAutoDoc tproc_ReportPower

## Features
Currently word document is not supported. We start from symbols in the code source and use markdown as intermedia.
  - PDF/HTML support
  - Plugin to extend the function
  - JS package support for static page

## Syntax
 - #:> description
 - #</ #/> code
 - # - list
 - #| flow chart
 - more

## Readmore
Test