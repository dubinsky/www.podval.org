# www.podval.org

```
./gradlew generateSite
./gradlew serveSite
```

`generateSite` writes `_site` (GitHub Pages). Plugin id `org.podval.tools.site-publisher`.
A local site-publisher checkout at `../site-publisher` is used when present
(`pluginManagement { includeBuild }` plus settings-body `includeBuild`, `-PsitePublisherDir=`);
CI resolves the plugin and `org.podval.tools:org.podval.tools.publisher` from Maven Central.
