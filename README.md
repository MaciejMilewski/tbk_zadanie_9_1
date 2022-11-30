# Instrukcja
W folderze z plikiem docker-compose.yml i docker-compose-test.yml:
```sh
.\run.ps1
```
Po zatrzymaniu docker-compose można usunąć niepotrzebne kontenery, wolumin i folder pgdata poleceniem:
```sh
.\clean.ps1  
``` 
# Screenshot
#### Docker Desktop - po uruchomieniu widzimy stworzone numbers-api oraz numbers-web
![Wynik po odpaleniu run.ps1 w konsoli](images/docker_desktop_view.jpg)
#### Polecenia z .\run.ps1
![Screen run.ps1](images/polecenia.jpg)
#### Po odpaleniu .\run.ps1 (widok konsoli)
![Screen po wykonaniu run.ps1](images/run_cmd.jpg)
#### Po odpaleniu .\clean.ps1
![Wynik po odpaleniu clean.ps1 w konsoli](images/after_clean_cmd.jpg)