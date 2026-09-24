# GLM-5.3 Flash API 한국어 가이드（glm-5.3-flash / glm5.3flash）

> 종량제, 최소 1달러 충전, OpenAI 호환 엔드포인트. **input $0.06; cached_input $0.012; output $0.2**

**[模型页](https://apimart.ai/model) · [实时价格](https://apimart.ai/pricing) · [获取 API Key](https://apimart.ai/keys)**

## 가격（快照 2026-09-24）

| 档位 | 单价 |
| --- | --- |
| `input` | $0.06 |
| `cached_input` | $0.012 |
| `output` | $0.2 |

按量计费、**$1 起充**，无订阅、无免费额度；每次任务响应返回 `cost` / `credits_cost`。

## 调用示例

```bash
curl --request POST --url https://api.apimart.ai/v1/images/generations \
  --header "Authorization: Bearer $APIMART_API_KEY" --header 'Content-Type: application/json' \
  --data '{"model":"glm-5.3-flash","prompt":"海边悬崖的现代别墅，黄昏","size":"16:9","n":1}'
```

## 披露

이 저장소는 서드파티 중계 서비스 APIMart 사용 가이드입니다.
