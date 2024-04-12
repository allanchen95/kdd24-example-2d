To illustrate, consider a simplified example with two sequences within an MSA, 

…  A … G …

…  T … C …


where we focus on the aggregation of information at a specific amino acid 'A'. With axis attention, information diffusion occurs in a stepwise manner from 'T' to 'A' and 'C' to 'G' (Column-wise Attention), followed by 'G' to 'A' (Row-wise Attention), aggregating insights from 'T', 'C', and 'G'. However, self-attention with 2D positional encoding streamlines this process, allowing 'A' to directly gather information from 'T', 'C', and 'G' in a single step, showcasing a more efficient means of capturing comprehensive co-evolutionary data. What’s more, the design of the 2D positional encoding mechanism guarantees the correctness of the information aggregations. 

This efficient information aggregation mechanism underpins our choice to reformulate MSAs into 1D sequences. By doing so, we leverage the advantages of high-performance computing technologies to further reduce computational costs and enhance the model's deployment feasibility for complex tasks such as protein sequence generation. The transition to a 1D generation process, supported by our 2D positional encoding strategy, represents a thoughtful evolution in our approach to modeling protein sequences, aiming to preserve and efficiently utilize crucial co-evolutionary information for accurate protein folding prediction. 
