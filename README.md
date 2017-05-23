# benchmark
This ia a stripped-down version of a campus course scheduling system, which contains a set of threads that rely on a shared 
collection of data, sometimes read-only and sometimes writing data. A benchmark exercise in performance measurement between 
two concurrent data structures was performed on the system. One utilizes `ConcurrentHashMap` and `Reentrant Lock` (both are JDK Components), 
while the other utilizes regular `HashMap` (JDK Component) and a `WriterPreferenceReadWriteLock` (cutomized). </br>
More detailed please see: http://gee.cs.oswego.edu/dl/csc375/a2.html 
# Execution
To run MyBenchmark.java and see outputs for each data structure, refer to 
http://openjdk.java.net/projects/code-tools/jmh/ for commands. 

# Outputs
Manually Collected Outputs in one file: http://cs.oswego.edu/~yxia/coursework/csc375/data.txt </br>
Graph Plotted using the data: http://cs.oswego.edu/~yxia/coursework/csc375/ </br>

# Useful References/Tutorials 
- http://openjdk.java.net/projects/code-tools/jmh/
- http://tutorials.jenkov.com/java-performance/jmh.html


