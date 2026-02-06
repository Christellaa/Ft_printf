# FT_PRINTF
42 School project aimed at re-implementing the standard C printf function. It handles variable arguments and supports formatted output with these specifiers: `%c, %s, %p, %d, %i, %u, %x, %X, %%`.

Following the [42 norm](https://github.com/42school/norminette)

## Skills developed
- Variadic functions
- Number, character and string formatting

## How to run
```make```

### Example usage
```C
#include "ft_printf.h"
int main(void)
{
	ft_printf("Hello %s! Number: %d\n", "world", 26);
} ```
