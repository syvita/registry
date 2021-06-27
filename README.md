# Syvirean Registry

The Syvirean Registry is a decentralised package registry for Node.js packages & Rust crates.

SR is entirely decentralised. 

It uses BNS for resolving packages and Hypr for secure transport. 

The CLI tools will connect to the hypr.resolve service by reading the global file defining what UDP port the hypr.resolve is running on locally. 

This file can _only_ be changed by the administrator and hypr.resolve, and shouldn't be changed manually by anyone or anything other than hypr.resolve. 
