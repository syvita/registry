# Syvirean Registry

The Syvirean Registry is a decentralised package registry for Node.js packages & Rust crates.

SR is entirely decentralised. 

It uses BNS for resolving packages and Hypr for secure transport. 

By default, the CLI tools will connect to the hypr.resolve service on `localhost:15`. 
If your resolution service is running on another port, you need to specify this by running `sr --set-resolver-port {portnumber}` where `{portnumber}` is the port the resolver is running on. 
