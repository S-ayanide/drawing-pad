# Drawing Pad

A simple drawing pad wrapped with Two.js inside a docker container. This app serves as a demonstration to wrap components with docker and serve it using Nginx.

## Quick Reference

- Maintained by:
  [Sayan Mondal](sayanmondal.me)

- Where to get help:
  [Create an issue](https://github.com/S-ayanide/drawing-pad/issues)

## Screenshots

<img src="https://i.ibb.co/pJV149C/Screenshot-2022-04-30-at-9-38-17-PM.png" alt="Screenshot-2022-04-30-at-9-38-17-PM" width="500" border="0">

## How to use this image

- Start an instance of the application in detached mode

  ```bash
  docker run --name drawing-pad -d sayanide/drawing-pad
  ```

- For local dev, clone the [repository](https://github.com/S-ayanide/drawing-pad) and run the dev docker-compose file

  ```bash
  docker-compose -f dockerfiles/docker-compose.dev.yml up -d --build
  ```
