# [L4D2] hx_stats 

网站: https://forums.alliedmods.net/showthread.php?t=298535
stats_web：https://github.com/TyUser/l4d2_hx_stats


用于Left 4 Dead 2（Co-op）玩家数据统计

要求的MySQL统计数据
•MySQL：如果您的MySQL服务器不在同一系统上，则需要外部连接！默认情况下不启用此功能，您可能需要与主机联系！
•Metamod：Source / SourceMM（最新版本）
•SourceMod：1.8 - 1.9最新版本

安装
•编辑/addons/sourcemod/configs/databases.cfg文件并添加包含以下信息的部分：

	"l4d2_stats"
	{
	"driver"	"mysql"
	"host"	"your_host"
	"database"	"your_db"
	"user"	"your_user"
	"pass"	"your_pass"
	}

•在游戏控制台中键入：
sm_addsqlcreate	//初始化数据库,添加并创建sql


聊天命令
• !rank - 显示您当前的排名信息。
• !top - 显示前15名玩家数据统计。
-
附加的文件
获取插件[http://www.sourcemod.net/vbcompiler.php?file_id=163444] 或 获取源代码[l4d2_hx_stats.sp - 15.7 KB）
最后由maks编辑; 17年6月15日在上午04时26分。


=========
同类型 https://forums.alliedmods.net/showthread.php?t=174289
