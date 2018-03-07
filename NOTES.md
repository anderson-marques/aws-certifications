# aws-certifications notes

## s3

- Offers eventual consistency for puts and deletes
- Has support for BitTorrent protocol. The charges can be lower than conventional client/server requests.
- Storage Classes
    - Standard - 99,99% availability - 99,999999999999% durability
    - Standard IA - Infrequently Accessed
    - RRD - Reduced Redundancy Storage - 99,99% durability and 99,99 availability
    - Glacier - Cheaper - Backups that can be recovered in question of hour
- Transfer aceleration enables use of cloudFront to make uploads faster
- Successful uploads generates HTTP 200 code
