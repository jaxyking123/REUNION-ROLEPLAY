# Reunion Utilities - Discord Ticket Bot

Discord bot za ticket sistem sa razlozima za otvaranje ticketa.

## Instalacija

1. Instaliraj dependencies:
```bash
npm install
```

2. Konfiguriši `config.json`:
   - `token`: Već podešen
   - `clientId`: Application ID bota
   - `guildId`: ID tvog servera
   - `ticketCategoryId`: ID kategorije gde će se kreirati ticketi (opciono)
   - `supportRoleId`: ID support role koja će imati pristup ticketima

3. Pokreni bota:
```bash
npm start
```

## Kako dobiti potrebne ID-ove

1. Uključi Developer Mode u Discord (User Settings > Advanced > Developer Mode)
2. Desni klik na server/kanal/rolu > Copy ID

## Komande

- `!start` - Pokreni ticket sistem (bot će te pitati u koji kanal da postavi panel)

## Razlozi za Ticket

Korisnici mogu odabrati jedan od sledećih razloga:
- 👮 Žalba na Admina
- 🎮 Žalba na Igrača
- 🐛 Prijava Buga

## Funkcionalnosti

- ✅ Setup preko `!start` komande
- ✅ Izbor kanala za ticket panel
- ✅ Tri razloga za otvaranje ticketa
- ✅ Automatska provera da korisnik nema već otvoren ticket
- ✅ Zatvaranje ticketa dugmetom
- ✅ Automatsko brisanje kanala nakon zatvaranja
- ✅ Notifikacije za support tim
