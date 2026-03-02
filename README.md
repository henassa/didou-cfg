# didou-cfg
here's my personal counter-strike 2 autoexec configuration

full cfg, if you have any questions don't hesitate to ask
```
bind "w" "+forward"
bind "a" "+left"
bind "s" "+back"
bind "d" "+right"

bind "space" "+jump"
bind "mwheelup" "+jump"
bind "mwheeldown" "+jump"
bind "c" "+jump"

bind "CTRL" "+duck"
bind "SHIFT" "+sprint"

bind "MOUSE1" "+attack"
bind "MOUSE2" "+attack2"
bind "r" "+reload"
bind "e" "+use"
bind "g" "drop"
bind "x" "+voicerecord"
bind "h" "switchhands"
bind "MOUSE3" "player_ping"
bind "MOUSE4" "toggleradarscale"
bind "MOUSE5" "+lookatweapon"

alias +qsw "slot3"
alias -qsw "lastinv"
bind "q" "+qsw"

alias "+dropbombbind" "slot3; slot5"
alias "-dropbombbind" "slot3; slot5; drop"
bind "alt" "+dropbombbind"

alias +netg "cl_showfps 2; +showscores"
alias -netg "cl_showfps 1; -showscores"
bind "tab" "+netg"

bind "kp_1" "buy secondary3; buy vesthelm; buy vest;"
bind "kp_2" "buy midtier2; buy vesthelm; buy vest;"
bind "kp_3" "buy rifle3; buy secondary3; buy vesthelm; buy vest; buy defuser;"

bind "t" "+spray_menu"
bind "z" "radio"
bind "y" "messagemode"
bind "u" "messagemode2"
bind "m" "teammenu"
bind "b" "buymenu"
bind "i" "show_loadout_toggle"
bind "ESCAPE" "cancelselect"
bind "," "toggleconsole"
bind "DEL" "disconnect"

bind "0" "slot10"
bind "1" "slot1"
bind "2" "slot2"
bind "3" "slot3"
bind "4" "slot4"
bind "5" "slot5"
bind "6" "slot6"
bind "7" "slot7"
bind "8" "slot8"
bind "9" "slot9"

bind "F1" "voice_modenable_toggle" 
bind "F3" "ᴘʟᴀʏɪɴɢ: Who asked (Feat: Nobody) ⚪ ◄◄⠀⏯⠀►►"
bind "F4" "say Choose your excuse: 1.Lags | 2.New mouse | 3.Low FPS | 4.Low team | 5.Hacker | 6.Lucker | 7.Smurf | 8.Hitbox | 9.Tickrate"
bind "=" "say ¯\\_(ツ)_/¯"

bind "mouse_x" "yaw"
bind "mouse_y" "pitch"
sensitivity 1.25
zoom_sensitivity_ratio 1.00

r_fullscreen_gamma 1 
fps_max 999
fps_max_ui 200
fps_max_tools 10
cl_showfps 1
hud_scaling 1
cl_autohelp 0

cl_hud_color 13
cl_color 3
hud_scaling "0.90"
cl_weapon_selection_rarity_color 0
cl_teamcounter_playercount_instead_of_avatars 1
cl_hud_radar_background_alpha 1
cl_hud_radar_scale 1.15
cl_radar_scale 0.30
cl_radar_scale_alternate 0.80
cl_radar_icon_scale_min 0

cl_sanitize_muted_players 1
cl_allow_animated_avatars 0
cl_player_ping_mute 1
cl_predict_body_shot_fx 0
cl_predict_head_shot_fx 0
cl_predict_kill_ragdolls 0
mm_session_search_qos_timeout 40
mm_dedicated_search_maxping 40
```
