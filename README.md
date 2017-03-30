# Node-event-loop-timers

This is a quick demo showing how the event loop handles timers, setImmediate and nextTick events.

Notice that the events outside of readFile are non-deterministic, except that nextTick will happen first.

Events in the readFile are deterministic.
