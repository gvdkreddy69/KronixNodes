# MUZICARD 🎵 [v2.5.2]

This Package Is A Modified Version of Musicard With Some Exicting New Themes.!

## Usage

```js
(async () => {
  const { AttachmentBuilder } = require("discord.js");
  const { muzicard } = require("muzicard");
  const card = new muzicard()
        .setName("Govinda Namalu")
        .setAuthor(`G V D K REDDY`)
        .setColor("auto")
        .setTheme("neonx")
        .setBrightness(69)
        .setThumbnail(this.dispatcher.player.info.thumbnail)
        .setProgress(69)
        .setStartTime("0:00")
        .setEndTime("3:63")

    const buffer = await card.build();
    const attachment = new AttachmentBuilder(buffer, { name: `musicard.png` });
    return message.channel.send(files:[attachment]);
  console.log("Done Dona Done Done!");
})();
```

# Preview Of Theme's:

| Square Thumbnail                                                                                                                                                                                                                                                                           | Round Thumbnail                                                                                                                                                                                                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Setting: `.setTheme("neon")` ![neon](https://media.discordapp.net/attachments/1152621602614280274/1195292083762757642/musicard.png?ex=65b37580&is=65a10080&hm=3dcd614d857b102ba0af5192facefcbffc73f5a4ba798eb27d6a773a88fcd138&=&format=webp&quality=lossless&width=1120&height=392)       | Setting: `.setTheme("neonx")` ![neonx](https://media.discordapp.net/attachments/1152621602614280274/1195592298319331398/musicard.png?ex=65b48d18&is=65a21818&hm=0da8854d5a6deab7352cece64393116ad3bb110113f6859b500ac3cca9a6b207&=&format=webp&quality=lossless&width=1176&height=412)     |
| Setting: `.setTheme("anime")` ![anime](https://media.discordapp.net/attachments/1152621602614280274/1195296498896883774/musicard.png?ex=65b3799c&is=65a1049c&hm=3f4d942f5f20567a23b62b84be105df77cd1ac1a24a6f4379831ec5f4692ed46&=&format=webp&quality=lossless&width=1120&height=392)     | Setting: `.setTheme("animex")` ![animex](https://media.discordapp.net/attachments/1152621602614280274/1195593940653580368/musicard.png?ex=65b48ea0&is=65a219a0&hm=365376edd366430baf6a187c35522abfe5dd261ce4f3e11e5cf0ff3c1964d073&=&format=webp&quality=lossless&width=1176&height=412)   |
| Setting: `.setTheme("animes")` ![animes](https://media.discordapp.net/attachments/1152621602614280274/1197827030889275462/musicard.png?ex=65bcae5a&is=65aa395a&hm=0d33df3d3ab167e3feb9a47cca2402f26f09bbd220f2dbe31771cbf0a965d40b&=&format=webp&quality=lossless&width=1101&height=387)   | Setting: `.setTheme("animesx")` ![animesx](https://media.discordapp.net/attachments/1152621602614280274/1197856535867564052/musicard.png?ex=65bcc9d5&is=65aa54d5&hm=4e734fa522677aa15de8012415b717b23389ebce1be8de8662a22f19f680df50&=&format=webp&quality=lossless&width=1101&height=387) |
| Setting: `.setTheme("space")` ![space](https://media.discordapp.net/attachments/1152621602614280274/1195356973605060669/musicard.png?ex=65b3b1ef&is=65a13cef&hm=5d3a55e937c3a062b802b2f89c285f213bb7bd3df99d0922b2965a6d56a7372d&=&format=webp&quality=lossless&width=1176&height=411)     | Setting: `.setTheme("spacex")` ![spacex](https://media.discordapp.net/attachments/1152621602614280274/1195361438261321778/musicard.png?ex=65b3b617&is=65a14117&hm=7d4e87f7a65e6fd298228726f3cb4854dd6c4cdf35881d7963d77d588b4f524d&=&format=webp&quality=lossless&width=1176&height=411)   |
| Setting: `.setTheme("classic")` ![classic](https://media.discordapp.net/attachments/1152621602614280274/1195347877690617866/musicard.png?ex=65b3a976&is=65a13476&hm=6a898e194a0dfd63202a926a051402cb7ea68809c4f0b5d0798d603c0aa5f9a2&=&format=webp&quality=lossless&width=1120&height=392) | Setting: `.setTheme("dynamic")` ![dynamic](https://media.discordapp.net/attachments/1152621602614280274/1195348615519019109/musicard.png?ex=65b3aa26&is=65a13526&hm=d848276bd9884c97c9c1781f7a614bf49dff5dda75d608fd00c9ed0aad0e33fa&=&format=webp&quality=lossless&width=1120&height=262) |

## Support / Help

| Links                                               | Developer's                                                    | Supporter's                                                     |
| --------------------------------------------------- | -------------------------------------------------------------- | --------------------------------------------------------------- |
| [iShowKronix' YT](https://youtube.com/@kronixx2077) | [G V D K REDDY](https://discord.com/users/1057674644905279498) | [A R J U N](https://discord.com/users/795294090609557504)       |
| [Kronix's Server](https://discord.gg/aMC2e8zgQb)    | [A K S H A T](https://discord.com/users/924144335535091744)    | [F I C K L I N G](https://discord.com/users/728958118536675369) |

## Credits

Original musicard package by [A3PIRE](https://github.com/a3pire/musicard)
