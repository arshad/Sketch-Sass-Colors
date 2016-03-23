# Sketch-Sass-Colors
This plugin displays colors as Sass variables for Sketch.

![sketch-sass-colors](https://cloud.githubusercontent.com/assets/124599/10825307/e7c0223e-7e7d-11e5-8ec3-60c633ea8ae6.png)

# Installation

![sketch-sass-colors-configure](https://cloud.githubusercontent.com/assets/124599/10826257/50944bb0-7e82-11e5-93af-4d51ddfc5684.png)

1. Download and extract the plugin.
2. Double click to install.
3. From the Sketch Menu bar, click on `Plugins ▸ Sass Colors ▸ Configure`.
4. Copy and paste the contents of your Sass color variables.
5. Save.

#### Note

You can use both Sass variables or Sass list. See examples below:

```
// Sass variables.
$grey: #ccc,
$grey-light: #EAEBEC,
$grey-dark: #231F20,
```

```
// Sass list.
$colors: (
  green: #01A490,
  teal: #20BDBE,
  purple: #92278F,
  purple-light: #C6168D,
  purple-dark: #5C2E91
);
```

# How to use

1. Select a layer.
2. Press `ctrl shift c`.
3. The Sass variable name and the matching colors will be displayed.

# License

The MIT License (MIT)

Copyright (c) 2015 Arshad Chummun

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
