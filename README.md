# Laptoprestore
- Step 1: (Open Windows Powershell)
- Step 2: Copy Paste: Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
- choco search (googlechrome, grep, curl)
-choco install (-y) googlechrome
-choco install vim
-choco install grep
-choco install visualstudiocode 
-All at once:
-- choco install -y grep visualstudio2019community googlechrome curl visualstudiocode origin 7zip git vim steam uplay docker-desktop
