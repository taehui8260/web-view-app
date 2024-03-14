# web-view-app
안드로이드 스튜디오를 사용하여 개발된 웹뷰 기반의 모바일 애플리케이션입니다. 이 애플리케이션은 사용자가 웹 콘텐츠를 브라우징하고, 사진을 찍거나 선택하여 웹 페이지에 직접 업로드할 수 있는 기능을 제공합니다.

## 기능

- **웹 콘텐츠 브라우징:** 사용자는 네이티브 앱 환경 내에서 웹 페이지를 탐색할 수 있습니다.
- **사진 찍기 및 업로드:** 애플리케이션은 카메라 사용 권한을 요청하고, 사용자가 직접 사진을 찍거나 기기에서 사진을 선택하여 웹 페이지에 업로드할 수 있습니다.

## 주요 특징

- **네이티브 앱과 웹의 결합:** 사용자는 웹의 유연성과 네이티브 앱의 효율성을 동시에 경험할 수 있습니다.
- **직관적인 사용자 인터페이스:** 사용자는 직관적인 인터페이스를 통해 쉽게 사진을 찍고 업로드할 수 있습니다.
- **사진 촬영 및 업로드:** 사용자가 앱 내에서 직접 사진을 촬영하고, 웹뷰를 통해 사진을 업로드할 수 있습니다.
- **퍼미션 요청:** 앱은 사진 촬영 및 업로드를 위해 카메라와 저장소 접근 권한을 사용자에게 요청합니다.
- **아이콘 설정:** 애플리케이션의 아이콘은 사용자에게 앱의 목적과 정체성을 전달하는 중요한 요소입니다. PhotoShareWebViewApp은 직관적인 사용자 경험을 위해 맞춤형 아이콘을 사용합니다.
- **스플래쉬 화면 구성:** 사용자가 앱을 시작할 때 첫 인상을 결정하는 스플래쉬 화면을 제공합니다. 이는 앱 로딩 시간을 사용자에게 보다 즐거운 경험으로 전환시킵니다.
- **환경변수 사용:** 외부 노출 방지를 위해 은밀한 정보는 local.properties에 따로 관리 합니다. [참고](:https://tae-hui.tistory.com/entry/Android-Studio-localproperties-%ED%99%9C%EC%9A%A9-%EB%B0%A9%EB%B2%95)

## 스크린샷

### 애플리케이션 화면
![메인 화면](https://github.com/taehui8260/web-view-app/assets/160584878/1426d46c-0079-452d-b60f-0ed7db2f5c46)

## 시작하기

이 프로젝트를 사용하기 위해서는 Android Studio가 설치되어 있어야 합니다. 프로젝트를 클론한 후, Android Studio에서 프로젝트를 열고 필요한 의존성을 동기화하세요.

## 권한 요청

애플리케이션은 카메라 사용 및 파일 시스템 접근을 위해 사용자로부터 다음 권한을 요청합니다.

- 카메라 사용 (`android.permission.CAMERA`)
- 외부 저장소 접근 (`android.permission.WRITE_EXTERNAL_STORAGE`)

## 개발 환경

- JDK 1.8
- Android Studio
- 최소 SDK 버전: 24
- 대상 SDK 버전: 34

## 라이선스

PhotoShareWebViewApp은 MIT 라이선스 하에 배포됩니다. 자세한 내용은 (LICENSE) 파일을 참조하세요.
