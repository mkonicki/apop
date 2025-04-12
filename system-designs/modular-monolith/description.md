# Modular monolith


## Pros & Cons
### Pros
- Strongly tightened 

### Cons
- Higher cost of scaling
- 

## Example usages

Whenever you are not a source owner of the systems, or the code based is quite a large one it's easier to build a smaller pipes which will connect systems into a one huge infrastructure.

![image](./Example%20usage.png) 

Each plugin allows to connect only a specific parts of the system without interfering into a specific softwares.

![image](azure%20implementation.png)

Above an example design how to integrate WebShops & Accounting system to process invoices on a regular basis once per month.
As far as the calls can be done in a batches once per day, week, month Azure Functions can bring up a low cost hosting environment.

## Books to read about it
1. [Fundamentals of Software Architecture: An Engineering Approach](https://www.amazon.com/Fundamentals-Software-Architecture-Comprehensive-Characteristics/dp/1492043451)
2. [Software Architecture: The Hard Parts: Modern Trade-Off Analyses for Distributed Architectures](https://www.amazon.com/Software-Architecture-Trade-Off-Distributed-Architectures/dp/1492086894)






