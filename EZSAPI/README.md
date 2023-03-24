# European Zombs Scrims API

Access with `https://creaffy.github.io/EZSAPI/...`

---

## Clans

### Clan Object

```json
{
  "name": CLANNAME,
  "tag": CLANTAG,
  "tier": CLANTIER,
  "players": [
    {
      "name": PLAYERNAME,
      "role": PLAYERROLE,
      "region": PLAYERREGION
    },
    {
      "name": PLAYERNAME2,
      "role": PLAYERROLE2,
      "region": PLAYERREGION2
    }
    // ...
  ],
  "tournaments_won": [
    TOURNAMENTID,
    TOURNAMENTID2,
    TOURNAMENTID3
    //...
  ]
}
```

- **CLANNAME**: Clan's name
- **CLANTAG**: Clan's tag
- **CLANTIER**: _1, 2, 3_
- **PLAYERNAME**: Player's name
- **PLAYERROLE**: _Leader, Representative, Player_
- **PLAYERREGION**: _EU, USW, USE, ASIA, OCE_
- **TOURNAMENTID**: Tournament's identifier

---

## Tournaments - COMING SOON

### Tournament Object

```json
{
  "id": TOURNAMENTID,
  "timestamp": TOURNAMENTTIMESTAMP,
  "winner": TOURNAMENTWINNER
}
```

- **TOURNAMENTID**: Identifier of the tournament
- **TOURNAMENTTIMESTAMP**: DD-MM-YYYY
- **TOURNAMENTWINNER**: Name of the clan that won
