# 闇音レンリ_DiffSinger

Readme translate by ChatGPT-4

VBのダウンロード：[こちら](github_release)

### <font color=yellow>ご注意ください：</font>

現在リリースされている声库はテストバージョンです。公式バージョンはOpenVpiがマルチ辞書を更新した後に更新されます。

VBの変換trainingと配布は、闇音レンリの代表者である[yuzuri_柚子莉](https://space.bilibili.com/328087514)からの許可を得ています。

---

## 闇音レンリ - 基本情報

（[萌娘百科_闇音レンリ](https://mzh.moegirl.org.cn/%E6%9A%97%E9%9F%B3Renri)からコピーしました）

- 本名：闇音レンリ
  
- キャラクターデザイン：kgr
  
- 別名：Yamine Renri、闇音、レンリ、連理、暗音renri、暗音連理、暗音蓮理、暗音蓮莉など
  
- 年齢：17歳
  
- 身長：158cm
  
- 体重：45kg
  
- 誕生日：9月28日
  
- 外見：ふわふわのピンクの長い髪、二つのアホ毛、ターコイズブルーの瞳。
  
- 中の人：yuzuri
  
- 好きなもの：月、星、装飾やレースの多い服。

---

## DiffSinger VBの紹介

<font color=yellow>（テストバージョン 20240310）</font>

Phoneme Scheme：Multi-langs

データソース：闇音レンリ・連続音Ver1.5——Normal

データ期間：48分

言語構成：三音節・二音節中国語（cross-language）+日本語（native）+英語（cross-language）+二音節広東語（cross-language）

音色構成：Normal

labeling＆training：旋转_turning_point

VBのサポートパラメータ：GENC、VELC

VB hop size：256（Kouon_RefineGAN Vocoderに対応）、512（OpenVpi NSF-HiFiGAN VocoderおよびFish NSF-HiFiGAN Vocoderに対応）

Supported Phonemizers：DIFF RHY、他城pによるMultispeakerV6 Phonemizer、XMTech Chinese TRI Phonemizer

Special thanks：yuzuri、久嘉、Akatsuki、可米斯圣
