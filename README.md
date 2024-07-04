# S3sInkJ

S3sInkJ is a fork from [cleeem/splatnet](https://github.com/cleeem/splatnet) project.

## How to use

#### Step 1. Add the JitPack repository to your build file

Add it in your root `build.gradle` at the end of repositories:

Gradle(Groovy)

```groovy
repositories {
    maven { url 'https://jitpack.io' }
}
```

Gradle(Kotlin)

```kotlin
repositories {
    maven(url = "https://jitpack.io")
}
```

Maven

```xml
<repositories>
	<repository>
	    <id>jitpack.io</id>
	    <url>https://jitpack.io</url>
	</repository>
</repositories>
```

#### Step 2. Add the dependency

Gradle(Groovy)

```groovy
dependencies {
    implementation 'com.github.bexonpak:S3sInkJ:(insert latest version)'
}
```

Gradle(Kotlin)

```kotlin
dependencies {
    implementation("com.github.bexonpak:S3sInkJ:(insert latest version)")
}
```

Gradle(Kotlin + toml)

`build.gradle.kts`

```kotlin
dependencies {
    implementation("com.github.bexonpak:S3sInkJ:(insert latest version)")
}
```

`libs.versions.toml`

```toml
[versions]
s3sinkj = "(insert latest version)"

[libraries]
s3sinkj = { module = "com.github.bexonpak:S3sInkJ", version.ref = "s3sinkj" }
```

Maven

```xml
<dependency>
    <groupId>com.github.bexonpak:S3sInkJ</groupId>
    <artifactId>S3sInkJ</artifactId>
    <version>(insert latest version)</version>
</dependency>
```

### Sincere thanks for the following open source projects

[cleeem/splatnet](https://github.com/cleeem/splatnet): Inherited from s3s [GPL-3.0](https://github.com/cleeem/splatnet?tab=readme-ov-file)

[frozenpandaman/s3s](https://github.com/frozenpandaman/s3s): [GPL-3.0](https://github.com/frozenpandaman/s3s?tab=GPL-3.0-1-ov-file)

[google/gson](https://github.com/google/gson): [Apache-2.0](https://github.com/google/gson?tab=Apache-2.0-1-ov-file)

[jhy/jsoup](https://github.com/jhy/jsoup): [MIT](https://github.com/jhy/jsoup?tab=MIT-1-ov-file)
