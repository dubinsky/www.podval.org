# www.podval.org

```
./gradlew generateSite
./gradlew serveSite
```

`generateSite` writes `_site` (GitHub Pages). A local site-publisher checkout at
`../site-publisher` is used when present (`-PsitePublisherDir=`); CI resolves
`org.podval.tools:org.podval.tools.publisher` from Maven Central.
