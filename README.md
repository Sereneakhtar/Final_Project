Team members: Serene Akhtar

# Family Matters Prolog Project
This Prolog project implements kinship relations based on the son "I'm My Own Grandpa" by Queue Luu Breeze. The goal is to verify kinship claims and relationships described in the song using Prolog rules and facts. 

### Instructions
1. Prolog Code Usage:
  - Load the 'family_matters.pl' file in a Prolog interpreter
  - Use predicates to query kinship relations and verify claims
    ```prolog
       ?- runit.
    ```
    - This will check and prove the claims specificed in the song
2. Defined Kinship Relations:
  - 'father(X, Y)' : X is the father of Y.
  - 'mother(X, Y)' : X is the mother of Y.
  - 'son(X, Y)' : X is the son of Y.
  - 'daughter(X, Y)' : X is the daughter of Y.
  - 'spouse(X, Y)' : X is married to Y.
  - 'grandfather(X, Z)' : X is the grandfather of Z.
  - 'grandmother(X, Z)' : X is the grandmother of Z.
  - 'grandchild(X, Z)' : X is the grandchild of Z.
  - 'son_in_law(X, Y)' : X is the son-in-law of Y.
  - 'brother(X, Y)' : X is the brother of Y.
  - 'uncle(X, Y)' : X is the uncle of Y.
3. Querying Kinship Relations:
  - Use the 'queryKinshipRelation/1' predicate to check if a specific kinship relation holds true:
    ```prolog
       ?- queryKinshipRelation(father(james, chris)).
    ```
    - This will output whether James is the father of Chris
### Notes
1. The Prolog Code defines standard kinship relations based on the song's characters and relationships.
2. The 'runit' predicate verifies specific clains and relationships from the song.
3. Additional queries can be made using the 'queryKinshipRelation/1' predicate to explore other kinship relationships.
