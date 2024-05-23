# YouTube 시청 기록 분석 

## YouTube 시청 기록 수집
![Poster](https://github.com/9unu/Short_form_video_watching_pattern_and_a_predictive_model/assets/124652096/a6ca7e17-e790-471e-8e2c-9dc12d48c2a6)

1. **video_info_function.ipynb**
   - YouTube API를 사용하여 비디오 정보를 얻는 함수가 포함된 파일입니다.

2. **youtube_watch_info.ipynb**
   - YouTube 시청 기록 파일 정보입니다.

3. **Youtube_video_info_extract.ipynb**
   - 시청 기록 파일(json)에서 비디오 ID 추출 -> YouTube API를 사용하여 비디오 정보 크롤링

## 데이터 처리

1. **csv_handling.ipynb**
   - 쇼츠 비디오만 추출합니다.
   - 다음 비디오와의 시청 시간 차이를 기반으로 실제 비디오 시청 시간을 추정합니다 (5분 이상 시청한 비디오는 적어도 한 번은 YouTube Shorts를 떠났다고 가정).
   - 목표 레이블 라벨링 (5분 미만 시청 비디오_1, 5분 이상 시청한 비디오_0).

2. **그래프 및 가설검정(전체, main).ipynb**
   - 쇼츠 영상 길이 및 실제 시청 시간 분포
   - 영상 길이에 따른 시청 시간 및 시청 영상 개수 분포
   - 카테고리별 시청 수 시각화
   * 중요한 것은 main에만 정리되어 있음
   * 전체에는 논문에 포함된 것 + 추가적인 가설검정, 비율들이 포함되어 있음
