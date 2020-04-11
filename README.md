# SteamCMD-TF2
Team Fortress 2 Dedicated Server

The follwing docker image allows for running a Team Fortress 2 server

Container Runtime Environment Variables:

    APP_SERVER_PORT - Port for the game to run on (default 27015)
    APP_SERVER_MAXPLAYERS - Max number of players (default 24)
    APP_SERVER_MAP - Starting map (default ctf_2fort)
    APP_SERVER_TOKEN - Use access token from http://steamcommunity.com/dev/managegameservers
    APP_SERVER_NAME - Server name (default: Team Fortress 2 Dedicated Server)
    APP_SERVER_CONTACT - Server contact (e.g. user@example.com)
    APP_SERVER_REGION - Server region (default: -1 (world))
