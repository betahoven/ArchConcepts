# Allocation
## Description
An **Allocation** is the decision of allocating one ore many logical functions to one logical component. This one component is then responsible for these functions.

Logical functions have to be implemented at some point in time. To be able to communicate with other software components it is necessary to have at least one interface.
As long as this component is no library, which can be integrated in the other software, this interface will often be realized with some sort of serialization.
It is practical to not have too many components ...