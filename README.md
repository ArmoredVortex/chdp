# CHDP
Command Handler for Discord.Py

This project is under AGPL-3.0 License


## Download
```shell
$ pip install chdp
```

## Use
1. Create Main file and config.json and folder **commands**

2. Fill config.json like below
```json
{
    "token": "Your Token",
    "prefix": "Your Prefix"
}
```

3. create a file in folder **commands** and fill it like below
```python
class Commnad:
    name = 'ping'
    async def run(self, client, message, ext): await message.channel.send('pong')
```

4. Run the Main file

## Contribute
Find a bug and tell it on the Issue tab

You can also Open a Pull Request
