# **類圖與對象圖**

Unified Modeling Language (UML) 是一種軟體工程中廣泛使用的圖形建模語言，旨在幫助軟體開發人員更好地理解、設計和描述軟體系統。其中，UML中的類圖和對象圖是兩個重要的建模工具。

# **UML類圖：**
UML類圖用於描述系統中的類別（或物件類型）以及它們之間的關係。它包括了類別的名稱、屬性（數據成員）、方法（行為），以及它們之間的關聯，例如繼承、關聯、聚合等。類圖通常用於軟體設計的早期階段，有助於規劃系統的架構和模組結構，確保程式碼的模組化和可維護性。它有助於團隊成員共享對系統結構的共同理解。

**目的：評估和規劃應用程式的靜態視圖；規定係統的職責；建立基礎元件圖和配置圖；執行正向和逆向工程。**

_**以下是類圖的範例:**_

![image](https://github.com/MikazukiWai/-01/blob/main/image/01.png)

在類圖中,我使用了動物中的鳥類來描述它們之間的聯繫和一些共同點

在上面的類圖中,我們有一個大類[**動物**]類和一個通用的[**鳥類**]類,它有[**羽毛**]和[**沒有牙齒**]兩個屬性以及[**卵生**]方法。

然后,我們有三個子類,分別是[**企鵝**],[**雞**]和[**鷹**]它們繼承了[**鳥類**]類,並具有各自的屬性,比如[**羽毛**]。

然後我在[**企鵝**]類中因為企鵝是在固定的環境在能生存

在大類[**動物**]類和[**氧氣/水**]類中我使用了虛線表示它們的[**依賴關係**]





# **UML對象圖：**
UML對象圖則是對系統中實際對象的實例進行建模。它展示了特定時刻系統中的對象以及它們之間的關係。對象圖關注的是對象的狀態和互動，有助於理解特定情境下的系統運作。這些圖通常用於軟體設計的更高層次，用於探討特定使用案例或場景下的對象交互。

**目的:在特定時刻可視化系統中的物件實例以及它們的狀態，以幫助理解和分析系統的動態結構。**

_**以下是對象圖的範例:**_

![image](https://github.com/MikazukiWai/-01/blob/main/image/02.png)

物件圖描述了特定時刻系統中的物件實例。在這個範例中，我們創建了幾個動物物件的範例：

這些物件代表了三個不同動物的實例:一個叫[**哺乳類**],[**魚類**]和[**鳥類**]的動物類。

每個物件都有自己的屬性值，比如[**哺乳類**]的陸地生活,[**魚類**]的海洋生活,[**鳥類**]的可以飛翔等等。

對象圖用於在某個時間點上系統中對象的實例和它們的狀態。在這個範例中，我只展示了三個對象，但實際系統中還有更多的對象實例，以及它們之間的關係。




# **類圖和對象圖的差別**

**類圖:** 用於描述系統中所包含的類別以及它們之間的相互關係。

**對象圖:** 用來描述某一時刻的一組物件及它們之間的關係。

兩個概念拎出來一對比，差異就很明顯了，在於後者多了「某一時刻」。

因此，物件圖可以視為類別圖的實例，用來表達各個物件在某一時刻的狀態。

物件圖中的建模元素主要有物件和鏈，物件是類別的實例，鍊是類別之間的關聯關係的實例。









# **參考資料**

https://blog.csdn.net/zll_0405/article/details/78898597

https://www.cnblogs.com/lyp3314/archive/2011/11/23/2260059.html

http://www.uml.org.cn/modeler/201909124.asp
