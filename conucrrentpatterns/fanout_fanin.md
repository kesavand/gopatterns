This describes about the fanout/fan in  pattern.

Fan-Out
=======
Multiple functions can read from the same channel until that channel is closed; this is called fan-out.
This provides a way to distribute work amongst a group of workers to parallelize CPU use and I/O.

Fan-In
======
A single function that multiplexes multiple  input channels onto a single channel that's closed when all the inputs are closed.
