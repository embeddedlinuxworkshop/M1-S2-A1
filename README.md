# M1-S2-A1
Assignment one for kernel module

- Check how many cores do you have using top command.
- Create number of cores + 2 processes dd if=/dev/zero of=/dev/null run in background.
- Change priority for them:
    - -20, -10, 0, .. , 19
- Monitor them using top command, did you notice any change ?
- Kill them all using killall command.
