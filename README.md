# Sources

[Build Flutter apps for iOS, Android, and Windows with Azure DevOps on QuickCoder](https://quickcoder.org/flutter_build_pipeline/)<br/>
[Build Flutter apps for iOS, Android, and Windows with Azure DevOps on Medium](https://xeladu.medium.com/building-flutter-apps-with-azure-devops-eaf9ae7ad158)

# Content

The repository contains a build pipeline in a YAML file that can be integrated in any existing Flutter project that should be built using Azure DevOps.

|Platform|File format|Signing configuration|
|-|-|-|
|Android|AAB|[Link](https://docs.flutter.dev/deployment/android#signing-the-app)|
|iOS|IPA|[Link1](https://docs.flutter.dev/deployment/ios#review-xcode-project-settings), [Link2](https://quarksoftware.my.site.com/quarkknowledgebase/s/article/How-to-create-IOS-provisioning-Profiles-1639097525913?language=en_US)|
|Windows|MSIX*|[Link](https://github.com/YehudaKremer/msix#%EF%B8%8F-signing-options)|

\* Requires package [MSIX](https://pub.dev/packages/msix) in Flutter application

## About me

- Follow me on [Medium](https://xeladu.medium.com)
- Visit my [QuickCoder blog](https://quickcoder.org)
- Check out my [digital products](https://xeladu.gumroad.com)
