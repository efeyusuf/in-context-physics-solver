# In Context Physics Solver
## Summary:

- All course materials from the famous "Introduction to Classical Mechanis" book from David Morin, which helped me a lot in my physics olympiads journey,  is stored in an embedding space.
- Problems & Solutions parts are also stored in a separate embedding space.
- In the test time, when a mechanics problem is assigned to the AI solver, there will be three settings:
    1) Zero-shot solving where only the problem itself is given to the AI and a solution is expected
    2) Few-shot solving where similar problems/solutions to the assigned problem at hand is found an given to the context of the problem to utilize in-context learning abilities of the models.
    3) The subject of the problem is searched through the embedding space and related subjects of the problem is fed to the model (no example problems, only the lecture material

As a result, the problem-solving abilities of these setting are compared.
One goal of this project is to understand the semantic search capabilities of language models' in the Physics domain.
Since we know all questions' and subjects' section numbers, we could have easily fed the content accordingly, with no need for the embedding search. But I am curious about language models' embedding space behavior for Physics.

