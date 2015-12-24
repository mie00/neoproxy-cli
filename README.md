# NeoProxy-cli

NeoProxy-cli is a node.js command line interface based on [NeoProxy](https://github.com/mie00/neoproxy) to do basic proxy tasks.

## Installation

1. Install neoproxy-cli globally.

  `npm install -g neoproxy-cli`

2. Type neoproxy to start the proxy server

  ```bash
  $ neoproxy --help

    Usage: neoproxy [options]

    Options:

      -h, --help                 output usage information
      -V, --version              output the version number
      -l, --logging              enable logging
      -p, --port <port>          the port the proxy server listens to [8087]
      -L, --limit <bandwidth>    limit connection speed
      --interval <milliseconds>  the interval to calculate the limit (melliseconds) [1000]

  ```
