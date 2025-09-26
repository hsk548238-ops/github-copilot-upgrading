# upgraded 폴더 구조 설명

`upgraded` 폴더는 레거시 프로젝트의 모든 파일과 폴더를 복사하여 최신화 작업을 진행하는 공간입니다. 주요 하위 폴더 및 파일은 다음과 같습니다:

- MANIFEST.in: 패키징 관련 설정 파일
- README.rst: 프로젝트 설명서
- distribute-0.6.10.tar.gz, distribute_setup.py: 레거시 Python 패키징 관련 파일
- setup.py: 프로젝트 설치 및 패키징 스크립트
- docs/: 프로젝트 문서 폴더
  - build/: Sphinx로 빌드된 문서 결과물
  - source/: Sphinx 문서 소스
- guachi/: 주요 Python 모듈
  - __init__.py, config.py, database.py: 핵심 모듈 파일
  - tests/: 단위 및 통합 테스트 코드
- guachi.egg-info/: 패키징 정보 폴더
  - PKG-INFO, SOURCES.txt 등

이 폴더에서 모든 업그레이드 작업(코드 수정, 테스트, 문서 개선 등)을 진행합니다.