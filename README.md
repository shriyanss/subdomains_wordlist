# subdomains_wordlist
Subdomains wordlist generted from subdomains of public bug bounty programs

## Download wordlists
- Everything filtered (less possibility of noise) (recommended)
```
curl https://raw.githubusercontent.com/shriyanss/subdomains_wordlist/main/filtered_subdomain_wordlist.txt -o filtered_subdomain_wordlist.txt
```

- Raw wordlist
```
curl https://raw.githubusercontent.com/shriyanss/subdomains_wordlist/main/wordlist.txt -o wordlist.txt
```
- Wordlist without subdomains that are only numbers (e.g. `1`, `10000`, and not `a100`)
```
curl https://raw.githubusercontent.com/shriyanss/subdomains_wordlist/main/no_number.txt -o no_number.txt
```
- Wordlist without UUIDs
```
curl https://raw.githubusercontent.com/shriyanss/subdomains_wordlist/main/no_uuid.txt -o no_uuid.txt
```

## About
The wordlist is generated with my tool [@shriyanss/subdomain_wordlist_gen](https://github.com/shriyanss/subdomain_wordlist_gen) (aka subgen) used over a list of subdomains gathered with [@projectdiscovery/subfinder](https://github.com/projectdiscovery/subfinder/blob/dev/LICENSE.md) run on domains from bug bounty programs obtained from [@arkadiyt/bounty-targets-data/data/domains.txt](https://github.com/arkadiyt/bounty-targets-data/blob/main/data/domains.txt)

## Contributing
If you have found any new pattern for noise in the wordlist, feel free to create a new issue.