# IDN Generator

## Summary
Small utility to generate similar IDN domain names.

The main purpose of this utility is to generate similar domain name for you organization and block those domain via Office365/Exchange/Google apps admin.

This can help prevent recent phishing attacks utilizing IDN domain names.

You can read more about IDN attacks here: https://www.phish.ai/2018/03/13/idn-homograph-attack-back-crypto/

## Example Usage
python is required

```bash
python3 main.py --help
python3 main.py phish .ai # This will print all the permutation of phish.ai, you can redirect the output to a file as well.
```

## Contribution
This is an open-source tool and any pull-requests are welcome adding features/bug-fixes and new dictionaries.
