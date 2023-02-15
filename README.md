# bbDomains.txt

The dictionary is generated using OpenAI ChatGPT and is intended to search for subdomains. 

The main task of this dictionary will be to search for development environments and utilities that are used on the projects (devops, qa, dev, pm)

Integration:
```
> git clone https://github.com/trickest/mksub
> cd mksub && go build .
> cp mksub /usr/local/bin
> mksub -d tesla.com -w bbDomains.txt -l 2 -o subs
```
