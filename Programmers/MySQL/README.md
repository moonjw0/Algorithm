<details> 
  <summary>
    <a href="https://school.programmers.co.kr/learn/courses/30/lessons/164671">
      7. 조회수가 가장 많은 중고거래 게시판의 첨부파일 조회하기
    </a>
  </summary> 
  <div markdown="1">
    <ul> <!-- 리스트1 -->
      <li>풀이 포인트!
        <ul> <!-- 리스트2 -->
          <li>CONCAT()</li>
          <li>서브쿼리</li>
        </ul>
      </li>
    </ul>
    <ul> <!-- 리스트1 -->
      <li>풀이 과정
        <ol> <!-- 리스트2 --> 
          <li>SELECT: CONCAT() 이용 -> FILE_PATH 형태 만들기</li>
          <li>FROM: USED_GOODS_BOARD 'B' + USED_GOODS_FILE 'F'</li>
          <li>ON: ID 연결 </li>
          <li>WHERE: 최대 조회수 찾는 쿼리 </li>
          <li>FILE_ID 내림차순 정렬</li>
        </ol>
      </li>
    </ul>
    <ul> <!-- 리스트1 -->
      <li>다른 풀이 방법
        <ol> <!-- 리스트2 --> 
          <li>"WHERE(조건 1개) = {}" 서브쿼리 -> LIMIT 사용가능</li>
          <li>FROM 서브쿼리</li>
        </0l>
      </li>
    </ul>

    
  </div> 
</details>