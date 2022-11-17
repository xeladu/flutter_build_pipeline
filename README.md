This repo contains files that are part of the post at [Building Flutter apps with Azure DevOps - xeladu.medium.com](https://xeladu.medium.com/building-flutter-apps-with-azure-devops-eaf9ae7ad158).

If you want to know more about testing for Flutter apps, check out [my article series on Medium](https://xeladu.medium.com/list/test-your-flutter-app-aabad9825b7f).

# Content

The repository contains a build pipeline in a YAML file that can be integrated in any existing Flutter project that should be built using Azure DevOps.

|Platform|File format|Signing configuration|
|-|-|-|
|Android|AAB|[Link](https://docs.flutter.dev/deployment/android#signing-the-app)|
|iOS|IPA|[Link1](https://docs.flutter.dev/deployment/ios#review-xcode-project-settings), [Link2](https://quarksoftware.my.site.com/quarkknowledgebase/s/article/How-to-create-IOS-provisioning-Profiles-1639097525913?language=en_US)|
|Windows|MSIX*|[Link](https://github.com/YehudaKremer/msix#%EF%B8%8F-signing-options)|

\* Requires package [MSIX](https://pub.dev/packages/msix) in Flutter application

# Support

If you like this post or my work in general, feel free to support me in any way ❤

- You can [become a Medium member via my referral link](https://xeladu.medium.com/membership) for just $5 a month! 💖
- You can [buy me a coffee](https://www.buymeacoffee.com/xeladu) ☕
- You can [browse my Gumroad store](https://xeladu.gumroad.com) for ebooks and freebies 📙
- You can [join my free monthly Medium Newsletter](https://bit.ly/xeladu-medium) 💌
- You can [find all my published stuff here](https://xeladu.medium.com/%E2%84%B9-xeladus-info-point-find-quickly-what-you-need-bbe620e97d8c) 📑
