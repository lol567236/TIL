# 마크다운 정리

## 	마크다운 문법

1. **순서가 있는 리스트 `.숫자` (ul) 과 순서가 있는 리스트 `*`(ol)로 작성할수있다**

   

2. **Fenced Code Block** 

   * 코드 블록은 backtick(`) 기호 3개를 활용하여 작성 ```

     * ```python
       print('hello')
       ```

   * 코드 블록에 특정 언어를 명시하면 코드에 색을 입혀 보기가 편해진다    

   * 

   

3. **Inline Code Block** 

   * 코드 블록은 backtick(`) 기호 1개를 인라인에 활용하여 작성 
   * `코드블록`

   

4. **Link** 

   * `[문자열](url)` 을 통해서 링크를 작성 가능하다
     * 특정 파일을 포함해서 연결 시킬 수도 있다
       * [링크예시](www.naver.com)
   * 이미지 
     * `![문자열](url)` 를 통해서 이미지를 사용가능
       * ![이미지 예시](https://mblogthumb-phinf.pstatic.net/MjAxNzAyMTdfNTMg/MDAxNDg3MzAwNTU2Njk0.UGLPWDcA4e5zW9p_A4Ttedc53wD1smw3wHqqJWoKyfIg.KujXt-RnjIrEqWHFlL659a4SpLLGhDN32sj3FkWbywwg.JPEG.pet4paws/gdferew.JPG?type=w2)

   

5. **인용문**

   * `>`를 사용하여 인용문을 작성할수 있다  

     * > 인용문 예시

   

6. **Table (표)**

   * ctrl + t 의 단축키를 사용해 생성 ( 소스 코드로는 거의 생성하지 않음.)

   * |      |      |      |
     | ---- | ---- | ---- |
     |      |      |      |

   

7. **글자 강조**

   * 굵게(bold) , 기울을 (Italic) 을 통해서 특정 글자를 강조할수 있음
     * `** bold **`  **bold** 
     * `*Italic*` *Italic*
     * `***Italic Bold***` ***Italic Bold***
     
     

8. **수평선**

   * 3개 이상의 asterisk(*) , Dashes(-), underscores(_) 를 사용하면 생성가능

     * `---` 

       ***

9. **마크다운 관련 자료**

   * https://github.github.com/gfm/
   * https://guides.github.com/features/mastering-markdown/
   * https://www.markdownguide.org/

10. **마크다운 이미지 관련 설정** 

    * 이미지는 아래처럼 설정을 해두면 마크다운 파일이 있는 위치에 폴더를 자동으로 만들고, 

      이미지를 모두 복사하여 상대경로로 표현해줌

      * 상대 경로 예시 : ./md-images/untitle.png
      * 절대 경로 예시: c:/HPHK/Desktop/TIL/untitle.png

    * 상대경로가 아니면, 파일의 위치가 다르기에 이미지가 안보일 수 있음

![Hearthstone Screenshot 04-21-22 20.18.17](markdown_1.assets/Hearthstone Screenshot 04-21-22 20.18.17.png)

`asset 생성용 이미지 입니다`

## 개발자에게 문서 작성이란? 

 * [백엔드 개발자를 꿈꾸는 학생 개발자들에게](https://d2.naver.com/news/3435170)
   * 레벨 2 개발자 : '자신이 경험한 사용법을 `문서화` 해서 팀내에 전파'
 * [Google Technical Writing](https://developers.google.com/tech-writing)
   *  Every engineer is also a writer 
 * [Technical writing conference](https://engineering.linecorp.com/ko/blog/write-the-docs-prague-2018-recap/ )
   * Clova 기술 문서 작성 및 관리 업무

