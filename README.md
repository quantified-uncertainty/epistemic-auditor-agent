# EA Epistemic Auditor

## What This Agent Does

The EA Epistemic Auditor is a sophisticated evaluator designed specifically for Effective Altruism and rationalist content. It goes beyond basic logical fallacy detection to provide deep epistemic analysis calibrated to audience expectations and document context.

## Core Capabilities

### 🎯 Audience-Aware Analysis
- Calibrates evaluation standards based on venue (EA Forum, LessWrong, personal blog, academic journal)  
- Adjusts expectations for different document types (research, opinion, critique, exploration)  
- Recognizes community-specific epistemic norms  

### 🔍 Non-Obvious Insight Detection
- Identifies hidden assumptions that readers might not consciously recognize  
- Surfaces surprising implications of arguments  
- Avoids wasting time on surface-level issues anyone would notice  

### 📊 Sophisticated Analysis Modules
The agent employs 10 specialized analysis frameworks:
- **Hidden Assumptions** - Unstated premises the audience might not share  
- **Confidence Calibration** - Whether certainty matches evidence quality  
- **Argument Structure Mapping** - Visual representation of logical dependencies  
- **Quantitative Claims Audit** - Systematic review of all numerical assertions  
- **Stakeholder Impact Analysis** - Who benefits/loses from proposals  
- **Epistemic Virtues Recognition** - Acknowledging good reasoning practices  
- **Alternative Interpretations** - Other valid readings of the same evidence  
- **Implementation Feasibility** - Practical challenges in proposals  
- **Historical Precedent Check** - Comparison to similar past efforts  
- **Robustness Testing** - How arguments fare under challenge  

### 🎭 Meta-Critique Capability
Special handling for critiques of critiques - maintains clear distinction between:
- The original work being critiqued  
- The critique's arguments about that work  
- The agent's evaluation of the critique's quality  

## When to Use This Agent

### ✅ Ideal For:
- EA Forum posts about cause prioritization, interventions, or methodology  
- LessWrong essays on rationality, AI alignment, or epistemics  
- Academic papers making empirical or normative claims  
- Critiques or responses to other EA/rationalist work  
- Grant proposals or intervention assessments  
- Personal reflections that make broader claims  

### ❌ Less Suitable For:
- Pure creative writing or fiction  
- Technical documentation without argumentative content  
- Social media posts or brief comments  
- Content outside EA/rationalist discourse norms  

## Output Structure

1. **Summary** - Brief overview of the document and key epistemic findings
2. **Audience Context Analysis** - Understanding the intended readers
3. **Document Type Assessment** - Calibrating appropriate standards
4. **Core Analysis** - 2-5 relevant analysis modules applied
5. **Synthesis** - Integration of findings and recommendations
6. **Key Highlights** - 5 specific comments on particular passages
7. **Grade** - 0-100 score with detailed justification
8. **Self-Critique** - Agent's assessment of its own evaluation quality

## Grading Philosophy

Grades are calibrated to document type:
- **Personal/Informal**: 60-85 baseline (focus on major issues)  
- **Exploratory/Conceptual**: 55-80 baseline (logical consistency)  
- **Empirical Research**: 45-75 baseline (methodological rigor)  
- **Policy/Recommendations**: 50-80 baseline (implementation feasibility)  
- **Critiques/Reviews**: 50-80 baseline (charitable interpretation)  

## Technical Notes for Modifiers

### Architecture
- XML-structured instructions optimize Claude's performance  
- Modular analysis system allows selective framework application  
- Third-person voice maintains professional distance  
- Self-critique mechanism provides quality calibration  

### Key Design Decisions
- **Audience-first approach**: Standards vary by context, not universal rules  
- **Non-obvious focus**: Avoids cluttering feedback with obvious issues  
- **Constructive framing**: Even critiques acknowledge epistemic virtues  
- **Practical orientation**: All feedback aims to be actionable  

### Testing Recommendations
- Test on diverse document types to verify calibration  
- Check that meta-critiques properly distinguish levels  
- Ensure grades align with document type baselines  
- Verify non-obvious insights are genuinely surprising  

## Version History

**v5** (Current) - Added meta-critique detection, improved audience calibration, expanded to 10 analysis modules, added epistemic virtues recognition
