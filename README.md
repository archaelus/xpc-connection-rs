# xpc-connection-rs

XPC connection bindings for Rust.

## What is XPC?

A low-level (libSystem) interprocess communication mechanism that is based on
serialized property lists for Mac OS. Read more at the
[Apple Developer website][apple developer].

[apple developer]: https://developer.apple.com/documentation/xpc

## Supported Data Types

*   `array`: `Vec<Message>`
*   `data`: `Vec<u8>`
*   `dictionary`: `HashMap<String, Message>`
*   `error`: `MessageError`
*   `int64`: `int64`
*   `string`: `String`
*   `uuid`: `Vec<u8>`

## Yet to Be Supported Data Types

*   `activity`
*   `bool`
*   `connection`
*   `date`
*   `double`
*   `endpoint`
*   `fd`
*   `null`
*   `shmem`
*   `uint64`
