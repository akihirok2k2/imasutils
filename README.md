# imasutils
Useful command line tool for Japanese IdolM@star (called IM@S)
A reference for 765PRO all stars (include million stars)

## Installation
    git clone https://github.com/akihirok2k2/imasutils.git
    ln -s [YOUR-INSTALL-DIR]/bin/imas /usr/local/bin/

## Usage
### imas list
The list 765PRO all stars

    $ imas list
    天海 春香
    如月 千早
    星井 美希
    萩原 雪歩
    高槻 やよい
    菊地 真
    水瀬 伊織
    四条 貴音
    秋月 律子
    三浦 あずさ
    双海 亜美
    双海 真美
    我那覇 響
    春日 未来
    最上 静香
    伊吹 翼
    田中 琴葉
    島原 エレナ
    佐竹 美奈子
    所 恵美
    徳川 まつり
    箱崎 星梨花
    野々原 茜
    望月 杏奈
    伴田 路子
    七尾 百合子
    高山 紗代子
    松田 亜利沙
    高坂 海美
    中谷 育
    天空橋 朋花
    エミリー スチュアート
    北沢 志保
    舞浜 歩
    木下 ひなた
    矢吹 可奈
    横山 奈緒
    二階堂 千鶴
    馬場 このみ
    大神 環
    豊川 風花
    宮尾 美也
    福田 のり子
    真壁 瑞希
    篠宮 可憐
    百瀬 莉緒
    永吉 昴
    北上 麗花
    周防 桃子


### imas echo
Haruka Amami's That serif!

    $ imas echo
    プロデューサーさん！ アイマスですよ！アイマス！

    $ imas echo -P あきひろ -m 仕事
    あきひろさん！ 仕事ですよ！仕事！



### imas grep
    $imas grep [-f FILENAME]
    Become green when there is an idle name

    $ imas grep [-f FILENAME] [ -n IDOLNAME]
    Become green when there is The idle name

    $ echo "STRINGS" | imas grep [-f FILENAME2] [-n IDOLNAME]
    Become green when there is The idle name. 
    standerd-input STRINGS  add to -f option to FILE


## Remove
    $ rm -rf /usr/local/share/rubimas
    $ rm -rf [YOUR-INSTALL-DIR]/imasutils
    $ unlink /usr/local/bin/ima
