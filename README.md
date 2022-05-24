# Alzheimer-prediction
Heewon's Code Review

<< 2022.05.03 >>
  
Data load (DeepDementia : main.py() Data Load)

* Need to download ADNI data
* Write data list we need   
  : (target paper) 'Multimodal multitask deep learning model for Alzheimer's disease progression detection based on time series data'
* Why use .tsv file format?  
  : TSV 파일은 데이터 열이 탭으로 구분 된 데이터 테이블을 저장함 (vs '.csv' : 데이터 열이 쉼표로 구분됨)  
  : 대부분의 스프레드 시트 프로그램(ex. Excel) 으로 가져와 데이터를 셀로 포맷 할 수 있음  
  : TSV 파일은 일반적으로 데이터베이스간에 데이터를 교환하는 데 유용함  
  reference : https://ko.scriptcult.com/4963.html
* Train the model by using any MRI data

<< 2022.05.9 >>

ADNI Data download

* Using this pdf file : 'IDA_User_Manual.pdf'
* Download  (Data download > Manual 참고)


<< 2022.05.10 >>

ADNI Data download

* Using this pdf file : 'IDA_User_Manual.pdf'


<< 2022.05.11 >>
* url을 이용하여 서버에서 직접 MR Image Data download 시도  -> IP 문제 발생 (download url을 생성한 IP와 download를 받으려는 IP (서버)가 다른 문제)

<< 2022.05.16 >> 
위에서 발생한 IP문제 문의

<< 2022.05.17 >> 
* 서버에 Firefox를 설치하여, 원격으로 서버에 접속하여 Firefox를 통해 GUI형식으로 IDA 웹 사이트에 접속, MR Image data download 시도  -> 다운로드가 중단되는 문제 발생

<< 2022.05.18 >>
* 서버 원격 접속이 불안정한 문제 발생  -> 데이터를 (본인) 컴퓨터에서 직접 다운로드 하는 방법 선택
* Target 논문에서 사용하는 data가 MR Image data가 아닌 FreeSurfer을 통해 추출된 data인 [UCSF]임을 확인

<< 2022.05.19 >>
* UCSF data Manual 살펴보기

<< 2022.05.21 >>
* 'ADNIMERGE packages for R' install 및 사용

<< 2022.05.23 >>
* Baseline data 


