<<<<<<< HEAD
{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### <유튜브 시청기록 수집>\n",
    "1. video_info_function.ipynb\n",
    ":유튜브 api로 영상 정보 따오는 함수 들어있는 파일\n",
    "\n",
    "2. youtube_watch_info.ipynb\n",
    ": 유튜브 시청기록 파일 정보\n",
    "\n",
    "3. Youtube_video_info_extract.ipynb\n",
    ": 시청 기록 파일(json)에서 영상 id 추출 -> 유튜브 api로 영상 정보 크롤링\n",
    "\n",
    "### <데이터 핸들링>\n",
    "1. 데이터셋 pickle 만들기.ipynb\n",
    "- 쇼츠 영상만 추출\n",
    "- 다음 영상과의 시청시각차이로 실제 영상 시청 시간을 추정함 (5분 이상 본 영상은 한번이상 Youtube_shorts를 나갔다고 가정함)\n",
    "- target label 라벨링 (5분 미만 영상_1 vs 5분 이상 시청한 영상_0)\n",
    "\n",
    "2. 그래프 및 가설 검정.ipynb\n",
    "- 날짜별 시청 영상 개수\n",
    "- 카테고리별 시청 횟수 시각화\n",
    "- 카테고리별 전체 영상 대비 5분 미만 시청 영상 비율 시각화\n",
    "- 비선호 영상 패턴 확인 (날짜별 시간별 시각화)"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "name": "python",
   "version": "3.10.11"
  },
  "orig_nbformat": 4
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
=======
# YouTube 시청 기록 분석 

## YouTube 시청 기록 수집

1. **video_info_function.ipynb**
   - YouTube API를 사용하여 비디오 정보를 얻는 함수가 포함된 파일입니다.

2. **youtube_watch_info.ipynb**
   - YouTube 시청 기록 파일 정보입니다.

3. **Youtube_video_info_extract.ipynb**
   - 시청 기록 파일(json)에서 비디오 ID 추출 -> YouTube API를 사용하여 비디오 정보 크롤링

## 데이터 처리

1. **데이터셋 pickle 만들기.ipynb**
   - 쇼츠 비디오만 추출합니다.
   - 다음 비디오와의 시청 시간 차이를 기반으로 실제 비디오 시청 시간을 추정합니다 (5분 이상 시청한 비디오는 적어도 한 번은 YouTube Shorts를 떠났다고 가정).
   - 목표 레이블 라벨링 (5분 미만 시청 비디오_1, 5분 이상 시청한 비디오_0).

2. **그래프 및 가설검정.ipynb**
   - 날짜별 시청한 비디오 수.
   - 카테고리별 시청 수 시각화.
   - 모든 비디오 중 5분 미만 시청한 비디오의 비율 시각화.
   - 선호하지 않는 비디오 패턴 확인 (날짜 및 시간별 시각화).

ubuntu update
>>>>>>> 51f67f9babb06e6e31a01860ec04b98e41705baa
