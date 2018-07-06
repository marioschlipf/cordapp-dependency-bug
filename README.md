Forked cordapp-example [https://github.com/corda/cordapp-example] to show a bug when including subprojects with
```compile project('...')```

The resulting jar will then include corda jars etc. that should not be there.