# busybox-ndk
build busybox for Android with ndk-build

    git clone --depth=1 https://github.com/topjohnwu/ndk-box-kitchen
    cd ndk-box-kitchen/
    git clone --depth=1 https://github.com/topjohnwu/ndk-busybox busybox
    git clone --depth=1 https://github.com/SELinuxProject/selinux.git jni/selinux
    git clone --depth=1 https://android.googlesource.com/platform/external/pcre jni/pcre
    wget https://dl.google.com/android/repository/android-ndk-r21e-linux-x86_64.zip
    unzip android-ndk-r21e-linux-x86_64.zip
    mv android-ndk-r21e ndk && rm -rf android-ndk-r21e-linux-x86_64.zip
