# IDE settings for Cookpad Android Style

This is an [Android Studio](https://developer.android.com/sdk/index.html) settings for the Cookpad coding style standard.

To introduce this settings, save the `codeStyleSettings.xml` to `.idea/`,
add `!.ideta/codeStyleSettings.xml` to `.gitignore`,
and restart Android Studio.

```sh
# in an android project:
curl -L "https://raw.githubusercontent.com/cookpad/android-code-style/master/.idea/codeStyleSettings.xml" > .idea/codeStyleSettings.xml
# restart Android Studio!
```

``gitignore
# .gitignore
idea/*
!.idea/codeStyleSettings.xml
```

# See Also

* https://github.com/cookpad/styleguide
* [AndroidStyle.xml provided by the android project ](https://github.com/android/platform_development/blob/master/ide/intellij/codestyles/AndroidStyle.xml)
* [Android XML arrangement settings for IntellJ IDEA provided by JetBrains](http://blog.jetbrains.com/idea/2013/10/rearrange-attributes-in-android-xml-files-with-intellij-idea-13/)
* [JetBrains Plugin Repository :: Save Actions](https://plugins.jetbrains.com/plugin/7642?pr=idea)
