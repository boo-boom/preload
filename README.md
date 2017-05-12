# preload
### index-plugin.html
    $('.box2').PreLoad({
        order: 'ordered',
        imgs: imgs,
        all: function () {
            console.log('全部加载完成...');
        }
    });
    
### index-.html
    $.preload(imgs,{
        order: 'ordered'
    });
