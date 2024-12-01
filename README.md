# python-note

**Making venv file and activate**

1. Search for "PowerShell" in the Start Menu.

2. Right-click on "Windows PowerShell" and select Run as Administrator.

```powershell
Set-ExecutionPolicy RemoteSigned
```

3. When prompted, type A (for "Yes to All") and press Enter.

```powershell
python<your_version> -m venv <venv_name>
```
4. Make venv and activate it.

```powershell
.\<venv_name>\Scripts\Activate
```


**List all installed packages**

```bash
py -m pip list
```


**Remove all installed packages**

```bash
py -m pip uninstall -r requirements.txt -y
```
