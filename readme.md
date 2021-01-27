# Backslide Template

## 기본 템플릿과 다른 점

* Noto Sans KR 적용 (애플 시스템의 경우 애플 네오 고딕 우선 적용)
* 단어 단위 줄바꿈 적용 (`word-break: keep-all`)
* 기본 행간 넓힘 (`line-height: 1.3`)

## 클론

```shell
gh repo clone grotesq/bs-template
```

## Backslide 설치

```shell
npm i -g backslide
```

## 실행

```shell
bs serve
```

## HTML 내보내기

```shell
bs export presentation.md
```

## PDF 생성

PDF 생성에는 Decktape 패키지가 필요합니다.

```shell
npm i -g decktape
```

```shell
bs pdf presentation.md
```
