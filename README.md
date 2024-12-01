<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="kiso.css">
</head>
<body>
    <h1>あなたのいいところは?</h1>
    <p>診断したい名前を入れてください。</p>
    <input type="text" id="user-name" sie="20" maxlength="20">
    <button id="assessment">診断する</button>
    <div id="result-area"></div>
    <div id="tweet-area">
        <br>
    <a href="https://twitter.com/intent/tweet?button_hashtag=あなたのいいとこころ&ref_src=twsrc%5Etfw" class="twitter-hashtag-button" data-text="診断結果の文章を一時的に入れる" data-show-count="false">Tweet #あなたのいいとこころ</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
    </div>
    <script src="kiso.js"></script>
</body>
</html>