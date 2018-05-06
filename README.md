# 說明 #
- 大標題是題目
- 打點的是重點註解
- 然後是網路相關文章
- 融合以上內容，做成一個自己想法的文章，說給面試你的人聽


#  Life cycle生命週期 
- APP的生命週期，從出生到程式結束發生的事件(阿伯作業一)

[https://medium.com/@ChunYeung/swift-%E8%AB%87%E8%AB%87%E5%B9%BE%E5%80%8B%E9%87%8D%E8%A6%81%E7%9A%84-ios-app-life-cycle-%E7%94%9F%E5%91%BD%E9%80%B1%E6%9C%9F-93380fe93d95](https://medium.com/@ChunYeung/swift-%E8%AB%87%E8%AB%87%E5%B9%BE%E5%80%8B%E9%87%8D%E8%A6%81%E7%9A%84-ios-app-life-cycle-%E7%94%9F%E5%91%BD%E9%80%B1%E6%9C%9F-93380fe93d95)

[http://www.hangge.com/blog/cache/detail_1319.html](http://www.hangge.com/blog/cache/detail_1319.html "UIViewController生命周期详解")

#  delegate跟protocol的的關係與使用
- protocol是兩個class用來溝通的方法
- delegate是一種設計模式，把功能交給另外一個對象去做，發生事件時要做的事情丟給另外一個class實作
- 在swift當中Delegate是使用protocol實踐
-常見 tableview的delegate

[https://juejin.im/post/59dd7c50f265da431522e1c1](https://juejin.im/post/59dd7c50f265da431522e1c1)

[http://www.hangge.com/blog/cache/detail_810.html](http://www.hangge.com/blog/cache/detail_810.html)

[https://dotblogs.com.tw/toysboy21/2015/02/03/148370](https://dotblogs.com.tw/toysboy21/2015/02/03/148370)
#  ARC機制，什麼是reference count
#  strong 跟 weak 對memeory的差別
- iOS記憶體管理
- 相關的修飾名詞strong,weak...
- 循環強引用造成記憶體不能回收的案例,要懂

[http://wiki.jikexueyuan.com/project/swift/chapter2/16_Automatic_Reference_Counting.html](http://wiki.jikexueyuan.com/project/swift/chapter2/16_Automatic_Reference_Counting.html)

[https://www.jianshu.com/p/eb8ff3b4157b](https://www.jianshu.com/p/eb8ff3b4157b)

[https://www.cnswift.org/automatic-reference-counting](https://www.cnswift.org/automatic-reference-counting)

[https://onevcat.com/2012/06/arc-hand-by-hand/](https://onevcat.com/2012/06/arc-hand-by-hand/)

#  closures 是什麼機制用法?

- 閉包是傳遞沒有名子的func
- 閉包特殊簡略寫法,尾隨閉包
- 閉包被定義的func被呼叫的時間點?

[http://ch-tseng.blogspot.tw/2015/02/swift-closure.html](http://ch-tseng.blogspot.tw/2015/02/swift-closure.html)

[https://medium.com/@mikru168/ios-closure-%E9%96%89%E5%8C%85-cf8ab16d6efc](https://medium.com/@mikru168/ios-closure-%E9%96%89%E5%8C%85-cf8ab16d6efc)
#  MVC架構是什麼及優缺點
- 控制器（Controller） — 負責轉發請求，對請求進行處理。
- 視圖（View） — 介面設計人員進行圖形介面設計。
- 模型（Model） — 程式設計師編寫程式應有的功能（實現演算法等等）、數據庫專家進行數據管理和數據庫設計(可以實現具體的功能)。

[https://wiki.jikexueyuan.com/project/ios-design-patterns-in-swift/mvc.html](https://wiki.jikexueyuan.com/project/ios-design-patterns-in-swift/mvc.html)

[https://medium.com/@nwy0206/%E7%A8%8B%E5%BC%8F%E5%AD%B8%E7%BF%92%E7%AD%86%E8%A8%98-model-view-controller-5a6690e76563](https://medium.com/@nwy0206/%E7%A8%8B%E5%BC%8F%E5%AD%B8%E7%BF%92%E7%AD%86%E8%A8%98-model-view-controller-5a6690e76563)

[https://medium.com/@cwlai.unipattern/app%E9%96%8B%E7%99%BC-%E4%BD%BF%E7%94%A8swift-%E8%A7%80%E5%BF%B5%E4%BB%8B%E7%B4%B9-mvc-a67c7a063ee7](https://medium.com/@cwlai.unipattern/app%E9%96%8B%E7%99%BC-%E4%BD%BF%E7%94%A8swift-%E8%A7%80%E5%BF%B5%E4%BB%8B%E7%B4%B9-mvc-a67c7a063ee7)

#  GCD的使用（Serial, Concurrent, Main dispatch queue）
- Main queue
- 介面上的一定要用main queue
- 其他queue的優先順序
- async, sync(同步,異步)

[http://qiubaiying.top/2017/10/04/GCD-%E5%9C%A8-Swift-%E4%B8%AD%E7%9A%84%E7%94%A8%E6%B3%95/](http://qiubaiying.top/2017/10/04/GCD-%E5%9C%A8-Swift-%E4%B8%AD%E7%9A%84%E7%94%A8%E6%B3%95/)

[https://swiftcafe.io/2016/10/16/swift-gcd/](https://swiftcafe.io/2016/10/16/swift-gcd/)
[https://www.jianshu.com/p/4902b6c3bd34](https://www.jianshu.com/p/4902b6c3bd34)

[https://www.appcoda.com.tw/grand-central-dispatch/](https://www.appcoda.com.tw/grand-central-dispatch/)
#  struct vs class差別
- class可以繼承
- class是reference
- stuct是vlaue 

[http://iosdevelopersnote.blogspot.tw/2014/12/swift-struct-class.html](http://iosdevelopersnote.blogspot.tw/2014/12/swift-struct-class.html)

[https://medium.com/%E5%BD%BC%E5%BE%97%E6%BD%98%E7%9A%84-swift-ios-app-%E9%96%8B%E7%99%BC%E5%95%8F%E9%A1%8C%E8%A7%A3%E7%AD%94%E9%9B%86/%E5%8F%96%E5%BE%97-swift-%E7%89%A9%E4%BB%B6%E7%9A%84%E8%A8%98%E6%86%B6%E9%AB%94%E4%BD%8D%E7%BD%AE-8ed0f1aaf051](https://medium.com/%E5%BD%BC%E5%BE%97%E6%BD%98%E7%9A%84-swift-ios-app-%E9%96%8B%E7%99%BC%E5%95%8F%E9%A1%8C%E8%A7%A3%E7%AD%94%E9%9B%86/%E5%8F%96%E5%BE%97-swift-%E7%89%A9%E4%BB%B6%E7%9A%84%E8%A8%98%E6%86%B6%E9%AB%94%E4%BD%8D%E7%BD%AE-8ed0f1aaf051)

[http://blog.51cto.com/13533483/2050344](http://blog.51cto.com/13533483/2050344)
#  frame 與bounds的差異 ?
- 連結裡面一張圖就搞懂了

[https://www.jianshu.com/p/964313cfbdaa](https://www.jianshu.com/p/964313cfbdaa)
