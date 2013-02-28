openport2pid
============

map and list open port and their process id.

**NOTE: works only under OS X**

## Installation

```bash
curl -fsSL https://raw.github.com/eladg/openport2pid/master/openport2pid > /usr/local/bin/openport2pid
chmod +x /usr/local/bin/openport2pid
```

## Usage

type `openport2pid` from everywhere

## Examples

```bash
elad$ openport2pid 
Port   Command    PID    User    
----   -------    ---    ----    
17500  Dropbox    335    elad
26164  Dropbox    335    elad
53668  ubd        3443   elad

elad$ sudo openport2pid 
Password:
Port   Command    PID    User    
----   -------    ---    ----    
22     launchd    1      root    
80     httpd      3129   _www    
88     kdc        73     root    
445    launchd    1      root    
548    launchd    1      root    
631    launchd    1      root    
17500  Dropbox    335    elad
26164  Dropbox    335    elad
53668  ubd        3443   elad

```