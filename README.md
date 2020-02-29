This program will call the hcship.DestroyLayer system call on the specified folder

This will effectively reclaim a lot of hard-drive space for an undocumented reason.

# Usage (in admin PS console)

1) Stop docker

```powershell
    net stop docker
```
2) run file:

```powershell
    cd "C:\ProgramData\docker"
    .\docker-ci-zap.exe -folder "."
```

3) restart docker

```powershell
    net start docker
```
