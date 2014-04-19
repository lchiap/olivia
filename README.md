# Overload Grid

Welcome to Overload Grid. This is a simple, easy and powerfull CSS Grid. It's free, you can use this Grid for your proyects.


## Installation

-   Clone `git clone https://github.com/Luifi/Overload-Grid`
-   [Download the latest version](https://github.com/.zip)



## Getting Started

#### First you need to link the stylesheet
```
<link rel="stylesheet" type="text/css" href="css/overload-grid.css">
<link rel="stylesheet" type="text/css" href="css/normalize.css">
```

#### Structuring your layouts
```
<div class="container">
    <div class="o-grid">
        <div class="boxM-100 boxS-100">
            <div class="bit-box">100</div>
        </div>
    </div>

    <div class="o-grid">
        <div class="boxM-50 boxS-100">
            <div class="bit-box">50</div>
        </div>
        <div class="boxM-50 boxS-100">
            <div class="bit-box">50</div>
        </div>
    </div>

    <div class="o-grid">
        <div class="boxM-25 boxS-50">
            <div class="bit-box">25</div>
        </div>
        <div class="boxM-25 boxS-50">
            <div class="bit-box">25</div>
        </div>
        <div class="boxM-25 boxS-50">
            <div class="bit-box">25</div>
        </div>
        <div class="boxM-25 boxS-50">
            <div class="bit-box">25</div>
        </div>
    </div>

    <div class="o-grid">
        <div class="boxM-25 boxS-100">
            <div class="bit-box">25</div>
        </div>
        <div class="boxM-50 boxS-100">
            <div class="bit-box">50</div>
        </div>
        <div class="boxM-25 boxS-100">
            <div class="o-grid">
                <div class="boxM-100 boxS-100 pReset mb10">
                    <div class="bit-box">25</div>
                </div>
            </div>
            <div class="o-grid">
                <div class="boxM-100 boxS-100 pReset">
                    <div class="bit-box">25</div>
                </div>
            </div>
        </div>
    </div>
</div>
```
You'll be able to create your quick and simple structures. The beauty of this grid is that it is 100% customizable and intuitiba. Take a vistaso the code, you see that each box has a size and is named according to their size. Eg a box that takes up 100% of the container is named box-100 and also with the other

#### Customising your grid
Maybe you want to go old school and create a two-column layout, It's so easy all you need is basic math (along as the .bit- classes equal to 100%, it will be perfect).
```
<div class="frame">
	<div class="bit-75">Content here</div>
	<div class="bit-25">Content here</div>
</div>
```
Creating the css is also simple:
```
.bit-75 {width:75%;}
.bit-25 {width:25%;}
```

### Support
If you have any questions or you're struggling with it, get in touch:

-   [hello.joer@gmail.com](mailto:hello.joer@gmail.com)
-   [@joericho](http://twitter.com/joericho)

### Tutorials
[Build a Freshly Squeezed Responsive Grid System](http://webdesign.tutsplus.com/tutorials/htmlcss-tutorials/build-a-freshly-squeezed-responsive-grid-system)
If you have written about Lemonade or want too - [let me know](http://twitter.com/joericho)

### Lets make Lemonade
Currently building the real documentation website for Lemonade, If you've got any finished results of using Lemonade or you've got any kind words to say - [get in touch](http://twitter.com/joericho)

### Thank you!
I've had some amazing feedback since creating Lemonade and I am glad it can help people.

Also want to thank people who are testing and contributing to the product.

### License
```
Copyright (C) 2013 Joe Richardson

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
