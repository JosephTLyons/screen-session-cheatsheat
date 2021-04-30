# screen-session-cheatsheat

## Create an unnamed screen session

`screen`

## Create a named screen session

`screen -S <session name>`

## Kill a specific screen session

`screen -XS <screen session id> quit`

## Kill all screen sessions

`killall screen`

## Detach from a screen session

`control` + `a`, release keys, then `d`

## List all active screen sessions

`screen -ls`

## Attach to a screen session

`screen -R <screen session id>`

## Kill the current screen session

`control` + `a`, release keys, then `k`
