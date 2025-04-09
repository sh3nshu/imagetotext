curl -X POST 'https://api.coze.cn/v1/workflow/run' \
-H "Authorization: Bearer xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx" \
-H "Content-Type: application/json" \
-d '{
  "parameters": {
    "url": "https://xxxxxxxx.com/contentPic/20210809/63786dcf-5a75-4734-adb8-6317b4c8436f.png"
  },
  "workflow_id": "xxxxxxxxxxxxxxxx"
}'

