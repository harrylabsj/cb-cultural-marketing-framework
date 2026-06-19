---
skill: cb-cultural-marketing-framework
name: Cultural Marketing Adaptation Framework
type: descriptive
version: 1.1.0
description: Marketing message and campaign adaptation for cultural contexts
author: Golden Bean (OpenClaw)
created: 2026-04-22
category: marketing
language: en
tags: marketing, localization, culture, adaptation, cross-border
outputs: json
requires_api: false
safety_boundary: Descriptive cross-border e-commerce planning only. No code execution, API calls, network requests, bookings, or real-time data. Does not provide professional advice. Verify information with official sources and qualified professionals.
---

# Cultural Marketing Adaptation Framework

## Overview

Cultural Marketing Adaptation Framework (Marketing message and campaign adaptation for cultural contexts). This skill provides a structured approach to adapting marketing strategies for international audiences. It analyzes cultural differences in communication styles, visual preferences, and value systems to generate culturally appropriate marketing recommendations.

The framework covers cultural analysis, message adaptation, channel-specific strategies, and implementation planning. It helps businesses avoid cultural missteps and create resonant marketing campaigns across different markets.

## Trigger Keywords

- "cultural marketing adaptation"
- "cross-cultural marketing framework"
- "localize marketing for culture"
- "cultural advertising adaptation"
- "international marketing localization"
- "culture-specific campaign planning"

## Workflow

1. **Input Analysis**: Parse user input to extract target culture, brand positioning, product category, and marketing channels
2. **Cultural Analysis**: Apply culture-specific communication and value system frameworks
3. **Message Adaptation**: Generate adapted messaging with cultural rationale
4. **Channel Strategy**: Develop channel-specific adaptation recommendations
5. **Output Delivery**: Return comprehensive JSON with analysis and recommendations

## Output Modules

### Cultural Analysis Framework
- Communication style analysis for target culture
- Visual preference assessment and design recommendations
- Value system alignment and key cultural principles
- Cultural taboos and sensitivities to avoid
- Brand positioning adjustments for cultural fit

### Message Adaptation Framework
- Original to adapted message transformations with rationale
- Slogan and tagline cultural adaptation
- Tone and voice adjustment recommendations
- Visual and imagery adaptation guidance
- Call-to-action cultural optimization

### Channel-Specific Adaptations
- Social media platform preferences by market
- Content style and posting frequency recommendations
- Engagement and community management strategies
- Influencer and partnership considerations
- Email marketing cultural adaptation

### Implementation Plan
- Phase 1: Cultural research and analysis
- Phase 2: Message and visual adaptation
- Phase 3: Testing and refinement
- Phase 4: Launch and monitoring

## Safety & Limitations

### Safety Boundaries
- **No Professional Advice**: Provides informational frameworks only. Does not replace professional marketing consultants.
- **No Real-Time Data**: Based on general cultural frameworks, not current market research.
- **No Campaign Execution**: No actual campaign creation or management capabilities.
- **No Code Execution**: Pure descriptive implementation. No shell commands or network requests.
- **Descriptive Only**: Provides planning frameworks and guidance only.

### Limitations
- Cultural generalizations may not apply to all segments within a culture
- Individual preferences vary within cultural groups
- Cultural norms evolve over time
- Requires verification with local market research
- Does not replace local marketing expertise

## Example Prompts

### Level 1: Basic Inquiry
"How to adapt my marketing for Japanese consumers?"

### Level 2: Specific Scenario
"Premium fashion brand marketing adaptation for German market"

### Level 3: Complex Planning
"Multi-market campaign adaptation for France, Germany, and Japan with different brand positions"

### Level 4: Detailed Case
"US sustainable tech company adapting social media and email marketing for Chinese consumers"

## Acceptance Criteria

### Functional Requirements
- Returns valid JSON structure from handle() function
- Includes input_analysis field with parsed input information
- Contains proper disclaimer with safety boundaries
- Provides culture-specific analysis and message adaptation
- Differentiated from other cross-border e-commerce skills

### Quality Requirements
- Clear and structured output
- Comprehensive framework coverage
- Actionable implementation guidance
- Proper safety boundaries enforced
- Input differentiation verified through tests

## Integration

### Complementary Skills
- Works with cb-product-localization-advisor for holistic market entry
- Integrates with cb-customer-service-localizer for consistent cultural approach
- Supports cb-market-entry-strategist for market selection

### Input/Output Flow
- Accepts natural language input via handle() function
- Returns structured JSON for system integration
- Can be chained with related skills for multi-faceted analysis

## Version History

### v1.0.0 (2026-04-22)
- Initial release
- Cultural analysis framework for major markets
- Message adaptation with rationale
- Channel-specific adaptation recommendations
- Input parsing and parameter extraction
- JSON output with input_analysis and disclaimer
- Safety boundaries and limitations documentation
- Test coverage with 5 tests per skill

## Technical Details

### Handler Interface


### Dependencies
- None (pure Python standard library only)

### File Structure
- handler.py: Main handler implementation
- tests/test_handler.py: Unit tests (5 tests)
- SKILL.md: This documentation file
- skill.json: Skill metadata and configuration
- ACCEPTANCE.md: Acceptance criteria documentation
- .claw/identity.json: Identity and authorship information

### Test Coverage
- JSON output validation test
- Disclaimer presence and content test
- Input differentiation test
- Marketing-specific functionality test
- Differentiation evidence test


## Usage Scenarios

| # | User Input | Expected Output |
|---|---|---|
| 1 | "Build a cultural marketing framework for our snack brand launching in India, UAE, and Indonesia (all Muslim-majority but culturally distinct)." | Framework dimensions: religious sensitivity (Halal certification, Ramadan campaigns), color symbolism (green=positive across all three, white=mourning in India but purity in UAE), humor norms, family representation, and celebrity endorsement expectations. Country-specific playbook per dimension. |
| 2 | "Review our global 'Summer Fun' campaign creative. Flag any cultural risks for our Middle East markets." | Risk audit: swimwear imagery in one visual (red flag for UAE/KSA), pork-reference in a tagline pun (unacceptable in Muslim-majority markets), and dating-implied scenario in a video clip. Suggests alternate creative for MENA region. |
| 3 | "We are developing a Lunar New Year campaign. Adapt the core concept for China, Vietnam (Tet), and Korea (Seollal) without a generic 'Asian' approach." | Differentiation guide: China (red envelopes, dragon dance, family reunion), Vietnam (yellow blossoms, banh chung, ancestor altars), Korea (sebae bow, hanbok, tteokguk soup). Distinct visual direction and copy for each market. |


### Scenario 2: 中国品牌出海怎么避免文化翻车
**User input:** "我们把产品卖到中东，但我们的广告片里女生穿得比较清凉，当地人说我们冒犯了他们的文化。以后怎么避免这种问题？"
**Expected output:** 跨境营销文化敏感度检查清单——第一步：自查内容（广告中的女性着装是否符合目标国规范、是否有涉及宗教符号/颜色禁忌/节日隐喻的内容、翻译后的文案在当地方言里有没有歧义或负面含义）；第二步：本地化团队验证（在中东国家找当地的市场/翻译/朋友审阅所有内容，审阅费值得花）；第三步：参考本土品牌（研究当地成功品牌的广告风格和表达方式，不要照搬而是调整）；第四步：做文化敏感性培训（团队出海前请咨询公司做一次关于目标国文化的1小时培训，费用不高但能避免大问题）；第五步：预留危机应对机制（一旦翻车立即下架内容+发道歉声明+找当地KOL帮忙澄清缓颊）。
