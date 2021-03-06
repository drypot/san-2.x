# 한글 에디터 산 2.x

DOS, OS/2 용 한글 에디터입니다.

산 1.x 는 16bit 도스 환경에서 동작했습니다.  
산 2.x 는 32bit 도스, OS/2 환경에서 동작했습니다.

1993 년도부터 만들었습니다.  
1994 년도부터 릴리즈했습니다.  
1996 년도에 개발을 중지했습니다.

이 리포지터리는 1996년도 개발이 중지된 상태를 보존한 것입니다.  
조합형, 완성형 한글 텍스트 문서들을 편의상 UTF8 문서로 변환했습니다.

## 산 2.x 의 주요 기능들

다양한 한글 코드 지원, 조합, 완성, 정상조합, 자동 판독.  
가상 메모리 지원, 전체 16M 제한, conventional + XMS + Disk.  
다중 문서 편집, 단 문서당 4메가로 제한.  
무제한 Undo / Redo.  
사용자 글쇠 정의.  
C 언어 스타일 매크로 프로그래밍 언어.  
다양한 자판지원, 두벌식, 세벌식, 드보락, 쿼티.

## Text Service / Terminal Service

대외적인 이름은 산 2.x 이었습니다.  
개인적으로 코드에 붙였던 이름은 Text Service 였습니다.  
Emacs 같은 플랫폼을 만들고 싶었던 것 같습니다.

Terminal Service 라는 OS/2 용 한글 터미널 에뮬레이터의 코드가 약간 섞여 있습니다.  
Text Service 와 코드 공유를 많이 해서 한 디렉토리에 두고 만들고 있었습니다.

## Build

빌드 관련된 파일은 borland 디렉토리에 들어있습니다.  
하지만 지금은 2019 년입니다. ^^;

## License

[MIT](LICENSE)
