|           Name           |  type | Default | Min | Max |     Flags     |                       Description                       |
|:------------------------:|:-----:|:-------:|:---:|:---:|:-------------:|:-------------------------------------------------------:|
| sv_resupply_cabinet      | bool  | 1       | 0   | 1   | FCVAR_NOTIFY  | allows the resupply cabinet to be disabled without mods |
| tf_ragdoll_cosmetics     | bool  | 1       | 0   | 0   | FCVAR_ARCHIVE | hides cosmetices on ragdolls                            |
| cl_player_joined_game    | bool  | 1       | 0   | 1   | FCVAR_ARCHIVE | hides player has joined the game message                |
| cl_player_left_game      | bool  | 1       | 0   | 1   | FCVAR_ARCHIVE | hides player has left the game message                  |
| cl_player_joined_team    | bool  | 1       | 0   | 1   | FCVAR_ARCHIVE | hides player has joined a team message                  |
| cl_player_changed_name   | bool  | 1       | 0   | 1   | FCVAR_ARCHIVE | hides player has changed name message                   |
| tf_unzoom_on_backstab    | bool  | 1       | 0   | 1   | FCVAR_ARCHIVE | unzooms when shield breaks                              |
| sv_suicide               | bool  | 1       | 0   | 1   | FCVAR_NOTIFY  | Allows a player to use kill or explode                  |
| cl_server_cvar_changed   | bool  | 1       | 0   | 1   | FCVAR_ARCHIVE | hides server convar has changed message                 |
| cl_achievement_earned    | bool  | 1       | 0   | 1   | FCVAR_ARCHIVE | hides achievement earned message                        |
| cl_achievement_particles | bool  | 1       | 0   | 1   | FCVAR_ARCHIVE | hides achievement particles                             |
| cl_item_found            | bool  | 1       | 0   | 1   | FCVAR_ARCHIVE | hides item found messages                               |
| sv_wrangler_disable_time | bool  | 1       | 0   | 1   | FCVAR_NOTIFY  | How long to disable wrangler after it's been used       |
| sv_sentrygun_shells      | int   | 40      |     |     | FCVAR_CHEAT   | Number of sentry gun shells to add on hit               |
| sv_sentrygun_rockets     | int   | 8       |     |     | FCVAR_CHEAT   | Number of sentry gun rockets to add on hit              |
| sv_sentrygun_think_delay | float | 0.05    |     |     | FCVAR_NOTIFY  | How long to wait between the sentry gun thinking        |
| sv_sentrygun_upgraded    | bool  | 1       | 0   | 1   | FCVAR_NOTIFY  | If 1, upgraded sentry guns are available                |
| sv_sapper_health         | int   | 100     |     |     | FCVAR_NOTIFY  | the health for the sapper                               |