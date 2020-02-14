# ro-crate2ocfl
Node.js script to convert a single RO-Crate data package to an OCFL repository with multiple RO-Crates - useful for turning repository archives back into repositories.

WARNING: Incomplete

At this stage you give it a path to an ro-crate metadata.json file and it writes out a temp dir with crates - hardwired ATM to look for File.

TODO: Config for how to traverse the tree and extract things we want