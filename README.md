## Rechercher et télécharger des applications depuis Aptoide



- Auteur : [Ainz](https://github.com/Nignanfatao)



***



## Exemple de recherche

```js

const { 

search

} = require('aptoide_apk_dl')



let search = await search('whatsapp')

console.log(search)

```

***

## résultats

```js

[

  { name: 'WhatsApp Messenger', id: 'com.whatsapp' },

  { name: 'Whatsapp Status Saver', id: 'com.sas.statussaverapp' },

  { name: 'WhatsApp Direct Message', id: 'com.verox.whatsappdirect' },

  {

    name: 'CallApp: Caller ID, Call Blocker & Recording Calls',

    id: 'com.callapp.contacts'

  },

  {

    name: 'Status Downloader for Whatsapp',

    id: 'com.freeapps.statussaverforwa'

  },

  { name: 'Whatsapp Web Pro', id: 'com.sas.whatswebpro' },

  { name: 'WhatsApp Spy', id: 'net.oz.team.chat.lives' },

  { name: 'Call Recorder', id: 'polis.app.callrecorder' },

  { name: 'WhatsApp Business', id: 'com.whatsapp.w4b' },

  { name: 'Cleaner Fast for WhatsApp', id: 'catch_.me_.if_.you_.can_' },

  { name: 'Hide WhatsApp', id: 'com.nabiltitou.whatshide' },

  {

    name: 'JasminChat - Live Video Chat with Strangers',

    id: 'com.jasmin_video.live_chat'

  },

  { name: 'tonos.ringtones.whatsapp', id: 'tonos.ringtones.whatsapp' },

  { name: 'Whatsapp Swab', id: 'com.soon.whatapp' },

  {

    name: 'Whatsapp Cleaner',

    id: 'io.makeroid.soumik2001_SM.WhatsAppCleanr'

  },

  {

    name: 'Stickers For WhatsApp - STICKER MAKER',

    id: 'com.wastickers.wastickerapps'

  },

  { name: 'WhatsApp Wallpaper', id: 'com.whatsapp.wallpaper' },

  { name: 'Autoreply Whatsapp', id: 'com.chatautoreplyplus' },

  { name: 'Curiosidades WhatsApp', id: 'com.curiosidades.whatsapp' },

  { name: 'Schat whatsapp', id: 'com.edwinnmd.schatwhatsapp' },

  {

    name: 'Colors for WhatsApp',

    id: 'com.eightsoft.wallpaperwhatsappgradients'

  },

  { name: 'Beta Whatsapp updates Plus', id: 'com.elite.whatsapppro' },

  { name: 'Phone 2 Location - Caller Id', id: 'and.p2l' },

  {

    name: 'Videos de Risa WhatsApp',

    id: 'com.videos.de.risa.para.whatsapp'

  },

  { name: 'Beta Whatsapp Updates Lite', id: 'com.elite.whatsapp' },

  { name: 'Wallpaper Whatsapp HD', id: 'com.wkapp.fondospantalla' },

  { name: 'BIG Launcher', id: 'name.kunes.android.launcher.demo' },

  { name: 'Whatsapp News &Android Updates', id: 'com.kingstellw.a' },

  {

    name: 'Beta Updater for WhatsApp',

    id: 'com.javiersantos.whatsappbetaupdater'

  },

  {

    name: 'Free Ringtones whatsapp',

    id: 'com.wkapp.tonosnotificaciones'

  },
{

    name: 'BIG Phone for Seniors',

    id: 'name.kunes.android.launcher.bigphone'

  },

  {

    name: 'Create Stickers for WhatsApp',

    id: 'com.didi.createstickers'

  }

]

```

***



## Exemple téléchargement

```js

const { 

download

} = require('aptoide_apk_dl')



let data = await download('com.whatsapp')

console.log(data)

```

***

## Résultat

```js

{

  name: 'WhatsApp Messenger',

  lastup: '2023-03-30 09:05:47',

  package: 'com.whatsapp',

  size: '78.36 MB',

  icon: 'https://pool.img.aptoide.com/mark8/1227f7edc0704ff99f73e0425d85ab5d_icon.png',

  dllink: 'https://pool.apk.aptoide.com/mark8/com-whatsapp-230717004-64686734-67cc547bc25d933b1b1434544048f5bd.apk'

}

```

***
