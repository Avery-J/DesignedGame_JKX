# DesignedGame_JKX
# 凑数游戏(0, 5, 10)
input Hnum1，Hnum2，Hresult
output Winner

Rnumlist1＝［None，None］
Rnumlist2＝［0，5，10］
Rresultlist＝［0，5，10，15，20］

def initRobort（）
    for i in range（0，2）
        Rnumlist1［i］＝Rnumlist2［random（0，3）］
    Rresult＝Rresultlist［random（0，5）］

def competition（Hnum1，Hnum2，Hresult，Rnumlist1，Rresult）
    result＝Hnum1+Hnum2+Rnumlist1［0］+Rnumlist1［1］
    if Hresult == result:
winner = ‘Human’
  else if Rresult == result:
winner = ‘Robort’
  else:
	winner = ‘None’
