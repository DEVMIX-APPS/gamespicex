gamespicex
==========

Game services client for cocos2d-x with GameSpice sweetness

## How to install

Clone this repo into your cocos2d-x root

    git clone git@github.com:gamespice/gamespicex.git

Open your ``Android.mk`` file and add the module

    $(call import-module,gamespicex) 

Add to LOCAL_WHOLE_STATIC_LIBRARIES

    gamespice_x_static

So it might look like this
    
    LOCAL_WHOLE_STATIC_LIBRARIES := cocos2dx_static cocosdenshion_static cocos_extension_static gamespice_x_static

Add to your ``AndroidManifest.xml``

    <uses-permission android:name="android.permission.INTERNET" />
