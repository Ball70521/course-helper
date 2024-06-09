# course-helper
## 檔案說明
- test.ipynb: 原先的LangChain (Llama3)
- data.json: 原始課程資料
- data2.json: 英文翻譯的課程資料
- LangChain.ipynb: 後來project使用的 LangChain (GPT-4o)
- answers.json: Llama3 LangChain 的測試問題和回答
- questions.json: GPT LangChain 的50個測試問題
## 資料夾說明
- Answer: GPT LangChain 的問題和回答(2種搜索方式各自回答5遍，因此有10份json)
- faiss_index: 用 FAISS 建立好的向量搜索庫

## 使用說明
1. 先申請 openAI 的 API key 並建立 .env 檔，然後加入 `OPENAI_API_KEY=申請的key`
2. 記得更改LangChain.ipynb程式碼裡面的檔案路徑
