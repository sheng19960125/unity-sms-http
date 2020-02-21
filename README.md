# unity-sms-http
## unity 基本介面拉版
1.標籤頁Hierarchy -> SampleScene -> 空白處建立(UI -> Canvas) -> 再以主要之Canvas右鍵立(UI -> 選擇你自己想要的Input)    
Canvas：UI類似畫布那種，所有的UI圖片(包含Button樣子、Text、Image)都會在以此為基礎下做渲染        
EventSystem：UI的事件系統，所有事件將會經過這個做副署，EX：按鈕的點擊...         
2.點選剛剛Click的Input後，在Inspector內會看到隸屬於Canvas的Input控制UI器       
RectTransform组件参数说明其中包含了(位子、旋轉、縮放、苗點等等信息)             
通用組件：       
1.Pos X、Pos Y、Pos Z：物體位子
2.Width、Height：圖片高度、寬度，一般UI裡面放大和缩小圖片的宽度和高度都是通過這裡來控制的，而不是直接调整缩放值。                   
3.Anchors：锚點位置，屏幕的寬高變化时要讓UI依然能按照预想的正常顯示，就需要通過锚點來定位。           
3.Pivot(X、Y)：中心點，該屬性定義圖片的中心點位置，（0.5，0.5）改好為圖片中心。若我们想左右拉長一个橫條，想讓它只在右邊增長，修改中心點位置（0，0.5），中心點位在最左邊，調整Width就會只看到橫條在右方向的長度變化。       
4.Rotation(X、Y、Z)：旋轉值
5.Scale(X、Y、Z)：縮放，這部分是自適應Base為1:1:1，不推存做修改

## unity Project
1.點擊Assets -> Scenes 右鍵創建C# Script        
默認開啟unity的編譯器，這部分也可以自行修改默認開啟的編譯器模式        

