# Math.h functions
> Homework for 07.09.2022

 1. **double ldexp(double x, int exponent)** - множить число на 2 в заданому ступені. `double ldexp(0.65, 3)` = 0.65 * 2³ = 0.65 * 8 = **5.2**
 2. **double pow(double x, double y)** повертає **x** піднятий до ступеня **y** тобто xʸ.  Наприклад якщо `double x = 5` та `double y = 2` то `pow(double x, double y)` буде *25*  
 3. **double sqrt(double x)** Повертає квадратний корінь **x**.  **Наприклад** : `double sqrt(double 9)` = *3.0*
 4. **double ceil(double x)** - повертає найблище більше або те ж саме ціле число. Тобто `ceil(1.4) = 2.0`, `ceil(-12) = -12`
 5. **double floor(double x)** - те ж саме що й **ceil()** але найблище менше число.
