---
title: Pro Tips & FAQs
---

{% include navbar.md %}

# Pro Tips
## <a name="enable-split-screen-mode-for-more-apps"></a>Enable force split-screen
Some apps like [Facebook Messenger](https://play.google.com/store/apps/details?id=com.facebook.orca), [LINE](https://play.google.com/store/apps/details?id=jp.naver.line.android), and [Google Duo](https://play.google.com/store/apps/details?id=com.google.android.apps.tachyon) don't support split-screen mode. To force them to allow split-screen mode:

1. [enable _developer settings_ on the phone](https://developer.android.com/studio/debug/dev-options#enable) if it isn't already.
2. open Android's **Settings** app.
3. enable the **System** > **Developer options** > **Force activities to be re-sizable** option. (it should be at the very bottom...)
5. restart the phone.
6. done! split-screen mode should work on tons more apps now.

Unfortunately, some apps like [Instagram](https://play.google.com/store/apps/details?id=com.instagram.android) may crash if put into split-screen mode. And other apps like the homescreen, and [Google Assistant](https://play.google.com/store/apps/details?id=com.google.android.apps.googleassistant) still disallow split-screen mode.

## Change long press duration
To change the long press duration:

1. open Android's **Settings** app.
2. go to: **Accessibility** > **Touch & hold delay**.

# Frequently Asked Questions

## Why isn't Split screen working on the home screen?
An app must be open before split-screen mode can be activated. (e.g. YouTube)

## Why am I getting _"App does not support split screen"_ message?
See [Enable force split-screen](#enable-split-screen-mode-for-more-apps).

## Why is split-screen mode turning on then off right away?
Some phones already come with a split-screen shortcut; this app, and the system shortcut could be interfering with each other. Go into the Split Screen app's settings, and turn off the trigger that's causing this issue. Alternatively, uninstall the Split Screen app.
