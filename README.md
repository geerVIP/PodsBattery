# PodsBattery
PodsBattery.apk破解版
主要修改了
    /* JADX WARN: Multi-variable type inference failed */
    public final void d() {
        l.a(this);
        g();
        i();
        I.b(this);
        if (o.l().b0()) {
            u.b(this);
        }
        h();
        a.b().i(this);
        h.e();
        f();
        e();
        Log.d("MyApplication", "Before force unlock");/在log中强制输出一个解锁状态
        n.i().S(true);
        Log.d("MyApplication", "After force unlock");/在log看是否正常输出状态
    }
    
移除了联网的权限<uses-permission android:name="android.permission.INTERNET"/>和广告权限的

<meta-data
            android:name="com.google.android.gms.ads.APPLICATION_ID"
            android:value="ca-app-pub-7872841047902755~9313583541"/>
        <provider
            android:name="com.google.android.gms.ads.MobileAdsInitProvider"
            android:exported="false"
            android:authorities="com.yugongkeji.podstool.mobileadsinitprovider"
            android:initOrder="100"/>
            这两部分
还有一个小改动初始话延迟调整了下，我就不贴出改动的代码了，毕竟代码的smali已经脱壳过了！能直接看到我改动过的地方，整个软件包都可以解包查看代码！并没有夹带任何私货，软件本身还是要手动给出一些权限，通知栏、应用显示上层、后台运行，没有通知栏你体验不到解锁后的通知栏功能，后台运行不开如今被系统睡眠了蓝牙连接弹窗效果就没有了，显示上层必须开不然弹窗效果直接没有，如果不知道自己的品牌手机怎么给权限的，自己去网上问问，我也不知道你用的是什么手机我也不一定用过，我的手机是Motorola razr 40ultra 出厂就是原生安卓，官方升级的时候最够只取到安卓15，这就我破解运行环境，原始就没有蓝牙耳机连接弹窗，
