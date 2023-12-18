# CircularBuffer
A simple circular buffer designed for object pool, aimed to reuse objects.

![CircularBuffer](doc/Circular_Buffer_Animation.gif) 

[wiki CircularBuffer](https://en.wikipedia.org/wiki/Circular_buffer)

## Targets

- [] CircularBuffer
- [] ObjectPool
- [] single producer single consumer mode: allocate in single thread, deallocate in single thread, no lock
- [] single producer multi consumer mode: allocate in single thread, deallocate in multi thread, with spinlock
