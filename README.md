# pathfinder-translation
패스파인더: 킹메이커 번역용 저장소입니다.

## 번역 기여
@Akintos 의 사설 서버에서 호스팅되는 [Weblate](http://akintos.iptime.org/projects/pathfinder_kingmaker/) 에 가입하면 번역 제안을 하실수 있습니다. 제안은 번역자들이 수락할 수 있습니다.

## 설명
[pathfinder-translation](https://github.com/akintos/pathfinder-translation) 이 2022-11-20 이후 업데이트 되지 않아, fork 하여 교정을 진행하고 있습니다.
제안은 github issue 에 등록해주시면 감사하겠습니다.

## How to Build
    $ brew install pip3
    $ pip3 install polib
    $ python3 build_locale.py -l ko -i ./locale -c <compressed_file_name>

## How to Install macOS (Steam)
    $ unzip compressed file (overwrite) to /Users/{userName}/Library/Application Support/Steam/steamapps/common/Pathfinder Kingmaker/Kingmaker.app/Contents/Resources/Data/StreamingAssets/Localization
    $ unzip -fo ./v20230210.zip -d /Users/{userName}/Library/Application\ Support/Steam/steamapps/common/Pathfinder\ Kingmaker/Kingmaker.app/Contents/Resources/Data/StreamingAssets/Localization