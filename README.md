# lib

## Repository 추가하기
```
repositories {
    maven {
        url = uri("https://lib:{PAT}@maven.pkg.github.com/moberancompany/lib")
    }
}


dependencies {
    implementation("com.moberan:abc:x.x.x")
}
```
