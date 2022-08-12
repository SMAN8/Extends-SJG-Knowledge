# Windows8/10/11 OSでのVirtualBoxのセットアップ `検証済み`

#### 環境

- Windows8/10/11 Home (Intel(R) Core(TM) i5-8250U CPU @ 1.60GHz   1.80 GHz)
- 実装RAM 8.00 GB (7.90 GB 使用可能)
- 64 ビット オペレーティング システム、x64 ベース プロセッサ

#### ダウンロード/インストール
- Ubuntu Desktop 20.04.4 LTS
- VirtualBox-6.1.36
---
## 1- VirtualBoxのダウンロード

1. VirtualBoxのダウンロードサイトにアクセスし、`VirtualBox 6.1.36 platform packages`の`Windows hosts`をタップしダウンロードする。
 - [VirtualBoxの入手](https://www.virtualbox.org/wiki/Downloads)

## 2- VirtualBoxのインストール

2-1.ダウンロードしたvirtualbox6.1.36のインストーラをダブルクリックで起動する。
| ファイル名 | VirtualBox-6.1.36-152435-Win.exe |
:---|:---

![1virtualbox](https://user-images.githubusercontent.com/80440848/184325406-c8453b6f-0912-467f-bad3-f0b2466066f3.png)

2-2.ダウンロードが完了したら、左下の赤い四角のインストーラーをタップして起動する。

![2 virtualbox_setup](https://user-images.githubusercontent.com/80440848/184338728-9a1a783f-6ee5-4c8e-a5b2-9ccec5e1dbf0.PNG)

2-3.この画面になったら、`Next>`をタップ。

![3 virtualbox_setup](https://user-images.githubusercontent.com/80440848/184339305-fc9e9dab-6314-46a7-afc7-630209297b1f.PNG)

2-4.続けてそのまま`Next>`をタップし、下の画面になったら`Install`をタップする。

![7 virtualbox_setup](https://user-images.githubusercontent.com/80440848/184339928-0b689ef2-4bb2-4c23-b2f4-151a4f2e44ce.PNG)

2-5.Windowsセキュリティが作動し、デバイスのソフトウェアをインストールしますか？と聞かれたら`インストール(I)`をタップし、下の画像の赤い四角で囲まれた`Finish`をタップする。

![10 virtualbox_setup](https://user-images.githubusercontent.com/80440848/184340436-fca6347b-ff73-4d00-8593-033da52aad5e.PNG)

2-6.VirtualBoxの管理画面が立ち上がり、インストールが完了しました。

![15](https://user-images.githubusercontent.com/80440848/184341211-b58971af-5abc-4d32-8d44-788810e07f2b.PNG)

## 3- Ubuntu OSのインストール

3-1.下の画像の赤い四角のところをタップしてダウンロードします。

- [Ubuntu20.04.4 LTSの入手](https://releases.ubuntu.com/20.04.4/?_ga=2.145106481.424434523.1659109603-1752942665.1659109603)

![2-1](https://user-images.githubusercontent.com/80440848/184349563-06b3ad6d-5295-4225-bd7f-6cc880e3d174.png)

3-2.ダウンロードしたubuntu-20.04.4-desktop-amd64を作成したフォルダ(ここではTest_CNodeというフォルダ)に移動しておく。

![4-Ubuntu_download](https://user-images.githubusercontent.com/80440848/184369093-df29585b-bb75-44c4-a3e6-fb411046b7da.PNG)

## 4- 仮想マシンの作成

4-1.マシンを作成する為に下の画像の赤い四角の`新規(N)`をタップする。

![15](https://user-images.githubusercontent.com/80440848/184372736-01258bc7-1d91-441d-9551-1945dac351d9.PNG)

4-2.名前とオペレーティングシステムの画面になったら、①マシンの名前、②マシンのフォルダー指定、③Linux、④Linux(64bit)を選択する。

![VirtualMashine-1](https://user-images.githubusercontent.com/80440848/184377673-e74f5eec-4398-4c26-903f-fe08dc551ec0.PNG)



