# cpp-linked-queue

A C-style singly linked list implementation of a FIFO queue in C++. Built to understand low-level memory management, pointers, and data structure fundamentals.

## Features

- Manual memory management with proper allocation/deallocation
- FIFO (First In, First Out) queue operations
- Memory-leak tested with AddressSanitizer
- Clean separation between data structures and operations

## API

| Function | Description |
|----------|-------------|
| `newQueue()` | Create a new queue |
| `queuePushPlayerEntry()` | Enqueue an item |
| `queuePopPlayerEntry()` | Dequeue an item |
| `queueFront()` / `queueBack()` | Peek at ends |
| `queueSize()` | Get current size |
| `deleteQueue()` | Clean up memory |

## Building
```bash
cmake -B build
cmake --build build
./build/bin/all-tests
```

## License

MIT
