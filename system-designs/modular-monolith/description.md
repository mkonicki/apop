# Modular monolith
One service with a module separation within the same service proper services are separated as a different modules

![image](./modular%20monolith.drawio.png)
# Decision factors
- Team size < 10 people
- Similar technology competences in the team
- Average engineer professional experience lower than 5 years 
- Estimated number of actions per day < 1 milion

## Pros & Cons
### Pros
- Low infrastructure costs 
- Only to maintain one service
- Easily to make a cutoffs within boundaries without an impact on bigger scope of the project 
- Boundaries can be easily separated in application

### Cons
- Codebase grows logarithmically 
- Strongly tightened references 

## Example usages
For a new systems which are not highly used and needs to be adjusted to business needs with every sprint.

![image](./Example%20usage.png) 

## Books to read about it
1. [Fundamentals of Software Architecture: An Engineering Approach](https://www.amazon.com/Fundamentals-Software-Architecture-Comprehensive-Characteristics/dp/1492043451)
2. [Software Architecture: The Hard Parts: Modern Trade-Off Analyses for Distributed Architectures](https://www.amazon.com/Software-Architecture-Trade-Off-Distributed-Architectures/dp/1492086894)
