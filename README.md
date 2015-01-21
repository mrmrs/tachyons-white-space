# TACHYONS-WHITE-SPACE

http://tachyons.io

Work In Progress. Pull requests and open issues welcome.

## Install
```
npm install --save-dev tachyons-white-space
```
or download the css on github and include in your project.

## The Code
```

/*

   WHITE SPACE

*/


.ws-norm    { white-space: normal; }
.ws-nowrap  { white-space: nowrap; }
.ws-pre     { white-space: pre; }

@include break(not-small) {
  .ws-norm-ns    { white-space: normal; }
  .ws-nowrap-ns  { white-space: nowrap; }
  .ws-pre-ns     { white-space: pre; }
}

@include break(medium) {
  .ws-norm-m    { white-space: normal; }
  .ws-nowrap-m  { white-space: nowrap; }
  .ws-pre-m     { white-space: pre; }
}

@include break(large) {
  .ws-norm-l    { white-space: normal; }
  .ws-nowrap-l  { white-space: nowrap; }
  .ws-pre-l     { white-space: pre; }
}
```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

