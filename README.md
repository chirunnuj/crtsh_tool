# crtsh_tool

### Installation
1. Clone the tool to local machine.
```
    $ git clone https://github.com/chirunnuj/crtsh_tool.git
```
2. Add execution permission to all files.
```
    $ cd crtsh_tool
    $ chmod +x crt*
```


### Usage
**crtcn:** Query certificate log by a domain name.
```
    $ crtcn "target.com"
``` 

**crtcn_big:** Query certificate log by a domain name, includes expired certificates.
```
    $ crtcn_big "target.com"
```

**crto:** Query certificate log by an organization name.
```
    $ crto "Target"
```

**crto_big:** Query certificate log by an organization name, includes expired certificates.
```
    $ crto_big "Target"
```