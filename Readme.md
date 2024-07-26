## Run

Modify your /etc/hosts
```
127.0.0.1       mock.connectid
127.0.0.1       mock.oidf
```


```
python -m http.server 8000
```

Open `http://mock.connectid:8000/connectid.html`