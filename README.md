# udbuisaasappflask

### Creating Secure Tokens
```
import binascii
import os
import click
@click.command()
@click.argument('bytes',default=128)
def cli(bytes):
  return click.echo(binascii.b2a_hex(os.urandom(bytes)))
```
### Viewing All Route Endpoints
```
docker-compose exec website snakeeyes routes
```


### Breaking down Lines of Code
```
docker-compose exec website snakeeyes loc
```
