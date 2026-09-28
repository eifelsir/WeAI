# Third-Party Notices

WeAI's application source is not published. This does not change the licenses
of third-party components included in its Android package.

| Component | Version | License | Upstream |
| --- | --- | --- | --- |
| Kotlin standard library | 2.1.20 | Apache-2.0 | https://github.com/JetBrains/kotlin |
| Gson | 2.11.0 | Apache-2.0 | https://github.com/google/gson |
| jsoup | 1.18.3 | MIT | https://github.com/jhy/jsoup |
| libxposed service | 101.0.0 | Apache-2.0 | https://github.com/libxposed/service |
| libxposed interface | 101.0.0 | Apache-2.0 | https://github.com/libxposed/service |
| JetBrains annotations | 13.0 | Apache-2.0 | https://github.com/JetBrains/java-annotations |
| Error Prone annotations | 2.27.0 | Apache-2.0 | https://github.com/google/error-prone |

The libxposed framework API is a compile-time dependency and is not bundled.
Build tools and test-only libraries are not distributed as application
dependencies.

License texts: [Apache-2.0](licenses/Apache-2.0.txt),
[jsoup MIT](licenses/jsoup-MIT.txt).

These libraries are used without source modifications; Android's optimizer may
transform or remove their bytecode. No endorsement by these projects is implied.
