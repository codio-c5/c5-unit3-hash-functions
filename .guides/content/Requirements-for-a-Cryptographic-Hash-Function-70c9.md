- **Variable input/ Fixed output size:** Can be applied to data of practically any size but the output is always a fixed number of bits.
- **Pre-image resistant:** Computationally infeasible to find the input value for a given hash value (one-wayness).
- **Collision resistant:** Computationally infeasible to find two inputs that have the same hash value.
- **Efficiency:** Easy (fast) to compute so practical on hardware and software
- **Pseudorandomness:** The outputs pass tests designed to detect pseudorandomness.

|||guidance
# Notes
On collision resistance:
Because hash functions map long messages to short messages, there will be collisions; i.e., theoretically, there will be messages (sequences of bits) that will map to the same hash value, because the space of messages is larger than the space of hashes. The third property on the slide, collision resistance, means that finding two messages that have the same hash value is practically impossible.

On pseudorandomness:
Pseudorandomness means exhibiting characteristics of randomness (while not being actually random). There are tests to check sequences for randomness. The bits that are produced as a result of a hash should exhibit characteristics of randomness, hence passing such tests, but cryptographic hash functions are the result of a deterministic function, so we know that they are not truly random. 

|||