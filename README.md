# screen-session-cheatsheat

## Create an unnamed screen session

`screen`

## Create a named screen session or attach to an existing named screen session

`screen -R <session name>`

## Kill a specific screen session

`screen -XS <screen session id> quit`

## Kill all screen sessions

`killall screen`

## Detach from a screen session

`control` + `a`, release keys, then `d`

## List all active screen sessions

`screen -ls`

## Kill the current screen session

`control` + `a`, release keys, then `k`

## Force detach screen session from another ssh session

`screen -r <session name>`
