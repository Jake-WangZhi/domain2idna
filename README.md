# domains2idna

## The tool to convert domains to the famous IDNA format.

The objective of this project is to provide a tool for list or hosts file maintainer that can convertible domain to the PunyCode/IDNA format.

* * *

## Documentation as place to be!

Want to know more about **domain2idna**?
We invite you to read the documentation at https://domain2idna.readthedocs.io!

Want a local copy!? We get you covered!

Simply run the following and enjoy the documentation!

```
$ # We move to the docs directory
$ cd docs/
$ # We build the documentation
$ make html
$ # We run the documentation with our favorite browser.
$ chromium _builld/html/index.html
```

## Main Features

- Read a given domain and convert it to the PunyCode/IDNA format.
- Read a file and convert all non commented line to the PunyCode/IDNA format.
- Print the converted data on screen.
- Save into a file the converte data.
- Return the converted data (when used as a module).
- Ignore commented inputs (starts with `#`)

## Supporting the project

[domain2idna](https://github.com/funilrys/domain2idna), [PyFunceble](https://github.com/funilrys/PyFunceble), [Dead-Hosts](https://github.com/dead-hosts), [Funceble](https://github.com/funilrys/funceble) and all other analog projects are or were powered by :coffee:!

This project helps you and or you like it?

[![Help me with a cup of coffee](https://img.shields.io/badge/Help%20me%20out-with%20a%20cup%20of%20%E2%98%95%20-blue.svg)](https://www.paypal.me/funilrys/)

## License

```
MIT License

Copyright (c) 2018 Nissar Chababy

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
```