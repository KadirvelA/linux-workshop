Display the user and group ids of your current user.
```plain
id
```{{exec}}

Display the last users who have logged onto the system.
```plain
last
```{{exec}}
Show who is logged into the system.
```plain
who
```{{exec}}
Show who is logged in and what they are doing.
```plain
w
```{{exec}}
Create a group named "test".
```plain
groupadd test
```{{exec}}
Create an account named john, with a comment of "John Smith" and create the user's home 
directory.
```plain
useradd -c "John Smith" -m john
```{{exec}}
Display the user and group ids of user John.
```plain
id john
```{{exec}}
Add the john account to the sales group
```plain
usermod -aG sales john
Delete the john account.
```plain
userdel john
```{{exec}}

```{{exec}}

<br>
