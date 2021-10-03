# Laptop Tamper Evident Repository

## Description:

This repository contains documents containing evidence of states of tamper evident proofs.  
This is to allow myself to check at anytime whether my laptop has been physically tampered with or not by comparing the evidence of the most recent state of the laptop's tamper evident roofs and whether they arestill present on the laptop in their exact same state.  
While inspiration from this repository is welcome, the sole reason that this is public is to ensure the ability to verify the integrity of the tamper evident proofs at any time and any where as long as I have an internet connection and by a 3rd party if ever necessary.   

## Verification Measures:

In order to ensure the authenticity of the documents, this repository utilises PGP keys for signatures in a very specific way.  

1. The presence of a master key which is initially added to the repositry both signed and in a commit signed with the PGP key with ID `43F6D286F0F2266848D09BDC1EBE542FEC563CF3` (long key ID `1EBE542FEC563CF3`). Just prior to its bi-annual expiry, is updated with a new master key (both signed and in a commit signed with both the soon expiring master key and another temporary public PGP key belonging to me, exactly no more than 24 hours prior to its expiration.   
2. The master key is SOLELY used for the signing of commits for the initial creation of the `README.md` file and for the signing of commits adding the temporary PGP keys.   
3. The usage of temporary PGP keys which are used to sign and commit new instances of evidence of the tamper evident proof states. These keys have a maximum lifespan of 1 hour (a longer timespan is proof of 3rd party involvement) and must be both signed and committed by the current master key.    
4. All changes to the README.md must be signed with the current master key.   
   
If a violation in ANY SINGLE ONE of these protocols occur, this repository is no longer to be trusted nor any of the tamper evident proofs.   
