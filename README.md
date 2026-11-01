# cursor-claude-workflow-kr

1인 AI 스튜디오 [세라윤](https://serayun.com)에서 실제로 쓰는 작업 흐름을 한국어로 정리한 저장소입니다.

**Claude로 작업지시서를 쓰고 → Cursor · Codex· Gemini로 구현하고 → 결과를 다시 Claude에게 검토받는** 방식이에요.

## 흐름

1. **정리 (Claude)**: 만들고 싶은 것을 말로 풀어 놓고, Claude에게 작업지시서로 정리해 달라고 합니다.
2. **구현 (Cursor · Codex)**: 작업지시서를 그대로 붙여 넣고 구현을 맡깁니다. 지시가 명확할수록 결과가 좋아요.
3. **검토 (Claude)**: 바뀐 내용과 막힌 점을 다시 Claude에게 보여 주고 다음 지시서를 받습니다.
4. **기록**: 막힌 점과 고친 방법을 짧게 남깁니다. (`logs/`)

## 템플릿

- [`templates/work-order.md`](templates/work-order.md): Claude에게 받는 작업지시서 양식

## 원칙

- 한 번에 하나의 작업만 지시합니다.
- 완료 기준(무엇이 되면 끝인지)을 반드시 적습니다.
- 실제로 써 보고 확인한 것만 기록합니다.

## 만든 것들

세레니얼 · SafeSM · 세라랩 · 미제 — 자세한 내용은 [serayun.com](https://serayun.com)

---

문의: founder@serayun.com · X [@suho79kr](https://x.com/suho79kr)
