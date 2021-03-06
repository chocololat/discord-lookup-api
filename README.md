# discord-lookup-api

Discord Lookup API is an API that lets you, with a given ID, get basic informations about a user

The API returns :
- User ID
- Avatar
- Banner (Image & Color)
- User tag (username#0000)

The API has built-in CORS support, so you won't have to worry 

## Usage

You can freely access the API [here](https://discordlookup.mesavirep.xyz)

You must specify an ID to the link

### Example:
`https://discordlookup.mesavirep.xyz/604779545018761237`

returns

`{
    "id":"604779545018761237",
    "tag":"mesa#0101",
    "avatar":"https://cdn.discordapp.com/avatars/604779545018761237/a_ae7d3d27a9dd1b032751b66599088b53",
    "banner":"https://cdn.discordapp.com/banners/604779545018761237/a_1f49e9dccb19e765c7b2d24bc0141a9c","banner_id":"a_1f49e9dccb19e765c7b2d24bc0141a9c","is_animated":true,"banner_color":"#BD08C2"
    }`


## Installation

1) Clone the repo using Git
2) Install dependencies (`npm i`)
3) Open ports (either 3000 or any other port)
4) Launch the server (`node server.js`)