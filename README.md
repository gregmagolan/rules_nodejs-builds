# Snapshot build of rules_nodejs

+ DATE                     : Tue  4 Oct 2022 13:35:50 PDT
+ CI                       : false
+ SYSTEM                   : Darwin Kernel Version 21.6.0: Mon Aug 22 20:17:10 PDT 2022; root:xnu-8020.140.49~2/RELEASE_X86_64
+ BUILD_VERSION            : 5.6.0
+ BUILD_BRANCH             : snapshot_builds_stable
+ GIT_SHA                  : b5513f598182c82870ee159d3980eaa662938519
+ GIT_SHORT_SHA            : b5513f598
+ GIT_COMMIT_MSG           : b5513f598 feat: snapshot builds
+ GIT_COMMITTER_USER_NAME  : Greg Magolan
+ GIT_COMMITTER_USER_EMAIL : gmagolan@gmail.com
+ GIT_BRANCH               : snapshot_builds_stable

## build_bazel_rules_nodejs
Add the following to your WORKSPACE to use the build_bazel_rules_nodejs snapshot build:
```python
load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
http_archive(
    name = "build_bazel_rules_nodejs",
    sha256 = "77bf206fd042c4402cb1b0d7f1f72b7cf7055e5d2c48476972affcee43b943e6",
    urls = ["https://github.com/gregmagolan/rules_nodejs-builds/raw/5.6.0+b5513f598/build_bazel_rules_nodejs-snapshot_builds_stable-snapshot.tar.gz"],
)
```

## rules_nodejs
Add the following to your WORKSPACE to use the rules_nodejs snapshot build:
```python
load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
http_archive(
    name = "rules_nodejs",
    sha256 = "48972e4103d4caddb0ac2b50d22cd237f557dee709ee41f00fed7db576556e3a",
    urls = ["https://github.com/gregmagolan/rules_nodejs-builds/raw/5.6.0+b5513f598/rules_nodejs-snapshot_builds_stable-snapshot.tar.gz"],
)
```

## @bazel/concatjs
Add the following to your package.json to use the @bazel/concatjs snapshot build:
```
"@bazel/concatjs": "https://github.com/gregmagolan/rules_nodejs-builds/raw/5.6.0+b5513f598/@bazel_concatjs-snapshot_builds_stable-snapshot.tar.gz"
```

## @bazel/create
Add the following to your package.json to use the @bazel/create snapshot build:
```
"@bazel/create": "https://github.com/gregmagolan/rules_nodejs-builds/raw/5.6.0+b5513f598/@bazel_create-snapshot_builds_stable-snapshot.tar.gz"
```

## @bazel/cypress
Add the following to your package.json to use the @bazel/cypress snapshot build:
```
"@bazel/cypress": "https://github.com/gregmagolan/rules_nodejs-builds/raw/5.6.0+b5513f598/@bazel_cypress-snapshot_builds_stable-snapshot.tar.gz"
```

## @bazel/esbuild
Add the following to your package.json to use the @bazel/esbuild snapshot build:
```
"@bazel/esbuild": "https://github.com/gregmagolan/rules_nodejs-builds/raw/5.6.0+b5513f598/@bazel_esbuild-snapshot_builds_stable-snapshot.tar.gz"
```

## @bazel/jasmine
Add the following to your package.json to use the @bazel/jasmine snapshot build:
```
"@bazel/jasmine": "https://github.com/gregmagolan/rules_nodejs-builds/raw/5.6.0+b5513f598/@bazel_jasmine-snapshot_builds_stable-snapshot.tar.gz"
```

## @bazel/protractor
Add the following to your package.json to use the @bazel/protractor snapshot build:
```
"@bazel/protractor": "https://github.com/gregmagolan/rules_nodejs-builds/raw/5.6.0+b5513f598/@bazel_protractor-snapshot_builds_stable-snapshot.tar.gz"
```

## @bazel/rollup
Add the following to your package.json to use the @bazel/rollup snapshot build:
```
"@bazel/rollup": "https://github.com/gregmagolan/rules_nodejs-builds/raw/5.6.0+b5513f598/@bazel_rollup-snapshot_builds_stable-snapshot.tar.gz"
```

## @bazel/runfiles
Add the following to your package.json to use the @bazel/runfiles snapshot build:
```
"@bazel/runfiles": "https://github.com/gregmagolan/rules_nodejs-builds/raw/5.6.0+b5513f598/@bazel_runfiles-snapshot_builds_stable-snapshot.tar.gz"
```

## @bazel/terser
Add the following to your package.json to use the @bazel/terser snapshot build:
```
"@bazel/terser": "https://github.com/gregmagolan/rules_nodejs-builds/raw/5.6.0+b5513f598/@bazel_terser-snapshot_builds_stable-snapshot.tar.gz"
```

## @bazel/typescript
Add the following to your package.json to use the @bazel/typescript snapshot build:
```
"@bazel/typescript": "https://github.com/gregmagolan/rules_nodejs-builds/raw/5.6.0+b5513f598/@bazel_typescript-snapshot_builds_stable-snapshot.tar.gz"
```

## @bazel/worker
Add the following to your package.json to use the @bazel/worker snapshot build:
```
"@bazel/worker": "https://github.com/gregmagolan/rules_nodejs-builds/raw/5.6.0+b5513f598/@bazel_worker-snapshot_builds_stable-snapshot.tar.gz"
```
