<?xml version="1.0" encoding="UTF-8"?>

<!-- config.xml reference: https://build.phonegap.com/docs/config-xml -->
<widget xmlns     = "http://www.w3.org/ns/widgets"
        xmlns:gap = "http://phonegap.com/ns/1.0"
        id        = "com.phonegap.helloworld"
        version   = "1.0.0">

    <name>Hello World</name>

    <description>
        Hello World sample application that responds to the deviceready event.
    </description>

    <author href="http://phonegap.com" email="support@phonegap.com">
        PhoneGap Team
    </author>

    <!-- Define the main entry-point to the application -->
    <content src="index.html" />

    <!-- Customize your app and platform with the preference element. -->
    <preference name="DisallowOverscroll"         value="true" />

    <!-- Define a specific version of PhoneGap to build into your app. -->
    <!-- <preference name="phonegap-version"       value="cli-6.0.0" /> -->

    <!-- Plugins -->
    <!-- Core plugins -->
    <plugin name="cordova-plugin-battery-status"      source="npm" spec="~1.2.4" />
    <plugin name="cordova-plugin-camera"              source="npm" spec="~2.4.1" />
    <plugin name="cordova-plugin-media-capture"       source="npm" spec="~1.4.3" />
    <plugin name="cordova-plugin-device"              source="npm" spec="~1.1.6" />
    <plugin name="cordova-plugin-dialogs"             source="npm" spec="~1.3.3" />
    <plugin name="cordova-plugin-file"                source="npm" spec="~4.3.3" />
    <plugin name="cordova-plugin-geolocation"         source="npm" spec="~2.4.3" />
    <plugin name="cordova-plugin-globalization"       source="npm" spec="~1.0.7" />
    <plugin name="cordova-plugin-inappbrowser"        source="npm" spec="~1.7.1" />
    <plugin name="cordova-plugin-network-information" source="npm" spec="~1.3.3" />
    <plugin name="cordova-plugin-vibration"           source="npm" spec="~2.1.5" />

    <!-- Define app icon and splashscreen for each platform. -->
    <platform name="android">
        <icon   src="www/res/icon/android/drawable-ldpi-icon.png"               density="ldpi" />
        <icon   src="www/res/icon/android/drawable-mdpi-icon.png"               density="mdpi" />
        <icon   src="www/res/icon/android/drawable-hdpi-icon.png"               density="hdpi" />
        <icon   src="www/res/icon/android/drawable-xhdpi-icon.png"              density="xhdpi" />
        <icon   src="www/res/icon/android/drawable-xxhdpi-icon.png"             density="xxhdpi" />
        <icon   src="www/res/icon/android/drawable-xxxhdpi-icon.png"            density="xxxhdpi" />
        <splash src="www/res/screen/android/drawable-land-ldpi-screen.png"      density="land-ldpi" />
        <splash src="www/res/screen/android/drawable-land-mdpi-screen.png"      density="land-mdpi" />
        <splash src="www/res/screen/android/drawable-land-hdpi-screen.png"      density="land-hdpi" />
        <splash src="www/res/screen/android/drawable-land-xhdpi-screen.png"     density="land-xhdpi" />
        <splash src="www/res/screen/android/drawable-land-xxhdpi-screen.png"    density="land-xxhdpi" />
        <splash src="www/res/screen/android/drawable-land-xxxhdpi-screen.png"   density="land-xxxhdpi" />
        <splash src="www/res/screen/android/drawable-port-ldpi-screen.png"      density="port-ldpi" />
        <splash src="www/res/screen/android/drawable-port-mdpi-screen.png"      density="port-mdpi" />
        <splash src="www/res/screen/android/drawable-port-hdpi-screen.png"      density="port-hdpi" />
        <splash src="www/res/screen/android/drawable-port-xhdpi-screen.png"     density="port-xhdpi" />
        <splash src="www/res/screen/android/drawable-port-xxhdpi-screen.png"    density="port-xxhdpi" />
        <splash src="www/res/screen/android/drawable-port-xxxhdpi-screen.png"   density="port-xxxhdpi" />
    </platform>

    <platform name="ios">
        <icon   src="www/res/icon/ios/icon.png"                         platform="ios" width="57"   height="57" />
        <icon   src="www/res/icon/ios/icon@2x.png"                      platform="ios" width="114"  height="114" />
        <icon   src="www/res/icon/ios/icon-40.png"                      platform="ios" width="40"   height="40" />
        <icon   src="www/res/icon/ios/icon-40@2x.png"                   platform="ios" width="80"   height="80" />
        <icon   src="www/res/icon/ios/icon-50.png"                      platform="ios" width="50"   height="50" />
        <icon   src="www/res/icon/ios/icon-50@2x.png"                   platform="ios" width="100"  height="100" />
        <icon   src="www/res/icon/ios/icon-60.png"                      platform="ios" width="60"   height="60" />
        <icon   src="www/res/icon/ios/icon-60@2x.png"                   platform="ios" width="120"  height="120" />
        <icon   src="www/res/icon/ios/icon-60@3x.png"                   platform="ios" width="180"  height="180" />
        <icon   src="www/res/icon/ios/icon-72.png"                      platform="ios" width="72"   height="72" />
        <icon   src="www/res/icon/ios/icon-72@2x.png"                   platform="ios" width="144"  height="144" />
        <icon   src="www/res/icon/ios/icon-76.png"                      platform="ios" width="76"   height="76" />
        <icon   src="www/res/icon/ios/icon-76@2x.png"                   platform="ios" width="152"  height="152" />
        <icon   src="www/res/icon/ios/icon-small.png"                   platform="ios" width="29"   height="29" />
        <icon   src="www/res/icon/ios/icon-small@2x.png"                platform="ios" width="58"   height="58" />
        <icon   src="www/res/icon/ios/icon-small@3x.png"                platform="ios" width="87"   height="87" />
        <splash src="www/res/screen/ios/Default-568h@2x~iphone.png"     platform="ios" width="640"  height="1136" />
        <splash src="www/res/screen/ios/Default-667h.png"               platform="ios" width="750"  height="1334" />
        <splash src="www/res/screen/ios/Default-736h.png"               platform="ios" width="1242" height="2208" />
        <splash src="www/res/screen/ios/Default-Landscape-736h.png"     platform="ios" width="2208" height="1242" />
        <splash src="www/res/screen/ios/Default-Landscape@2x~ipad.png"  platform="ios" width="2048" height="1536" />
        <splash src="www/res/screen/ios/Default-Landscape~ipad.png"     platform="ios" width="1024" height="768" />
        <splash src="www/res/screen/ios/Default-Portrait@2x~ipad.png"   platform="ios" width="1536" height="2048" />
        <splash src="www/res/screen/ios/Default-Portrait~ipad.png"      platform="ios" width="768"  height="1024" />
        <splash src="www/res/screen/ios/Default@2x~iphone.png"          platform="ios" width="640"  height="960" />
        <splash src="www/res/screen/ios/Default~iphone.png"             platform="ios" width="320"  height="480" />
    </platform>

    <platform name="wp8">
        <icon   src="www/res/icon/wp8/ApplicationIcon.png"   platform="wp8" width="99"  height="99" />
        <icon   src="www/res/icon/wp8/Background.png"        platform="wp8" width="159" height="159" />
        <splash src="www/res/screen/wp8/screen-portrait.jpg" platform="wp8" width="768" height="1280" />
    </platform>

    <platform name="windows">
        <!-- For Windows the recommended approach to define app icons is to use target attribute -->
        <!-- <icon src="www/res/icon/windows/StoreLogo.png"         target="StoreLogo" /> -->
        <!-- <icon src="www/res/icon/windows/Square30x30Logo.png"   target="Square30x30Logo" /> -->
        <!-- <icon src="www/res/icon/windows/Square44x44Logo.png"   target="Square44x44Logo" /> -->
        <!-- <icon src="www/res/icon/windows/Square70x70Logo.png"   target="Square70x70Logo" /> -->
        <!-- <icon src="www/res/icon/windows/Square71x71Logo.png"   target="Square71x71Logo" /> -->
        <!-- <icon src="www/res/icon/windows/Square150x150Logo.png" target="Square150x150Logo" /> -->
        <!-- <icon src="www/res/icon/windows/Square310x310Logo.png" target="Square310x310Logo" /> -->
        <!-- <icon src="www/res/icon/windows/Wide310x150Logo.png"   target="Wide310x150Logo" /> -->
        <icon src="www/res/icon/windows/Square150x150Logo.scale-100.png"     platform="windows"   width="150"  height="150" />
        <icon src="www/res/icon/windows/Square30x30Logo.scale-100.png"       platform="windows"   width="30"   height="30" />
        <icon src="www/res/icon/windows/StoreLogo.scale-100.png"             platform="windows"   width="50"   height="50" />
        <splash src="www/res/screen/windows/SplashScreen.scale-100.png"      platform="windows"   width="620"  height="300" />
        <!-- scaled images are specified here for backward compatibility only so we can find them by size -->
        <icon   src="www/res/icon/windows/StoreLogo.scale-240.png"           platform="windows"   width="120"  height="120" />
        <icon   src="www/res/icon/windows/Square44x44Logo.scale-100.png"     platform="windows"   width="44"   height="44" />
        <icon   src="www/res/icon/windows/Square44x44Logo.scale-240.png"     platform="windows"   width="106"  height="106" />
        <icon   src="www/res/icon/windows/Square70x70Logo.scale-100.png"     platform="windows"   width="70"   height="70" />
        <icon   src="www/res/icon/windows/Square71x71Logo.scale-100.png"     platform="windows"   width="71"   height="71" />
        <icon   src="www/res/icon/windows/Square71x71Logo.scale-240.png"     platform="windows"   width="170"  height="170" />
        <icon   src="www/res/icon/windows/Square150x150Logo.scale-240.png"   platform="windows"   width="360"  height="360" />
        <icon   src="www/res/icon/windows/Square310x310Logo.scale-100.png"   platform="windows"   width="310"  height="310" />
        <icon   src="www/res/icon/windows/Wide310x150Logo.scale-100.png"     platform="windows"   width="310"  height="150" />
        <icon   src="www/res/icon/windows/Wide310x150Logo.scale-240.png"     platform="windows"   width="744"  height="360" />
        <splash src="www/res/screen/windows/SplashScreenPhone.scale-240.png" platform="windows"   width="1152" height="1920" />
    </platform>

    <!--
        Define access to external domains.
        <access />            - a blank access tag denies access to all external resources.
        <access origin="*" /> - a wildcard access tag allows access to all external resource.
        Otherwise, you can specify specific domains:
    -->
    <access origin="*" />
    <!--
       <access origin="http://phonegap.com" />                    - allow any secure requests to http://phonegap.com/
       <access origin="http://phonegap.com" subdomains="true" />  - same as above, but including subdomains, such as http://build.phonegap.com/
       <access origin="http://phonegap.com" browserOnly="true" /> - only allows http://phonegap.com to be opened by the child browser.
    -->

    <!-- Added the following intents to support the removal of whitelist code from base cordova to a plugin -->
    <!-- Whitelist configuration. Refer to https://cordova.apache.org/docs/en/edge/guide_appdev_whitelist_index.md.html -->

    <allow-intent href="http://*/*" />
    <allow-intent href="https://*/*" />
    <allow-intent href="tel:*" />
    <allow-intent href="sms:*" />
    <allow-intent href="mailto:*" />
    <allow-intent href="geo:*" />
    <platform name="android">
        <allow-intent href="market:*" />
    </platform>
    <platform name="ios">
        <allow-intent href="itms:*" />
        <allow-intent href="itms-apps:*" />
    </platform>

</widget>
