<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />

<style>
    html {
        line-height: 1.15;
        -webkit-text-size-adjust: 100%;
    }

    body {
        margin: 0;
    }

    hr {
        box-sizing: content-box;
        height: 0;
        overflow: visible;
    }

    pre {
        font-family: monospace, monospace;
        font-size: 1em;
    }

    a {
        background-color: transparent;
    }

    abbr[title] {
        border-bottom: none;
        text-decoration: underline;
        text-decoration: underline dotted;
    }

    b,
    strong {
        font-weight: bolder;
    }

    code,
    kbd,
    samp {
        font-family: monospace, monospace;
        font-size: 1em;
    }

    small {
        font-size: 80%;
    }

    sub {
        font-size: 1rem;
        line-height: 0;
        position: relative;
        vertical-align: baseline;
        bottom: -0.25em;
        color: #999;
    }

    img {
        border-style: none;
    }

    button,
    input,
    optgroup,
    select,
    textarea {
        font-family: inherit;
        font-size: 100%;
        line-height: 1.15;
        margin: 0;
    }

    button,
    input {
        overflow: visible;
    }

    button,
    select {
        text-transform: none;
    }

    [type='button'],
    [type='reset'],
    [type='submit'],
    button {
        -webkit-appearance: button;
    }

    [type='button']::-moz-focus-inner,
    [type='reset']::-moz-focus-inner,
    [type='submit']::-moz-focus-inner,
    button::-moz-focus-inner {
        border-style: none;
        padding: 0;
    }

    [type='button']:-moz-focusring,
    [type='reset']:-moz-focusring,
    [type='submit']:-moz-focusring,
    button:-moz-focusring {
        outline: 1px dotted ButtonText;
    }

    fieldset {
        padding: 0.35em 0.75em 0.625em;
    }

    legend {
        box-sizing: border-box;
        color: inherit;
        display: table;
        max-width: 100%;
        padding: 0;
        white-space: normal;
    }

    progress {
        vertical-align: baseline;
    }

    textarea {
        overflow: auto;
    }

    [type='checkbox'],
    [type='radio'] {
        box-sizing: border-box;
        padding: 0;
    }

    [type='number']::-webkit-inner-spin-button,
    [type='number']::-webkit-outer-spin-button {
        height: auto;
    }

    [type='search'] {
        -webkit-appearance: textfield;
        outline-offset: -2px;
    }

    [type='search']::-webkit-search-decoration {
        -webkit-appearance: none;
    }

    ::-webkit-file-upload-button {
        -webkit-appearance: button;
        font: inherit;
    }

    details {
        display: block;
    }

    summary {
        display: list-item;
    }

    [hidden],
    template {
        display: none;
    }

    * {
        -webkit-box-sizing: border-box;
        box-sizing: border-box;
    }

    ::-moz-selection {
        background: #00d2ff;
    }

    ::selection {
        background: #00d2ff;
    }

    body,
    html {
        font-size: 100%;
        font-family: -apple-system, 'BlinkMacSystemFont', 'Segoe UI',
            'Roboto', 'Helvetica', 'Arial', sans-serif,
            'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol','malgun gothic';
        word-break: keep-all;
        letter-spacing: -0.3px;
        color: #14142b;
        padding-bottom: 2rem;
        overflow-x: hidden;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
    }

    @media screen and (max-width: 960px) {
        body,
        html {
            font-size: 14px;
        }
    }
    section {
        padding: 0 2rem;
    }

    p {
        margin: 0 0 1rem;
        font-size: 1.1rem;
        line-height: 1.4;
    }

    a {
        color: #14142b;
        -webkit-transition: color 0.3s ease;
        transition: color 0.3s ease;
        text-decoration: none;
    }

    a:hover {
        color: #14142b;
    }

    h1 {
        font-size: 3rem;
        letter-spacing: -1.5px;
        margin: 3rem 0 2.5rem;
    }

    @media screen and (max-width: 960px) {
        h1 {
            font-size: 2rem;
            margin: 3rem 0 2rem;
        }
    }

    h2 {
        font-size: 2rem;
        margin: 3rem 0 1rem;
    }

    h3 {
        font-size: 1.5rem;
        margin: 0 0 1rem;
    }
    h4 {
        font-size: 1.4rem;
        margin: 0 0 1rem;
    }

    @media screen and (max-width: 960px) {
        h4 {
            font-size: 1.25rem;
            margin: 0;
        }
    }

    h5 {
        font-size: 1.2rem;
        margin: 0 0 0.5rem;
        color: #333;
    }

    ul {
        list-style: none;
        padding: 0;
        margin: 1rem 0;
        font-size: 1.1rem;
    }
    ul li ul {
        margin: 0;
    }
    .container {
        width: 100%;
        max-width: 50rem;
        margin: auto;
    }

    .paragraph {
        font-size: 1.5rem;
        line-height: 1.4;
        font-weight: 500;
    }

    @media screen and (max-width: 960px) {
        .paragraph {
            font-size: 1.125rem;
        }
    }

    .row {
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        padding: 1rem 0;
        border-bottom: 1px solid #efefef;
    }
    .row:last-child {
        border: none;
    }

    .row-left {
        -ms-flex-preferred-size: 18rem;
        flex-basis: 16rem;
        padding-right: 1rem;
        -ms-flex-negative: 0;
        flex-shrink: 0;
    }

    .row-right {
        -webkit-box-flex: 1;
        -ms-flex-positive: 1;
        flex-grow: 1;
    }

    @media screen and (max-width: 960px) {
        .row {
            -webkit-box-orient: vertical;
            -webkit-box-direction: normal;
            -ms-flex-direction: column;
            flex-direction: column;
        }

        .row-left {
            -ms-flex-preferred-size: 100%;
            flex-basis: 100%;
            padding-right: 0;
            padding-bottom: 1rem;
        }
    }
    .row ul > li {
        position: relative;
        padding: 0.2rem 0 0.2rem 1rem;
        font-weight: bold;
    }

    .row ul > li ul li {
        font-weight: 400;
    }
    .skill-group {
        padding: 1rem 0 0;
        border-bottom: 1px solid #efefef;
    }
    ul.skill > li {
        display: inline-block;
        padding: 0 0.1rem 0.4rem 0;
    }

    ul.skill span {
        display: block;
        color: white;
        border-radius: 1.5rem;
        padding: 2px 10px;
        font-size: 1rem;
    }
    ul.skill span.level1,
    ul.skill span.etc {
        background-color: white;
        border: 1px solid #eff0f6;
        color: #bca4ff;
    }
    ul.skill span.level2 {
        background-color: #bca4ff;
        border: 1px solid #bca4ff;
    }
    ul.skill span.level3 {
        background-color: #5f2eea;
        border: 1px solid #5f2eea;
    }

    .role {
        display: block;
    }

    .project {
        padding: 0;
    }

    .time {
        display: block;
        margin-bottom: 1.5rem;
    }
    .anchorjs-link {
        font: 1em / 1 anchorjs-icons;
        padding-left: 0.375em;
        margin-left: -0.375em;
    }
    ul.contact li {
        padding:0.5rem 0;
    }
    ul.contact span {
        font-weight: 500;
        padding: 0 0.5rem 0 0;
    }
</style>

<div class="container">
    <section>
        <h1 id="최영화">
            <a
                class="anchorjs-link"
                href="#최영화"
                aria-label="최영화"
                data-anchorjs-icon=""
            ></a>
            최영화<br />9년 차 프런트엔드&백엔드 개발자
        </h1>
        <p class="paragraph">
            웹 서비스를 설계/개발/배포/운영한 경험이 있으며, 비즈니스
            가치 구현을 위한 최선의 방법을 찾기 위해 항상 고민하고
            있습니다.<br /><br />
            유지보수성을 고민합니다. 중복코드와 반복작업을 틈틈히
            리팩토링 하여 예상하지 못했던 이슈에 대비하고 생산성을 향상
            시킵니다.<br /><br />
            구성원 간의 신뢰를 바탕으로 주도적으로 업무를 진행할 수 있는
            밝고 건강한 조직을 선호합니다.
        </p>
        <ul class="contact">
            <li>
                <span>Github</span>
                <a
                    href="mailto:nice1st_p@naver.com"
                    title="이메일 보내기"
                    >nice1st_p@naver.com</a
                >
            </li>
            <li>
                <span>E-mail</span>
                <a
                    href="https://github.com/nice1st"
                    title="github 블로그로 이동"
                    target="_blank"
                    >https://github.com/nice1st</a
                >
            </li>
        </ul>
    </section>
    <section>
        <h2 id="skills">
            <a
                class="anchorjs-link"
                href="#skills"
                aria-label="skills"
                data-anchorjs-icon=""
            ></a
            >Skills
        </h2>
        <div id="back-end" class="skill-group">
            <h3>
                <a
                    class="anchorjs-link"
                    href="#back-end"
                    aria-label="back-end"
                    data-anchorjs-icon=""
                ></a>
                Back-End
            </h3>
            <ul class="skill horizon5">
                <li><span class="level3">JAVA</span></li>
                <li><span class="level3">Spring</span></li>
                <li><span class="level3">JPA</span></li>
                <li><span class="level2">Spring Cloud MSA</span></li>
                <li><span class="level2">JWT</span></li>
                <li><span class="level2">Gradle</span></li>
                <li><span class="level1">RabbitMQ</span></li>
                <li><span class="level1">NodeJS</span></li>
                <li><span class="level2">Dotnet</span></li>
                <li><span class="level2">Mysql</span></li>
                <li><span class="level1">Redis</span></li>
            </ul>
        </div>
        <div id="front-end" class="skill-group">
            <h3>
                <a
                    class="anchorjs-link"
                    href="#front-end"
                    aria-label="front-end"
                    data-anchorjs-icon=""
                ></a>
                Front-End
            </h3>
            <ul class="skill horizon5">
                <li><span class="level3">Javascript</span></li>
                <li><span class="level3">ES6</span></li>
                <li><span class="level2">VanillaJS</span></li>
                <li><span class="level1">React</span></li>
                <li><span class="level2">Web Component</span></li>
                <li><span class="level2">Babel</span></li>
                <li><span class="level2">Webpack</span></li>
                <li><span class="level2">D3</span></li>
            </ul>
        </div>
        <div id="etc" class="skill-group">
            <h3>
                <a
                    class="anchorjs-link"
                    href="#etc"
                    aria-label="etc"
                    data-anchorjs-icon=""
                ></a>
                ETC
            </h3>
            <ul class="skill horizon5">
                <li><span class="etc">Git</span></li>
                <li><span class="etc">SVN</span></li>
                <li><span class="etc">Jenkins</span></li>
                <li><span class="etc">Docker</span></li>
                <li><span class="etc">Linux</span></li>
                <li><span class="etc">Vi</span></li>
                <li><span class="etc">Redmine</span></li>
            </ul>
        </div>
    </section>
    <section>
        <h2 id="Work Experience">
            <a
                class="anchorjs-link"
                href="#Work Experience"
                aria-label="Work Experience"
                data-anchorjs-icon=""
            ></a>
            Work Experience
        </h2>
        <div class="row">
            <div class="row-left">
                <h3 id="KTICT">
                    <a
                        class="anchorjs-link"
                        href="#KTICT"
                        aria-label="KTICT"
                        data-anchorjs-icon=""
                    ></a
                    >KTICT
                </h3>
                <!-- <span class="role">Front-End Engineer</span> -->
                <span>
                    <time datetime="2020-06">2020.06</time> - 현재
                </span>
            </div>
            <div class="row-right">
                <div class="project">
                    <h4 id="CCTV 웹 뷰어 개발">
                        <a
                            class="anchorjs-link"
                            href="#CCTV 웹 뷰어 개발"
                            aria-label="CCTV 웹 뷰어 개발"
                            data-anchorjs-icon=""
                        ></a>
                        CCTV 웹 뷰어 개발
                    </h4>
                    <ul>
                        <li>
                            외주 인력에 의해 개발 된 프로젝트 유지보수
                            및 내재화 진행
                        </li>
                        <li>
                            개발 구조 설계 및 개발
                            <ul>
                                <li>
                                    Spring Cloud 기반 MSA 설계 및 개발
                                </li>
                                <li>데이터 모델링 및 RDB 설계</li>
                                <li>컴포넌트 기반 UI 개발</li>
                            </ul>
                        </li>
                    </ul>
                    <ul class="skill">
                        <li><span class="level3">JAVA</span></li>
                        <li><span class="level3">Spring Boot</span></li>
                        <li>
                            <span class="level2"
                                >Spring Cloud Eureka</span
                            >
                        </li>
                        <li>
                            <span class="level2"
                                >Spring Cloud Zuul</span
                            >
                        </li>
                        <li><span class="level2">Hibernate</span></li>
                        <li><span class="level2">JWT</span></li>
                        <li><span class="level2">Mysql</span></li>
                        <li><span class="level1">RabbitMQ</span></li>
                        <li><span class="level3">Javascript</span></li>
                        <li><span class="level2">Babel</span></li>
                        <li><span class="level2">Webpack</span></li>
                        <li><span class="level2">Dotnet</span></li>
                    </ul>
                    <ul>
                        <li>
                            DevOps 환경 구축
                            <ul>
                                <li>Jenkins 도입하여 배포 자동화</li>
                            </ul>
                        </li>
                    </ul>
                    <ul class="skill">
                        <li><span class="etc">Jenkins</span></li>
                        <li><span class="etc">Git</span></li>
                        <li><span class="etc">Gradle</span></li>
                        <li><span class="etc">Docker</span></li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="row-left">
                <h3 id="띵스파이어">
                    <a
                        class="anchorjs-link"
                        href="#띵스파이어"
                        aria-label="띵스파이어"
                        data-anchorjs-icon=""
                    ></a
                    >띵스파이어
                </h3>
                <!-- <span class="role">Front-End Engineer</span> -->
                <span>
                    <time datetime="2019-10">2019.10</time> - 2020.05
                    (6개월)
                </span>
            </div>
            <div class="row-right">
                <div class="project">
                    <h4 id="GIS 기반 유무선 통신장비 관제 UI 개발">
                        <a
                            class="anchorjs-link"
                            href="#GIS 기반 유무선 통신장비 관제 UI 개발"
                            aria-label="GIS 기반 유무선 통신장비 관제 UI 개발"
                            data-anchorjs-icon=""
                        ></a>
                        GIS 기반 유무선 통신장비 관제 UI 개발
                    </h4>
                    <ul>
                        <li>
                            컴플레인 발생시 고객 정보를 통해 장애구간을
                            바로 확인할 수 있도록 설계하여 응대 속도를
                            높임
                        </li>
                    </ul>
                    <ul class="skill">
                        <li><span class="level3">JAVA</span></li>
                        <li><span class="level2">Nexcore</span></li>
                        <li><span class="level2">oracle</span></li>
                        <li><span class="level3">Javascript</span></li>
                        <li><span class="level3">JQuery</span></li>
                        <li><span class="level1">TMap API</span></li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="row-left">
                <h3 id="파이오링크">
                    <a
                        class="anchorjs-link"
                        href="#파이오링크"
                        aria-label="파이오링크"
                        data-anchorjs-icon=""
                    ></a
                    >파이오링크
                </h3>
                <!-- <span class="role">Front-End Engineer</span> -->
                <span>
                    <time datetime="2016-11">2016.11</time> - 2019.08
                    (2년 9개월)
                </span>
            </div>
            <div class="row-right">
                <div class="project">
                    <h4 id="네트워크 스위치 컨트롤러">
                        <a
                            class="anchorjs-link"
                            href="#네트워크 스위치 컨트롤러"
                            aria-label="네트워크 스위치 컨트롤러"
                            data-anchorjs-icon=""
                        ></a>
                        네트워크 스위치 컨트롤러
                    </h4>
                    <ul>
                        <li>
                            장비와 소켓 통신을 통해 데이터를 수집하고
                            관제 및 컨트롤 서비스 설계 및 개발
                        </li>
                        <li>
                            실시간 통신 모듈로 성능 및 유저 사용성 개선
                            <ul>
                                <li>
                                    장비로부터 수집 된 데이터를
                                    Broadcast 가능한 pub/sub 패턴 모듈을
                                    개발
                                </li>
                                <li>
                                    D3 컴포넌트 등 으로 실시간 데이터를
                                    시각화 하여 유저 사용성 개선
                                </li>
                                <li>
                                    웹 소켓 게이트웨이 모듈로 성능 향상
                                </li>
                            </ul>
                        </li>
                        <li>
                            스케일 아웃으로 성능 향상
                            <ul>
                                <li>서버 스케일 아웃 설계</li>
                                <li>
                                    Redis 도입하여 성능 향상 및 서버
                                    동기화
                                </li>
                                <li>
                                    GlusterFS 도입하여 서버 리소스
                                    동기화
                                </li>
                                <li>
                                    Redis 와 Elastic Search 클러스터링
                                </li>
                            </ul>
                        </li>
                        <li>
                            API 성능 개선
                            <ul>
                                <li>
                                    QueryDSL 활용하여 쿼리 성능 개선
                                </li>
                                <li>코드 리팩토링으로 성능 개선</li>
                            </ul>
                        </li>
                        <li>
                            개발 생산성 향상
                            <ul>
                                <li>
                                    웹 컴포넌트기반 개발을 도입하여
                                    생산성과 안정성 향상
                                </li>
                            </ul>
                        </li>
                        <li>
                            위자드 컴포넌트 설계 및 개발 하여 사용성
                            개선
                        </li>
                        <li>
                            DocumentFragment 활용하여 DOM rendering 성능
                            개선
                        </li>
                        <li>조직 문화 개선에 진취적으로 임함</li>
                    </ul>
                    <ul class="skill">
                        <li><span class="level3">JAVA</span></li>
                        <li><span class="level3">Spring Boot</span></li>
                        <li><span class="level2">Netty</span></li>
                        <li>
                            <span class="level1">Elastic Search</span>
                        </li>
                        <li><span class="level2">Mysql</span></li>
                        <li><span class="level1">Redis</span></li>
                        <li><span class="level1">GlusterFS</span></li>
                        <li><span class="level3">Javascript</span></li>
                        <li><span class="level3">JQuery</span></li>
                        <li><span class="level2">D3</span></li>
                        <li><span class="level2">Babel</span></li>
                        <li><span class="level2">Webpack</span></li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="row-left">
                <h3 id="다임즈">
                    <a
                        class="anchorjs-link"
                        href="#다임즈"
                        aria-label="다임즈"
                        data-anchorjs-icon=""
                    ></a
                    >다임즈
                </h3>
                <!-- <span class="role">Front-End Engineer</span> -->
                <span>
                    <time datetime="2011-07">2011.07</time> - 2016.04
                    (4년 9개월)
                </span>
            </div>
            <div class="row-right">
                <div class="project">
                    <h4 id="EMS 통합관제">
                        <a
                            class="anchorjs-link"
                            href="EMS 통합관제"
                            aria-label="EMS 통합관제"
                            data-anchorjs-icon=""
                        ></a>
                        EMS 통합관제
                    </h4>
                    <ul>
                        <li>
                            네트워크, 트래픽, 서버, DBMS 등의 장비에서
                            수집 된 정보를 대시보드로 서비스 하는 웹
                            어플리케이션 개발
                        </li>
                        <li>
                            유저 사용성 개선
                            <ul>
                                <li>
                                    Flexible 한 대시보드를 설계 하여
                                    사용성 개선
                                </li>
                                <li>MDI UI 로 유저 커스텀 기능 제공</li>
                                <li>
                                    MicroOffice 리본 메뉴 UI 와 Window8
                                    Metro UI 벤치마킹 하여 UX 설계
                                </li>
                            </ul>
                        </li>
                        <li>통계 쿼리 성능 개선</li>
                    </ul>
                    <ul class="skill">
                        <li><span class="level3">JAVA</span></li>
                        <li><span class="level3">Spring</span></li>
                        <li><span class="level2">MariaDB</span></li>
                        <li><span class="level3">Flex</span></li>
                        <li><span class="level2">Mybatis</span></li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
    <section>
        <div align="right">
            <sub><i>Last updated: 2021.04.14</i></sub>
        </div>
    </section>
</div>