# workflow

$ --> global scope (access global data)

. --> fetch data from perticular block of code.

list[0] --> access data from specific group of elements from list 
//for ex. if we want first object from list so we use list[0].

workflow input - 

when output of parent workflow is given to subworkflow as a input then it works as workflow input and we use that data in further nodes.

ex. ${workflow.input.shipment_id}
