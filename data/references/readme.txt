https://mothur.s3.us-east-2.amazonaws.com/wiki/silva.seed_v138_1.tgz

Downloaded SILVA SEED reference v138.1.

Unpack .tgz, remove readme.md, save all other files in references/. Done using wget and tar for easy reproduction.

Ignore directory as part of .gitignore: data/

To download, run from root directory:
wget -nc -P data/references https://mothur.s3.us-east-2.amazonaws.com/wiki/silva.seed_v138_1.tgz
tar xvzf data/references/silva.seed_v138_1.tgz -C data/references/silva_seed 
