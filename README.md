# NH-IDEA PLAYGROUND 교육용 자료 - 360° 파노라마 VR 제작편

## 개요
본 프로젝트는 360° 파노라마 VR 제작 교육용 자료이다.
다음과 같은 내용을 포함하고 있음

- DSRL 카메라를 이용한 사진 촬영 결과물 (4장의 사진)
- DSRL 카메라 사진을 이용한 PTGui 작업 결과물 (1개의 저장파일)
- DSRL 카메라 사진을 이용한 Stitching 완료 이미지 (1장의 사진)
- 360 VR 카메라 촬영 결과 이미지 (1장의 사진)
- krpano Tools의 Make Vtour 제작 결과물 (vtour 폴더)

## Git Branch 소개
각 브랜치별로 포함한 파일을 아래와 같이 정리합니다.
### 1_stitching_preparation
스티칭을 위한 DSLR 사진 촬영 결과물 4장을 포함합니다.
동서남북 총 4면의 사진으로 각 사진은 좌우 약 180°, 상하 약 180°의 영역이 촬영되었습니다.

### 2_stitching_ptgui
PTGui에 4장의 사진을 추가하고 Align, Stitching 한 경과물은 만들 수 있는 저장파일을 포함합니다.

### 3_stitching_result
PTGui를 통해 Stitching된 파노라마 이미지를 'Create'으로 jpg 로 제작한 파일을 포함합니다.

### 4_krpano_vtour
PTGui로 제작된 2:1 Equirectangular jpg 이미지를 krpano tools를 이용하여 제작한 vtour 폴더를 포함합니다.
vtour폴더 내에는 VR을 구동할수 있는 일체의 파일을 포함하고 있습니다.
