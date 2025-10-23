## For-While
#### For
```bash
alias beep='echo -ne "\007"'
function beeper() {
    for (( i=0; i<$1; i++ ))
    do
        beep
    done
}
```
#### While
```bash
alias beep='echo -ne "\007"'
function beeperWhile() {
    i=0
    while (( i < $1 ))
    do
        beep
        ((i++))   # αυξάνουμε το i κατά 1
    done
}
```
