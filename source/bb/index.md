---
title: 唠叨
date: 2023-05-21 11:43:44
comments: false
---
<head>
  <!-- ... -->
  <meta http-equiv="Cache-Control" content="no-cache, no-store, must-revalidate">
  <meta http-equiv="Pragma" content="no-cache">
  <meta http-equiv="Expires" content="0">

  <script>
    function loadJS(src, callback) {
      var script = document.createElement('script');
      script.src = src;
      script.addEventListener('load', callback);
      document.head.appendChild(script);
    }

    loadJS('//cdn.jsdelivr.net/gh/Uyoahz26/daodao@main/dist/qexo-dao.min.js', function() {
      qexoDaodao?.init({
        el: "#qexoDaoDao",
        avatar: "https://cdn.jsdelivr.net/gh/hzy-a/picx-images-hosting@master/20230528/QQ图片20230528220731.28o7n9mukqqs.webp",
        name: "hzy",
        limit: 10,
        useLoadingImg: false,
        baseURL: "https://hexo.hzyi.eu.org/",
        format: "yyyy年MM月dd日",
      }).then(function (){
        console.log("qexoDaodao加载完成");
      });
    });
  </script>
  <!-- ... -->
</head>
<body>
  <!-- ... -->
  <div id="qexoDaoDao"></div>
</body>

