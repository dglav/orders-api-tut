## Redis

```bash
# Install Redis and Redis-CLI
$ brew install redis

# Start serever
$ brew services start redis

# Check status
$ brew services info redis

# Stop server
$ brew services stop redis
$
```

[Reference Documentation](https://redis.io/docs/latest/operate/oss_and_stack/install/install-redis/install-redis-on-mac-os/)

I will be using docker, so use the following command to start the Docker instance.

```bash
$ docker run -p 6379:6379 redis:latest
```

Then use the CLI installed via brew to check that it is connected and functioning normally.

```bash
$ redis-cli
```
