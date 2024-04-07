# KILL TABS (& extensions) (on all browsers)

<img src="./ext-abuse.png">

as both a double tab _and extension_ abuser, [the original kill-tabs](https://www.github.com/sindreorhus/kill-tabs) was almost perfect :)

This fork simply removes one logical and operator on line 3 in this bit of code » the result = kills extension processes as well :smirk:

```javascript
.some(name =>
  x.cmd.includes(processes[name])) &&
  x.cmd.includes('--type=renderer') ||
  x.cmd.includes('--extension-process')
)
```

# todo

- safari
- firefox
- brave, edge (shld be the same)
