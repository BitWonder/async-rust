# async-rust
trying Tokio in rust


--

The entirety of this project was to figure out why I couldn't get an async main to run
Reason: tokio = { version = "1.29.1", features = ["full"] } <- needs to be in dependencies
if not including full features then async main wouldn't work