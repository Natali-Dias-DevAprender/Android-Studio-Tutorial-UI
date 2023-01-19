# Android-Studio-Tutorial-UI 💡
Este tutorial mostrará como criar um painel moderno de material Android simples e uma página de login e assinatura com código Adobe XD e XML.
Android Studio Tutorial Material Design Android Studio Modern tela do painel UI Design app Tutorial:
- Adobe XD para Android Studio XML
- material UI estúdio android 
- IU do painel móvel 
- interface do usuário móvel

<p align="center">
  <a href="https://media.discordapp.net/attachments/1019265341311963186/1065417508665966662/Tela_inicial_1.png?width=192&height=401" target="blank"><img src="https://media.discordapp.net/attachments/1019265341311963186/1065417508665966662/Tela_inicial_1.png?width=192&height=401"" width="200" alt="DesenvolvMED_logo" /></a>
</p>

    🎨 Customization and Attributes
All customizable attributes for Splashy

Attribute Name	Default Value	Description
setLogo(resId : Int)	R.drawable.splashy	The main logo for Splashy
setTitle(resId : Int)
OR
setTitle(value : String)	R.string.app_name
OR
"Splashy"	The main title for Splashy either from strings.xml or string value
setDuration(timeInMs : Long)	2000	The time to show Splashy in Millisecond
setSubTitle(resId : Int)
OR
setSubTitle(value : String)	R.string.subtitle
OR
"Splash screen made easy"	The subtitle for Splashy either from strings.xml or string value. This also enables subtitle.
setInfiniteDuration(yes: Boolean)	false	Sets splash screen for infinite time if "true". Can be dismissed by calling Splashy.hide()
showTitle(show: Boolean)	true	To show title or not.
setTitleColor(color: Int)
OR
setTitleColor(colorValue: String)	R.color.black
OR
"#000000"	The color of title either resource id from strings.xml OR HEX value.
setTitleSize(titleSize: Float)	40F	The size of title text in float.
setTitleFontStyle(fontName : String)	"fonts/satisfy_regular.ttf"	To set custom font for title.
setSubTitleColor(color: Int)
OR
setSubTitleColor(colorValue: String)	R.color.gray
OR
"#888888"	The color of sub title either resource id from strings.xml OR HEX value.
setSubTitleSize(titleSize: Float)	16F	The size of title text in float.
setSubTitleItalic(italic : Boolean)	true	To set subtitle in italic style or not.
setSubTitleFontStyle(fontName : String)	"fonts/satisfy_regular.ttf"	To set custom font for subtitle.
showLogo(show: Boolean)	true	To show Logo or not.
setLogoWHinDp(width: Int, height: Int)	(200, 200)	To set Logo Width(W) and Height(H) in DP.
setLogoScaleType(scaleType: ImageView.ScaleType)	ImageView.ScaleType.CENTER_CROP	To set default scale type of Logo.
Eg. ImageView.ScaleType.CENTER_CROP, CENTER, FIT_XY and others
showProgress(show: Boolean)	false	To show circular progress bar or not.
setProgressColor(resId: Int)
OR
setProgressColor(value: String)	R.color.black
OR
"#000000"	To set color of progressbar either resource id from strings.xml OR HEX value. Also enables progressbar
setBackgroundColor(resId: Int)
OR
setBackgroundColor(value: String)	R.color.white
OR
"#FFFFFF"	The background of Splash screen either resource id from strings.xml OR HEX value.
setBackgroundResource(resId: Int)	R.drawable.bg	The background resource for splash screen from drawable.
setAnimation(type: Animation, duration: Long)	(NONE,800)	The amazing splash screen animations with duration.
Eg. (Splashy.Animation.SLIDE_IN_TOP_BOTTOM, 800) , Types: SLIDE_IN_TOP_BOTTOM, SLIDE_IN_LEFT_BOTTOM, SLIDE_IN_LEFT_RIGHT, SLIDE_LEFT_ENTER, GLOW_LOGO, GLOW_LOGO_TITLE, GROW_LOGO_FROM_CENTER
setClickToHide(hide: Boolean)	true	Hides splash screen on anywhere click.
setFullScreen(yes: Boolean)	false	To show splashy full screen or not.
show()	--	Finally shows splash screen.
Splashy.onComplete(getComplete: OnComplete)	--	Listener when splash screen ends to perform some operations
Splashy.hide()	--	Hides splash screen. Helpful when set to infinite duration.
📃 License
Copyright 2019 Rahul Dange

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
