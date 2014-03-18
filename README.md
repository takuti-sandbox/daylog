## daylog

**daylog** is simple daily lifelog command using [DayOne](http://dayoneapp.com/).

1. Install **DayOne Command Line Interface** from [HERE](https://dayone.zendesk.com/hc/en-us/articles/200258954-Day-One-Tools).
2. Input your log like `./daylog "[11:00] drinking coffee"`. (daylog generates text file *day.log* automatically.)
3. Before you go to bed, export today's log to DayOne like `./daylog bye`. Then daylog exports today's log, and removes *day.log*.

If you add daylog's directory to the path like `export PATH=$PATH:$HOME/daylog`, you can use simple `daylog` command. ( ./ is not needed.)
