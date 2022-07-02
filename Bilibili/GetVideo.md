# 获取视频

- 接口地址：https://api-v1-vc.hotpe.top/bilibili/video/
- 返回格式：flv
- 请求方法：GET
- 示例代码：https://api-v1-vc.hotpe.top/bilibili/video/BV14q4y1V7dW.flv

> 相当于视频直链

视频测试：
<script src="https://cdn.bootcdn.net/ajax/libs/flv.js/1.6.2/flv.min.js"></script>
<video id="videoElement"></video>
<script>
    if (flvjs.isSupported()) {
        var videoElement = document.getElementById('videoElement');
        var flvPlayer = flvjs.createPlayer({
            type: 'flv',
            url: 'https://api-v1-vc.hotpe.top/bilibili/video/BV14q4y1V7dW.flv'
        });
        flvPlayer.attachMediaElement(videoElement);
        flvPlayer.load();
        flvPlayer.play();
    }
</script>
