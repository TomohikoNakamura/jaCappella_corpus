{% include youtube-embed.html video_url="https://www.youtube.com/embed/RnhTfLkIsxk?si=SXNInuJ4hDLKIonH" ratio="16/9" %}

# jaCappella corpus / jaCappellaコーパス
The *jaCappella* corpus is a corpus of Japanese a cappella vocal ensembles.
It consists of 50 copyright-cleared vocal ensemble songs and their audio recordings of individual voice parts. (Note that the jaCappella corpus team reserves all copyrights and neighboring rights of the vocal ensemble songs.)
These songs were arranged from out-of-copyright Japanese children's songs.
All songs have six voice parts (lead vocal, soprano, alto, tenor, bass, and vocal percussion).
They are divided into 10 subsets (jazz, punk rock, bossa nova, popular, reggae, enka, neutral, ballad, edm, and soulfunk), each of which features typical characteristics of a music genre.

*jaCappella*コーパスは，日本語のアカペラ重唱曲のコーパスです．
本コーパスは，50曲の著作権処理済みアカペラ重唱曲と各声部の単独歌唱音源からなります．（jaCappellaコーパスチームは，作成した重唱曲に関する全ての著作権と著作隣接権を保有しています．）
これらの重唱曲は，著作権保護期間の終了した童謡・唱歌から編曲して作成されています．
声部は，lead vocal，soprano，alto，tenor，bass，vocal percussionの6つです．
本コーパスは，10個のサブセット（jazz, punk rock, bossa nova, popular, reggae, enka, neutral, ballad, edm, and soulfunk）からなり，それぞれ対応するジャンルの典型的な特徴を備えた曲群からなります．

## Audio files of singing voices / 歌唱音源ファイル
The singing voices were recorded in a recording studio.
The sampling frequency is 48 kHz and the audio file is provided in a monaural WAVE format.
All singers are native Japanese speakers.

歌唱音源は曲・声部毎にレコーディングスタジオで収録されたものであり，サンプリング周波数は48 kHz，モノラル形式のWAVEファイルとして保存されています．
歌唱者は全て日本語母語話者です．

## Musical score / 譜面
The musical scores with Japanese lyrics are provided in the PDF and MusicXML formats.
This dataset contains MusicXML files whose lyrics were modifed for singing voice synthesis (e.g. "は"->"わ", "へ"->"え").
For non-Japanese researchers, MusicXML files with Romaji transcriptions of lyrics are provided.

**Remark**: Romaji transcription does not exactly match Japanese pronunciation. For the exact Japanese pronounciation, please refer to the singing voices.


譜面は，PDFおよびMusicXML形式で配布されます．
また，歌声合成用に歌詞を発音表記に変換したMusicXMLファイル（e.g., 「は」->「わ」，「へ」->「え」），非日本語話者用に歌詞をヘボン式ローマ字で表記したMusicXMLファイルも同梱しています．

**注意点**：ヘボン式ローマ字表記の歌詞は日本語の発音とは完全に一致するわけではありません．正確な日本語の発音に関しては，歌声を参考にして下さい．

## Metadata / メタデータ
Metadata of the songs are given as a csv file.
The items in the csv file are as follows.
- title_in_en: Title in Hepburnian Roman alphabet
- title_in_ja: Title in Japanese
- lyric_writer: Lyric writer name of the original song in Japanese
- copyright_of_lyric_writer: Copyright of the lyric writer of the original song
- composer: Composer name of the original song in Japanese
- copyright_of_composer: Copyright of the composer of the original song
- arranger_in_en：Arranger name of the song of our corpus in English
- arranger_in_ja：Arranger name of the song of our corpus in Japanese
- subset：Subset name
- voice_part：Voice part name
- singer_id: Singer identifier (ID)
- gender: Singer's gender
- first_lang: First language of singer

原曲の情報や歌唱者のID・性別などは，csvファイルにメタデータとしてまとめられています．
csvファイルの項目は以下の通りです．
- title_in_en: ヘボン式ローマ字での曲名
- title_in_ja：日本語での曲名
- lyric_writer：原曲の作詞者
- copyright_of_lyric_writer：原曲の作詞者の著作権
- composer：原曲の作曲者
- copyright_of_composer：原曲の作曲者の著作権
- arranger_in_en：本コーパスの当該楽曲の編曲者（英語名表記）
- arranger_in_ja：本コーパスの当該楽曲の編曲者（日本語名表記）
- subset：サブセット名
- singing_part：声部
- singer_id：歌唱者ID
- gender：歌唱者の性別
- first_lang：歌唱者の母語

# Terms of Use / 利用規約
## English version
- You may not use any of the data contained in the jaCappella (hereafter, the material) for commercial purposes.
- You may not copy or redistribute the material in any medium or format. Exceptionally, you are allowed to publish a small portion of the corpus (e.g., a few phrases from around 5 songs) to demonstrate the results of your research and development on your web pages.
- You must give appropriate credit and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- If you remix, transform, or build upon the material, you may not distribute the modified material. The distribution of modified material are exceptionally allowed only to the extent necessary for research purposes. Possible use cases are as follows.
  - Research at academic institutions
  - Research for non-commercial purposes (including research by commercial organizations)
  - Personal use (including blogs, etc.)
- Any use that will violate public order and standards of decency are prohibited.
- Use by antisocial forces (groups or individuals who pursue economic benefits through the use of violence, force, and fraudulent methods) is prohibited.

## 日本語版
- jaCappellaコーパスに含まれる全データ（以下，本データと呼ぶ）は，現在商用目的では利用できません．
- 本データの再配布や複製は，いかなるメディアやフォーマットでも禁止です．例外的に，あなたのウェブページで研究・開発結果のデモンストレーションを目的としたコーパスの一部公開（例えば，5曲程度の数フレーズ）は可能です．
- あなたは適切なクレジットを表示し，変更があったらその旨を示さなければなりません。これらは合理的であればどのような方法で行っても構いませんが，許諾者があなたやあなたの利用行為を支持していると示唆するような方法は除きます。
- あなたが本データをリミックスし，改変し，あるいは本データをベースに新しい作品を作った場合，あなたは改変された資料を頒布してはなりません。例外的に，研究に必要な程度の改変であれば，改変されたデータを頒布することは可能です．想定される利用例は以下です．
  - 学術研究機関機関での研究
  - 非商用目的での研究（営利団体での研究も含む）
  - 個人での利用（ブログなどを含む）
- 公序良俗に反する利用は認められていません．
- 反社会的勢力（暴力、威力と詐欺的手法を駆使して経済的利益を追求する集団又は個人をいう）の使用を禁じます．

## For commercial Use / 商用利用に関して
We welcome commercial use of this corpus. The commercial use is chargeable and please feel free to contact the following members for your commercial use.

このコーパスの商用利用を歓迎します．商用利用は有料となりますので，下記のメールアドレスまでお気軽にご連絡ください．  

jacappella-group [at] g.ecc.u-tokyo.ac.jp

# Download / ダウンロード
You can download [here]({{ site.download_url }}).

[ここ]({{ site.download_url }})からダウンロードできます．

# Update logs
- Feb. 2024: Data distribution on huggingface datasets started.
- Dec. 2023: v.2.0.1
  - Fixed bug: Modified `bass.wav` and `vocal_percussion.wav` of `yurikagonouta` in the soul/funk subset
- Dec. 2023: v2
  - Added sheet music and audio recordings of 15 songs (ballad, EDM, and soul/funk)
- Feb. 2023: v1.1
  - Some accidental marks modified in accordance with harmony.
  - Added MusicXML files for singing voice synthesis
  - Added MusicXML files with Romaji transcriptions of lyrics

- 2024/2: huggingface datasets上でのデータ配布を開始
- 2023/12：v.2.0.1配布
  - Soul/funkサブセットの揺籃のうたに関して，`bass.wav`と`vocal_percussion.wav`が入れ替わっていた問題を修正
- 2023/12：v2.0配布
  - 15曲（ballad，EDM，soul/funk）の譜面，歌唱音源を追加
- 2023/2：v1.1配布
  - 和声に合わせて臨時記号を修正
  - 歌声合成用MusicXMLファイルを追加
  - ヘボン式ローマ字表記歌詞のMusicXMLファイルを追加

# Example applications
- [Vocal ensemble separation / 重唱分離](https://tomohikonakamura.github.io/Tomohiko-Nakamura/demo/jaCappella_sep/), [code](https://github.com/TomohikoNakamura/asteroid_jaCappella/tree/jaCappella/egs/jaCappella)

# Contributors (The jaCappella corpus team)
- [Tomohiko Nakamura / 中村友彦](https://tomohikonakamura.github.io/Tomohiko-Nakamura/)
- [Shinnosuke Takamichi / 高道 慎之介](https://sites.google.com/site/shinnosuketakamichi/home) (The University of Tokyo / 東京大学)
- Naoko Tanji / 丹治 尚子 (The University of Tokyo / 東京大学)
- Hiroshi Saruwatari / 猿渡 洋 (The University of Tokyo / 東京大学)

# Citation / 引用
If you use the jaCappella corpus, please cite [the following paper]({{ site.paper_url }}).

jaCappellaコーパスを利用する際は，[以下の論文]({{ site.paper_url }})を引用してください．

```
@inproceedings{TNakamura202306ICASSP,
    author={Nakamura, Tomohiko and Takamichi, Shinnosuke and Tanji, Naoko and Fukayama, Satoru and Saruwatari, Hiroshi},
    title={jaCappella corpus: A Japanese a cappella vocal ensemble corpus},
    booktitle = ICASSP,
    month     = jun,
    year      = 2023,
    url_arXiv = {https://arxiv.org/abs/2211.16028},
    url_Demo  = {demo/jaCappella_sep},
    url_Code  = {https://github.com/TomohikoNakamura/asteroid_jaCappella},
    doi       = {10.1109/ICASSP49357.2023.10095569},
    lang      = {en}
}
```

# Links / リンク
- [Saruwatari Takamichi Lab.](https://www.sp.ipc.i.u-tokyo.ac.jp/)

# Acknowledgement / 謝辞
The jaCappella corpus team reserves all copyrights and neighboring rights of the vocal ensemble songs.
The music arrangement and sound production were performed by Alpha Enterprises, Inc.

jaCappellaコーパスチームは，作成した重唱曲に関する全ての著作権と著作隣接権を保有しています．
譜面，音源制作は，株式会社アルファエンタープライズが行いました．