# Getting Started with Locust

Using Locust Docs to Run Getting Started with Provided Documentation

#How to run

1. Clone this repository
2. Install Chocolatey via powershell (as administrator): [Chocolatey Software | Installing Chocolatey](https://chocolatey.org/install) 

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

3. Install Python in cmd (as administrator) using

```
choco install python
```

4. Install Locust in cmd (as administrator) using

```
pip3 install locust
```

5. Run locust on the locustfile.py location

6. Open locust's web interface and run the load test

Example value
Number of users: 1
Spawn Rate: 1
Host: Select your own webserver




