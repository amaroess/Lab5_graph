# Graph Data Structures Lab (C)

## Project Overview

This is a C programming lab focused on implementing a **Graph** data structure using an adjacency list representation backed by a hash map.

The project includes:
- `graph.c` / `graph.h` — Graph implementation (adjacency list using a Map)
- `list.c` / `list.h` — Linked list implementation
- `map.c` / `map.h` — Hash map implementation
- `test.c` — Unit and integration tests
- `test.sh` — Test runner script (includes git integration for submission)

## Running Tests

To compile and run all tests:

```bash
gcc -g test.c list.c map.c -Wall -o a.out && ./a.out
```

Or use the provided test script (includes git commit logging):

```bash
bash test.sh
```

## User Preferences

- Language: C (C11)
- Build tool: GCC
- No web frontend or backend — pure terminal/console C project
