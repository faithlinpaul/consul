# consul


token for "consul" in atlas.hashicorp.com
7dm59vtr84gyJQ.atlasv1.HWEKfN8ZvR8zWW1ibnn23PgoOmwfFCIikccLK4knytqYoIpZLIBazeyeVkYyXF6ykWo



#packer -> builds
#Setup Atlas authorization by exporting an API token
This will create a new token for your account. You can manage all tokens in your account settings. 
Run the following command to export it into your environment: 

export ATLAS_TOKEN="L0AUuGQxUm1RLg.atlasv1.y5W9QRphzpVkQkZ4CKPZ8Guy54Hfo0b1GiNUFGM6l2RP4yLgGVjty5VIcRyZA2cKA9c"

#Verify your configuration and authorization:
This sends a test request to Atlas to verify your token is configured correctly. 

curl "https://atlas.hashicorp.com/ui/tutorial/check?access_token=$ATLAS_TOKEN"

