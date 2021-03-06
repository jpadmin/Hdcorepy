# Hdcorepy
A simple python wrapper around [HostDime](http://www.hostdime.in/)'s client [API](https://api.hostdime.com/).

## Installing as a Python Module

The recommended method of installation is via [pip](https://pypi.org/project/hdcorepy/)

    # Install pip
    yum install python-pip (CentOS)
    
    apt-get install python-pip (Ubuntu)
    
    # Install hdcorepy
    pip install hdcorepy
    
    
## Usage

~~~python
from hdcorepy import Client
hdinClient = Client(privateKey, publicKey)
response = hdinClient.call("server.list")
print response
~~~

## Reference

For a comprehensive overview of the HostDime API, please see our [API reference](https://api.hostdime.com/docs/).

## License - MIT


Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
