# django-tutorial

새로 알게된 것 : settings.py에서 DEBUG 속성 값을 TRUE로 설정하면 디버그 모드로 작동하여 자동으로 정적 파일들을 제공한다.

(그래서 DEBUG = FALSE로 수정헀을 시, 정적 파일들을 찾지 못하는 문제가 발생했다)

항상 DEBUG 모드를 활성화 시키지 않아도 python library의 Whitenoise를 설치하면 정적 파일들을 제공해준다.


source : https://www.w3schools.com/django/index.php
