# Design-of-Hamming-Code-Decoder

The calling hierarchy of the three VIs is as follows:
- `LAB6_template.vi` calls `LAB6_sub.vi`, which further calls `decimal_to_binary.vi`. 
- This includes a Hamming code encoder (source code encrypted and base deciphered). Students need to accurately enter their personal student number on the front panel for it to work correctly.

The original information is a sequence of 10 ASCII characters, with each character corresponding to 8 bits. Using (7,4) Hamming code:
- Encode every 4 bits of the original information into a 7-bit codeword, then simulate the random generation of error bits.
- Generate a total of 140-bit binary codeword sequence.
- Each codeword has at most 1 bit error; the entire sequence has a limited number of 3 to 5 error bits.
