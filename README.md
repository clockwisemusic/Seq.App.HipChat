# Seq.App.HipChat

An app for Seq (http://getseq.net) that forwards messages to HipChat.

## Changes

### 1.1.3
- Added support for proxy server

### 1.1.2
- Merged in ([default0](https://github.com/default0/Seq.App.HipChat/commit/b3f524e9dfd3fac9f076a6486923db6b4ed4f612)) support for message templates

### 1.1.1
- ([#7](https://github.com/stayhard/Seq.App.HipChat/pull/7)) Support latest HipChat server (thanks [bratfizyk](https://github.com/bratfizyk) and [nblumhardt](https://github.com/nblumhardt))

### 1.1.0

- ([#2](https://github.com/stayhard/Seq.App.HipChat/pull/2)) Option for setting custom HipChat install base URL (thanks [ciwchris](https://github.com/ciwchris))
- ([#5](https://github.com/stayhard/Seq.App.HipChat/pull/5)) Links to Seq from HipChat messages are now compatible with Seq v2 (thanks [jerbri](https://github.com/jerbri))

## Building NuGet Package

From solution root, run:

- msbuild
- nuget pack ./Seq.App.HipChat/Seq.App.HipChat.nuspec