### How to use?
1. Clone this repo.
```shell
git clone https://github.com/GeekSquirrel/plexamp-headless-docker
cd plexamp-headless-docker
```
2. Build your image.
```shell
docker build -t plexamp:latest .
```
3. Modify compose.yaml. PLEXAMP_CLAIM_TOKEN is required and you can change other values following the comments.
4. Run with Docker Compose
```shell
docker compose up -d
```
5. Open it in http://[your-ip]:32500
6. If you get "Coulnd't start Playback" when you play a song. Try to tap "Disconnect" button in casting menu, refresh, and then reconnect. It works if the volume bar appears at the bottom of the casting menu.
<img width="375" alt="Screenshot 2024-01-25 012257" src="https://github.com/GeekSquirrel/plexamp-headless-docker/assets/127181546/36d0e4aa-a092-4235-9880-654e283e3c6c">
