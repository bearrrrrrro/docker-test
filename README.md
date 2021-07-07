```bash
docker build -t test
docker run -p 3000:80 -v $(pwd)/src:/var/www/html test
```

- -t 命名
- -p 指定 port
- -v 指定 volume

