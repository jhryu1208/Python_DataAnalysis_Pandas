# Data Anyalsis/Preprocessing/Visualization-Pandas
<div class="alert alert-block" style="border: 1px solid #FFB300;background-color:#F9FBE7;">

- <b>데이터 분석을 입문하기 위한 파이썬 데이터 분석 전처리 기본

- Jupyter Notebook 공부</b>

- <b>COVID19 Data Source by Johns Hopkins CSSE</b>
  - https://github.com/CSSEGISandData/COVID-19

- <b>브라질_olist 쇼핑몰업체의 ecommerce 데이터</b>
  - https://github.com/jhryu1208/Python_DataAnalysis_Pandas/tree/master/Pandas/Brazilian_Ecommerce_EDA/olist_ecommerce_data
</div>

## [ 데이터 포맷 이해 ]

- [CSV파일 다루기](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/CSV_Practice.ipynb)
- [JSON파일 다루기](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/JSON_Practice.ipynb)
- [XML파일 다루기](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/XML_Practice.ipynb)

## [ Pandas 기본 문법 ]

- [Pandas 라이브러리 기본 이해](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/Pandas/Pandas_Basic.ipynb)
  - Pandas 라이브러리
  - Series (CRUD) Create/Read/Update/Delete
      > [ 데이터 시리즈 Create ]
      > pd.Series( value list, index = [index list])
  - Pandas 데이터 타입
  - Pandas 데이터 타입 변경
      > Series객체.astype('변경타입')
  - Dataframe (CRUD) Create/Read/Update/Delete
      > [ 데이터 프레임 Create ]
      > pd.Dataframe( {key : value,...}, index = [index list])
  - Dataframe에서 특정 행/열/값 가져오기
      >행 가져오기 : ex) df.loc[2000]
      >열 가져오기 : ex) df.iloc[0]
      >value 가져오기 : ex) df.loc[2000]['미국'] or df.['미국'][2000]

## [ 탐색적 데이터 분석 ]

- [EDA 기본 패턴 적용을 위한 Pandas 라이브러리 문법 활용](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/Pandas/Pandas_EDA.ipynb)

## [ 데이터 전처리를 위한 Pandas 라이브러리 사용법]

- [Pandas 라이브러리 데이터 가공](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/Pandas/Pandas_Data_Processing.ipynb)
- [데이터프레임 연결/병합을 통해 데이터 가공하기](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/Pandas/Pandas_Merge_Concat.ipynb)

## [ COVID-19 현황 분석 및 시각화]

- [COVID-19 확진자 현황 실제 데이터 전처리](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/Pandas/Pandas_Real_Data_Processing.ipynb)
- [최종 전처리 데이터로 그래프 생성](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/Pandas/Pandas_Graph.ipynb)

- [COVID 19 확진자 현황 Chart Race](https://public.flourish.studio/visualisation/3282433/)
    ![COVID19-CONFIMRED](https://user-images.githubusercontent.com/53929665/90008809-e4078980-dcd7-11ea-8bae-7973bafbbbf2.gif)

- [COVID-19 사망자 현황 실제 데이터 전처리 및 시각화](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/Pandas/COVID19-Death-Accumulation.ipynb)
- [COVID 19 사망자 현황 Chart Race](https://public.flourish.studio/visualisation/3285190/)
    ![COVID19-DEATH](https://user-images.githubusercontent.com/53929665/90008305-1664b700-dcd7-11ea-83cf-1f52b50ce198.gif)


## [ 시각화 라이브러리 사용]

- [iplot 사용법 이해](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/Pandas/Pandas_Visualization_Iplot.ipynb)
- [plotly 사용법 이해](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/Pandas/Pandas_Visualization_Plotly.ipynb)
- [데이터분석을 위한 데이터분류 이해](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/Pandas/Deep_Data_and_Visual.ipynb)

## [ Olist (BR) Ecommerce 데이터 분석 및 시각화]

- [Brazilian_Ecommerce_EDA1](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/Pandas/Brazilian_Ecommerce_EDA/BEE1.ipynb)
  - 데이터 사전 준비/이해와 EDA과정 적용
- [Brazilian_Ecommerce_EDA2](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/Pandas/Brazilian_Ecommerce_EDA/BEE2.ipynb)
  - Olist 쇼핑몰을 이용하는 고객 수
  - 주고객들의 거주지
  - 주고객들의 지불방법
- [Brazilian_Ecommerce_EDA3](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/Pandas/Brazilian_Ecommerce_EDA/BEE3.ipynb)
  - 월별 평균 거래액 분석
  - 월별 거래액 시각화
- [Brazilian_Ecommerce_EDA4](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/Pandas/Brazilian_Ecommerce_EDA/BEE4.ipynb)
  - 월별/일별/연도별/요일별/계절별 거래 건수 확인
  - 요일/시간 간의 거래액 상관관계 분석
- [Brazilian_Ecommerce_EDA5](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/Pandas/Brazilian_Ecommerce_EDA/BEE5.ipynb)
  - 카테고리별 판매/거래액 분석
- [Brazilian_Ecommerce_EDA6](https://github.com/jhryu1208/Python_DataAnalysis_Pandas/blob/master/Pandas/Brazilian_Ecommerce_EDA/BEE6.ipynb)
  - 월별 평균 배송시간 분석
