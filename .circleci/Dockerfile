FROM mcr.microsoft.com/windows/servercore:ltsc2022

# To install Chocolatey; See https://docs.chocolatey.org/en-us/choco/setup
RUN Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

RUN choco install vscode
