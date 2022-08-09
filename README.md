# speaker
working space for speaker



### First group

1. Geometry-agnostic multi-channel personalized speech enhancement (多通道特定人物語音強化)
  * 學長論文：[用於智慧家庭助理與任意陣列配置之多通道個人語音活性偵測與音質提升系統](https://etd.lib.nctu.edu.tw/cgi-bin/gs32/gsweb.cgi?o=dallcdr&s=id=%22G021090335300%22.&searchmode=basic)
    * 本論文提出之技術
    1. `多通道個人語音活性偵測` (Voice Activity Detection, VAD)
       * 針對目標用戶開啟`語音辨識系統`，以減少計算成本和電池消耗
    2. `多通道目標語音增強技術`
       * 提升電話會議中的語音品質    
    <br/>
    
    * 為防受到背景噪音干擾，從嘈雜訊號中提取目標語音之作法：
    1. 利用目標之`聲音特徵`：語者事先註冊的語音和`長短期空間相關(Long Short-Term Spatial Coherence)特徵`
    2. 結合神經網路模型：`CNN`(作為編碼器、解碼器)和`RNN`(擁有長短期記憶(Long Short-Term Memory))

    <br/>
    
    * 結果
      * 將麥克風陣列所提取的`空間資訊`與`神經網路`結合，可以不受麥克風陣列的幾何影響，在`不同的陣列中`皆能`準確地偵測且提取目標語音`並`大幅提升語音增強`的效果。

2. AI beamformer for target speech enhancement and source localization (目標語音強化＆來源定位的AI波束形成器)
  * 學長論文：[結合陣列信號處理與深度學習於語音活性偵測、音質提升與聲源定位之應用](https://etd.lib.nctu.edu.tw/cgi-bin/gs32/gsweb.cgi/ccd=NzyIzu/record?r1=92&h1=10)
  
    <br/>
    
  * [All-neural beamformer for continuous speech separation](https://arxiv.org/abs/2110.06428)
    * `CSS`
      * continuous speech separation
      * aims to `separate overlapping voices` from a continuous influx of conversational audio spoken `by an unknown number of speakers`
      * ex : a meeting conversation recorded by a microphone array
    
    <br/>
    
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
