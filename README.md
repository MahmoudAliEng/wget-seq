# wget-seq
Script for downloading multiple files from bash using a specific pattern

Save the script where you want to downlaod the files as **seq_wget**, give it execution permission (```chmod +x seq_wget```), and then run, for example:

```$ ./seq_wget https://datacases.s3.us-east-2.amazonaws.com/datathon-2020/Netinfo/Full+Dataset/vest00000000%02d 0 25```
this will download 26 files where each files differ just in the two last caracters where it puts the seqeseential number in two caracters.
