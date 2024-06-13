# Dreammate-Generator

##Dataset
You must download 페르소나 기반의 가상 인물 몽타주 데이터 from AI-Hub.(https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&dataSetSn=618)

##VQGAN
Train VQGAN with 페르소나 기반의 가상 인물 몽타주 데이터.
You must use requirement version of libraries to run this model.
If you update the pytorch-lightning, this model may show you ModuleError.

##KoDALLE
Get model file from trained VQGAN model above.
Trained VQGAN will used for encoder and decoder of KoDALLE.
>이미지 생성 과정 적어주세요

##styleGANEX
>스타일 transfer 과정 적어주세요
