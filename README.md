# This repository is for proof of existance

This is the "electronic" equivalent of the self addressed sealed envelop

it use a "reverse encrypt" to mount a cypher directory to be added to the
 [github/repository](http://github.com/michel47/filed.git)
 
The reverse option allow us to avoid data duplication for "remote-encryption"

```sh
# initialization:
bin/gocryptfs -config .secure/config.key -reverse -init cypher
# mounting:
bin/gocryptfs -config .secure/config.key -reverse .git cypher
```

