MinecraftRadio – Paper 1.21.11

Voraussetzungen
- Simple Voice Chat (Plugin) auf dem Server, die Mod bei den Spielern
- ffmpeg auf dem Server installiert (oder Pfad in config.yml: ffmpeg-path)
- Java 21

Bauen:   mvn package    ->  target/MinecraftRadio.jar  -> in /plugins
Befehle: /start radio [sender]   /stopradio   /addradio <streamurl> <name> (OP)
