# PHP-learning
## Syntax
#### echo - it's like a print statment
```php
<?php
    echo 'Hello World!';
?>  
```

```output
Hello World!
```

### variables
variables can be declared by using $ followed by a variable name then asigning values to it

we can also use {} to format the echo statment to print variables in a string literal
```php
<?php
    $name = "K Naresh";
    echo "my name is {$name}"
?>  
```

```output
my name is K Naresh
```

### Data types

```php
<?php
    $name = "Naresh"; // string
    $age = 22; // integer
    $hobby = "coding";
    $duration = 3.5; // float

    echo "Hi, I'm {$name}.<br>";
    echo "I'm {$age} years old.<br>";
    echo "I love {$hobby}, daily i spend around {$duration} hr on {$hobby}."
?>  
```

```output
Hi, I'm Naresh.
I'm 22 years old.
I love coding, daily i spend around 3.5 hr on coding.
```
