# 🎋 내 손안의 작은 대나무숲, Shade 
<br/>

> 어느 누구에게도 말 못할 고민을 털어놓을 공간을 위해 만들어졌습니다. <br/>
> 지금 당신에게 있는 고민, 이곳에서 많은 친구들이 함께 도와줍니다. 

<br/>

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/2022-IT-SHOW-Shade&count_bg=%23849ED1&title_bg=%23849ED1&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com) <br/>
[webpage](https://shade.emirim.kr/)

<br/>
 
<img width="1800" alt="목업" src="https://user-images.githubusercontent.com/72568433/174945438-0ec72400-0c1b-4967-9588-8fc91020c5a5.png">

<br><br><br>

## 🛠️ Tech

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

## 🌐 Development settings

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
📦 
├─ .gitignore
├─ .idea
│  ├─ .gitignore
│  ├─ .name
│  ├─ compiler.xml
│  ├─ deploymentTargetDropDown.xml
│  ├─ git_toolbox_prj.xml
│  ├─ gradle.xml
│  ├─ jarRepositories.xml
│  ├─ misc.xml
│  └─ vcs.xml
├─ app
│  ├─ .gitignore
│  ├─ build.gradle
│  ├─ google-services.json
│  ├─ proguard-rules.pro
│  └─ src
│     ├─ androidTest
│     │  └─ java
│     │     └─ com
│     │        └─ example
│     │           └─ shade
│     │              └─ ExampleInstrumentedTest.java
│     ├─ main
│     │  ├─ AndroidManifest.xml
│     │  ├─ ic_launcher_mainicon-playstore.png
│     │  ├─ java
│     │  │  └─ com
│     │  │     └─ example
│     │  │        └─ shade
│     │  │           ├─ adapter
│     │  │           │  ├─ CommentAdpater.java
│     │  │           │  ├─ MypostAdapter.java
│     │  │           │  ├─ NoticeAdapter.java
│     │  │           │  ├─ PostAdapter.java
│     │  │           │  ├─ SchoolAdapter.java
│     │  │           │  └─ TimeLineAdapter.java
│     │  │           ├─ exception
│     │  │           │  ├─ NeisException.java
│     │  │           │  └─ ParseException.java
│     │  │           ├─ fragment
│     │  │           │  ├─ MyPageFragment.java
│     │  │           │  ├─ MySchoolFragment.java
│     │  │           │  ├─ MyWriteFragment.java
│     │  │           │  └─ TimeLineFragment.java
│     │  │           ├─ model
│     │  │           │  ├─ Comment.java
│     │  │           │  ├─ Notice.java
│     │  │           │  ├─ Post.java
│     │  │           │  ├─ School.java
│     │  │           │  └─ User.java
│     │  │           └─ view
│     │  │              ├─ DeleteActivity.java
│     │  │              ├─ MainActivity.java
│     │  │              ├─ NoticeActivity.java
│     │  │              ├─ PostDatailActivity.java
│     │  │              ├─ RecyclerDecoration.java
│     │  │              ├─ SplashActivity.java
│     │  │              ├─ VersionActivity.java
│     │  │              ├─ WritePostActivity.java
│     │  │              ├─ server
│     │  │              │  ├─ SchoolAPI.java
│     │  │              │  └─ SearchSchoolActivity.java
│     │  │              └─ userActivity
│     │  │                 ├─ JoinActivity.java
│     │  │                 └─ LoginActivity.java
│     │  └─ res
│     │     ├─ anim
│     │     │  └─ spin.xml
│     │     ├─ drawable
│     │     │  ├─ back.xml
│     │     │  ├─ background_btn_phone_confirm.xml
│     │     │  ├─ background_btn_reg.xml
│     │     │  ├─ background_btn_write_finish.xml
│     │     │  ├─ background_btn_writepost.xml
│     │     │  ├─ background_btnmic.xml
│     │     │  ├─ background_button.xml
│     │     │  ├─ background_cardview_round.xml
│     │     │  ├─ background_mypage_like.xml
│     │     │  ├─ background_searchview.xml
│     │     │  ├─ background_splash.xml
│     │     │  ├─ btn_delete.xml
│     │     │  ├─ btn_main.xml
│     │     │  ├─ btn_second.xml
│     │     │  ├─ chat.xml
│     │     │  ├─ cloud.png
│     │     │  ├─ delete.xml
│     │     │  ├─ delete_back.png
│     │     │  ├─ edit.xml
│     │     │  ├─ ic_launcher_background.xml
│     │     │  ├─ ic_launcher_foreground.xml
│     │     │  ├─ icon_main.png
│     │     │  ├─ icon_splash.png
│     │     │  ├─ like.xml
│     │     │  ├─ like_check.png
│     │     │  ├─ like_checkbox.xml
│     │     │  ├─ like_uncheck.png
│     │     │  ├─ menu_selector_color.xml
│     │     │  ├─ mic.xml
│     │     │  ├─ mypage.xml
│     │     │  ├─ mypage_button1.png
│     │     │  ├─ mypage_button2.png
│     │     │  ├─ mypage_button3.png
│     │     │  ├─ mypage_button4.png
│     │     │  ├─ mypage_button5.png
│     │     │  ├─ school.xml
│     │     │  ├─ send.xml
│     │     │  ├─ splash.xml
│     │     │  ├─ timeline.xml
│     │     │  ├─ user.xml
│     │     │  └─ write.xml
│     │     ├─ font
│     │     │  ├─ font.xml
│     │     │  ├─ notosanskrblack.ttf
│     │     │  ├─ notosanskrbold.ttf
│     │     │  ├─ notosanskrdemilite.ttf
│     │     │  ├─ notosanskrlight.ttf
│     │     │  ├─ notosanskrmedium.ttf
│     │     │  ├─ notosanskrregular.ttf
│     │     │  └─ notosanskrthin.ttf
│     │     ├─ layout
│     │     │  ├─ activity_delete.xml
│     │     │  ├─ activity_join.xml
│     │     │  ├─ activity_login.xml
│     │     │  ├─ activity_main.xml
│     │     │  ├─ activity_mypage_like.xml
│     │     │  ├─ activity_notice.xml
│     │     │  ├─ activity_posts_detail.xml
│     │     │  ├─ activity_search_school.xml
│     │     │  ├─ activity_version.xml
│     │     │  ├─ activity_write_detail.xml
│     │     │  ├─ dialog_bamboo.xml
│     │     │  ├─ dialog_delete.xml
│     │     │  ├─ dialog_withdrawal.xml
│     │     │  ├─ fragment_my_school.xml
│     │     │  ├─ fragment_my_write.xml
│     │     │  ├─ fragment_mypage.xml
│     │     │  ├─ fragment_timeline.xml
│     │     │  ├─ item_comments.xml
│     │     │  ├─ item_my_posts.xml
│     │     │  ├─ item_notice.xml
│     │     │  ├─ item_posts.xml
│     │     │  ├─ item_school.xml
│     │     │  ├─ splash.xml
│     │     │  ├─ toolbar_base.xml
│     │     │  ├─ toolbar_mypage.xml
│     │     │  ├─ toolbar_mywrite.xml
│     │     │  ├─ toolbar_school.xml
│     │     │  └─ toolbar_write.xml
│     │     ├─ menu
│     │     │  └─ menu_bottom_nav.xml
│     │     ├─ mipmap-anydpi-v26
│     │     │  ├─ ic_launcher.xml
│     │     │  ├─ ic_launcher_mainicon.xml
│     │     │  ├─ ic_launcher_mainicon_round.xml
│     │     │  └─ ic_launcher_round.xml
│     │     ├─ mipmap-hdpi
│     │     │  ├─ ic_launcher.webp
│     │     │  ├─ ic_launcher_mainicon.png
│     │     │  ├─ ic_launcher_mainicon_foreground.png
│     │     │  ├─ ic_launcher_mainicon_round.png
│     │     │  └─ ic_launcher_round.webp
│     │     ├─ mipmap-mdpi
│     │     │  ├─ ic_launcher.webp
│     │     │  ├─ ic_launcher_mainicon.png
│     │     │  ├─ ic_launcher_mainicon_foreground.png
│     │     │  ├─ ic_launcher_mainicon_round.png
│     │     │  └─ ic_launcher_round.webp
│     │     ├─ mipmap-xhdpi
│     │     │  ├─ ic_launcher.webp
│     │     │  ├─ ic_launcher_mainicon.png
│     │     │  ├─ ic_launcher_mainicon_foreground.png
│     │     │  ├─ ic_launcher_mainicon_round.png
│     │     │  └─ ic_launcher_round.webp
│     │     ├─ mipmap-xxhdpi
│     │     │  ├─ ic_launcher.webp
│     │     │  ├─ ic_launcher_mainicon.png
│     │     │  ├─ ic_launcher_mainicon_foreground.png
│     │     │  ├─ ic_launcher_mainicon_round.png
│     │     │  └─ ic_launcher_round.webp
│     │     ├─ mipmap-xxxhdpi
│     │     │  ├─ ic_launcher.webp
│     │     │  ├─ ic_launcher_mainicon.png
│     │     │  ├─ ic_launcher_mainicon_foreground.png
│     │     │  ├─ ic_launcher_mainicon_round.png
│     │     │  └─ ic_launcher_round.webp
│     │     ├─ values-night
│     │     │  └─ themes.xml
│     │     └─ values
│     │        ├─ colors.xml
│     │        ├─ ic_launcher_mainicon_background.xml
│     │        ├─ strings.xml
│     │        └─ themes.xml
│     └─ test
│        └─ java
│           └─ com
│              └─ example
│                 └─ shade
│                    └─ ExampleUnitTest.java
├─ build.gradle
├─ gradle.properties
├─ gradle
│  └─ wrapper
│     ├─ gradle-wrapper.jar
│     └─ gradle-wrapper.properties
├─ gradlew
├─ gradlew.bat
└─ settings.gradle
```
©generated by [Project Tree Generator](https://woochanleee.github.io/project-tree-generator)

<br><br><br>

## 👩🏻‍💻 Developed by

[심이진](https://github.com/0pyaq0) – s2011@e-mirim.hs.kr <br/>
* PM, 안드로이드 개발, UI/UX 디자인 <br/>

[김유나](https://github.com/U-and-Me) – s2005@e-mirim.hs.kr <br/>
* 안드로이드 개발 (API 담당)

<br><br><br>

## ⚡How to contribute

1. (<https://github.com/2022-IT-SHOW-Shade/android.git>)을 포크합니다.
2. (`git checkout -b feature/branch-name`) 명령어로 새 브랜치를 만드세요.
3. (`git commit -am 'Add some branch-name'`) 명령어로 커밋하세요.
4. (`git push origin feature/branch-name`) 명령어로 브랜치에 푸시하세요. 
5. PR을 보내주세요!

