# mdm-tabshell-CreateGridSummarySyntaxFromAxis

GridSummaryBase with nets, reorder, hidden stubs, individual weights, etc...

Just wanted to suggest an alternative approach to creating grid summary tables with nets other than creating a DV, that has a bunch of problems - DVs do not have automatically new stubs added when new wave is in the data, they take space making the data bigger and processing longer, and do not have any reasonable meaning other than just being a copy with nets.
 
So, just wanted to suggest another function that creates grid summary from normal syntax with nets that we use from DA. This way all can be easily updated, reordered. We do not need to rerun data to update definitions.
 
The biggest benefit using such syntax is that it is super powerful, stubs can be grouped in nets or "combine" statements, pinned to the bottom, individual weights applied... Super flexibility, we do not need a separate function to exclude stubs or reorder. All controlled from same syntax as used for plain variables. And syntax can be normally controlled from DA (if it starts using this approach).
 
This is just experimental, to demonstrate what is possible. Just out of fun.
 
So, please see table code here, and necessary functions here
