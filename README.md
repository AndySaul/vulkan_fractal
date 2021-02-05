# vulkan_fractal

Proof-of-concept for using Vulkan compute APIs with Rust

Uses [image](https://crates.io/crates/image), [vulkano](https://crates.io/crates/vulkano) and [vulkano-shaders](https://crates.io/crates/vulkano-shaders) crates

* https://github.com/vulkano-rs
* https://vulkano.rs/

## Running the program
 
* Hardware must support Vulkan
* Vulkan components must be installed, along with some other tools
  * See https://github.com/vulkano-rs/vulkano#setup
* Cargo run --release
  * First compilation may take some time as dependencies are built
