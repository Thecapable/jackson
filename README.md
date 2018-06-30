# J<sub>ack</sub>SON
<p align="center">
<img src="./jackson.png" height="300px"/>
</p>  

Have you ever used JSON as your config? Have you keep secrets in config as plain text, that you dont want to? Then this is the right tool for you.  
J<sub>ack</sub>SON is the simple and flexible file extension of JSON file types written in `python` (in less than 50 lines of code), this extenion allows the users to keep their secrets in environment variables and pass the reference to those environment variables into the JSON file(jackson). The secrets in the environment variables will be read securely in to the in memory dict.

The problem that it solves:  
* Retrive secrest from env variables.
* Retrive secrets from remote/servers(HSMs).


