# remark
192.168。109.78  1883

可以使用横屏下的计算器。用（）代替*#。。比如说你的*#*#2846579#*#*可以使用计算器的（）（）2846579（）（）

相机相关api需要升级
布局文件嵌套比较多

签名

../../static/images/news.png

C:\Program Files\Java\jdk-11.0.1\bin>jarsigner -verbose -keystore D:\code\edus_parents\appBuild\platforms\android\minivision.jks -signedjar "F:\WeChat Files\wztxyxw\Files\OPPOSignVerify\OppoSignVerify_signed.apk" "F:\WeChat Files\wztxyxw\Files\OPPOSignVerify\OppoSignVerify.apk" minivision


latitude=0.0#longitude=0.0#province=#coordType=GCJ02#city=#district=#cityCode=#adCode=#address=#country=#road=#poiName=#street=#streetNum=#aoiName=#poiid=#floor=#errorCode=7#errorInfo=KEY错误#locationDetail=auth fail:INVALID_USER_SCODE#SHA1AndPackage#4C:9E:6C:1A:FD:49:1A:E1:AB:D9:C8:B7:A1:77:55:16:49:0A:75:78:com.minivision.kgparent#gsid#953dd18c807d69d0dbe57f564963d8f6#csid#7562e644c65b408aaf177704a8ddca29#0701#description=#locationType=0



gradle clean assembleRelease


//分享回调监听
oks.setCallback(new PlatformActionListener() {
            @Override
            public void onComplete(Platform platform, int i, HashMap<String, Object> hashMap) {

            }

            @Override public void onError(Platform platform, int i, Throwable throwable) {
                throwable.getMessage();
                throwable.getStackTrace().toString();
            }

            @Override public void onCancel(Platform platform, int i) {

            }
        });

WebView.setWebContentsDebuggingEnabled(true);//web调试

宝贝动态 时间格式 服务器处理

MediaScannerConnection msc = new MediaScannerConnection(KinderGartenApplication.getInstance().getApplicationContext(), null);
            msc.connect();
            msc.scanFile(currentFile.getPath(), "image/jpeg");

%1$d/%2$d

String key = System.currentTimeMillis() + filePath.substring(filePath.lastIndexOf("."));//保留“.”    
String key = System.currentTimeMillis() + filePath.substring(filePath.lastIndexOf(".") + 1);//不保留“.”    

//测试环境
yuan心:
家长端：projectId=7e21285f8cad4a10910d77897f28fcf5


yuan心:
教师端：projectId=b5dd01f0e28e4a54ba737ed9a3709b52


//生产环境

家长端：projectId=3db5fc93243a4fe281c4e597445abda3
教师端：projectId=c51b70da6f8b44bba18ebd1587f3f412


Matrix matrix = new Matrix();
        //镜子效果
        matrix.setScale(-1, 1);
        matrix.postTranslate(mBitmap.getWidth(), 0);
        mBitmap = Bitmap.createBitmap(mBitmap, 0, 0, mBitmap.getWidth(), mBitmap.getHeight(), matrix, true);

家长版签名：
              b5b698d8195b7d39d4eea32f985baaea

webview.setWebViewClient(new WebViewClient() {
    @Override
    public void onReceivedSslError(WebView view, SslErrorHandler handler, SslError error) {
 
        // 不要使用super，否则有些手机访问不了，因为包含了一条 handler.cancel()
        // super.onReceivedSslError(view, handler, error);
 
        // 接受所有网站的证书，忽略SSL错误，执行访问网页
        handler.proceed();
    }
}

视频码率与质量成正比，体积也随之变大

gradlew processDebugManifest --stacktrace
gradlew assembleRelease


动画开始前，设置 LayerType 为 LAYER_TYPE_HARDWARE（代码为官方示例）

1
2
view.setLayerType(View.LAYER_TYPE_HARDWARE, null);
ObjectAnimator.ofFloat(view, "rotationY", 180).start();
动画结束的时候，重新设置为LAYER_TYPE_NONE（代码为官方示例）

1
2
3
4
5
6
7
8
9
view.setLayerType(View.LAYER_TYPE_HARDWARE, null);
ObjectAnimator  = ObjectAnimator.ofFloat(view, "rotationY", 180);
.addListener(new AnimatorListenerAdapter() {
    @Override
    public void onAnimationEnd( animation) {
        view.setLayerType(View.LAYER_TYPE_NONE, null);
    }
});
.start();



mTextToSpeech = new TextToSpeech(MainActivity.this, new TextToSpeech.OnInitListener() {
                    @Override
                    public void onInit(int i) {
                        if (i == TextToSpeech.SUCCESS) {
                            int result = mTextToSpeech.setLanguage(Locale.ENGLISH);
                            if (result == TextToSpeech.LANG_MISSING_DATA || result == TextToSpeech.LANG_NOT_SUPPORTED) {
                            } else {
                                mTextToSpeech.speak("支持原生中文语音播报功能", TextToSpeech.QUEUE_FLUSH, null);
                            }
                        }
                    }
                });

Androidx迁移  解决glide无法编译问题  annotationProcessor externalAndroidAnno  

adb -s 设备号 logcat -s xskj   指定设备查信息

adb -s 1912A46900600027 install F:\general\release\MINI_A_GME_IC_N_V2.3.1.11.apk

adb pull /sdcard/DeviceMonitorLog/com.minivision.pad_tb_cloud/ ./

adb logcat -v time >test27.txt

adb install -r F:\general\release\MINI_A_GME_IC_N_V2.3.1.11.apk  //覆盖安装

gradlew assembleRelease

卸载系统应用 文件管理器
F:\>adb shell
root@TPS469:/ # pm list packages | grep com.android.rk
package:com.android.rk
package:com.android.rk.mediafloat
root@TPS469:/ # pm uninstall -k --user 0 com.android.rk
Success
root@TPS469:/ # pm uninstall -k --user 0 com.android.rk.mediafloat
Success
root@TPS469:/ #
