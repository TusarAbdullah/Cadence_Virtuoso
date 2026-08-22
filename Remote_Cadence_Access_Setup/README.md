## Remote Cadence Access (via University PC)

Our university licenses Cadence directly, so instead of installing it 
locally, we remotely access a university-provided PC that already has 
Cadence set up.

### 1. Xlaunch Setup
Launch Xlaunch to start the X server locally (needed for X11 
forwarding, so the remote PC's GUI apps display on our screen).

### 2. PuTTY Configuration
- **Host Name**: university PC's IP/hostname
- **Connection → SSH → X11**: check **Enable X11 forwarding**
- Click **Open**

### 3. Login
- Enter **username**
- Enter **password**

### 4. Launch GUI file manager
```
nautilus
```

### 5. Launch Cadence
Open a new terminal window, then:
```
csh
virtuoso &
```
