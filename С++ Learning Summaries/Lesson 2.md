# If statement
> Ярослав Карасевич, 14 вересня 2022

### Before
**#define PI 3.1415** - кожен раз коли компілятор зустрічає змінну PI то міняє її на 3.1415, працює набагато швидше
**const** - змінна яку неможливо змінити в коді після створення, працює швидше ніж без, але повільніше ніж **#define**.
**#define** - директива препроцессора

## Оператори
**Оператор** - той, хто робить операцію
**Операнд** - той, над ким роблять операцію

**E.G**
`value = a + 5`
`a`, `5` - операнд
`+` - оператор

### Оператори

**Unary**
	*Arith*: +, -
	*Logic* : ! (not)
	*Short*: 	
	- Prefix : ++, --
	- Posix : ++, --
	*Binary*: ~ (not, inversion)
	*Memory*: & (ampersand) - оператор взяття адреса
	*Priotity*: ()

**Binary**
	*Assigh*: =
	*Arith*: +, -, *, /, %
	*Binary*: ^, &, |, <<, >> (потім)
	*Short*: +=, -=, *=, /=, %=
	*Logic*: && (and), || (or)
	*Comparation*: >, <, >=, <=, != (not equal), == (equal)

**Ternary**
*E.G.* : a > b ? 1 : -1 (if a > b then 1, else -1)

## If, Else
`C++` **if/else** structure
``` C++
if (cond)
{
	...
} 
else 
{
	...
}
```

`C++` **If/Else** example

``` C++
int value;

cout << "value > ";
cin >> value

if (value > 5)
{
	cout << "Value is greater than 5\n";
} 
else if (value == 5)
	cout << "Value is 5\n";
else
	cout << "Value is less than 5\n";
	
return 0
```
> Якщо тільки один рядок то можна і без { }
