# hail-the-utils - Htop
This is the most popular top utility. 

To check your host machine's process run the following,
```
docker run -it --rm --pid=host cgroups/utils:htop
```

To check the process list of a specific container run the following,
```
docker run -t --pid=container:30cb54597e38 cgroups/utils:htop
```
You can also alias it to day to day use,
```
alias htop="docker run -it --rm --pid=host cgroups/utils:htop"
```
Then just run htop
```
htop
```
