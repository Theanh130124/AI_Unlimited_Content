# AI_Unlimited_Content

Openrouter

N8N


Settings Scheduler

![image](https://github.com/user-attachments/assets/d5342c2f-d1c6-4905-97f4-82ad1aaeb3c4)


Code kiểm tra là bài viết mới đã đăng chưa nếu chưa thì đăng (không đăng bài cũ)

![image](https://github.com/user-attachments/assets/03ae598c-4c9d-4d2b-b734-576a3410eca8)


```
const staticData = $getWorkflowStaticData('global');

// Initialize lastStatus if it doesn't exist
if (typeof staticData.lastStatus == 'undefined') {
    staticData.lastStatus = 0;
}

// Get new Status from Table
const newStatus = staticData.lastStatus + 1;

if (newStatus === 30) {
    staticData.lastStatus = 0;
} else {
    staticData.lastStatus = newStatus;
}

return [{json:{
    id: newStatus
}}];

```


Airtable  -> Chuẩn bị chủ đề  -> Lấy key trong builderhub

![image](https://github.com/user-attachments/assets/27c070f2-e25c-4564-a209-8e2e93016271)


Setting Airtable  
![image](https://github.com/user-attachments/assets/63789f2f-6428-4958-b19e-706e72f32ad8)



Settings HTTPS request -> phần này nếu có tiền có thể làm con CHATPPT

```


url : https://openrouter.ai/api/v1/chat/completions

method : Post

Header : Authorization  Bearer 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

Body : raw :  {
  "model": "deepseek/deepseek-chat-v3-0324:free",
  "messages": [
    {
      "role": "user",
      "content": "Thủ đô của Việt Nam là gì"
    }
  ]
  
}
```

![image](https://github.com/user-attachments/assets/f5e0e792-f8ef-41da-9088-32beced86c56)
![image](https://github.com/user-attachments/assets/61d5d4db-ff9a-4c73-8bdb-f79346235804)
![image](https://github.com/user-attachments/assets/a9fa14eb-cda1-4a74-8fd4-16c41b3462ce)









![image](https://github.com/user-attachments/assets/20ae9f38-e54c-4562-9bd9-273bb3e00cb7)
