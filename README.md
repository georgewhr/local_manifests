# Harold Labs
# Download Android source with patches(local_manifests)
# Refer to http://source.android.com/source/downloading.html
 $ repo init -u https://android.googlesource.com/platform/manifest -b android-7.1.0_r4
 $ cd .repo
 $ git clone https://github.com/georgewhr/local_manifests -b nougat
 $ repo sync
