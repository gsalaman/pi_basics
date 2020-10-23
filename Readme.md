# Getting Started with the Raspberry Pi
For matrix operations, the Pi has to push a lot of data over the ribbon cable in a very timely manner.  Becasue of this, we want to be running as little on the Pi as possible...which means no fancy GUI.  Fortunately, we can configure the Pi to look like a stripped-down unix box...and we can connect over WiFi in what we call "headless" operation.

## SSH
To connect to the pi, we'll be using a program called `ssh` which stands for "Secure Shell".  You may have heard of programs called telent or rlogin or sh; this is a modern, secure version of those.

On Dawson's network, we can connect to the pi using it's name...for the purposes of this example, we'll assume that is `matrix-pi1`.  On this pi, we'll be using a default user with pre-setup permissions, called `pi`.

On a mac, we'll log in via a command window.  Open up spotlight search (command-spacebar), and type `command`.  That should bring up a window that looks like this:  
(image_coming_soon) 

We're first going to make sure that we can see the pi.  Type the following command: 
```
ping matrix-pi1
```
(if you have a different pi name, use it instead of `matrix-pi1`)

You should see responses, like this:
```
coming soon
```

Now it's time to actually log in.  We'll do so with this command:
```
ssh pi@matrix-pi1
```
This directs us to do a secure shell connection `to matrix-pi1` with the user `pi`

Next, it'll ask for the password...which you should already have from your instructor.

Ta da!  You are in!

## Directory Navigation
`.`, 
`..`, `~`  
cd

## File manipulation
cp 
mv  
wildcards  

## Editors
vi  
nano  


## Running python
