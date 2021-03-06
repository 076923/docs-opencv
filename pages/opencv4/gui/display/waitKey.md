---
title: 키 입력 대기
sidebar: opencv4_sidebar
permalink: waitKey
folder: opencv4
---

<div class="row">
    <div class="col-lg-12">
        <h2 class="page-header">waitKey</h2>
    </div>
    <div class="col-lg-12">

        <ul id="myTab" class="nav nav-tabs nav-justified">
            <li class="active"><a href="#service-one" data-toggle="tab"><i class="fa fa-support"></i> C++</a>
            </li>
            <li class=""><a href="#service-two" data-toggle="tab"><i class="fa fa-support"></i> C#</a>
            </li>
            <li class=""><a href="#service-three" data-toggle="tab"><i class="fa fa-support"></i> Python</a>
            </li>
        </ul>

        <div id="myTabContent" class="tab-content">
            <div class="tab-pane fade active in" id="service-one">
<pre class="prettyprint"><code class="language-cpp">int cv::waitKey(
    int delay = 0
)</code></pre>
            </div>
            <div class="tab-pane fade" id="service-two">
<pre class="prettyprint"><code class="language-cs">int Cv2.WaitKey(
    int delay = 0
)</code></pre>
            </div>
            <div class="tab-pane fade" id="service-three">
<pre class="prettyprint"><code class="language-py">retval = cv2.waitKey(
    delay = None
)</code></pre>
            </div>
        </div>
    </div>
</div>

<br>

{{site.data.alerts.important}}
하나 이상의 윈도우 창이 존재할 경우에만 작동합니다.
{{site.data.alerts.end}}

<br>

### 요약(Summary)

> 키 이벤트 발생까지 대기하거나, 지정된 시간까지 대기합니다. 키 이벤트가 발생하면 해당 키 값을 반환합니다.

### 매개변수(Parameter)

> `대기(delay)` 밀리초(millisecond, ms)만큼 대기합니다.

### 반환값(Returns)

> `키 값(retval)` 눌러진 키의 값을 반환
