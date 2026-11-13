# Third-Party Notices

WeAI's application source is not published. This does not change the licenses
of third-party components included in its Android package.

| Component | Version | License | Upstream |
| --- | --- | --- | --- |
| Kotlin standard library | 2.1.20 | Apache-2.0 | https://github.com/JetBrains/kotlin |
| Gson | 2.11.0 | Apache-2.0 | https://github.com/google/gson |
| jsoup | 1.18.3 | MIT | https://github.com/jhy/jsoup |
| Glide GIF decoder | 4.16.0 | BSD-2-Clause / MIT / Apache-2.0; see notices | https://github.com/bumptech/glide |
| libxposed service and interface | 101.0.0 | Apache-2.0 | https://github.com/libxposed/service |
| JetBrains annotations | 13.0 | Apache-2.0 | https://github.com/JetBrains/java-annotations |
| Error Prone annotations | 2.28.0 | Apache-2.0 | https://github.com/google/error-prone |
| smali dexlib2 | 3.0.9 | BSD-3-Clause / Apache-2.0 | https://github.com/google/smali |
| DexKit | 2.3.0 | Apache-2.0 | https://github.com/LuckyPray/DexKit |
| Guava (Android) | 33.3.1-android | Apache-2.0 | https://github.com/google/guava |
| Guava failureaccess | 1.0.2 | Apache-2.0 | https://github.com/google/guava |
| Guava listenablefuture compatibility artifact | 9999.0-empty-to-avoid-conflict-with-guava | Apache-2.0 | https://github.com/google/guava |
| FindBugs JSR-305 annotations | 3.0.2 | Apache-2.0 | https://github.com/findbugsproject/findbugs |
| Checker Framework qualifiers | 3.43.0 | MIT | https://github.com/typetools/checker-framework |
| J2ObjC annotations | 3.0.0 | Apache-2.0 | https://github.com/google/j2objc |
| PdfBox-Android | 2.0.27.0 | Apache-2.0; see notices | https://github.com/TomRoush/PdfBox-Android |
| Bouncy Castle provider, PKIX and utility libraries | 1.72 | MIT | https://github.com/bcgit/bc-java |
| RE2/J | 1.8 | BSD-3-Clause | https://github.com/google/re2j |
| Silk-Codec-Android native codec and JNI wrapper | upstream JNI distribution | Apache-2.0 | https://github.com/YunJavaPro/Silk-Codec-Android |

The libxposed framework API is a compile-time dependency and is not bundled.
Build tools and test-only libraries are not application dependencies.

License texts and notices: [Apache-2.0](licenses/Apache-2.0.txt),
[jsoup MIT](licenses/jsoup-MIT.txt), [Glide GIF decoder](licenses/glide-gifdecoder.txt),
[smali notices](licenses/smali-NOTICE.txt), [Checker Framework MIT](licenses/checker-qual-MIT.txt),
[PdfBox-Android](licenses/pdfbox-NOTICE.txt), [Bouncy Castle](licenses/bouncycastle-MIT.html),
[RE2/J](licenses/re2j-LICENSE.txt).

DexKit copyright (c) LuckyPray and DexKit contributors. Host feature rules do not
redistribute WeChat bytecode. The Silk Java wrapper retains the upstream JNI
method declarations, with module-specific native-library loading.
Android's optimizer may transform library bytecode. No upstream endorsement is implied.
