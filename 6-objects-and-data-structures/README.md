# Objects and Data Strutures

## Data Abstraction

Hiding implementation is about abstractions.

## Data/Object Anti-Symmetry

- Objects - hide their data behind abstractions and expose functions that operate on that data.
- Data structures - expose their data and have no meaningful functions.

## The Law of Demeter

The method should not invoke methods on objects that are returned by any of the allowed functions.

### Train Wrecks

Chains of calls generally should be avoided.

### Hybrids

Hybrid structures that are half object and half data structure should be avoided.

### Hiding Structure

## Data Transfer Objects

DTO - A class with public variables and no functions.

### Active Record

Active records are special forms of DTOs, they have public variables, but have navigational methods like save and find as well.