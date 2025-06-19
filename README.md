
seoulsubway - 서울시 지하철 유동인구 시각화 및 예측

프로젝트 개요
2025년 3월 서울시 지하철 데이터를 기반으로, 출퇴근 시간 혼잡도 분석 및 예측 모델링을 수행하였습니다.

구성 파일
| 파일명 | 설명 |
|--------|------|
| `seoul_subway_forecast_bar_lstm.ipynb` | RF + LSTM 예측 모델 |
| `seoul_subway_forecast_lstm_improved.ipynb` | 개선된 LSTM + RMSE 평가 |
| `seoul_subway_time_analysis.ipynb` | 시간대별 히트맵 및 혼잡역 시각화 |
| `seoul_subway_top10_average.ipynb` | 출퇴근 시간대 혼잡역 일평균 출력 |
| `data/` 폴더 | 사용한 csv 원본 파일 3종 |

실행 방법
1. Python 3.10 이상, Jupyter 환경 필요
2. 각 ipynb 파일을 순차 실행하거나, `Kernel > Restart & Run All`로 전체 실행
3. 출력된 히트맵 html, 시각화 그래프, RMSE 확인

개발 환경
- Python 3.10
- Pandas, Numpy
- Matplotlib, Seaborn
- Scikit-learn
- Tensorflow 2.x

데이터 출처
서울 열린데이터 광장 (https://data.seoul.go.kr/)
