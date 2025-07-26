<h3>Why do we need thread pool?</h3>
<p>In Java, threads are mapped to system-level threads, which are the operating system’s resources. In simple view we can say the more threads we spawn, the less time each thread spends doing actual work.
The Thread Pool pattern helps to save resources in a multithreaded application and to contain the parallelism in certain predefined limits.</p>

<h3>What thread pool pattern does?</h3>
<p>When we use a thread pool, we write our concurrent code in the form of parallel tasks and submit them for execution to an instance of a thread pool. This instance controls several re-used threads for executing these tasks.
  The pattern allows us to control the number of threads the application creates and their life cycle. We’re also able to schedule tasks’ execution and keep incoming tasks in a queue.</p>
