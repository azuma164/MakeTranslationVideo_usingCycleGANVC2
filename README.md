# CycleGAN-VC2, Make it Talk, ESPnet2-ASRを用いた翻訳動画生成
- こちらは、東京大学工学部電気電子工学科・電子情報工学科の後期実験のうちの一つ「人工知能演習」の成果物です
- 我々は今回、同一話者による翻訳動画生成というテーマに取り組みました
- 詳しい内容は[こちらのスライド](https://docs.google.com/presentation/d/19x3D4mF2lnlS_hGi-JnrOCVlNS9QgH8cxBwck3ulSCs/edit?usp=sharing)に書いてあります. demoもスライド上で見ることができます
- 中身はgoogle colaboratory上で簡単に試すことができます

## what we did

input : obama's English voice(wav file) output : obama's Japanese voice and movie(mp4)

This colab file is made in an experiment of our university. We used ESPnet2-ASR to recognize sound, CycleGAN-VC2 to convert Japanese API voice to Obama's Japanese voice, and make it talk to make Obama's Talking-Head animation.

## references
- https://github.com/jackaduma/CycleGAN-VC2
- https://github.com/yzhou359/MakeItTalk
- https://github.com/espnet/espnet

We used above repositories. We really appreciate them!!
