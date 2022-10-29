- Path 정보
	.ipynb Path
		./data 파일 밖에 저장합니다.
		sample path : ./
	Data Path
		traing data : ./data/train
		validation data : ./data/validation/
		test data : ./data/test
	Model Path
		model 저장 경로 : ./data/model.pt
	Submission Path
		submission 저장 경로 : ./data/
		sample path : ./data/sample_submission.csv
		최종제출 submisstion : ./data/submission_final.csv
	TaPR Lib path
		whl file : ./data/eTaPR-1.12-py3-none-any.whl

- 실행방법
1. anaconda 설치 이후 진행 부탁드립니다. 추가로 linux 환경에서 진행 부탁드립니다.
2. anaconda prompt에서 conda create -n haicon2021ori python=3.6.13 을 실행합니다.
3. conda activate haicon2021ori 를 실행합니다.
4. conda update --all 을 실행합니다.
5. pip install -r requirements.txt 를 실행합니다.
6. jupyter notebook 을 실행합니다.
7. data파일과 TaPR Lib 를 path정보에 맞게 저장합니다.
8. jupyter notebook 환경에서 실행 파일인 HAICon2021_final.ipynb를 data폴더 밖에 저장합니다.
9. .ipynb 파일을 실행합니다.