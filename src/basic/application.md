# Application

Creating a new application creates a root `Window` and a `Context`. Views declared within the closure passed to `Application::new()` are added to the context and rendered into the root window.
```rust
use vizia::prelude::*;

fn main() {
    Application::new(|cx|{

    })
    .run();    
}
```
Calling `run()` on the `Application` causes the program to enter the event loop and for the main window to display.

![](../img/application.png)


