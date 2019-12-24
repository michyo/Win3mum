About
=====

Win3mum is a fork of Win3mu by michyo (Michiyo Tagami).
Win3mu is a free software originally by Topten Software.

This is a  Windows 3.0 emulator.
It includes an 8086 CPU emulation that loads 16-bit Windows executables and maps API calls onto the modern 32 or 64-bit Windows API.

Compilation
===========

Requires Visual Studio 2019 and .NET 4.7.2.

Usage
=====

win3mu <programName> [/debug|/release] [/break] [/config:name]

for Japanese
============

Win3muはTopten Softwareにより開発されたオープンソースのWindows 3エミュレーターです。
CPUエミュレーションを内包し、16ビットのWindows実行ファイルを32/64ビットのAPIにマップして呼び出します。

現時点で伝わりやすいように、語弊を恐れずに簡単に言うと、Windows 3.1のソフトウェアをWindows 10で動くように変換することができます。

このツールに16ビットのWindows実行ファイルを渡すと、元の実行ファイルはリネームされ、オリジナルと同じ名前とアイコンを持った新たな実行ファイルが作成されます。
この実行ファイルは、通常のWindowsアプリケーションと同様に実行することができます。

オリジナルのWin3muは Visual Studio 2017／.NET 4.6.1 で作られており、ソースプロジェクトに必要なオープンソースが含まれておらず、ビルドできるまでに手間がかかりました。
ですので、私(みっちょ)が、2019年12月24日時点で最新であるVisual Studio 2019／.NET 4.7.2の環境で単純にビルドできるように整えたものが、このWin3mumです。

Original links
==============

[Topten Software Win3mu](https://www.toptensoftware.com/win3mu/)  
[Technical details](https://hackernoon.com/win3mu-part-1-why-im-writing-a-16-bit-windows-emulator-2eae946c935d)  
[Sharp86](https://bitbucket.org/toptensoftware/sharp86)  
[PetaJson](https://github.com/toptensoftware/JsonKit/tree/classic)  
[ConFrames](https://bitbucket.org/toptensoftware/conframes)  
