# srcds-guardian

## description

Little console utility that wraps around srcds.exe and steamcmd.exe

It provides the following features:

- auto install steamcmd, and a game server of choice (optional);
- automatic restarts of servers;
- automatic server updates from steam;
- optimizes the resource class for srcds and steamcmd;
- automatically remove crashdumps after a week;
- watchdog:
  - checks for memory leaks, and restarts if needed;
  - checks for servers that are hanging;
  - checks for servers that burn 100% cpu;
  - auto restarts after the last player leaves.

 In short: everything you need to run a hazzle free server.

## how to use

- Download the latest release from the GitHub Actions tab;
- Copy SourceGuardian.exe into an empty folder;
- Run it:

```
.\SrcdsGuardian.exe -appid 582400 -game reactivedrop
```

That's all.
