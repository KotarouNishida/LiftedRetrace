# 03_Measurement_Sequence_Design.md

## 1. 計測システムの全体構成

![System Overview](./Figures/System_Overview.png) 
本研究で用いた計測システムは、ハードウェア部、FPGA部、Host-PC部の三層構造から構成されます。  
ハードウェアでは探針(カンチレバーの先端部)から得られた信号をアナログ処理し、ADCを介してFPGAへ入力します。  
FPGAはリアルタイム性が要求される、信号検出、フィードバック制御および走査信号の生成を担い、  
Host-PCではデータの処理、保存や表示、補正など計算量の大きい処理を実行する構成です。
