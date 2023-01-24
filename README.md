# Description

A Python library by Dire Analytics for sending emails

## Installation

conda install lxml  
pip install git+https://github.com/edire/demail.git

## Usage

```python
from demail.gmail import SendEmail

SendEmail(to_email_addresses='', subject='', body='', user='', password='')
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

MIT License

## Updates

01/24/2023 - Updated modules to separate emails by commas into list.
12/31/2022 - Added SendGrid.