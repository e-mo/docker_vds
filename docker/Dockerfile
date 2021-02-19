FROM emorse/steamcmd:latest

#create valheim user and install valheim dedicated server
RUN useradd -m valheim
USER valheim:valheim

RUN /usr/games/steamcmd +login anonymous +force_install_dir /home/valheim/ValheimServer +app_update 896660 +quit
