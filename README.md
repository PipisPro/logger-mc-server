# logger-mc-server

[![Build Status](https://travis-ci.org/bkaradzic/bgfx.svg?branch=master)](https://github.com/levshx/logger-mc-server/releases/tag/Ant)

Minecraft logger (Moderation tools)


![Main](https://sun9-51.userapi.com/GD3opq0rZy0cIYgKWrDuoYZFUNcsFXtlZK43Zg/E-cfp-GmimY.jpg)

Push notifications

![Main](https://sun9-49.userapi.com/8uohoLFQ68EJbWSWb3BlJDXGgDlN1CtVyozA6Q/TGSMqPkce7I.jpg)

### Message types:
* [G] Global chat
* [L] Local chat
* [C] Commands


## Triggers:
![Trigger1](https://sun9-32.userapi.com/bt5-NMiInq_X-JvhBjuFYf03NvLgpAJF-GYHDg/e6EmtsZw-CA.jpg)

![Trigger2](https://sun9-19.userapi.com/SZ24SWcW8tFxaQxiRDhceBpUr8hSOzXedL5sjg/xQtiMFAfSnA.jpg)

![Trigger3](https://sun9-50.userapi.com/cYLOlF5E2TAy213AoiX0fQE_d2W8HsJxwR_T7w/Bn5NVEudgXY.jpg)

![Trigger4](https://sun9-58.userapi.com/5G4ZbzSFJMD1AERif3IBki790UBtGo-yFy2n3w/MTIj3H3KjmM.jpg)

![Trigger5](https://sun9-8.userapi.com/ZDYNUI6xSuo3lwYtgRE7k01PO8GQJyQ1woD3Lg/xFn2fPDyXa0.jpg)

## More settings in settings.json
```json
  {
    "https": false,
    "chatUrl": "logs.s9.mcskill.ru/Technomagic2_public_logs/",
    "dropUrl": "logs.s9.mcskill.ru/Technomagic2_logger_public_logs/",
    "deathUrl": "logs.s9.mcskill.ru/Technomagic2_public_logs/",
    "adCommerce": true,
    "obscenity": true,
    "adWarp": true,
    "restartedTrigger": true,
    "adCommerceWords": [
      "продаю",
      "продам",
      "обменяю",
      "куплю"
    ],
    "adWarpWords": [
      "warp",
      "/warp",
      "варп"
    ],
    "commandsTrigger": [
      "/screenshot levshx",
      "/warp end",
      "/seen levshx",
      "/whois levshx",
      "/tp levshx",
      "/vanish"
    ],
    "obscenityWords": [
      "s*ka",
      "b**at",
      "н**уй",
      "б**дь",
      "кр*тин"
    ],
    "playerJoinTrigger": [
      "SkyDrive_",
      "Astrallis",
      "levshx",
      "moskovroma",
      "Flying_Joe",
      "n1ke374",
      "bng"
    ],
    "publicWordsTrigger": [
      "levshx",
      "лев",
      "левша"
    ],
    "localWordsTrigger": [
      "бесплатно",
      "верни",
      "дюп",
      "баг"
    ],
    "messageWordsTrigger": [
      "бесплатно",
      "пожалуйста",
      "дюп",
      "баг"
    ]
  }
```
