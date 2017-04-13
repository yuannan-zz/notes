# 回测代码分析

## daily 
	频率为daily的回测，每天会生成以下四种action:
	>* BEFORE_TRADING_START_BAR：日切的第一个action，调用on_dt_changed和before_trading_start
	* SESSION_START：
	* BAR
	* SESSION_END
	