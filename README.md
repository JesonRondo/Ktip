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

    direction: "down"       // С��ͷλ��tip��λ��[left, top, right, down]
    theme    : "default"    // tips����
    atX      : 0            // λ��Ŀ���λ�õ�x���꣬��Ϊ��������ԭ����Ե�λ��Ϊ��ʼλ�� ƫ��1px
    atY      : 0            // λ��Ŀ���λ�õ�y���꣬��Ϊ��������ԭ����Ե�λ��Ϊ��ʼλ�� ƫ��1px
    tipWidth : 0            // tip��ȣ��ɶ��ƣ�С�ڵ���0Ϊ������
    stick    : 0            // tip���ֺ�����
    offset   : 15           // С��ͷ��ƫ����
    triangle : true         // �Ƿ���Ҫtrangle
    closeBtn : true         // �Ƿ���Ҫclose btn
    hover    : false        // hoverģʽ���������tip��ʧ
    callback : null         // �������Ļص�����
    zIndex   : null         // z��
    closeCallback: null     // �رպ�Ļص����� arg: $cntbox