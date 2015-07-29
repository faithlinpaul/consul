# consul


token for "consul" in atlas.hashicorp.com
7dm59vtr84gyJQ.atlasv1.HWEKfN8ZvR8zWW1ibnn23PgoOmwfFCIikccLK4knytqYoIpZLIBazeyeVkYyXF6ykWo


#https://atlas.hashicorp.com/tutorial/packer-vagrant/1


This is a tutorial for building Vagrant Boxes with Packer and Atlas
Use `packer push` to automatically build, upload, and release Vagrant boxes to your team or community with Packer and Atlas.
Do you have Packer 0.8.0 or greater installed?
You can check by running `packer version`.
Do you have a Packer template for building a Vagrant box to work with?
This is a JSON file and associated provisioning scripts.
Great. Some of the tutorial instructions may be a little different for you, but you can definitely follow along with your existing template.
If you're unsure you want to use your existing project, don't hesistate to follow the example and delete it afterwards.
You're ready to get started.


#Setup Atlas authorization by exporting an API token
This will create a new token for your account. You can manage all tokens in your account settings. 
Run the following command to export it into your environment: 

export ATLAS_TOKEN="L0AUuGQxUm1RLg.atlasv1.y5W9QRphzpVkQkZ4CKPZ8Guy54Hfo0b1GiNUFGM6l2RP4yLgGVjty5VIcRyZA2cKA9c"

#Verify your configuration and authorization:
This sends a test request to Atlas to verify your token is configured correctly. 

curl "https://atlas.hashicorp.com/ui/tutorial/check?access_token=$ATLAS_TOKEN"

