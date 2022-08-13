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

## 3- Ubuntu OSのイメージディスクのダウンロード

3-1.下の画像の赤い四角のところをタップしてダウンロードします。

- [Ubuntu20.04.4 LTSの入手](https://releases.ubuntu.com/20.04.4/?_ga=2.145106481.424434523.1659109603-1752942665.1659109603)

![2-1](https://user-images.githubusercontent.com/80440848/184349563-06b3ad6d-5295-4225-bd7f-6cc880e3d174.png)

3-2.ダウンロードしたubuntu-20.04.4-desktop-amd64を作成したフォルダ(ここではTest_CNodeというフォルダ)に移動しておく。

![4-Ubuntu_download](https://user-images.githubusercontent.com/80440848/184369093-df29585b-bb75-44c4-a3e6-fb411046b7da.PNG)

## 4- 仮想マシンの作成

4-1.マシンを作成する為に下の画像の赤い四角の`新規(N)`をタップする。

![15](https://user-images.githubusercontent.com/80440848/184372736-01258bc7-1d91-441d-9551-1945dac351d9.PNG)

4-2.名前とオペレーティングシステムの画面になったら、①マシンの名前、②マシンのフォルダーパス指定、③Linux、④Linux(64bit)を選択する。

![VirtualMashine-1](https://user-images.githubusercontent.com/80440848/184377673-e74f5eec-4398-4c26-903f-fe08dc551ec0.PNG)

4-3.メモリサイズは、4GB(4000MB)に変更する。

![VirtualMashine-2](https://user-images.githubusercontent.com/80440848/184456824-af083067-728d-499a-ac2a-7d2129fbc9c9.png)

4-4.下の画像の状態で「仮想ハードディスクを作成する(C)」を選択した状態のまま下の`作成`をタップ。

![VirtualMashine-3](https://user-images.githubusercontent.com/80440848/184457064-512963cb-5144-4dff-92c7-b5c20c9460f5.png)

4-5.「VDI(VirtualBox Disc Image)」の状態のまま、`次へ(N)`をタップ。

![VirtualMashine-4](https://user-images.githubusercontent.com/80440848/184457609-bbbb30ca-8532-4dfc-88e3-68e461c8c14c.png)

4-6.「可変サイズ(D)」の状態のまま`次へ(N)`をタップ。

![VirtualMashine-5](https://user-images.githubusercontent.com/80440848/184457983-b7fd39f8-b760-4d67-8e14-5f65cc0183e0.png)

4-7.ハードディスクのサイズを50GBに変更し`作成`をタップ。

![VirtualMashine-6](https://user-images.githubusercontent.com/80440848/184458184-e63329cc-4265-4fd5-a6b0-85fbcb2507b7.png)

4-8.おめでとうございます！仮想マシンが作成されました。

![VirtualMashine-7](https://user-images.githubusercontent.com/80440848/184459602-b88ad8ae-7a94-41e2-bb40-4a44aac4f238.PNG)

## 5- VirtualBoxの環境設定

5-1.VirtualBoxが終了している状態から、下の画像の四角をダブルクリックして、VirtualBoxを起動する。

![Setting_Mashine-1](https://user-images.githubusercontent.com/80440848/184461165-f5690181-46ac-4501-beb6-9d91f2bab20a.PNG)

5-2.ファイル > `環境設定(P)...`をタップ。

![Setting_Mashine-2](https://user-images.githubusercontent.com/80440848/184461509-39b2f551-7094-40ab-acda-c54d90d52e9f.PNG)

5-3.一般 > デフォルトの仮想マシンフォルダー(M)の 下の画像の赤い四角をタップし`その他`を選択。

![Setting_Mashine-3](https://user-images.githubusercontent.com/80440848/184462645-502725ab-e9f8-4413-89cc-c92d74fa983a.PNG)

5-4.仮想マシンの関連ファイル等の置き場所を決める為、フォルダ(ここではTest_CNodeフォルダ)を選択し、`OK`をタップし環境設定を完了する。

![Setting_Mashine-4](https://user-images.githubusercontent.com/80440848/184462980-4acdccd3-214f-4771-9336-35e0e1b97733.PNG)

## 6- 仮想マシンの環境設定

6-1.対象の仮想マシンを選択したまま、赤い四角の線に囲まれた`設定`をタップ。

![Setting_Mashine-1](https://user-images.githubusercontent.com/80440848/184465981-d70cd0cb-a06f-4d53-87a0-63f2369da05f.PNG)

6-2.一般 > 高度(A)へと移動し、クリップボードの共有とドラック&ドロップを`無効`から`双方向`へ変更する。

![Setting_Mashine-2](https://user-images.githubusercontent.com/80440848/184466214-f00c4119-04f6-4beb-b9c1-5a9946e16c5c.PNG)

6-3.次に、システム > マザーボード(M)へ移動し、起動順序の`フロッピー`のチェックマークを外し、`ネットワーク`にチェックマークを入れる。その他は、デフォルトのままで良い。

![Setting_Mashine-3](https://user-images.githubusercontent.com/80440848/184466552-1c02f7f2-cf4e-4b4f-b0c5-70a6f1a2bc14.PNG)

6-4.システム > プロセッサー(P)に移動し、プロセッサー数(P)を`2`に変更する。

![Setting_Mashine-4](https://user-images.githubusercontent.com/80440848/184466800-bcc15b4f-fa88-4319-b601-83ae5b690f28.PNG)

6-5.ストレージに移動し、赤い四角の`空`を選択したまま、右の赤い四角のディスクのようなマークが表示されるので、そのディスクマークをタップする。

![Setting_Mashine5](https://user-images.githubusercontent.com/80440848/184466892-c17b8f39-5255-4ec4-a2f9-644ddac9c1e2.png)

6-6.ディスクマークをタップしたら、`ディスクファイルを選択...`を選択。

![Setting_Mashine-6](https://user-images.githubusercontent.com/80440848/184467440-65ab8f20-a3b5-4260-a445-4741770447d8.PNG)

6-7.3-2で移動したフォルダを選択して、Ubuntu-20.04.4-desktop-amd64を選択する。

![Setting_Mashine-7](https://user-images.githubusercontent.com/80440848/184467480-91534242-b20c-4485-beca-7481caf1ab53.PNG)

![Setting_Mashine-8](https://user-images.githubusercontent.com/80440848/184467707-ad80d336-138c-441b-a720-902b2a26bfdb.PNG)

6-8.ネットワークのアダプター1の`ネットワークアダプターを有効化(E)`にチェックを入れておく。**※全てのセッティングが終わった後、セキュリティを堅牢にする為、チェックマークを外したままKESの更新作業等を行う。**

![Setting_Mashine-9](https://user-images.githubusercontent.com/80440848/184467931-80da9d62-98d0-4e6b-b336-d76e1957f307.png)


