# When the Solution of the Problem is — identifying the right Problem? 

It might seem counterintuitive, but often the key to solving a difficult problem is not finding the solution — it’s pinpointing the exact problem that needs to be addressed. Clearly articulating the problem statement is crucial; once the problem is well-defined, the solution becomes easier to conceptualize and implement.

## A Structured Approach to Identifying Problem Statements
A systematic method for defining problem statements can be highly beneficial. One approach is to classify them as either inward- or outward-looking.

### Inward-looking problem statements focus on addressing an existing pain point.
Example: Meta’s original motivation for developing Cassandra was to create a data system that enabled efficient searches across billions of user messages. Existing SQL databases couldn’t scale to meet this requirement.
### Outward-looking problem statements emerge when an idea lacks an immediate, obvious business application.
Example: Meta sought to combine the best attributes of two database systems — Google’s BigTable, which provided structured data access, and Amazon’s Dynamo, which offered high availability. The result was Cassandra, which incorporated both qualities.

## Approaches to Streamlining Problem Identification
### Think in Reverse
Instead of logically tackling a challenge, flip the perspective. If the goal is to improve user experience, ask: How could it be made so frustrating that no one would use it?

At first, using mobile phones for OTT streaming seemed counterintuitive in an era of large, high-definition TV screens. Yet, mobile viewing became popular among commuters who later continued watching on their home screens. This unexpected behavior led platforms like Netflix to introduce mobile-specific subscription plans.

Reverse thinking pushes creative boundaries, making it easier — and more fun — to highlight what to avoid.

### Question Everything
Generate assumptions about the issue, then challenge them. For example, if automating a test case is difficult due to compute or infrastructure constraints, could cloud technologies provide an alternative?

### Increase the Dimensionality of the Problem
The concept of Support Vector Machines in ML — where adding dimensions helps classify data more effectively — can be extended to problem-solving. SCAMPER is one such framework:

S = Substitute: What alternative component, system, or technique could replace the current one? (e.g., Choosing between AWS Lambda and its Microsoft or Google equivalents.)

C = Combine: How can functionality be merged for efficiency? (e.g., Failover and backup nodes improving server reliability.)

A = Adapt: Can an existing solution be repurposed? (e.g., Design patterns originating from previous problem-solving approaches.)

M = Magnify: What if a component’s output were increased? (e.g., Quora’s “vertical sharding” approach to improving MySQL write scalability.)

P = Put to Other Uses: Can a component serve multiple functions? (e.g., Redis acting as a cache, message broker, and database.)

E = Eliminate: Can the same outcome be achieved without a component? (e.g., Using Principal Component Analysis (PCA) to reduce ML dataset dimensionality.)

R = Rearrange: What changes occur if components are repositioned? (e.g., ELT (Extract, Load, Transform) vs. ETL (Extract, Transform, Load) in big data analytics.)

## Classic Problem-Solving Approaches
### The Ideal-Reality-Response Model
Often, the mapping from ideal business requirements to achievable technical design requirements might follow the below steps.

A. The Ideal: Define the desired goal or optimal state-> Business Requirements

B. The Reality: Identify obstacles preventing that goal from being achieved-> Technical Design Constraints

C. The Response: Propose solutions to bridge the gap and move toward the ideal state.

### The Five W’s Approach
Use who, what, when, where, and why to provide clear context, useful background, and valuable insights. This approach is particularly effective for risk mitigation planning and stakeholder communication.

### Surprise the Norm
Impose unconventional constraints to drive lateral thinking and creative problem-solving. Hackathons are an example of a structured approach to fostering innovation.

## Conclusion: Do You Still Have a Problem?
Defining the right problem is often more critical than finding the right solution. By using reverse thinking, structured frameworks like SCAMPER, and classic problem-solving techniques, teams/individuals can refine their approach and uncover innovative solutions. When in doubt, rethink the problem itself — because the solution often lies in how well the challenge is framed.
