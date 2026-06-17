First read the report and the encrypted text file.

And then we use dCode to identify the encryption used, First layer : Base64.

We then decode it using dCode or CyberChef with Base64 and now we have a new layer of encryption.

We then use dCode again to identify the next encryption used, Second layer : ROT47.

And then we can use either dCode or CyberChef with ROT47 and now we have another new layer of encryption.

This time we can identify it ourselves since it is in Hex values.

However, when we use the From Hex filter on it, it is unreadable due to some of the characters needed to be subbed.

Key character substitutions needed:

1. q → d  
2. r → e  
3. s → f  
4. o → b  
5. p → c


After using Find/Replace to do the character substitutions, we get this full text :

Dear Dr. Andersson,

As you may know, I have your daughter. In the next 24 hours, she will be killed in the most gruesome way imaginable. I know what you did to me and my family in Iraq, and so do you. The funny thing is, even though you're staring at this exact text, which tells you exactly where your daughter is, through all the layers of encoding, you will never find her in time.

After all you did to me, I take so much enjoyment from knowing how you're staring at this message, knowing that the answer lies within, yet completely powerless to find it. So as promised, here is your daughter: inched.barman.fast. Good luck finding us in time. She's with me now, crying for someone to find her, which you will, in pieces. Pieces created out of her flesh while she was still alive. That's what you get for the horrors you put me and my family through.

Fuck you, Dr. Andersson.

inched.barman.fast
