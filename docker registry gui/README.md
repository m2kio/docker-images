### create `htpasswd` file

> you will need `apache2-utils` package
>
> sudo apt install apache2-utils -y

```bash
htpasswd -Bc htpasswd username
```

### to add more users to the file, remove `-c` flag

```bash
htpasswd -B htpasswd username2
```
