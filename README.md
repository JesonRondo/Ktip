Ktip
====

tip plugin

###call method

    $("#demo").ktip(str, {
        direction: "top",
        offset: 20,
        atX: 0,
        atY: 0
    });
    
###option

    direction: "down"       // 小箭头位于tip的位置[left, top, right, down]
    theme    : "default"    // tips主题
    atX      : 0            // 位于目标的位置的x坐标，若为负，则与原点相对的位置为起始位置 偏差1px
    atY      : 0            // 位于目标的位置的y坐标，若为负，则与原点相对的位置为起始位置 偏差1px
    tipWidth : 0            // tip宽度，可定制，小于等于0为不设宽度
    stick    : 0            // tip保持毫秒速
    offset   : 15           // 小箭头的偏移量
    triangle : true         // 是否需要trangle
    closeBtn : true         // 是否需要close btn
    hover    : false        // hover模式，鼠标移走tip消失
    callback : null         // 加载完后的回调函数
    zIndex   : null         // z轴
    closeCallback: null     // 关闭后的回调函数 arg: $cntbox