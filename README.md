# Website Blocker in Python

Python program to block disruptive websites during the day

This program blocks websites during certain working hours.
It can be used to increase productivity and reduce distractions.

Algorithm:

1. Windows, MAC, and Linux and a file named `hosts` in the following locations:

```
Windows: C:/Windows/System32/drivers/etc/hosts
MAC and Linux: /etc/hosts
```

2. Add the following lines of text to this file:

```
127.0.0.1 website_domain_name
```

This specifies that the specified website domain name gets redirected to the 127.0.0.1 IP address.

3. Using file-handling methods, you can open this file and write this line to the `hosts` file.

4. The program runs in an infinite loop and checks the time every five seconds.

- If the time is between 8 am and 4 pm, it writes the above line to the `hosts` file, else, it deletes the line from the `hosts` file.


