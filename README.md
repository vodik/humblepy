# README

A Humble Indie Bundle webscraper / download manager.

## Configuration

```
[keys]
1="foobar"
2="foobar"
3="foobar"
4="foobar"
5="foobar"
android1="foobar"
android2="foobar"
botanicula="foobar"
frozenbyte="foobar"
frozensynapse="foobar"
introversion="foobar"
mojang="foobar"
voxatron="foobar"
```

## Usage

`humblepy [options] [bundles]`

## Options

```
-b / --bundle=NAME
    Specify a bundle by name
        humblepy -b frozenbyte

-t / --target=NAME
    Specify the comma separated platforms of interest
        humblepy -t linux,audio

-v / --verbose
    Enable verbose reporting for info, warnings, and errors.

--as-root
    Enable running as root for system-wide installs. *NOT RECOMMENDED*
```

## Copyright

```
Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
```
