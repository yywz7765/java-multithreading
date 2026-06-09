**Language:** English | [简体中文](README.md)

# Java Multithreading Notes

💫 A practical note repository to help you quickly learn Java multithreading and concurrent programming

Covers thread lifecycle, thread communication, locking, thread pools, JUC utilities, and core topics such as `BlockingQueue`, `Callable/FutureTask`, and `ForkJoin`.

Well suited for interview prep, knowledge review, and a fast start in Java concurrency.

This repository is a lightweight study-oriented knowledge base for Java concurrency and `java.util.concurrent`. The current structure is optimized for readability: the homepage is a navigation page, while foundational and topic-specific content lives in dedicated documents.

## Start here

- Chinese home: [README.md](README.md)
- Docs index: [docs/README.md](docs/README.md)
- Core overview: [docs/Multithreading Basics.md](docs/Multithreading%20Basics.md)

## Who this repository is for

- developers preparing for Java or backend interviews
- learners who want a clean overview of threads, locks, thread pools, and JUC
- anyone who wants a lightweight, easy-to-review concurrency note repository

## Topic map

| Topic | Summary | Document |
| --- | --- | --- |
| Multithreading basics | Lifecycle, communication, locks, `volatile`, `ThreadLocal`, thread pools, JUC tools | [docs/Multithreading Basics.md](docs/Multithreading%20Basics.md) |
| JUC overview | Process vs thread, states, `wait` vs `sleep`, concurrency vs parallelism | [docs/JUC.md](docs/JUC.md) |
| BlockingQueue | Concepts, categories, core APIs, and example usage | [docs/BlockingQueue.md](docs/BlockingQueue.md) |
| Callable and FutureTask | Return values, blocking result retrieval, example usage | [docs/Callable FutureTask.md](docs/Callable%20FutureTask.md) |
| ForkJoin | Divide-and-conquer model, key classes, recursive task example | [docs/ForkJoin.md](docs/ForkJoin.md) |
| Redis batch helper | Batch generation of Redis test data | [docs/batchRedis.md](docs/batchRedis.md) |

## Suggested reading order

1. Start with [docs/Multithreading Basics.md](docs/Multithreading%20Basics.md) for the big picture.
2. Continue with [docs/JUC.md](docs/JUC.md) for terminology and thread states.
3. Read [docs/BlockingQueue.md](docs/BlockingQueue.md), [docs/Callable FutureTask.md](docs/Callable%20FutureTask.md), and [docs/ForkJoin.md](docs/ForkJoin.md) by topic.
4. Use [docs/batchRedis.md](docs/batchRedis.md) only if you need the Redis test-data helper note.

## Quick interview cheatsheet

| Topic | Short memory aid |
| --- | --- |
| Lifecycle | New -> Runnable -> Running -> Blocked / Waiting -> Terminated |
| `synchronized` vs `Lock` | Start with `synchronized`; use `Lock` when you need more control |
| `wait()` vs `sleep()` | `wait()` releases the lock, `sleep()` does not |
| `volatile` | Visibility + ordering constraints |
| `ThreadLocal` | Per-thread variable storage |
| Thread pool | Reuse threads and control concurrency limits |
| `CountDownLatch` | One thread waits for many |
| `CyclicBarrier` | Many threads wait for each other |
| `Semaphore` | Limit concurrent access |

## Notes

- Chinese is still the main reading language for the detailed topic content
- English support focuses on navigation, overview, and quick comprehension
- This repository is intended to be clear and reviewable rather than exhaustive
