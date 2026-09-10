The `time()` function of the `time` module in Python returns the current time in seconds since the epoch (January 1, 1970, 00:00:00 UTC) expressed as a float. This can be used directly or manipulated into a more human-readable format.

Try running the code cell below a few times to see how it changes with each execution.

```py-cell
import time

current_time = time.time()
print(current_time)
```