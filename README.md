# InvFX

[![Kotlin](https://img.shields.io/badge/java-17-ED8B00.svg?logo=java)](https://www.azul.com/)
[![Kotlin](https://img.shields.io/badge/kotlin-1.9.22-585DEF.svg?logo=kotlin)](http://kotlinlang.org)
[![Gradle](https://img.shields.io/badge/gradle-8.7-02303A.svg?logo=gradle)](https://gradle.org)
[![Maven Central](https://img.shields.io/maven-central/v/xyz.icetang.lib/invfx-core)](https://search.maven.org/artifact/xyz.icetang.lib/invfx-core)
[![GitHub](https://img.shields.io/github/license/gooddltmdqls/invfx)](https://www.gnu.org/licenses/gpl-3.0.html)
[![Kotlin](https://img.shields.io/badge/youtube-아이스탕-red.svg?logo=youtube)](https://www.youtube.com/@아이스탕)

### Kotlin DSL for PaperMC Inventory GUI

---

* #### Features
    * Frame
        * Button
        * Pane
        * List

---

#### Gradle

```kotlin
repositories {
    mavenCentral()
}
```

```kotlin
dependencies {
    implementation("xyz.icetang.lib:invfx-api:<version>")
}
```

### plugins.yml

```yaml
name: ...
version: ...
main: ...
libraries:
  - xyz.icetang.lib:invfx-core:<version>
```
