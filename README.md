RSA-Two-different-keys-Same-Ciphertext
======================================

RSA Two different keys Same Ciphertext

The project consists of two parts
 Your task is to identify the smallest value d to decrypt all ciphertext that were generated using e1 and e2. Use the modulus and the two public exponents to obtain this value.
 Afterwards, use this special value d to decrypt two ciphertext. You were able to catch these two different ciphertext, which result in different plaintexts, from other course members. One if them is encrypted with the public key e1, the other one is encrypted with the public key e2.
Example
Modulus = 6A163
Plaintext: OK
The ciphertext encrypted with e1=1E437 is 57A27.
The ciphertext encrypted with e2=35A47 is 57A27.
In one of your courses you got the task to send RSA encrypted messages to your course participants. Every participant has his own key pair. All public keys are known by every course member. You want to send the same message encrypted with the different public exponents to every participant.
You encrypt the message using every single public key. Wait, you already know this ciphertext. Actually, two colleagues have chosen the same modulus by accident. However, their public keys are different. Nevertheless the message encrypted with the different keys leads to the same ciphertexts.
