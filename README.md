# PureView - 이미지 뷰어 및 편집기

PureView는 PyQt6를 기반으로 개발된 강력하고 빠른 이미지 뷰어 및 배치 편집 도구입니다. 사용자 친화적인 다크 테마 인터페이스와 전문적인 이미지 처리 기능을 제공합니다.

## 📥 설치 파일 다운로드 (Windows)
직접 설치하여 사용하려면 아래 링크에서 설치 파일을 다운로드하세요:
- **[PureView_Setup_v1.0.exe 다운로드](https://github.com/cyber1025-dot/PureView-Download/raw/main/PureView_Setup_v1.0.exe)**

## 주요 기능

- **빠른 이미지 뷰어**: 다양한 이미지 포맷은 물론 PDF 및 비디오 파일 뷰잉을 지원합니다.
- **다중 탭 지원**: 여러 폴더나 파일을 탭 인터페이스를 통해 효율적으로 관리할 수 있습니다.
- **배치 프로젝트 관리**: 다량의 이미지를 한 번에 처리할 수 있는 강력한 컨버터를 제공합니다.
  - **크기 조절**: 픽셀 지정 또는 비율(%) 기반 리사이징 지원
  - **포맷 변환**: JPEG, PNG, WEBP 등 주요 포맷 지원 및 품질 설정
  - **워터마크**: 텍스트 워터마크를 이미지에 삽입 가능
  - **일괄 이름 변경**: 규칙 기반의 파일명 변경 기능
- **단일 인스턴스 실행**: 여러 번 실행해도 하나의 창에서 효율적으로 제어됩니다.
- **라이선스 관리**: 30일 평가판 라이선스 시스템이 내장되어 있습니다.

## 설치 및 실행 방법

### 요구 사항
- Python 3.8 이상
- PyQt6
- Pillow (PIL)

### 실행 방법
1. 저장소를 클론합니다:
   ```bash
   git clone https://github.com/cyber1025-dot/PureView.git
   ```
2. 가상환경을 생성하고 의존성을 설치합니다:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   pip install PyQt6 Pillow
   ```
3. 프로그램을 실행합니다:
   ```bash
   python src/main.py
   ```

## 프로젝트 구조

- `src/`: 모든 소스 코드가 포함된 메인 디렉토리
  - `main.py`: 애플리케이션 진입점
  - `converter.py`: 이미지 배치 변환 로직 및 UI
  - `windows/`: 메인 윈도우 및 주요 창 구성
  - `widgets/`: 재사용 가능한 UI 컴포넌트
  - `utils/`: 파일 타입 감지, 라이선스 체크 등 유틸리티
- `설명서/`: 프로젝트 관련 기술 문서 및 가이드

## 라이선스
본 프로그램은 평가판 시스템을 포함하고 있습니다. 상세 내용은 `src/utils/license_checker.py`를 참조하세요.
