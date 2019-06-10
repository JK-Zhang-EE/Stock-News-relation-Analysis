1. 需要用 WebCrawler_seeking alpha 先抓取新聞資料

   命名方式為 company_name + "_news.csv"


2. 使用 Analysis_Model

   需要執行
	ChangeNewsFormat("company_name")
	Analysis("company_name")
	
	
	ex:
	ChangeNewsFormat("HP")
	Analysis("HP")