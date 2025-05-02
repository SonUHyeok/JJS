---
Genre: Game
TEAM: 전지적 졸업 시점
Authors:
  - 백선희
  - 손우혁
  - 황애라
Affiliations:
  - Soongsil University
Figma: "https://www.figma.com/design/N2aT2N3sOJcUOOFSsCDPEZ/%EB%94%94%EC%9E%90%EC%9D%B8?node-id=779-232&t=xaIZoRMNblZIWJmT-1"
---

<body>
  <hr>
  <img src = "images/1.png" alt = "Example 001" style="display: block; margin: auto;">
</body>


<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
  <div class="column is-four-fifths">
    <h2>기획 의도</h2>
    <div class="content has-text-justified">
      2034년, 핵전쟁의 불길이 서울을 삼켰습니다. 폐허가 된 여의도. 살아남은 인간들은 방사능을 피해, 안드로이드들의 힘을 빌려 지하 깊숙이 '쉘터'라 불리는 거대 도시를 구축했습니다. 그로부터 오랜 시간이 흐른 어느 날, 한 안드로이드가 눈을 뜹니다. 기억이라고는 자신을 애타게 부르던 소녀의 모습 뿐. 소녀를 찾아 헤매는 여정이 시작됩니다. 이 모험의 끝에 당신은 어떤 진실과 마주하게 될까요? 텍스트 어드벤처와 도트 그래픽 전투가 어우러진, 선택에 따라 운명이 달라지는 모바일 멀티엔딩 게임. METRO:BOT — 지금 바로 플레이하세요. (QR코드 스캔 / 안드로이드용 / 네트워크 연결 필요)
    </div>
  </div>
</div>


<!-- Dataset Download Buttons -->

## SIDL Dataset 
We provide 80% of the scenes for training and learning. The remaining scenes are used for online evaluation.
### Patchify images (512x512)
For efficient training and learning, we provide patchified images. 
<div class="buttons" style="text-align: center; margin-top: 1em;">
  <a class="button is-primary" href="https://drive.google.com/file/d/1es3rPo5Y9O96EjDVXanUY8NpaRprWH-h/view?usp=sharing" target="_blank">Train</a>
  <a class="button is-primary" href="https://drive.google.com/file/d/1u5-MDauO3XolXsU6eOARwlXo7SnpLwqA/view?usp=sharing" target="_blank">Validation</a>
  <a class="button is-primary" href="https://drive.google.com/file/d/1-SFyyjH0G3C68OfDjZ_O7M4mOqkcJdEf/view?usp=sharing" target="_blank">Test</a>
</div>

### Full-resolution images (4032x3024)
<div class="buttons" style="text-align: center; margin-top: 1em;">
  <a class="button is-primary" href="https://drive.google.com/file/d/1s_gUw1DCqokihl3YtO3lu9_GnLZaSElI/view?usp=sharing" target="_blank">Train</a>
  <a class="button is-primary" href="https://drive.google.com/file/d/1OHxG8Jh0goKIhkJTe9NXZ6uIuD5qVaNH/view?usp=sharing" target="_blank">Validation</a>
</div>

### RAW files
We also provide RAW image files (DNG) along with metadata.
<div class="buttons" style="text-align: center; margin-top: 1em;">
  <a class="button is-primary" href="https://drive.google.com/file/d/1k78IIsUl2eYPnPvWkBampU0qlMrW4F-u/view?usp=sharing" target="_blank">DNG images</a>
  <a class="button is-primary" href="https://drive.google.com/file/d/1lAab5F3jjCByY4OEvGSAfykyAqp2wfTi/view?usp=sharing" target="_blank">Metadata</a>
</div>

### Online Evaluation  
<div class="buttons" style="text-align: center; margin-top: 1em;">
  <a class="button is-primary" href="http://203.253.25.170:8080" target="_blank">Click here to launch evaluation</a>
</div>  
Click the button above to evaluate your model on the SIDL benchmark.


### ISP pipeline
Coming soon


### Citation
<pre><code class="language-bibtex">
@inproceedings{choi2025sidl,
  title     = {SIDL: A Real-World Dataset for Restoring Smartphone Images with Dirty Lenses},
  author    = {Choi, Sooyoung and Park, Sungyong and Kim, Heewon},
  booktitle = {Proceedings of the AAAI Conference on Artificial Intelligence},
  volume    = {39},
  number    = {3},
  pages     = {2545--2554},
  year      = {2025}
}
</code></pre>

