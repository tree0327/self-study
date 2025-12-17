# self-study
예복습, 자습 저장소입니다.

## conda 가상환경 명령어
기능,명령어 형식,예시 명령어,설명
생성,conda create -n [환경이름] python=[버전],conda create -n my_data_env python=3.10,새로운 이름과 파이썬 버전을 지정하여 가상 환경을 만듭니다.
활성화,conda activate [환경이름],conda activate my_data_env,생성된 가상 환경을 시작하여 사용합니다.
비활성화,conda deactivate,conda deactivate,현재 활성화된 가상 환경을 종료하고 base 환경으로 돌아갑니다.
목록 확인,conda env list,conda env list,현재 시스템에 존재하는 모든 Conda 가상 환경 목록을 확인합니다.
삭제,conda env remove -n [환경이름],conda env remove -n my_data_env,지정된 가상 환경을 영구적으로 삭제합니다. (주의: base 환경은 삭제 불가)