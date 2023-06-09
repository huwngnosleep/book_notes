with the enable of parallelism from hardware, the CPU can do multiple work at a time 

# Instruction level parallelism

**Pipelining**:
the execution of a program can be divide into multiple stages

![](2023-05-25-17-46-48.png)

pipelining is a technique, which can utilize CPU parallel ability. But it is a tradeoff between latency and bandwith

**Superscalar Architectures**

instead of using a single pipeline, we can use multiple pipelines

![](2023-05-25-17-53-32.png)

# Multiprocessor

Instead of a single core, we can use multiple processors at the same time, with a common memory shared among them, but this will result in conflicts and bus traffic. 

Computer designers solved this problem by assigning each processor a local memory, which can not be accessed by others. This can resolve the problem of traffic and conflicts

![](2023-05-29-18-00-45.png)
    
