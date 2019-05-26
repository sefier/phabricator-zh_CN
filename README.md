# phabricator-zh_CN
参考了简体和繁体两个版本，目前有简繁混合的问题，但是一方面是最新版本的翻译库，另外一方面汉化的更彻底，因为推荐用这个版本。

如果要自己修改，请修改PhabricatorCNChineseTranslation中的$new_simple部分即可。

About
=====

The ``phabricator-zh_CN`` project provides chinese locales for `Phabricator <https://phabricator.com>`.

Setup
-----

1. Drop the code into phabricator/src/extensions/
2. Configure Settings -> Account -> Account Settings -> Translation via http://issue.wanthings.com/settings/panel/account/
3. Select`中文 (简体中文)`.


FAQ
-----
Q: 提示`Two subclasses of "PhutilLocale" ("PhutilCNChineseLocale" and "PhutilSimplifiedChineseChinaLocale") define locales with the same locale code ("zh_CN"). Each locale must have a unique locale code.`
A: 请删除翻译项目中的`PhutilCNChineseLocale.php`文件
