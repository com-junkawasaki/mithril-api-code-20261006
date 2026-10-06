# Mithril API Code live verification — 2026-10-06 JST

User requested api.mithril.fund instead of OpenRouter. Actual Code and authenticated App browser sessions, plus installed/notarized Desktop preview.27 through the default Hermes profile, independently generated and accepted the two To-do functions.

| Consumer | API request ID | Input/output tokens | Generation and verification seconds |
| --- | --- | --- | --- |
| Code | chat:29bf3a33-4b71-495b-b400-2b88f0c44cf4 | 1397 / 219 | 8.636 |
| App | chat:b52b078f-1408-4e22-81bd-a68c15203f08 | 1295 / 219 | 8.289 |
| Desktop | chat:8ad88c2a-0cf5-415b-9351-77333c5f464c | 318 / 219 | 8.256 |

Each receipt names https://api.mithril.fund/v1/chat/completions and qwen/qwen3.8-27b. All three produce identical admitted AST and source, check both toggle inputs plus all 511 boolean vectors of length 0–8, preserve the marker, and make one API call. API charges were not returned and remain null. No Jev inference or OpenRouter credential is used. These are measured single calls, not comparative reliability or speed benchmarks.

Code source c641b5fb392766eaf54611dd8c4b17f9565a656a deployed via successful CI 37468498921. App shared UI source 89856c3a07edb7df6f8efdc2c414e7c325c4137b deployed via successful CI 37465988605. Desktop preview.27 published all 20 assets via successful CI 37465994810; official ARM64 ZIP SHA256 457ccb8268ed968b88afb2be02483e40be4232b6c9c4c66f7f99456f9e1251c8, codesign strict and notarized Developer ID assessment passed before installation. Shared package is 0.6.10; Agent plugin pin f5e4b783fead7bf56f859eb97303522c9525cdcb.

A real earlier API proposal chat:04479846-2fb3-4226-a52c-9887fb6fd6b7 incorrectly used a boolean conditional as a callable predicate. Strict admission rejected it. PR533 clarified contextual types without weakening acceptance or substituting a known solution. Accepted failures remain charged to the existing request quota; its ledger was not reset.

Code UI created the public repository, saved the actual generated sources and inference receipt at 82d244cd186ccba65e6cc289f662e5c11f2a41d2, and requested Pages publication:
- https://github.com/com-junkawasaki/mithril-api-code-20261006
- https://com-junkawasaki.github.io/mithril-api-code-20261006/

Read-back comparison confirmed the published receipt and CLJK files exactly match the real Code API response. App and Desktop receipts were obtained from their actual requests/visible native editor and matched its AST/source. This new publication is from Code; previous shared JS/Python publication across Desktop/App/Code is documented separately in ../shared-code-kuro-2026-10-06.

Proof boundary: typed AST evaluation and deterministic source emission, not native CLJK compilation. The TodoMVC UI and Wasm policy are maintained starter assets. Native source edits do not rebuild the Wasm kernel. Arbitrary repository execution and application/API generation remain unsupported. The existing Desktop token lacks chat:read for cloud chat; Code uses its independently scoped inference authorization and no scope was broadened.
