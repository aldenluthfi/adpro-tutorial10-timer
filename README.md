# Tutorial Pemrograman Lanjut
## Alden Luthfi - 2206028932

### 1.2. Understanding how it works.
The async program will execute the function in the background and will not block the main thread. The main thread will continue to execute the next code without waiting for the async function to finish. The async function will be executed in the background and will be executed in the order it was called. that is why "hey hey" appeared before "Howdy" and "Done"

### 1.3. Multiple Spawn and removing drop
not dropping the spawner