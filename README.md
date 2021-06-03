# Bmon
This is a bandwidth monitoring utility. 

To check your host machine's process run the following,
```
docker run -it --net=host cgroups/utils:bmon
```

To check the process list of a specific container run the following,
```
docker run -it --net=container:30cb  cgroups/utils:bmon
```
You can also alias it to day to day use,
```
alias htop="docker run -it --net=host cgroups/utils:bmon"
```
Then just run bmon
```
bmon
```
