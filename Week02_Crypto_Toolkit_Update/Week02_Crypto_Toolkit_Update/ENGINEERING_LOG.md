# Engineering Log
Elaine Nguyen - 9/2/2026
## Week 2 - Toolkit v0.1

Add a Week 2 entry to `ENGINEERING_LOG.md`:

1. Which modules did you add? 
Messed around with each code block sections, such as gcd and the seed for sercet vs random.
2. Which mathematical function was most difficult to understand? 
The one mathematical function I got stuck on was Part 5: Entropy.
3. What is one way randomness can fail in a cryptographic system? 
One way randomness can fail is through a predictable seed. If an attacker knows or can guess the seed, they may be able to predict the pattern and figure out future random values.
4. What is one rule you will follow when generating random values in future projects? 
one rule I will follow is to use Python's secrets module instead of using just random module when generating random values for cryptographic purposes.

## Final Reflection

**Why does cryptography need both mathematical structure and unpredictability?**
**Your answer:** 
Cryptography needs to have both mathematical structure and unpredictability because both are important for keeping information secured. Modular arithmetic allows cryptographic systems to perform calculations within a specific set of numbers, while modular inverses can help reverse certain operations when decrypting a message or information. At the same time entropy does provide unpredictability, which is very important when generating secure keys and other random values. If the random values are predictable, an attacker may be able to figure out the key even if the mathematical system is strong.