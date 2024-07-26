# Godot Signal System Lib

### What's This Mod?
This mod provides an implementation of a signal system, inspired by event-driven programming paradigms. It allows different parts of your mod or application to communicate in a decoupled manner.

### Features:
* Signal Handling: Manage and emit events using signals.
* Flexible Communication: Connect multiple listeners to respond to events.
* Decoupled Architecture: Improve modularity and reduce direct dependencies between components. 

### Example Usage:
```java
import core.signal.Signal;

public class ExampleUsage {
private static final Signal<String> MESSAGE_SIGNAL = new Signal<>();

    public static void main(String[] args) {
        // Connect a listener to handle String messages
        MESSAGE_SIGNAL.connect(message -> {
            System.out.println("Received message: " + message);
        });

        // Emit a message
        String message = "Hello, World!";
        MESSAGE_SIGNAL.emit(message);
    }
}
```
This mod is useful for enhancing communication and event handling within your mod.

### Mod examples
I don't know; I don't have any real examples, but could you give me one?

