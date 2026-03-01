# Chapter 1. Introduction

We delve into the realm of software architecture to understand how the 
larger parts of systems fit together, along with numerous trade-offs.

Software Architects must understand and analyze systems deeply, in all their
complexity, and must make important trade-off decisions, sometimes with 
incomplete information.

Software architects make the kind of decisions that AI cannot, evaluating 
trade-offs within complex, changing contexts.

Architecture can only be understood in context. Architects base their decisions
on the realities of their environment. All architectures are product of their
context.

# Defining Software Architecture

Let's say that software architecture has four dimensions:
- Style
- Characteristics
- Logical Components
- Decisions

The software architecture of a system consists of an architectural style as
the starting point, combined with the architecture characteristics it must 
support, the logical components to implement its behaviour, and the 
architecture decisions justifying it all.

## Architecture Characteristics

Architecture Characteristics define the capabilities (-ilities) of a system.
In short, what the system should do. 
Architecture Characteristics:
- Availability
- Scalability
- Fault Tolerance
- Performance
- Reliability
- Security
- Elasticity
- Deployability
- Testability
- Agility
- Recoverability
- Learnability


## Logical Components
Logical Components define its behaviour. Designing logical components is one 
key task for an architect.


## Architectural Style
Once an architect has analyzed the architectural characteristics and logical 
components the system needs then they know enough to choose an appropriate  
architecture style as a starting point for implementing the system.


## Architecture Decisions
The fourth dimension that define software architecture is Architecture 
Decisions, which defines the rules for how a system should be constructed. 
Architecture Decisions forms the constraints of the system and direct the 
development teams on what is and what isn't allowed.


# Laws of Software Architecture

Things that seems universally true about software architecture, we call this
"laws" of software architecture.

## First Law: Everything in software architecture is a trade-off

Nothing exists on a nice, clean spectrum. Every decision a software architect
make must account for a large number of variables that take on different 
values depending on the circumstances. Trade-offs are the essense of software
archicture decisions.

If you think you've discovered something that isn't a trade-off, more like
you just haven't identified the trade-off, yet.

You can't just do trade-off analysis once and be done with it


## Second Law: Why is more important than How

If someone shows me a architecture I've never seen before, I can understand 
how it works but I might struggle with why the previous architect or team made
certain decisions. 

Architects make decisions within specific contexts, making difficult decisions.
Why an architect made a particular decision includes the trade-offs they 
considered.

## Third Law: Most architecture decisions aren't binary

Most architecture decisions aren't binary but rather exist on a spectrum 
between extremes.


# Expectations of an Architect

We've identified 8 core expectations:
- Make architecture decisions.
- Continually analyze the architecture.
- Keep current with latest trends.
- Ensure compliance with decisions.
- Understand diverse technologies, frameworks, platforms and environments.
- know the business domain.
- Lead a team and possess interpersonal skills.
- Understand and navigate through organizational politics. 


## Make Architecture Decisions

An architect is expected to define the architecture decisions and design 
principles used to guide technology decisions within the team, within the 
department, or across the company.

Guide is the key word here, architects should guide technology choices rather
than just specify them. He has to guide the development team to choose the 
right tool. 

But sometimes, the architect has to decide for the team to preserve a particular
characteristic (scalability, performance,..).

## Continually Analyze the Architecture

An architect is expected to continually analyze the architecture and the 
current technology context, and recommend ways of improvement.

Architecture vitality assesses how viable an architecture is after a few 
years, given changes in both the business domain and technology.

Architectures experiment structural decay, due to devolopers making changes
in code and design, and this impact the architectural characteristics. 

Other important aspect is testing and release, it't important to be able to 
modify code quickly. If it take weeks to test the changes and months to release
a new version, we cannot consider that the architecture has agility. 


## Keep Current with Latest Trends






