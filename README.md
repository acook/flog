# flog

- **home**: http://ruby.sadi.st
- **repo**: https://github.com/seattlerb/flog
- **rdoc**: http://seattlerb.rubyforge.org/flog


## Description

Flog reports the most tortured code in an easy to read pain
report. The higher the score, the more pain the code is in.


## Features / Problems

- Easy to read reporting of complexity/pain.
- Colourised output (by
  [@vrinek](https://github.com/vrinek/flog/commit/f31388220b6143d6a23056a7ab2f5e4c1f130c32))


## Synopsis

    % find lib -name \*.rb | xargs flog
    Total Flog = 1097.2 (17.4 flog / method)
    
       323.8: Flog total
        85.3: Flog#output_details
        61.9: Flog#process_iter
        53.7: Flog#parse_options
    ...


## Requirements

- ruby2ruby (only for -v)
- ruby_parser


## Install

    sudo gem install flog


## License

(The MIT License)

Copyright (c) Ryan Davis, seattle.rb

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

