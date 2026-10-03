# css-image-crop-template-builder
Repository for [css-image-crop-template-builder](https://tools.wmflabs.org/css-image-crop-template-builder/) from Wikimedia Toolforge

# CSS 이미지 자르기 도우미
위키미디어 툴포지(Wikimedia Toolforge)에 있는 [css-image-crop-template-builder](https://tools.wmflabs.org/css-image-crop-template-builder/)의 소스 코드 저장소입니다.

위키미디어 환경에서 위키미디어 공용의 이미지나 위키문헌의 페이지 문서 URL을 입력하여, 해당 이미지를 불러와 원하는 영역을 선택하면, 해당 영역만 표시해 주는 [틀:CSS 이미지 자르기](https://ko.wikisource.org/wiki/%ED%8B%80:CSS_%EC%9D%B4%EB%AF%B8%EC%A7%80_%EC%9E%90%EB%A5%B4%EA%B8%B0)에 사용할 코드를 만들어 주는 도구입니다.

## 사용 방법

1. [`css-image-crop-tool.html`](./css-image-crop-tool.html)을 브라우저에서 엽니다.
2. 위키미디어 공용에서의 파일명 또는 위키문헌에서의 페이지 문서의 URL을 입력하고 **불러오기**를 누릅니다.
3. 이미지에서 자를 영역을 마우스로 선택하고, 필요하면 크기와 위치를 조정합니다.
4. 생성된 틀 코드를 복사해 사용합니다.

PDF·DjVu·TIFF처럼 여러 쪽으로 된 파일은 주소나 파일명에 쪽 번호를 지정할 수 있습니다.

이 도구는 위키미디어 API를 사용하므로, 이미지를 불러올 때 인터넷 연결이 필요합니다.

## 라이선스

이 프로젝트는 [MIT License](./LICENSE)에 따라 배포됩니다.