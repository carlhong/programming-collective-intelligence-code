#chapter 2

##基于用户的数据字典:
		'人1': {'物1': 评分, '物2': 评分, ...}
1. 人评分的相似度
	物1 人1的评分
	物1 人2的评分
2. 推荐物品（人评分高的物品）
	物1 人1的评分×人1评分（物1）的相似度+人2的评分×人2评分（物1）的相似度

##基于物品的数据字典:
		'物1': {'人1': 评分, '人2': 评分, ...}
1. 物品收到评分的相似度
2. 推荐物品（物品适用于人）
