# Info
This image seems useless if you don't want to connect Pterodactyl and Cloudnet. You can download the egg here [keksgauner/eggs/cloudnet](https://github.com/keksgauner/eggs/tree/master/minecraft/cloudnetv3)

Since there is no existing image that includes the Docker IP in config.json during startup, \
I created a Docker image specifically designed to insert that the Docker IP for Pterodactyl.

There are several options. Either the image I created is used or you create it yourself. Decide for yourself.
- [CloudNet](https://github.com/keksgauner/docker-stuff/tree/main/pterodactyl/images/cloudnet)
  - `keksgauner/cloudnet:latest`
  - `hub.docker.com/r/keksgauner/cloudnet`

# Links that may interest you:
- [CloudNet](https://github.com/CloudNetService/CloudNet-v3)
  - CloudNet Service - The CloudNet Network Environment Technology

# My Repositories
- [keksgauner/docker-stuff](https://github.com/keksgauner/docker-stuff)
  - There is the sorcecode if you want to build the image yourself or suggest improvements.
- [keksgauner/eggs](https://github.com/keksgauner/eggs)
  - There is the peterodactyl egg to which the whole thing refers. 
