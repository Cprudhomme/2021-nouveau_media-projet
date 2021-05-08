# Explanation of the Ceasar code

Cryptography is a technique for writing an encrypted message, thanks to secret codes or decryption keys. One of these techniques is the Caesar code, which makes the message incomprehensible.  The Caesar code consists of shifting the letters a certain number of places to the right or left in the alphabet . Guessing the number of places shifted is the most difficult.

For example, let's encrypt the message **"HARRY POTTER”** with a shift of **2 to the right**. 

Alphabet:                 ABCDEFGHIJKLMNOPQRSTUVWXYZ

Caesar's Alphabet (+2) :  CDEFGHIJKLMNOPQRSTUVWXYZAB

With a shift of **2 to the left**, H would become J, A would become C, and so on : My message **"HARRY POTTER"** is now **"JCTTA RQVVGT"**.

I can also encrypt my message without using the linear alphabet, but a disordered alphabet with a shift of **3 to the right this time**.
Let's take our "HARRY POTTER" message.

Disordered alphabet:                AZERTYUIOPQSDFGHJKLMWXCVBN

Caesar's Alphabet (+3) :            RTYUIOPQSDFGHJKLMWXCVBNAZE

With a shift of **3 to the right**, H would become L, A would become R, and so on. 
My message **"HARRY POTTER"** is now **"LRUUO DSIIYU"**.

Now let's make it a little more complicated with this sentence: **“I have seen your heart and it's mine.”**  from our dear friend Lord Voldemort.

Disordered alphabet:                 AZERTYUIOPQSDFGHJKLMWXCVBN

Caesar's Alphabet (+3) :             RTYUIOPQSDFGHJKLMWXCVBNAZE

With a shift of **3 to the right**, I would become Q, H would become L, A would become R and so on. 
My message **"I have seen your heart and it's mine"** is now **“Q LRAY GYYE OSPU LYRUI REH QI'G CQEY.”**.



