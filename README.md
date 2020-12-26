# Dacon_Analyze_Jejuspace
* Dacon의 공간정보 탐색적 데이터 분석 경진대회 코드입니다. (It is the code of the DACON conference that is EDA of space information in Jeju-do island)  
(https://data-newbie.tistory.com/458)

### 설치해야하는 패키지(required packages)
* numpy : 1.18.1
* pandas : 1.0.3
* fiona : 1.8.13.post1
* geopandas : 0.8.1
* plotly : 4.14.1
* descartes : 1.1.0
* 기타 (further information)
  * 위의 패키지 설치시 그 외 다른 패키지들은 자동으로 설치됨 (if you install these packages, you don't need to setup other packages like shapely.geometry)
  * python version : 3.7.7 

### 패키지 설치방법 (package installation method)
  -> 아나콘다3 설치해야 함(you need to install Anaconda3)
* conda create -n my_python python==3.7.7
* conda activate my_python
* conda install spyder
* conda install numpy=1.18.1 pandas=1.0.3
* conda install fiona=1.8.13.post1
* conda install geopandas==0.8.1
* conda install plotly == 4.14.1
* conda install descartes == 1.1.0

### 폴더 셋팅
* 데이터의 경우 따로 다운받으셔서 넣으셔야 합니다. (You need to download each data and put it to each folder)
* geometry 폴더(folder) : LSMD_ADM_SECT_UMD_50_202012.dbf, LSMD_ADM_SECT_UMD_50_202012.shp, LSMD_ADM_SECT_UMD_50_202012.shx 파일을 여기 넣으시면 됩니다. (you have to put these data like 'LSMD_ADM_SECT_UMD_50_202012.dbf', 'LSMD_ADM_SECT_UMD_50_202012.shp' and 'LSMD_ADM_SECT_UMD_50_202012.shx' to geometry folder)  
(download : http://data.nsdi.go.kr/dataset/15145)
* data 폴더(folder) : KRI-DAC_Jeju_data5, KRI-DAC_Jeju_data6, KRI-DAC_Jeju_data7, KRI-DAC_Jeju_data8 파일을 여기 넣으시면 됩니다.(you have to put these data like 'KRI-DAC_Jeju_data5', 'KRI-DAC_Jeju_data6', 'KRI-DAC_Jeju_data7' and 'KRI-DAC_Jeju_data8' to geometry folder)  
(download : https://dacon.io/competitions/official/235682/data/)

### 사용한 외부데이터
* 행정구역_읍면동(법정동) (제주도)
(http://data.nsdi.go.kr/dataset/15145)


