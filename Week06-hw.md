# 游戲功能性需求與非功能性需求


---
# 功能分解圖-Functional Decomposition Diagram
![](FDD.png "Functional Decomposition Diagram")
## [Figma_Prototype](https://www.figma.com/proto/MvdXjIDhOMf1wYrrSlkXxd/Untitled?node-id=2%3A2&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=2%3A2&show-proto-sidebar=1)

# 需求分析的文字描述
1. #### 玩家可點擊開始遊戲來遊玩
2. #### 遊戲開發人員可改變關卡設置
3. #### 玩家可透過控制滑鼠來遊玩關卡
4. #### 玩家可點擊設置來改變操作 
1. ## 鏡頭移動
- #### 拖曳彈弓前，鏡頭可以隨玩家所欲移動，發射小鳥后，鏡頭以小鳥為中心移動。(include)
2. ## 背景音樂
- #### 游戲中的背景音效，小鳥飛出及擊中的音效,按鍵音效。(extend)
3. ## 彈弓拖曳及小鳥飛出
- #### 通過滑鼠對彈弓進行拖曳，進而控制小鳥飛出。(include)
4. ## 敵人及場景創建
- #### 在關卡中以各種障礙物創建場景，並在場景上生成敵人。不同障礙物有不同的特性。(include)
5. ## 碰撞實現
- #### 添加碰撞效果，包括小鳥與障礙物及敵人的碰撞，障礙物與障礙物的碰撞。(include)
6. ## UI功能
- #### 游戲界面中顯示當前狀態下游戲得分、星星數量。
- #### 進入游戲先進入選擇關卡的界面，如果在關卡中沒有獲得所有星星，可以選擇重新。(include)
