## VNC set up
1. Download VNC viewer and install it

2. Use Xshell to connect to the server, with IP as 10.236.176.23

3. Run 
 ```Shell 
    vncserver -geometry 2560x1440
 ```
to open a new prot of your own. (“2560x1440” is the resolution of your monitor, 'x' is the lowecase letter 'x')

4. Open VNC on you computer, enter IP and port number as 10.236.176.23:* (* is your port number)

5. To kill you port, run
```Shell 
    vncserver -kill *
 ```

6. Do not kill the port of other interns!