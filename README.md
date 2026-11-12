# Year-12-Systems-SAC
an music player mixed with a phone design (might get changed)

# starting/introduction
when i mean by 'phone design' operating system will be around an phone 'shape' or i can just do an music player that has bluetooth combatability and a audio jack (convenience)
so, for this, i dont have an exact idea on what im doing or the knowlege on how to code, so im going to wing it and use AI for the code and possibly *how* i wire it as i dont know at the moment.
i dont know if i can use aliexpress parts but if im not able to, ill find alternative parts to the aliexpress parts i find. i also dont exactly know how to make a portfolio so ill be going off on what i am able to do as i dont know how to word it. ill include some images on a phone design of a ipod/music player.

had an actual idea change, casset player, like the one in guardians of the galaxy, but there wont be a casset player in it, but it will look like a casset player, i do need to have a mechanical system on the thing, i might just have a belt that makes it look like a casset player on the outside on the lid to cover the touch screen with just a motor. 

i had a search and there isnt any casset modules that could be bought and be used, i still need to have a search to see if there are any mechanical components i could/can use for the media player, the current idea i have is: tactile input/controls, kenetic and visual feedback. those two are the only 'good' idea that i can implement into the media player, for example: for the tactile input/control, i could have some buttons on/in the case for like pause / skip / rewind-backp for the song while i still have the touch screen to change songs and change playlists... thats an actual good idea to be honest, i could have like a hinge to protect the screen that has a cover on it and i can make it somewhat look like a actual casset player but non-functional as its going to be more for aesthetics. i still need to figure out the wiring diagram to be fair. when im prototyping the media player when i get all the parts i can make like a circut board (PCB) to have it not like, mess up the signaling for each of the components

# materials (ideas):
- microcontroller, display, some sort of controls or like a touch screen for the display, audio jack, SD reader + SD card, battery (havent decided on how much watthours it should hold), battery charger (probably a USB C and including a lightning port for convenience too), cassette player reader thing (not used but still keeping it here as its an actual good idea), 

# material list (basic):
- esp 32: https://www.aliexpress.com/item/1005005704190069.html?src=google&src=google&albch=shopping&acnt=742-864-1166&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=UneMJZVf&gclsrc=aw.ds&albagn=888888&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en1005005704190069&ds_e_product_merchant_id=5852244380&ds_e_product_country=AU&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=21819463808&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=21819486122&gclid=Cj0KCQiA-8XXBhDaARIsADnEOrCq64YOvA1zoFXdpRzaIj6mhmmib3ehLft0jWMOvCPC_0lWs53vyqAaAiGrEALw_wcB
- 4 inch touch screen: https://www.aliexpress.com/item/1005009295152503.html?src=google&src=google&albch=shopping&acnt=742-864-1166&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=UneMJZVf&gclsrc=aw.ds&albagn=888888&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en1005009295152503&ds_e_product_merchant_id=5852244380&ds_e_product_country=AU&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=21819463808&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=21819486122&gclid=Cj0KCQiA-8XXBhDaARIsADnEOrB8Kc6E0DDUacMff6IJ2FciH6hqvCVdTUk12c8GJE65Cq31cGo-840aAi7AEALw_wcB
- battery (havent decided the capacity yet):
- SD reader: https://www.aliexpress.com/item/1005011587213547.html?src=google&src=google&albch=shopping&acnt=742-864-1166&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=UneMJZVf&gclsrc=aw.ds&albagn=888888&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en1005011587213547&ds_e_product_merchant_id=5852244380&ds_e_product_country=AU&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=21819463808&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=21819486122&gclid=Cj0KCQiA-8XXBhDaARIsADnEOrD4cmL0Gw_R6GYEqL0YEEv45mowkt7zO5u51T2_DJrjemm0HAMzMZkaAhzpEALw_wcB
- LCD (touchscreen): https://www.aliexpress.com/item/1005009295152503.html?src=google&src=google&albch=shopping&acnt=742-864-1166&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=UneMJZVf&gclsrc=aw.ds&albagn=888888&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en1005009295152503&ds_e_product_merchant_id=5852244380&ds_e_product_country=AU&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=21819463808&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=21819486122&gclid=Cj0KCQiA-8XXBhDaARIsADnEOrB8Kc6E0DDUacMff6IJ2FciH6hqvCVdTUk12c8GJE65Cq31cGo-840aAi7AEALw_wcB
- possibly/potentialy another USB C: https://www.aliexpress.com/item/1005008364309354.html?src=google&src=google&albch=shopping&acnt=742-864-1166&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=UneMJZVf&gclsrc=aw.ds&albagn=888888&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en1005008364309354&ds_e_product_merchant_id=5852244380&ds_e_product_country=AU&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=21819463808&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=21819486122&gclid=Cj0KCQiA-8XXBhDaARIsADnEOrAsSVpObE26plKie1hWXu758QPZzNYfQd2WPZTPE8ZwRNUThgcSBtcaAlbwEALw_wcB
- 

# the idea im going for:

here is an image on what im going for 

<img width="1621" height="913" alt="image" src="https://github.com/user-attachments/assets/62816830-b7e9-4743-a463-3d830d1851ce" />

you can see from this image that it looks like a phone but is a music player, im going for this look, for the music player because i hate ads, and requiring a subscription for ad free and free skips and changing songs, it also looks cool too and i wanted to make something like this or get something like this that i have actualy built myself (and with some help with AI) that i can fix and upgrade over time to add new things that would be cool

# other:
ill update the material list over time to include more detail and update the amounting for the material list, ill probably change the screen size to where its small but not that small as i need to see how the actual screen looks in person so i dont get the wrong size as i also want this to be like a 'phone' but not a phone?


# time table
- made material list, material (ideas), starting/introduction, other, 'the idea im going for' : on 10/11/2026






