# ๐ ๋ด ์์์ ์์ ๋๋๋ฌด์ฒ, Shade 
<br/>

> ์ด๋ ๋๊ตฌ์๊ฒ๋ ๋ง ๋ชปํ  ๊ณ ๋ฏผ์ ํธ์ด๋์ ๊ณต๊ฐ์ ์ํด ๋ง๋ค์ด์ก์ต๋๋ค. <br/>
> ์ง๊ธ ๋น์ ์๊ฒ ์๋ ๊ณ ๋ฏผ, ์ด๊ณณ์์ ๋ง์ ์น๊ตฌ๋ค์ด ํจ๊ป ๋์์ค๋๋ค. 

<br/>

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=2022-IT-SHOW-Shade_android&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=2022-IT-SHOW-Shade_android) [![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=2022-IT-SHOW-Shade_android&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=2022-IT-SHOW-Shade_android) [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/2022-IT-SHOW-Shade&count_bg=%23849ED1&title_bg=%23849ED1&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com) <br/>
[webpage here!](https://shade.emirim.kr/)


<br/>
 
<img width="1800" alt="๋ชฉ์" src="https://user-images.githubusercontent.com/72568433/174945438-0ec72400-0c1b-4967-9588-8fc91020c5a5.png">

<br><br><br>

## ๐ ๏ธ Tech

<br/>

#### APP
- Java
- Android Studio

<br>

#### Database & Server
- Firebase
- Firebase Realtime Database
- Neis API

<br><br><br>

## ๐ Development settings

```
android {
    compileSdk 31

    defaultConfig {
        applicationId "com.example.shade"
        minSdk 21
        targetSdk 31
        versionCode 1
        versionName "1.0"

        testInstrumentationRunner "androidx.test.runner.AndroidJUnitRunner"
    }

    buildTypes {
        release {
            minifyEnabled false
            proguardFiles getDefaultProguardFile('proguard-android-optimize.txt'), 'proguard-rules.pro'
        }
    }
    compileOptions {
        sourceCompatibility JavaVersion.VERSION_1_8
        targetCompatibility JavaVersion.VERSION_1_8
    }
}
```

```
๐ฆ 
โโย .github
โย ย โโย workflows
โย ย ย ย ย โโย build.yml
โโย .gitignore
โโย .idea
โย ย โโย .gitignore
โย ย โโย .name
โย ย โโย compiler.xml
โย ย โโย deploymentTargetDropDown.xml
โย ย โโย git_toolbox_prj.xml
โย ย โโย gradle.xml
โย ย โโย jarRepositories.xml
โย ย โโย misc.xml
โย ย โโย vcs.xml
โโย README.md
โโย app
โย ย โโย .gitignore
โย ย โโย build.gradle
โย ย โโย google-services.json
โย ย โโย proguard-rules.pro
โย ย โโย src
โย ย ย ย ย โโย androidTest
โย ย ย ย ย โย ย โโย java
โย ย ย ย ย โย ย ย ย ย โโย com
โย ย ย ย ย โย ย ย ย ย ย ย ย โโย example
โย ย ย ย ย โย ย ย ย ย ย ย ย ย ย ย โโย shade
โย ย ย ย ย โย ย ย ย ย ย ย ย ย ย ย ย ย ย โโย ExampleInstrumentedTest.java
โย ย ย ย ย โโย main
โย ย ย ย ย โย ย โโย AndroidManifest.xml
โย ย ย ย ย โย ย โโย ic_launcher_mainicon-playstore.png
โย ย ย ย ย โย ย โโย java
โย ย ย ย ย โย ย โย ย โโย com
โย ย ย ย ย โย ย โย ย ย ย ย โโย example
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย โโย shade
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โโย adapter
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โย ย โโย CommentAdpater.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โย ย โโย MypostAdapter.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โย ย โโย NoticeAdapter.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โย ย โโย PostAdapter.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โย ย โโย SchoolAdapter.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โย ย โโย TimeLineAdapter.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โโย exception
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โย ย โโย NeisException.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โย ย โโย ParseException.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โโย fragment
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โย ย โโย MyPageFragment.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โย ย โโย MySchoolFragment.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โย ย โโย MyWriteFragment.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โย ย โโย TimeLineFragment.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โโย model
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โย ย โโย Comment.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โย ย โโย Notice.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โย ย โโย Post.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โย ย โโย School.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โย ย โโย User.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย โโย view
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย ย ย ย โโย DeleteActivity.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย ย ย ย โโย MainActivity.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย ย ย ย โโย NoticeActivity.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย ย ย ย โโย PostDatailActivity.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย ย ย ย โโย RecyclerDecoration.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย ย ย ย โโย SplashActivity.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย ย ย ย โโย VersionActivity.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย ย ย ย โโย WritePostActivity.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย ย ย ย โโย server
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย ย ย ย โย ย โโย SchoolAPI.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย ย ย ย โย ย โโย SearchSchoolActivity.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย ย ย ย โโย userActivity
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย ย ย ย ย ย ย โโย JoinActivity.java
โย ย ย ย ย โย ย โย ย ย ย ย ย ย ย ย ย ย ย ย ย ย ย ย โโย LoginActivity.java
โย ย ย ย ย โย ย โโย res
โย ย ย ย ย โย ย ย ย ย โโย anim
โย ย ย ย ย โย ย ย ย ย โย ย โโย spin.xml
โย ย ย ย ย โย ย ย ย ย โโย drawable
โย ย ย ย ย โย ย ย ย ย โย ย โโย back.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย background_btn_phone_confirm.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย background_btn_reg.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย background_btn_write_finish.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย background_btn_writepost.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย background_btnmic.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย background_button.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย background_cardview_round.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย background_mypage_like.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย background_searchview.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย background_splash.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย btn_delete.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย btn_main.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย btn_second.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย chat.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย cloud.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย delete.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย delete_back.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย edit.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_background.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_foreground.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย icon_main.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย icon_splash.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย like.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย like_check.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย like_checkbox.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย like_uncheck.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย menu_selector_color.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย mic.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย mypage.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย mypage_button1.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย mypage_button2.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย mypage_button3.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย mypage_button4.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย mypage_button5.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย school.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย send.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย splash.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย timeline.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย user.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย write.xml
โย ย ย ย ย โย ย ย ย ย โโย font
โย ย ย ย ย โย ย ย ย ย โย ย โโย font.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย notosanskrblack.ttf
โย ย ย ย ย โย ย ย ย ย โย ย โโย notosanskrbold.ttf
โย ย ย ย ย โย ย ย ย ย โย ย โโย notosanskrdemilite.ttf
โย ย ย ย ย โย ย ย ย ย โย ย โโย notosanskrlight.ttf
โย ย ย ย ย โย ย ย ย ย โย ย โโย notosanskrmedium.ttf
โย ย ย ย ย โย ย ย ย ย โย ย โโย notosanskrregular.ttf
โย ย ย ย ย โย ย ย ย ย โย ย โโย notosanskrthin.ttf
โย ย ย ย ย โย ย ย ย ย โโย layout
โย ย ย ย ย โย ย ย ย ย โย ย โโย activity_delete.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย activity_join.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย activity_login.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย activity_main.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย activity_mypage_like.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย activity_notice.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย activity_posts_detail.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย activity_search_school.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย activity_version.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย activity_write_detail.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย dialog_bamboo.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย dialog_delete.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย dialog_withdrawal.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย fragment_my_school.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย fragment_my_write.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย fragment_mypage.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย fragment_timeline.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย item_comments.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย item_my_posts.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย item_notice.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย item_posts.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย item_school.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย splash.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย toolbar_base.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย toolbar_mypage.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย toolbar_mywrite.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย toolbar_school.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย toolbar_write.xml
โย ย ย ย ย โย ย ย ย ย โโย menu
โย ย ย ย ย โย ย ย ย ย โย ย โโย menu_bottom_nav.xml
โย ย ย ย ย โย ย ย ย ย โโย mipmap-anydpi-v26
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_mainicon.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_mainicon_round.xml
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_round.xml
โย ย ย ย ย โย ย ย ย ย โโย mipmap-hdpi
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher.webp
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_mainicon.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_mainicon_foreground.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_mainicon_round.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_round.webp
โย ย ย ย ย โย ย ย ย ย โโย mipmap-mdpi
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher.webp
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_mainicon.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_mainicon_foreground.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_mainicon_round.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_round.webp
โย ย ย ย ย โย ย ย ย ย โโย mipmap-xhdpi
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher.webp
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_mainicon.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_mainicon_foreground.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_mainicon_round.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_round.webp
โย ย ย ย ย โย ย ย ย ย โโย mipmap-xxhdpi
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher.webp
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_mainicon.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_mainicon_foreground.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_mainicon_round.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_round.webp
โย ย ย ย ย โย ย ย ย ย โโย mipmap-xxxhdpi
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher.webp
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_mainicon.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_mainicon_foreground.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_mainicon_round.png
โย ย ย ย ย โย ย ย ย ย โย ย โโย ic_launcher_round.webp
โย ย ย ย ย โย ย ย ย ย โโย values-night
โย ย ย ย ย โย ย ย ย ย โย ย โโย themes.xml
โย ย ย ย ย โย ย ย ย ย โโย values
โย ย ย ย ย โย ย ย ย ย ย ย ย โโย colors.xml
โย ย ย ย ย โย ย ย ย ย ย ย ย โโย ic_launcher_mainicon_background.xml
โย ย ย ย ย โย ย ย ย ย ย ย ย โโย strings.xml
โย ย ย ย ย โย ย ย ย ย ย ย ย โโย themes.xml
โย ย ย ย ย โโย test
โย ย ย ย ย ย ย ย โโย java
โย ย ย ย ย ย ย ย ย ย ย โโย com
โย ย ย ย ย ย ย ย ย ย ย ย ย ย โโย example
โย ย ย ย ย ย ย ย ย ย ย ย ย ย ย ย ย โโย shade
โย ย ย ย ย ย ย ย ย ย ย ย ย ย ย ย ย ย ย ย โโย ExampleUnitTest.java
โโย build.gradle
โโย gradle.properties
โโย gradle
โย ย โโย wrapper
โย ย ย ย ย โโย gradle-wrapper.jar
โย ย ย ย ย โโย gradle-wrapper.properties
โโย gradlew
โโย gradlew.bat
โโย settings.gradle
```
ยฉgenerated by [Project Tree Generator](https://woochanleee.github.io/project-tree-generator)

<br><br><br>

## ๐ฉ๐ปโ๐ป Developed by

[์ฌ์ด์ง](https://github.com/0pyaq0) โ s2011@e-mirim.hs.kr <br/>
* PM, ์๋๋ก์ด๋ ๊ฐ๋ฐ, UI/UX ๋์์ธ <br/>

[๊น์ ๋](https://github.com/U-and-Me) โ s2005@e-mirim.hs.kr <br/>
* ์๋๋ก์ด๋ ๊ฐ๋ฐ (API ๋ด๋น)

<br><br><br>

## โกHow to contribute

1. (<https://github.com/2022-IT-SHOW-Shade/android.git>)์ ํฌํฌํฉ๋๋ค.
2. (`git checkout -b feature/branch-name`) ๋ช๋ น์ด๋ก ์ ๋ธ๋์น๋ฅผ ๋ง๋์ธ์.
3. (`git commit -am 'Add some branch-name'`) ๋ช๋ น์ด๋ก ์ปค๋ฐํ์ธ์.
4. (`git push origin feature/branch-name`) ๋ช๋ น์ด๋ก ๋ธ๋์น์ ํธ์ํ์ธ์.ย 
5. PR์ ๋ณด๋ด์ฃผ์ธ์!

<br/><br/>

[![SonarCloud](https://sonarcloud.io/images/project_badges/sonarcloud-white.svg)](https://sonarcloud.io/summary/new_code?id=2022-IT-SHOW-Shade_android)

