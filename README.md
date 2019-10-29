
InfoCraft
=========
Infocraft è un server *Minecraft Spigot v1.12.2* con il corredo di plugin per [AscensumCraft](https://youtu.be/p9g2e-BYjgI), SheetCraft, etc., con tutte le Sandboxes del caso, anche in NetherLand.

Server Update
-------------
Per aggiornare Il [Docker Minecraft](https://cloud.docker.com/u/artsakenos/repository/docker/artsakenos/minecraft), in particolare il tag infocraft, basta aggiornare mondi, plugin, scripts ed eventualmente anche il server di [questo repository](https://github.com/artsakenos/InfoCraft) e pushare.

Una Build viene lanciata automaticamente, vedi [InfoCraft_build.docker](https://github.com/artsakenos/InfoCraft/blob/master/InfoCraft_build.docker).

Server Run
----------
Si può lanciare il container con

	docker run -it -p 25565:25565 artsakenos/minecraft:infocraft

Vedi [InfoCraft_run.docker](https://github.com/artsakenos/InfoCraft/blob/master/InfoCraft_run.docker).
