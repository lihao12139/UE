# 基础概念

## GameInstance游戏实例

游戏实例贯穿游戏始终的,像主界面UI就可以放在这里面

## GameModeBase游戏模式

可以拥有多个不同的模式,但是每个关卡只能拥有一个模式,制定规则

## GameStateBase游戏状态

一般用于存储游戏模式里面的数据

## PlayerState玩家状态

每一个玩家只允许有一个,单机游戏无影响,联机就要自己指定自己的,存储玩家的信息

## PlayerController

控制玩家的行为



## AActor

可被放置的对象

## APawn

可被控制的对象

控制器绑定,输入处理,基础移动



## ACharacter

专为角色而生,复杂行为