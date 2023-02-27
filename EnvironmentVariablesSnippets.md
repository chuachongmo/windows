# Setting an Environment Variable Temporarily/Current Terminal Session


```
set YOUR_ENV=C:\ccm\ccm
echo %YOUR_ENV%
```

You should get back "C:\ccm\ccm"

This variable is lost once the terminal is closed.

# Setting an Environment Variable Permanently


# Setting a variable with the current path location

```
set "ccm=%cd%"
echo %ccm%
```
You should get back your current directory



