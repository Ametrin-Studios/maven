# MCModsMaven
This is a maven repository to use it add these lines to your repositories in your build.gradle
```gradle
maven {
  url "https://github.com/BarionLP/MCModsMaven/raw/main/"
}
```

## Example dependecy
```gradle
implementation fg.deobf("com.ametrinstudios:ametrin:${minecraft_version}-${ametrin_version}")
```
