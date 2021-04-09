<!doctype html>
<html lang="ko">
    <head><head>5
    <body>
        <style>
        li {
            list-style:none;
        }
        .blockTag{
            background-color: yellowgreen;
        }
        .blockTag > div{
            background:tomato;
            border:1px solid black;
        }

        .inlineTag span{
            background-color: skyblue;
            border: 1px solid black;
        }
        </style>
        <div class="blockTag">
            <div>block 1</div> <!--세로로 떨어진다.-->
            <div>block 2</div>
            <div>block 3</div>
        </div>

        <div class="inlineTag">
            <span>inline 1</span> <!--가로로 떨어진다.-->
            <span>inline 2</span>
            <span>inline 3</span>
        </div>
    </body>
</html>
