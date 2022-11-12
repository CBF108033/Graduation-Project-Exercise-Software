# 專題—健體端勢
【健體端勢】便利實用的居家運動輔助軟體，具運動姿勢預測、 語音提示以修正姿勢、帳號註冊登入、體感介面、即時熱量消耗、歷史紀錄查詢等功能。  
<div align=center><img alt="exercise" src="./images/AllPose.png" width=35%></div>
<br/>

### 主系統
- **簡介**  
本健身訓練應用程式採用Google的MediaPipe為核心，使用體感介面以手勢操作系統，若隨時想要暫停或是切換動作只需要做特定姿勢，不需要走到電腦前操控介面就能達成目的，如此增加使用者運動流程的流線化，提高使用者運動的效率。當使用者動作不確實時會提供即時語音回饋，因此使用者可以由反覆的動作糾正逐漸抓到動作的要領。
<div align=center><img alt="AR Museum" src="./images/all.jpg" width=70%></div>  
<br/>

- **技術**  
本應用使用CNN、OpenCV+MediaPipe的姿勢識別模型BlazePose。 使用CNN訓練建立三動作模型預測使用者動作，以及透過OpenCV讀取每一幀的影像並使用BlazePose高準度身體姿勢追蹤的機器學習推測出全身的關鍵點。
<div align=center><img alt="tech" src="./images/technology.jpg" width=50%></div>  
<br/>

- **實際操作**
<div>
<img alt="tech" src="./images/exercisingPredict.gif" width=27%> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img alt="tech" src="./images/exercising.gif" width=27%> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img alt="tech" src="./images/exercisingMusic.gif" width=27%> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img alt="tech" src="./images/exercisingStop.gif" width=27%> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img alt="tech" src="./images/exercisePoseSwitch.gif" width=27%> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img alt="tech" src="./images/exercisingUserSwitch.gif" width=27%> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</div>
