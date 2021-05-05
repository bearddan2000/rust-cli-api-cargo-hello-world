# rust-cli-api-cargo-hello-world

## Description
A POC for a rust REST Api.

## Tech stack
- rust
- cargo
  - tokio
  - warp

## Docker stack
- rust:1.43

## To run
`sudo ./install.sh -u`
- Available at http://localhost/hello/<name>
  - <name> can be a string or number

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
https://blog.logrocket.com/creating-a-rest-api-in-rust-with-warp/
