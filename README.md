# set_execution_policy_windows

- <img width="1245" alt="image" src="https://github.com/gokul-1998/set_execution_policy_windows/assets/82328858/5ba26ad4-3eb6-4b93-942f-9bbf36a46334">
- in windows we often encounter the above issue , when we try to create and activate our virtual environment, the solution for this is, very simple

    - open windows powershell in administrator mode, and paste the following command `Set-ExecutionPolicy Unrestricted -Force`
    - then close the vscode and open it and try activating the venv, it will work
