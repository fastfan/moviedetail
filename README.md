# moviedetail
douban movie detail


΢��С����Reader&Movie 
===================================  
   
������Ŀ
-----------------------------------  
 #### ����΢��web�����߹��ߣ�clone��Ŀ�����أ���΢��web�����ߴ���Ŀ��ģ�����ϣ������CTRL+S���鿴��Ŀ
      git clone https://github.com/sunshine824/WeChat_Reader-Movie.git
 #### ���ģ������Ч�����£�
  ![](https://github.com/sunshine824/WeChat_Reader-Movie/blob/master/static/jdfw.gif)
  
 ��Ŀ�ṹ
-----------------------------------
```javascript
.
������ README.md
������ data                                    // �Զ���data����
������ images                                  //��̬ͼƬ�ļ���
������ pages
��   ������ movies                              //��Ӱģ��
��   ��   ������ more-movie                      //�����Ӱҳ��
��   ��   ��   ������ more-movie.js
��   ��   ��   ������ more-movie.json             //more-movie�����ļ�
��   ��   ��   ������ more-movie.wxml
��   ��   ��   ������ more-movie.wxss
��   ��   ������ movie                           //������Ӱ���
��   ��   ������ movie-grid                      //���е�Ӱ���ϵ����
��   ��   ������ more-list                       //���������Ӱ�б�
��   ��   ������ movie-detail                    //��Ӱ����
��   ��   ������ stars                           //�������
��   ��   ������ movies.js                       //��Ӱģ��ű�
��   ��   ������ movies.json
��   ��   ������ movies.wxml 
��   ��   ������ movies.wxss
��   ������ posts                              //����ģ��
��   ��   ������ post-detail                    //�����������
��   ��   ������ post-item                      //�����������
��   ��   ������ post.js 
��   ��   ������ post.json  
��   ��   ������ post.wxml 
��   ��   ������ post.wxss
��   ������ welcome                           //��ӭ����ļ�
��   ��   ������ welcome.js 
��   ��   ������ welcome.json  
��   ��   ������ welcome.wxml 
��   ��   ������ welcome.wxss
������ untils                               //��������ģ��
������ ������ untils.js
������ app.js
������ app.json                            //���������ļ�
������ app.wxss                            //������ʽ��
������ static
```

 ע������
-----------------------------------
      1.������������ֲ�:vertical="{{true}}"

      2.�����ֹ�¼�ð��:catch+�¼�

      3.wx.navigateTo ��ƽ����ת������ҳ��������ҳ�� ��ת��ᴥ�� onHide
        wx.redirectTo ��ƽ����ת ��ת��ᴥ�� onUnload 

      4.���ҳ��ʹ����tabBar�����ֻ��ʹ��wx.switchTabʵ����ת��wx.navigateTo��wx.redirectTo����

      5.Ϊʲô����֡��ű��������δ��ȷ����Page()���Ĵ�����ʾ��
       *������������ԭ��ͨ������Ϊ��Ӧҳ���js�ļ��û�е���Page��������ʹjs�ļ���û���κδ��룬Ҳ��Ҫ��js�����һ���յ� Page({})��ע��Page��PҪ��д��

      6.Ϊʲô����֡�Expecting ��String����Number����NULL����True....���������Ĵ�����ʾ��
       *������������ԭ�����ڶ�Ӧҳ���json�ļ�û�м���{ }����ʹjson�ļ���û���κ����ݣ�Ҳ��Ҫ����һ��{ }����ΪĬ�ϴ��롣json�ļ����������ע�ʹ��룬�����ע�͵Ĵ��룬ͬ���ᱨ�������

      7.Ϊʲô ���֡� Failed to load image http://2110932784.debug.open.weixin.qq.com/pages/posts/images/post/crab.png : the server responded with a status of 404 (HTTP/1.1 404 Not Found) From server 127.0.0.1��
       *�������Ƶ����ִ���ͨ��������ͼƬ��·�����Զ�����ġ�������ͼƬ���������ﲻ��˵�ˣ���Ϊû����Ժ;��Ե�·�������������˾�����������ͼƬurl���ˡ�����˵˵���ص�ͼƬ·�����⡣��ע�⣬���ͼƬ·����д��һ��js�ļ�A���B���������js�ļ�����ôͼƬ��·�������������B�����·�������ԣ�����ڹ�����js�ļ���ʹ�þ���·����
       ����һ�㣬���Ѵ�ң�С�������Դ�ļ�������ͼƬ���л���ģ�������Ҫע�⡣

### ����ע��������鿴[С����ע������](https://zhuanlan.zhihu.com/oldtimes)

### �������� ���� ɨ��ά��
 ![](https://github.com/sunshine824/WeChat_Reader-Movie/blob/master/static/IMG_0137.PNG)
 ![](https://github.com/sunshine824/WeChat_Reader-Movie/blob/master/static/IMG_0138.PNG)
 ![](https://github.com/sunshine824/WeChat_Reader-Movie/blob/master/static/IMG_0139.PNG)
 ![](https://github.com/sunshine824/WeChat_Reader-Movie/blob/master/static/IMG_0140.PNG)
 ![](https://github.com/sunshine824/WeChat_Reader-Movie/blob/master/static/IMG_0141.PNG)
