
# Experiments with Use Cases

In order to determine a minimal useful schema, real world use cases were expressed in various candidate formats

# How to do things


## How to generate a signature for a claim

Use https://json-ld.org/playground/ and click on Signed with..

If you do Signed with Bitcoin you need a bitcoin private key

TODO: how do you get a bitcoin private key - add here

preferred to use elliptic curve private keys .. 25519

see https://w3c.github.io/json-ld-bp/

Some source vocabularies:

```
curl -H "Accept: application/ld+json" https://www.w3.org/ns/activitystreams
 > activitystreams.jsonld
```

https://schema.org/version/latest/schemaorg-current-https.jsonld


## Prior work

https://github.com/worknation/work.nation#architecture
