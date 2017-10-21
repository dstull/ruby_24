![ruby_2.4.2](https://img.shields.io/badge/ruby-2.4.2-brightgreen.svg) ![License MIT](https://img.shields.io/badge/license-MIT-blue.svg) 


ruby_24 sets up a container running centos 7 and ruby 2.4

### Usage

To run it:

    $ docker run -d hammer098/ruby_24

### Docker Compose

```yaml
version: '3'

services:
  ruby_24:
    image: hammer098/ruby_24

### Contributing

Before submitting pull requests or issues, please check github to make sure an existing issue or pull request is not already open.
