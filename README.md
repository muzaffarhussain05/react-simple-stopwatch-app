# A Stopwatch Example of referencing a value with useRef

This example uses a combination of state and refs. Both startTime and now are state variables because they are used for rendering. But we also need to hold an interval ID so that we can stop the interval on button press. Since the interval ID is not used for rendering, it’s appropriat
