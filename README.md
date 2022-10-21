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
