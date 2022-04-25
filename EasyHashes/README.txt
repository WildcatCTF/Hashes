The different fields are seperated by ':'. Ignore these when passing to hashcat. This means you may have to make a
new text file with only the hash codes. Good luck and PM me the USER's passwords.

1st field: username (Administrator, User1, etc.)
2nd field: Relative Identification (RID): last 3-4 digits of the Security Identifier (SID),
which are unique to each user
3rd field: LM hash
4h field: NTLM hash

Hint: You should get used to checking out the man pages of every command and tool. The command won't be exactly the same as in class. 
Compare this read me to some of the switches.
