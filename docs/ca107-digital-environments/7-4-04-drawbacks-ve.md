# 7.4.4  

![Retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 7.3.2.  
If you have access to the textbooks, you can use those resources to enhance your understanding. 

# 7.4.4 Understand the drawbacks of the use of virtual environments

This section covers the drawbacks of virtual environments, including extra hardware load, slower execution time and the potential for false representation of performance.

---

## Extra hardware load

**Features / Characteristics / Role**

- multiple virtual machines share the same physical resources  
- host systems must manage additional abstraction layers  
- increased demand placed on CPU, memory, storage and network capacity  

**Benefits**

- supports consolidation of systems  
- enables flexible allocation of resources  

**Drawbacks**

- higher baseline resource consumption  
- increased risk of contention between virtual machines  
- requires more powerful host hardware  

---

## Slower execution time

**Features / Characteristics / Role**

- virtualisation introduces overhead between software and physical hardware  
- workloads compete for shared resources  
- performance depends on hypervisor efficiency and host capacity  

**Benefits**

- acceptable performance for many general-purpose workloads  
- allows prioritisation of critical virtual machines  

**Drawbacks**

- reduced speed compared to native execution  
- latency may increase under heavy load  
- unsuitable for some performance-critical applications  

---

## Potential for false representation of performance

**Features / Characteristics / Role**

- virtual test environments may not accurately reflect physical deployment conditions  
- shared resources can mask real-world bottlenecks  
- simulated environments can distort timing and throughput measurements  

**Benefits**

- provides indicative performance data  
- supports early-stage evaluation  

**Drawbacks**

- results may not translate to live systems  
- can lead to incorrect capacity planning  
- increases risk of deployment issues  

---

## Judgement

Suitability of virtual environments depends on:

i. performance sensitivity of workloads  
ii. available hardware resources  
iii. accuracy requirements for testing and benchmarking  
iv. organisational capability to manage virtual infrastructure  

While virtual environments provide flexibility and consolidation benefits, their drawbacks constrain use in performance-critical scenarios and require careful capacity planning and monitoring.

---

!!! tip "Exam tip"
    Avoid listing drawbacks without impact. Link each limitation to performance, resource usage or testing accuracy. Higher marks come from explaining how these constraints affect deployment decisions and suitability.
