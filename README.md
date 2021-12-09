

The purpose of the PR is to implement Poseidon hash function in the
Zei cryptographic library. Both numerical computation and turbo-plonk
circuit are included. There are tests to prove that the hash values
are consistent with these obtained within Neptune project.

The implementation is based on the simplified version of Neptune
library. Only the unoptimized version is used. The main value of the
project for the author was educational - to get an insight into the
Zei/Findora internals.

Links:

Poseidon papers:

https://www.poseidon-hash.info/


Neptune implementation of the Poseidon hash

https://github.com/filecoin-project/neptune


Future work:

1) implement Neptune circuit optimizations

2) implement all Poseidon cryptographic primitives (such as the cipher)

3) compare circuit size with the baseline Rescue circut 

4) create an implementation of the API and Findora protocol with
Poseidon. Measure performace.


