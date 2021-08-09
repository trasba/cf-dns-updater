# cf-dns-updater

cf-dns-updater is a Python project to update cloudflare dns records  
the entries are updated based on the current ipv4/ipv6 address of the machine the code runs on

## Prerequisites

see requitements.txt

## Usage

* adjust config.json  
  token can be obtained from cloudflare website

```json
{
    "token":"123abc..."
}
```  
* python cf-dns-upd.py <example.domain.com>

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)