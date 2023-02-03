# OBS Scene Collection: Advanced-PET

![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/DriCro6663/advanced-pet)
![GitHub](https://img.shields.io/github/license/DriCro6663/advanced-pet)

[![Demo-Youtube-v1.0.0](https://img.youtube.com/vi/LzrnZg5Scx4/0.jpg)](https://www.youtube.com/watch?v=LzrnZg5Scx4)

This is a scene collection for [OBS](https://obsproject.com/ja), inspired by the PET of Mega Man Exe.

> [Mega Man Exe AXESS ~ Beast+ PET: Advanced-PET series](https://www.nicovideo.jp/watch/sm30540016)

Use [Scene Collection Manager](https://obsproject.com/forum/resources/scene-collection-manager.1434/) to import scene collections.

## Introduction

* [PET Screen](https://exe-rockman.net/wp-content/uploads/2020/06/pet06.png) by [N-guchino](https://exe-rockman.net/).

    <details>
    <summary>Image: PET Screen by N-guchino</summary>

    [![N-guchino_PET](https://exe-rockman.net/wp-content/uploads/2020/06/pet06.png)](https://exe-rockman.net/make_a_pet_extra01/)

    </details>

* [PET Screen](https://www.nicovideo.jp/watch/sm36826926) by [Kamiya](https://www.nicovideo.jp/user/19608348).

    <details>
    <summary>Image: PET Screen by Kamiya</summary>

    [![ロックマンエグゼ風仮想背景](https://img.cdn.nimg.jp/s/nicovideo/thumbnails/36826926/36826926.61672808.original/r1280x720l?key=288286928b9953df497529e34b1532da9f672da9b8e034b847091eaf6e526f75)](https://www.youtube.com/watch?v=lhHvjWNb8AA)

    </details>

* Mega Man EXE AXESS ED animation

    <details>
    <summary>Image: Mega Man EXE AXESS ED animation</summary>

    [![光とどく場所ノンテロ](https://img.cdn.nimg.jp/s/nicovideo/thumbnails/30540016/30540016.original/r1280x720l?key=52b270c1df982983aa0f64c9f029287bb0965a98f31a33d56cacd9c0dc75bc5a)](https://www.nicovideo.jp/watch/sm30540016)

    </details>

I have used the above as a reference.

My abbreviated thanks are hereby extended.

## Overview

Scenes created using [Scene Collection Manager](https://obsproject.com/forum/resources/scene-collection-manager.1434/), inspired by the PET of Mega Man Exe. Collection backup.

## How to use

1. Install [OBS](https://obsproject.com/en) and [SAMMI](https://github.com/SAMMISolutions/SAMMI-Official/releases). <br> * I put SAMMI in C:\Program Files\SAMMI.

2. Install the following plug-ins to [OBS](https://obsproject.com).

    * [Scene Collection Manager](https://obsproject.com/forum/resources/scene-collection-manager.1434/)
    * [Move transition](https://obsproject.com/forum/resources/move-transition.913/)
    * [StreamFX](https://obsproject.com/forum/resources/streamfx-for-obs%C2%AE-studio.578/)

        > As of 01/13/2023, I am using [StreamFX 0.12.0 Alpha 151](https://github.com/Xaymar/obs-StreamFX/releases/tag/0.12.0a151). Please select the version of StreamFX according to your OBS.

3. Please refer to the link below to set up the connection between [OBS](https://obsproject.com/ja) and [SAMMI](https://github.com/SAMMISolutions/SAMMI-Official/releases). <br>*Originally, LioranBoard 2 and SAMMI are the same software, so it should be helpful.

    > [How to install LioranBoard 2 and work with Twitch and YouTube Live](https://kurocha.jp/lioranboard2-setup)
    >
    > [OBS] The most powerful free streamdeck LioranBoard2 introduction guide distribution [VTuber / Bishamonten Liyukko](https://www.youtube.com/live/Vf76nyIeeng?feature=share)

4. Download from [Release](https://github.com/DriCro6663//releases) and extract the compressed file.

5. Refer to [kurocha](https://kurocha.jp/)'s [Article: Plug-in for easy and convenient OBS backup](https://kurocha.jp/obs-scene-collection-manager) and use [Scene Collection Manager](https://obsproject.com/forum/resources/scene-collection-manager.1434/) to import json files of scene collections.

    <details><summary>
    Image: Import scene collection backup
    </summary>
    
    ![kurocha-import-01](https://kurocha.jp/wp-content/uploads/2022/05/2022-05-09_17h12_27-1.jpg)
    
    ![kurocha-import-02](https://kurocha.jp/wp-content/uploads/2022/05/2022-05-09_17h14_04.jpg)
    
    ![kurocha-import-03](https://kurocha.jp/wp-content/uploads/2022/05/2022-05-09_17h17_53.jpg)
    
    > [Plug-in for easy and convenient OBS backup](https://kurocha.jp/obs-scene-collection-manager)
    </details>

    <details><summary>
    *If you have any problems after importing, please refer to the following sound settings.
    </summary>

    * BGM: [Deep World](https://oto.how/sound/457), Playback speed: 150 %, Volume: -32.0 db
    * PET-boot-se: [Sound Design-04](https://koukaon.g-sozai.com/se-532.html), Playback speed: 50 %, Volume: -8.0 db
    * task-bar-se: [Cyber11-1](https://otologic.jp/free/se/cyber02.html), Playback speed: 200 %, Volume: +8.0 db
    * loading-se: [Cyber13-1](https://otologic.jp/free/se/cyber02.html)
    * scene-change-se: [Cyber14-1](https://otologic.jp/free/se/cyber02.html)
    * decision-se: [Cyber15-1](https://otologic.jp/free/se/cyber02.html)
    * PET-frame-se: [Cyber16-2](https://otologic.jp/free/se/cyber02.html)
    * v-se: [Cyber17-1](https://otologic.jp/free/se/cyber02.html)

    </details>

6. Import deck environment from [SAMMI](https://github.com/SAMMISolutions/SAMMI-Official/releases). <br>* Just in case, make a backup before importing.

    1. Start SAMMI.
    2. Open the deck json file in the SAMMI folder that you downloaded from the release and unzipped, and copy the contents.
    3. Then select the Paste Deck item on SAMMI to expand the deck.

    <br>

    > Share a deck  
    > In SAMMI, select a deck you wish to share with someone, right click on it and select Copy Deck. This will copy all your JSON deck data into your clipboard. You can then paste it into a text file to share with others.  
    > To Import a deck, press Paste Deck in SAMMI’s side menu.  
    > [SAMMI FAQ -Buttons & Commands-](https://sammi.solutions/docs/faq/commands)

## Environment

PC: [GL72M 7RDX](https://www.msi.com/Laptop/GL72M-7RDX/Specification)  
CPU: [i7-7700HQ CPU @ 2.80GHz 7th Gen](https://www.intel.co.jp/content/www/jp/ja/products/sku/97185/intel-core-i77700hq-processor-6m-cache-up-to-3-80-ghz/specifications.html)  
GPU: GeForce® GTX 1050 with 2GB GDDR5

## Notes

* The json files exported from the Scene Collection Manager can also be imported using the standard OBS functionality. However, the temporary path of the local file set when exporting from the Scene Collection Manager is read, so the file is not correctly linked to the local file.

    <details><summary>
    Image: Points to note when importing scene collection backup
    </summary>
    
    ![kurocha-note-01](https://kurocha.jp/wp-content/uploads/2022/05/2022-05-09_17h11_06.jpg)
    
    ![kurocha-note-02](https://kurocha.jp/wp-content/uploads/2022/05/2022-05-09_17h17_02.jpg)
    
    > [Plug-in for easy and convenient OBS backup](https://kurocha.jp/obs-scene-collection-manager)

    </details>

* This scene collection is created on the premise of using [LioranBoard 2](https://github.com/LioranWaters/Lioranboard2Update) and [SAMMI](https://sammi.solutions/).

* This scene collection may be discontinued without notice.

## Updates

* 2023/02/03: <br>[v1.0.0](https://github.com/DriCro6663/advanced-pet/releases/tag/v1.0.0) released. <br>Improved boot effects. Added end effects.

    <details><summary>
    Previous Updates
    </summary>

    * 2023/02/01: <br>[v0.0.5-beta](https://github.com/DriCro6663/advanced-pet/releases/tag/v0.0.5) released. <br>DS 4:3 scene added. Added ED. Organize the SAMMI deck: make frequently used operations into functions.

    * 2023/01/25: <br>[v0.0.4-beta](https://github.com/DriCro6663/advanced-pet/releases/tag/v0.0.4) released. Added GBA-3:2 scene. Add/organize comment scenes. Added BGM and SE. Added SAMMI's deck.

    * 2023/01/21:<br>[v0.0.3-alpha](https://github.com/DriCro6663/advanced-pet/releases/tag/v0.0.3) released. Added delivery standby, wait a minute, and end-of-delivery scenes. Organized each animation settings.

    * 2023/01/18:<br>[v0.0.2-alpha](https://github.com/DriCro6663/advanced-pet/releases/tag/v0.0.2) released. Added taskbar animation setting.

    * 2023/01/13:<br>[v0.0.1-alpha](https://github.com/DriCro6663/advanced-pet/releases/tag/v0.0.1) released. Backup of the production in progress.

    </details>

## Developer Information & Responsibility

* [Github DriCro6663](https://github.com/DriCro6663)
* [Twitter Dri_Cro_6663](https://twitter.com/Dri_Cro_6663)
* [YouTube ドリクロ -DriCro-](https://www.youtube.com/channel/UCyWgav9wdiPVjYphB7jrWCQ)
* [PieceX DriCro6663](https://www.piecex.com/users/profile/DriCro6663)
* [Memorandum of DriCro](https://dri-cro-6663.jp/)
* dri.cro.6663@gmail.com

## Credits

* BGM by [Oto.how](https://oto.how/)
* ED by [D-elf.com](https://www.d-elf.com/)
* SE by [OtoLogic](https://otologic.jp/) (CC BY 4.0)
* SE by [G-Sozai](https://koukaon.g-sozai.com/)

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Dataset" property="dct:title" rel="dct:type">OBS Scene Collection: Advanced-PET</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/DriCro6663/advanced-pet" property="cc:attributionName" rel="cc:attributionURL">Dri Cro</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

Please also check the [LICENSE](.LICENSE) file.
