### Webredirection

Open redirect (also known as unvalidated redirects and forwards) is a URL redirection vulnerability. An attacker can exploit it to redirect users from a trusted to a potentially malicious third-party website and steal their credentials via a phishing attack. 
- webredirection collects and executes all payloads from BB reports for Open Redirect. 

### Installation:
* A step by step guide that will tell you how to get the development environment up and running: 

```
$ git clone https://github.com/whoami-anoint/webredirection
$ cd webredirection
```

### Usuage 
* make-payloads.sh - replace www.whitelisteddomain.tld with a specific whitelisted domain in your test case.
```
./make-payloads.sh www.whitelisteddomain.pw

./make-payloads.sh www.google.com

./make-payloads.sh app.domain.com
```

```Happy Hacking!!❤️```
