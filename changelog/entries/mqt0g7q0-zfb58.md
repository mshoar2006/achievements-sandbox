## prevent race condition in async handler

Introduced a mutex around the shared resource to prevent data races.
