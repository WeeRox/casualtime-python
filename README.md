This is the Python version of [casualtime-android](https://github.com/WeeRox/casualtime-android/)

# Example program
```
import casualtime
from datetime import datetime, date, time
dt = datetime.combine(date(2018, 1, 1), time(8))
print(casualtime.get_casualtime(dt))
```
