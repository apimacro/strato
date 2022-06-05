# strato
botreck scenario for strato.de to login make a screnshoot, get a list of domains, invoices
## strato.de

scenarios for botreck: got strato.de , login,get history, get domains, ..

### Add to file: apifork.txt

https://github.com/botreck/strato strato

```bash
echo "https://github.com/botreck/strato strato" >> apifork.txt
```

and install in project

```bash
./apifork install
```

start using

```bash
./apidsl 'puppeteer.csv("strato.de/login_user_screenshot.csv")'
```