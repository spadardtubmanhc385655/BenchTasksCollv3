# Final Pool of Implemented Tasks

Tasks collected from every developer branch and marked `implemented` in the Notion **Task Tracker** (Task Status Table),
after checking the newest commits that added tasks on each branch.

- Tasks: 77 (54 previously tracked + 23 newly reviewed)
- Newly reviewed tasks that are still `implementing` are excluded: audit-logger, currency-converter, customer-portal, insights-engine, resource-monitor, sitemap-generator.
- Each task is stored verbatim at `tasks/finalpool/<task-name>/`, ready to be selected by the runner.

## Acceptance check for new tasks

Based on `tasks/examples/example-task`: `docs/task.md` and `docs/agent_system_prompt.md` must exist,
be non-empty and be written entirely in English; the optional `docs/user_system_prompt.md`, when present
and non-empty, must also be English. `evaluation/main.py` must be present; its contents and the optional
`preprocess/main.py`, `initial_workspace/` and `groundtruth_workspace/` are only checked for existence.

## Task inventory

| Task | Implementor | Source branch | Source path |
| --- | --- | --- | --- |
| activity-logger | lueyang-dev | lueyang-dev | tasks/lueyang/activity-logger |
| alert-system | yuzhen-dev | yuzhen-dev | tasks/yuzhen/alert-system |
| analytics-dashboard | lv | lv | tasks/lv/analytics-dashboard |
| asset-optimizer | yuxuan-dev | yuxuan-dev | tasks/yuxuan/asset-optimizer |
| backup-utility | xiaochen_dev | xiaochen_dev | tasks/xiaochen/backup-utility |
| blog-engine | gyy | gyy | tasks/gyy/blog-engine |
| booking-system | junteng_dev | junteng_dev | tasks/junteng/booking-system |
| cache-optimizer | wenshuo-dev | wenshuo-dev | tasks/wenshuo/cache-optimizer |
| calendar-sync | junteng_dev | junteng_dev | tasks/junteng/calendar-sync |
| canvas-automation | ruige | ruige | tasks/ruige/canvas-automation |
| canvas-grade-automation | jl_dev | jl_dev | tasks/jl/canvas-grade-automation |
| certificate-manager | zhaochen | zhaochen | tasks/zhaochen/certificate-manager |
| chat-bot | lv | lv | tasks/lv/chat-bot |
| client-portal | lueyang-dev | lueyang-dev | tasks/lueyang/client-portal |
| cms-builder | gyy | gyy | tasks/gyy/cms-builder |
| contact-manager | junteng_dev | junteng_dev | tasks/junteng/contact-manager |
| content-manager | yuxuan-dev | yuxuan-dev | tasks/yuxuan/content-manager |
| content-scheduler | gyy | gyy | tasks/gyy/content-scheduler |
| coupon-manager | fan-dev | fan-dev | tasks/fan/coupon-manager |
| crm-system | lueyang-dev | lueyang-dev | tasks/lueyang/crm-system |
| customer-feedback-processor | jl_dev | jl_dev | tasks/jl/customer-feedback-processor |
| data-analytics | ruige | ruige | tasks/ruige/data-analytics |
| data-validator | yuzhen-dev | yuzhen-dev | tasks/yuzhen/data-validator |
| deal-manager | lueyang-dev | lueyang-dev | tasks/lueyang/deal-manager |
| deployment-tool | xiaochen_dev | xiaochen_dev | tasks/xiaochen/deployment-tool |
| discount-calculator | fan-dev | fan-dev | tasks/fan/discount-calculator |
| email-campaign | lueyang-dev | lueyang-dev | tasks/lueyang/email-campaign |
| email-classification-system | jl_dev | jl_dev | tasks/jl/email-classification-system |
| error-tracker | xiaochen_dev | xiaochen_dev | tasks/xiaochen/error-tracker |
| expense-tracker | ruige | ruige | tasks/ruige/expense-tracker |
| feedback-collector | lv | lv | tasks/lv/feedback-collector |
| file-manager | ruige | ruige | tasks/ruige/file-manager |
| follow-up-reminder | lueyang-dev | lueyang-dev | tasks/lueyang/follow-up-reminder |
| form-builder | yuzhen-dev | yuzhen-dev | tasks/yuzhen/form-builder |
| health-monitor | xiaochen_dev | xiaochen_dev | tasks/xiaochen/health-monitor |
| help-desk | junteng_dev | junteng_dev | tasks/junteng/help-desk |
| image-processor | wenshuo-dev | wenshuo-dev | tasks/wenshuo/image-processor |
| inventory-management | jl_dev | jl_dev | tasks/jl/inventory-management |
| invoice-generator | yuzhen-dev | yuzhen-dev | tasks/yuzhen/invoice-generator |
| load-balancer | zhaochen | zhaochen | tasks/zhaochen/load-balancer |
| log-analyzer | ruige | ruige | tasks/ruige/log-analyzer |
| loyalty-program | fan-dev | fan-dev | tasks/fan/loyalty-program |
| media-organizer | haoze | haoze | tasks/haoze/media-organizer |
| monitoring-agent | xiaochen_dev | xiaochen_dev | tasks/xiaochen/monitoring-agent |
| network-analyzer | yuxuan-dev | yuxuan-dev | tasks/yuxuan/network-analyzer |
| order-processor | junteng_dev | junteng_dev | tasks/junteng/order-processor |
| payment-processor | yuzhen-dev | yuzhen-dev | tasks/yuzhen/payment-processor |
| pdf-report-generator | jl_dev | jl_dev | tasks/jl/pdf-report-generator |
| permission-manager | yuzhen-dev | yuzhen-dev | tasks/yuzhen/permission-manager |
| personalization-service | lv | lv | tasks/lv/personalization-service |
| price-tracker | fan-dev | fan-dev | tasks/fan/price-tracker |
| product-catalog | junteng_dev | junteng_dev | tasks/junteng/product-catalog |
| qr-generator | junxian_dev | junxian_dev | tasks/junxian/qr-generator |
| reminder-service | junteng_dev | junteng_dev | tasks/junteng/reminder-service |
| robots-handler | gyy | gyy | tasks/gyy/robots-handler |
| sales-pipeline | lueyang-dev | lueyang-dev | tasks/lueyang/sales-pipeline |
| scheduler | wenshuo-dev | wenshuo-dev | tasks/wenshuo/scheduler |
| search-engine | wenshuo-dev | wenshuo-dev | tasks/wenshuo/search-engine |
| security-scanner | xiaochen_dev | xiaochen_dev | tasks/xiaochen/security-scanner |
| sentiment-analyzer | lv | lv | tasks/lv/sentiment-analyzer |
| shipment-tracker | junteng_dev | junteng_dev | tasks/junteng/shipment-tracker |
| social-connector | junxian_dev | junxian_dev | tasks/junxian/social-connector |
| social-publisher | gyy | gyy | tasks/gyy/social-publisher |
| status-checker | xiaochen_dev | xiaochen_dev | tasks/xiaochen/status-checker |
| storage-manager | zhaochen | zhaochen | tasks/zhaochen/storage-manager |
| streaming-service | haoze | haoze | tasks/haoze/streaming-service |
| subtitle-generator | haoze | haoze | tasks/haoze/subtitle-generator |
| survey-builder | lv | lv | tasks/lv/survey-builder |
| sync-service | yuxuan-dev | yuxuan-dev | tasks/yuxuan/sync-service |
| tag-manager | gyy | gyy | tasks/gyy/tag-manager |
| task-scheduler | yuxuan-dev | yuxuan-dev | tasks/yuxuan/task-scheduler |
| template-engine | zhaochen | zhaochen | tasks/zhaochen/template-engine |
| territory-manager | lueyang-dev | lueyang-dev | tasks/lueyang/territory-manager |
| translation-api | junxian_dev | junxian_dev | tasks/junxian/translation-api |
| video-trimmer | haoze | haoze | tasks/haoze/video-trimmer |
| voice-processor | lv | lv | tasks/lv/voice-processor |
| web-crawler | ruige | ruige | tasks/ruige/web-crawler |