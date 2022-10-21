# 42_docker

Configuración docker entorno 42 Barcelona

Comprobar espacio usuario

	du -d0 -h ~/

Se necesita tener usuados menos de 3.5Gb

## Liberar espacio

	rm -Rf ~/.docker
	rm -Rf ~/Library/Containers/com.docker.docker
	rm -Rf ~/Library/Application\ Support/Docker\ Desktop
	rm -Rf ~/Library/Group\ Containers/group.com.docker
	rm -f ~/Library/HTTPStorages/com.docker.docker.binarycookies
	rm -Rf ~/Library/Logs/Docker\ Desktop
	rm -f ~/Library/Preferences/com.docker.docker.plist
	rm -Rf ~/Library/Saved\ Application\ State/com.electron.docker-frontend.savedState
	rm -f ~/Library/Preferences/com.electron.docker-frontend.plist

Desistalar Docker desde  **"Manager Software Centre"**

Salir sesión mac

Instalar Docker desde **"Manager Software Centre"**

Copiar la carpeta Data en sgoinfre/Perso/<User_42>/Docker/

/Users/<User_42>/Library/Containers/com.docker.docker/Data

	cp /Users/<User_42>/Library/Containers/com.docker.docker/Data sgoinfre/Perso/<User_42>/Docker/

Borrar /Users/<User_42>/Library/Containers/com.docker.docker/Data
	rm -rf /Users/<User_42>/Library/Containers/com.docker.docker/Data

Hacer ln
	ln -s sgoinfre/Perso/<User_42>/Docker/ Data

coprobar 

	ls -la

Iniciar Docker

Se ejecuta correctamente

asignar directorio para container de intercambio



## Iniciar Docker

**Nota**
	No tocar nada hasta que 
