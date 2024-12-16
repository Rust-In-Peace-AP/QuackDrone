# QuackDrone #
  
  You should import it in the Cargo.toml as follow:  

  ```toml
  [dependencies]
  ap2024_unitn_rustinpeace_quackdrone = { git = "https://github.com/Rust-In-Peace-AP/QuackDrone.git" }
  ```

  Then in the code like this:

  ```rust
  use ap2024_unitn_rustinpeace_quackdrone;
  ...
  
  fn main(){
  
    let drone = ap2024_unitn_rustinpeace_quackdrone::QuackDrone::new(...);
  
  }
  
  `
