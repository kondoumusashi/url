# [参考資料](https://taiko.bui.pm/)

* 目次
    1. [DirectX11](#1_)
    2. [DirectX12](#2_)
    3. [Vulkan](#3_)
    4. [Shader](#4_)
    5. [その他](#5_)
    6. [Youtube channel](#6_)

## <span style="color:#334488;">1. DirectX11</span><a name="1_"></a>

#### [～プログラミング～ DirectX 11を始めよう](https://araramistudio.jimdo.com/2017/06/06/%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9F%E3%83%B3%E3%82%B0-directx-11%E3%82%92%E5%A7%8B%E3%82%81%E3%82%88%E3%81%86/)
>C++言語でDirectX 11を使ったアプリケーションを開発してみましょう。
DirectX 9の時との比較をしながらDirectX 11でのアプリケーションの作り方をまとめてみようと思います。

#### [◇DirectX11プログラミング](https://yun.cup.com/directx11.html)
>ブログで記載した際には『立体視プログラミング』として行なっています
ディスプレイが購入できなくて立体視のところは頓挫していますが……
その中で，DirectX11関連のものをまとめました

## <span style="color:#334488;">2. DirectX12</span><a name="2_"></a>

#### [Learning DirectX 12 – Lesson 1 – Initialize DirectX 12](https://www.3dgep.com/learning-directx-12-1/)
>これは、DirectX12アプリケーションを最初から作成する方法を教える一連のレッスンの最初のレッスンです。
このレッスンでは、使用可能なDirectX 12対応のディスプレイアダプターを照会する方法、DirectX 12デバイスを作成する方法、スワップチェーンを作成する方法、およびスワップチェーンのバックバッファーを画面に表示する方法についても学習します。
コマンドキューとコマンドリストを作成し、Nバッファーレンダリングを正しく実装するためにCPUとGPUの操作を同期する方法も学習します。

#### [Learning DirectX 12 – Lesson 2 – Rendering](https://www.3dgep.com/learning-directx-12-1/)
>これは、DirectX12を利用したアプリケーションを最初から作成する方法を教える一連のレッスンの2番目のレッスンです。
このレッスンでは、頂点とインデックスのデータをグラフィックスプロセッシングユニット（GPU）にアップロードしてレンダリングします。
基本的な頂点シェーダーとピクセルシェーダーについて説明し、それらのシェーダーを利用するパイプライン状態オブジェクト（PSO）を作成する方法についても説明します。
ルート署名は、レンダリングパイプラインのステージで使用されるパラメーターを定義します。
このレッスンでは、シーン内のモデルを回転させるために使用されるModel-View-Projection（MVP）マトリックスを含む単一の定数バッファーを定義する単純なルートシグネチャが作成されます。

## <span style="color:#334488;">3. Vulkan</span><a name="3_"></a>

#### [Vulkan Tutorial](https://vulkan-tutorial.com/Introduction)
>このチュートリアルでは、VulkanグラフィックスとコンピューティングAPIの使用の基本について説明します。
Vulkanは、Khronosグループ（OpenGLで知られる）による新しいAPIであり、最新のグラフィックカードのより優れた抽象化を提供します。
この新しいインターフェイスを使用すると、アプリケーションの目的をより適切に説明できます。
これにより、OpenGLやDirect3Dなどの既存のAPIと比較して、パフォーマンスが向上し、ドライバーの動作が驚くほど少なくなります。 
Vulkanの背後にある考え方は、Direct3D 12やMetalの考え方と似ていますが、Vulkanには完全にクロスプラットフォームであるという利点があり、Windows、Linux、Android向けに同時に開発できます。

## <span style="color:#334488;">4. Shader</span><a name="4_"></a>

#### [川瀬式グレアエフェクトを勉強する(1) PROJECT ASURA](http://project-asura.com/program/d3d11/d3d11_010.html)
>この記事はGraphics Advent Calendar 2017の17日目の記事です。
会社でポストエフェクトを担当することになりました。ポストエフェクトといえば，川瀬さんが超絶有名です。
そんなわけで，川瀬さんが公開している資料からグレアエフェクトについて学んでみようと思います。
今回は川瀬式グレアエフェクトの中から，ブルームとスターを実装する要素技術について勉強してみます。

#### [川瀬式グレアエフェクトを勉強する(2) PROJECT ASURA](http://project-asura.com/program/d3d11/d3d11_011.html)
>この記事はGraphics Advent Calendar 2017の23日目の記事です。
前回に引き続き川瀬式グレアエフェクトを勉強してみようと思います。
今回は，レンズゴーストを実装してみます。 

#### [CEDEC事前インタビュー：実は理論より見た目？　世界的レンダリスト川瀬氏が目指す光学処理とは](https://www.4gamer.net/games/105/G010549/20100830009/)
>シリコンスタジオといえば，CG界では名高いシリコングラフィックスの流れを汲むゲーム関連会社で，ゲーム制作というよりは関連ミドルウェアなどを開発しているところである。
同時に，日本のトップレンダリストが集まるところとしても知られている。
今回は，そのなかでも世界的に評価の高いレンダリスト川瀬正樹氏に，氏が最近のCEDECで中心的な話題としている，リアルなカメラの効果を出すエフェクトはどこから生まれてきたのか，最近のゲームグラフィックスの動向などについていろいろ聞いてみた。

## <span style="color:#334488;">5. その他</span><a name="5_"></a>

#### [プログラムを高速化する話](https://www.slideshare.net/KMC_JP/ss-45855264)
>プログラムを高速化するためのテクニックをまとめました。京大 マイコンクラブ

#### [プログラムを高速化する話Ⅱ 〜GPGPU編〜 ](https://www.slideshare.net/KMC_JP/gpgpu-91122680)
>GPUを利用して汎用演算を行う技術であるGPGPUを用いて、プログラムを高速化する技法についてまとめました。
高速化の具体例も適宜用いて解説しています。 

#### [基礎線形代数講座 SEGA TECH BLOG](https://techblog.sega.jp/entry/2021/06/15/100000) - [スライドシェア](https://www.slideshare.net/SEGADevTech/ss-249343092) 
>みなさん、はじめまして。技術本部　開発技術部のYです。
ひさびさの技術ブログ記事ですが、タイトルからお察しの通り、今回は数学のお話です。
＃数学かよ　って思った方、ごめんなさい（苦笑）

## <span style="color:#334488;">6. Youtube channel</span><a name="6_"></a>

#### [CEDECチャンネルYouTube版](https://www.youtube.com/channel/UCmHaPXvwn9_4pMNAV6ewgoA)

#### [GAME CREATORS CONFERENCE](https://www.youtube.com/channel/UC09h5BXuH8d-biTMzDcj0Rg/featured)

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

---

##### [星のカービィ全話](https://www.youtube.com/playlist?list=PL3dEBp1M8Ury5o1tOjab06vymI4ZJnRop)
##### [みっちりねこマーチ](https://www.youtube.com/watch?v=lAIGb1lfpBw)
##### [Slideshare Downloader](https://slidesharedownloader.ngelmat.net/)
##### [ 日曜劇場「DCU」New！2022年1月スタート](http://abehiroshi.la.coocan.jp/)