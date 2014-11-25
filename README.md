demo_support_files
==================

Used to store files used by STs and the like for demos/tutorials

Notes about given files:

RsPsLib.tgz takes the standard file from v13.x and modifies it as follows:
Edit the file RS\RsApiCallWithRetry.ps1
Change line 38 from
[System.Net.ServicePointManager]::SecurityProtocol = [System.Net.SecurityProtocolType]::Ssl3;
to
[System.Net.ServicePointManager]::SecurityProtocol = [System.Net.SecurityProtocolType]::Tls;
