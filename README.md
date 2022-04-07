# collection
collection of security tools as a docker-compose

- You manualy need to create a bucket in minio named thehive, inoder to save data and screenshot in TH

- Default credentials TH: admin@thehive.local passwd: secret

- Default credentials Minio: minioadmin passwd: minio

- Default password n8n: thehive passwd: thehive

- Cortex api key must configured in TH gui to connect Cortex

- Webhook needs be configured in TH gui inorder to use n8n

- Hostname in dockernetwork = containername, so if you want connect n8n to thehive using dockernetwork the address is http://thehive:9000

# this is by no-means production ready and intended for testing purposes
