<div align=center>
    <h1>CSS REVIEW</h1>
    <p>Cascading style sheet: 폭포수 처럼 떨어진다는 의미. 정의된 세부 정의가 있다면 그 스타일을 사용하고, 그렇지 않다면 기본 스타일을 사용한다.
    </p>
    <br>
    <h2>STYLE TYPE</h2>
    <p>Author Style: 개발자가 지정한 스타일이 우선 적용</p>
    <p>User Style: 사용자가 지정한 스타일이 다음 순위 적용</p>
    <p>Brower Style: 브라우저에서 기본으로 제공하는 스타일이 마지막 순위 적용</p>
    <br>
    <h2>!important</h2>
    <p>모든 스타일을 무시하고 가장 먼저 적용한다. 가급적이면 쓰지 않는 것이 좋다.</p>
</div>
<div align=center>
    <h1>flexbox</h1>
    <h3>Container 속성</h3>
    <ul>
        <li>display:flex</li>
        <li>flex-direction</li>
        <li>flex-wrap</li>
        <li>flex-flow</li>
        <li>justify-content: center, flex-end, flex-start, space-between, space-around, space-evenly</li>
        <li>align-items: 수직 축 정렬. 아이템들이 한 줄에 있을 때 유용하게 사용된다.</li>
        <li>align-content: 수직 축 정렬 및 줄 간의 간격을 조정할 때 사용한다. flex-wrap: wrap 상태일 때 유용.</li>
    </ul>
    <br>
    <h3>item 속성</h3>
    <ul>
        <li>order</li>
        <li>flex-grow</li>
        <li>flex-shrink</li>
        <li>flex-basis</li>
        <li>flex</li>
        <li>align-self</li>
    </ul>
    <p>flex: row가 기본값이며, flex: column이 되면 justify-content 속성은 세로 축 중심으로, align-items 속성은 가로축 중심으로 변화한다.</p>
</div>
<div align=center>
    <h1>Grid</h1>
    <h3>gridBox 속성</h3>
    <ul>
        <li>display: grid</li>
        <li>grid-template-columns</li>
        <li>grid-template-rows</li>
        <li>grid-template-areas</li>
        <li>grid-gap: grid-column-gap & grid-row-gap</li>
    </ul>
    <br>
    <h3>grid cell 속성</h3>
    <ul>
        <li>grid-column-start</li>
        <li>grid-column-end</li>
        <li>grid-row-start</li>
        <li>grid-row-end</li>
        <li>grid-area</li>
    </ul>
</div>