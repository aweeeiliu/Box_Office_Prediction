# Box_Office_Prediction
Main side project at iSpan BDSE (2022/11~2023/5).
透過爬取tmdb & imdb網站資料,對資料進行清整與分析,挑選出有興趣的欄位後,將其丟入模型訓練,最終得出XGBoost R2 score 0.72
本專題對票房預測尚算及格,然評分預測卻不盡理想,因評分項目容易因個人差異而有所變化,較難有客觀給分水準,故10分類的評分(加上NLP判斷空值label)較難準確,僅1與10分類有達到8成以上準確
