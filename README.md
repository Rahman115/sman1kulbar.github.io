# smansa-kulbar

go to link - <https://rahman115.github.io/smansa-kulbar/>

## Command Puch code

```git init

git add .

git commit -m "update"

git push

```

### DNS Management

- sman1kulbar.sch.id `__A__`

```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

- sman1kulbar.sch.id `__AAAA__`

```
2606:50c0:8000::153
2606:50c0:8001::153
2606:50c0:8002::153
2606:50c0:8003::153
```

- www `__CNAME__` input 🔸 `sman1kulbar.github.io`
- sman1kulbar.sch.id `__SPF(txt)__` input 🔸 `google-site-verification=QquoVGLdywL66xprcPBUFEbBlNkJsv97grERGUNmhVg`

open Git Bash
``
dig EXAMPLE.COM +noall +answer -t A
``
