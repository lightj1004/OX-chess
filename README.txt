網路程式設計 hw2
學號：406410007
姓名：何明杰

執行步驟:
1. make
2. ./server -> 新增server 
3. ./client 0.0.0.0 -> 新增client端

如何進行遊戲:

1. 輸入使用者名稱 -> "1 姓名"
2. 顯示線上使用者 -> "2"
3. 邀請其他使用者 -> "3 邀請者 被邀請者"
4. 接收使用者邀請 -> "4 邀請者 invite 被邀請者"	
5. 被邀請者的回應 -> 不接受 -> "5 0 邀請者"
        	       -> 接受 -> "5 1 邀請者"
6. 邀請者與被邀請者接收server訊息 -> "6"  \\開始遊戲，印出棋盤
7. 開始下棋 -> "棋盤位址" \\-0~-8 i.e. -2

棋盤格式:
 0 -> 未使用    棋盤位址： -0 -1 -2
 1 -> 邀請者             -3 -4 -5
 2 -> 被邀者             -6 -7 -8

8. 登出 -> "logout"





