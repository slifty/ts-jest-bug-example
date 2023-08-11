# How to reproduce

```
$> npm i
$> npx jest --runInBand --coverage
...
$> echo $?
```

You'll see that the status code returned is `0` but it should be `1`.
