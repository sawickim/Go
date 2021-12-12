Program tworzy dwa endpointy z których jeden dodaje plik do folderu
localhost:8080/upload

a drugi listuje nazwy plików wraz ze scieżką.
localhost:8080/list

Użyto komponentu live-server do odpalenia frontendu.
localhost:8080

Skomponowano dockerfile który odpala obraz dockerowy poleceniem: 
docker build projekt.go .
oraz kontener
docker run -d -p 80:80 docker/getting-started
