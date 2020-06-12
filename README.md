# fizzbuzz
single statement fizzbuzz in C
```c
	for (int i = 0; ++i <= 100; printf("FizzBuzz\n\0Fizz\n\0Buzz\n\0%d\n" + (i % 15 ? (i % 3 ? (i % 5 ? 22 : 16) : 10) : 0), i));
```
to build:
```sh
make fizzbuzz
```

## License
public domain
