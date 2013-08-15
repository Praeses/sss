sss
===

secure shared shell by the seashore

Overview
===
Share you shell connection with multiple users.  

## Current method

### Host
```Bashscript
add remote user account
allow access via ssh
start shared tmux session
```

### Client
```Bashscript
ssh user@remote.host
tmux join session
do work
```

## sss way

### Host
```Bashscript
sss start # => magic pin given
do work
```

### Client
```Bashscript
sss [magic pin]
do work
```

