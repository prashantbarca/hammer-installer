# Hammer installer

This tool could be used to install the [hammer parser combinator toolkit](https://github.com/prashantbarca/hammer).

## Requirements

- git
- curl
- scons
- ruby >= 2.0.0 if installing ruby bindings 

## Installing dependencies

### Mac OSX 

    brew install glib scons curl
    
### Ubuntu
    
    sudo apt-get install gcc scons pkg-config libglib2.0-0 glib2.0-dev curl

## Install hammer 

To install hammer as it is...

    curl https://raw.githubusercontent.com/prashantbarca/hammer-installer/master/bin/hammer-installer | bash -s -- -a
    
Or install hammer with the ruby bindings...
  
    curl https://raw.githubusercontent.com/prashantbarca/hammer-installer/master/bin/hammer-installer | bash -s -- -r
    
## License

Copyright 2017 Prashant Anantharaman

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
