# speaker
working space for speaker



### First group

1. Geometry-agnostic multi-channel personalized speech enhancement (多通道特定人物語音強化)
  * 學長論文：[用於智慧家庭助理與任意陣列配置之多通道個人語音活性偵測與音質提升系統](https://etd.lib.nctu.edu.tw/cgi-bin/gs32/gsweb.cgi/ccd=NzyIzu/record)

2. AI beamformer for target speech enhancement and source localization (目標語音強化＆來源定位的AI波束形成器)
  * 學長論文：[結合陣列信號處理與深度學習於語音活性偵測、音質提升與聲源定位之應用](https://etd.lib.nctu.edu.tw/cgi-bin/gs32/gsweb.cgi/ccd=NzyIzu/record?r1=92&h1=10)
  * [All-neural beamformer for continuous speech separation](https://arxiv.org/abs/2110.06428)
    * `CSS`
      * continuous speech separation
      * aims to `separate overlapping voices` from a continuous influx of conversational audio spoken `by an unknown number of speakers`
      * ex : a meeting conversation recorded by a microphone array
    * goal
      * previously, we use `minimum variance distortionless response(MDSR)` filter to improve the `automatic speech recognition (ASR) accuracy`
      * aims to reach the same goal by `the all deep learning MVDR (ADL-MVDR) model` now

3. Joint neural speaker localization and speech separation for any number of speakers (任意數量人物之語音分離＆定位)
  * [SLOGD: SPEAKER LOCATION GUIDED DEFLATION APPROACH TO SPEECH SEPARATION](https://arxiv.org/pdf/1910.11131.pdf)

4. All neural telepresence system (全神經遠程呈現系統)
* [a high-fidelity telepresence system](https://dl.acm.org/doi/10.1145/3478513.3480490)
  * present a real-time communication system, experience a face-to-face conversation
  * no need to wear special glasses or earphone
  * the system consists of 
    * `head-tracked autostereoscopic display`
    * `high-resolution 3D capture`
    * rendering subsystems
    * `network transmission` using compressed color and depth video streams
  * other distributions
    * a novel `image-based` geometry fusion algorithm
    * `free-space dereverberation`
    * `talker localization`

 
  


### Second group

1. Supervised and unsupervised  anomalous sound detection (機器異音檢測)

2. Acoustic zone control /Sensor interpolation (喇叭陣列應用)
  * 學長論文：[基於隨機麥克風排序陣列之兩階段遠場聲源識別技術](https://etd.lib.nctu.edu.tw/cgi-bin/gs32/gsweb.cgi/ccd=mhCDzj/record?r1=1&h1=1)
  * 學長論文：[超指向性麥克風陣列應用於近場聲源全像及高感度麥克風陣列](https://etd.lib.nctu.edu.tw/cgi-bin/gs32/gsweb.cgi/ccd=NzyIzu/record?r1=4&h1=10)
 
3. Speech separation in adverse environments (語音分離+去噪+去迴響)

4. Acoustic camera (陣列可視化音源方位) ：硬體FPGA收音+軟體陣列定位演算法
