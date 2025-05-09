# 정예성 배구선수 소개 웹사이트

이 프로젝트는 배구선수 '정예성'을 소개하는 반응형 웹사이트입니다. ©JJippong의 Spectral 템플릿을 기반으로 하였으며, 폰트는 Pretendard로 전면 교체하였습니다.

## 주요 특징
- 반응형 디자인 (PC/모바일 모두 최적화)
- Pretendard 웹폰트 적용
- 넷리파이(Netlify)로 간편 배포

## 기술 스택
- HTML5, CSS3 (Sass 일부)
- JavaScript (jQuery)
- Pretendard 웹폰트
- Netlify (정적 웹사이트 배포)
- Font Awesome (아이콘)
- Spectral 템플릿 기반 커스텀

## 폰트 적용 방법
- HTML `<head>`에 아래 코드를 추가하였습니다:
  ```html
  <link rel="stylesheet" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable-dynamic-subset.min.css" />
  ```
- CSS 최상단에 아래 코드를 추가하였습니다:
  ```css
  @import url("https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/variable/pretendardvariable-dynamic-subset.min.css");
  body, input, select, textarea {
    font-family: 'Pretendard Variable', Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', sans-serif;
  }
  ```

## 배포 및 접근 URL
- 본 프로젝트는 Netlify를 통해 배포됩니다.
- 실제 서비스 주소: https://jjippong.netlify.app/

## 라이선스 및 크레딧
- 템플릿: Spectral by ©JJippong (CCA 3.0)
- 폰트: Pretendard (SIL Open Font License)
- 아이콘: Font Awesome
- 기타: jQuery, Scrollex, Responsive Tools

