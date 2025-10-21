# contributing

# Contributing to ê/uto

> **Welcome, TechnoHero! This guide will help you contribute effectively to the Effective Utopia network.**

**"No rules here, for any rule is unfreedom. We give choices."**

---

## 🌍 Quick Start

### First-Time Contributors

1. **Read the [Onboarding Guide](docs/onboarding/)** - Understand the network
2. **Join [Discord](https://discord.gg/P9suffJv)** - Connect with the community
3. **Browse [Issues](../../issues)** - Find something to work on
4. **Ask Questions** - We're here to help!

### Experienced Contributors

1. Check [open issues](../../issues) and [discussions](../../discussions)
2. Review [project boards](../../projects) for priorities
3. Fork → Branch → Commit → PR (details below)
4. Engage in code review and iteration

---

## 🎯 Our Mission

**"To prevent dystopias and build utopias, increase the probability of the ultimate effective utopia — p(e/uto) — by at least 1% each week."**

Every contribution, no matter how small, moves us toward this goal.

---

## 🤝 Ways to Contribute

### 1. 📝 Documentation

**Always Valuable:**
- Fix typos and grammar
- Improve clarity
- Add examples
- Translate content
- Create tutorials

**How to Start:**
- Look for issues labeled `documentation`
- Read through existing docs and spot gaps
- Propose improvements in discussions

### 2. 💻 Code

**What We Need:**
- Bug fixes
- New features
- Performance improvements
- Test coverage
- Tool integrations

**How to Start:**
- Check issues labeled `good first issue`
- Review the [Tools Guide](docs/tools-configuration-guide.md)
- Set up your development environment
- Pick a manageable task

### 3. 🎨 Design & Creative

**What We Need:**
- Visual assets (logos, banners, icons)
- Brand guidelines
- UI/UX improvements
- Video content
- Music and audio

**How to Start:**
- Browse [asset galleries](https://www.cosmos.so/cosimosportinari/uto-official)
- Check issues labeled `design` or `creative`
- Share work in Discord `#creative-lab`
- Upload to Cosmos.so with proper licensing

### 4. 🧪 Testing & Feedback

**What We Need:**
- Bug reports
- Feature testing
- Usability feedback
- Documentation review

**How to Start:**
- Use the tools and report issues
- Test new features in beta
- Review PRs from a user perspective
- Share feedback in discussions

### 5. 🌱 Community Support

**What We Need:**
- Answering questions in Discord
- Onboarding new members
- Moderating discussions
- Organizing events

**How to Start:**
- Hang out in Discord channels
- Welcome newcomers in `#multichat-welcomes-all`
- Help in `#tree/uto`
- Facilitate discussions

### 6. 🧠 Research & Ideas

**What We Need:**
- Framework development
- Ethical analysis
- Technical research
- Strategic thinking

**How to Start:**
- Engage in `#save-worlds-antidys/prouto`
- Study the [GMSF framework](docs/gmsf-technical-documentation.md)
- Participate in philosophical discussions
- Write essays or proposals

---

## 📋 Contribution Guidelines

### Code of Conduct

**Core Principles:**
1. **Be Kind** - Compassion is couture
2. **Be Respectful** - Everyone's contribution matters
3. **Be Constructive** - Offer solutions, not just criticism
4. **Be Inclusive** - Welcome all backgrounds and skill levels
5. **Be Honest** - Truth as primary function (LOGOS)

**We Don't Tolerate:**
- Harassment or discrimination
- Spam or self-promotion without context
- Destructive criticism
- Gatekeeping or elitism
- Bad faith arguments

**Conflict Resolution:**
- Use the [three-cycle dialectical process](docs/gmsf-technical-documentation.md#2-conflict-resolution)
- Seek synthesis, not victory
- Involve moderators if needed
- Assume positive intent

### Communication Guidelines

**Be Clear:**
- Use descriptive titles
- Provide context
- Link to relevant resources
- Use proper formatting

**Be Concise:**
- Get to the point
- Use bullet points
- Break up long text
- TL;DR for long posts

**Be Responsive:**
- Reply to feedback
- Update on progress
- Close resolved issues
- Thank contributors

### Attribution

**Always:**
- Credit original authors
- Link to sources
- Use proper licenses
- Acknowledge collaborators

**Never:**
- Plagiarize
- Claim others' work
- Violate copyright
- Misrepresent authorship

---

## 🔧 Technical Contribution Process

### 1. Set Up Development Environment

**Prerequisites:**
```bash
# Git
git --version

# Node.js (if applicable)
node --version
npm --version

# Your preferred editor
code --version  # VSCode
```

**Clone the Repository:**
```bash
# Fork first on GitHub, then:
git clone https://github.com/YOUR-USERNAME/REPO-NAME
cd REPO-NAME

# Add upstream remote
git remote add upstream https://github.com/all-uto/REPO-NAME
```

**Install Dependencies (if applicable):**
```bash
npm install
# or
pip install -r requirements.txt
# or
bundle install
```

### 2. Find or Create an Issue

**Before Starting Work:**
1. Check if an issue exists
2. If not, create one describing what you want to do
3. Wait for feedback/approval (for big changes)
4. Assign yourself to the issue

**Good Issue Template:**
```markdown
## Description
[Clear description of the problem or enhancement]

## Proposed Solution
[What you plan to do]

## Impact
[How this increases p(e/uto)]

## Alternatives Considered
[Other approaches you thought about]

## Additional Context
[Screenshots, links, examples]
```

### 3. Create a Branch

**Naming Convention:**
```bash
# Features
git checkout -b feature/add-user-authentication

# Bugs
git checkout -b fix/broken-image-upload

# Documentation
git checkout -b docs/improve-readme

# Refactoring
git checkout -b refactor/simplify-api-calls
```

### 4. Make Your Changes

**Best Practices:**
- Make focused, atomic commits
- Write clear commit messages
- Test your changes
- Update documentation
- Follow code style

**Commit Message Format:**
```
type(scope): brief description

- Detailed explanation if needed
- Reference issues with #123

Fixes #123
```

**Types:** feat, fix, docs, style, refactor, test, chore

**Example:**
```bash
git commit -m "feat(onboarding): add symbolic ritual section

- Added 5 symbolic onboarding rituals
- Included templates and examples
- Updated table of contents

Closes #42"
```

### 5. Push and Create Pull Request

**Push Your Branch:**
```bash
git push origin feature/your-feature-name
```

**Create PR on GitHub:**
- Use clear, descriptive title
- Fill out PR template completely
- Link related issues
- Request review from relevant people
- Mark as draft if not ready

**PR Template:**
```markdown
## Description
[What does this PR do?]

## Related Issues
Closes #123
Related to #456

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation
- [ ] Refactoring
- [ ] Other: ___

## Testing
- [ ] I have tested these changes
- [ ] Tests pass locally
- [ ] I added new tests (if applicable)

## Documentation
- [ ] I updated relevant documentation
- [ ] I added code comments
- [ ] I updated the CHANGELOG (if applicable)

## Checklist
- [ ] My code follows the style guidelines
- [ ] I have performed a self-review
- [ ] I have commented complex code
- [ ] My changes generate no new warnings
- [ ] I have checked for accessibility
- [ ] I have updated dependencies (if needed)

## Screenshots (if applicable)
[Add screenshots here]

## Additional Notes
[Anything reviewers should know]
```

### 6. Respond to Feedback

**During Review:**
- Respond to all comments
- Make requested changes
- Ask questions if unclear
- Push additional commits
- Re-request review when ready

**Be Open:**
- Feedback is a gift
- Learn from suggestions
- Don't take it personally
- Iterate and improve

### 7. Merge!

**After Approval:**
- Maintainer will merge
- Delete your branch
- Update local repository
- Celebrate! 🎉

```bash
# Update your local main
git checkout main
git pull upstream main

# Delete merged branch
git branch -d feature/your-feature-name
git push origin --delete feature/your-feature-name
```

---

## 📁 Repository Structure

### Understanding the Organization

```
all-uto/
├── all-uto/                    # Main hub
├── e-uto/                      # Primary info
├── technoheroism/              # Philosophy
├── communities/                # Community directory
├── CoCreators/                 # CoCreators branch
├── cocreators-meganrim/        # Meganrim project
├── music/                      # Music branch
├── fashion/                    # Fashion branch
├── blueteam/                   # GMSF framework
├── eco/                        # Eco branch
├── tools-and-workflows/        # Tools guide
├── startups/                   # Startup branch
├── ai-alignment/               # AI alignment
├── assets/                     # Shared assets
└── members/                    # Member directory
```

### Where to Contribute

**Documentation:**
- Main READMEs in each repo
- `/docs` folders for detailed guides
- Wiki (if enabled)

**Code:**
- `/src` for source code
- `/scripts` for automation
- `/examples` for demonstrations

**Assets:**
- `/assets` for images, logos, etc.
- Cosmos.so galleries for portfolios
- Google Drive for large files

**Tests:**
- `/tests` or `/__tests__`
- Follow existing patterns

---

## 🎨 Style Guidelines

### Markdown Documentation

**Formatting:**
```markdown
# H1 for main title (one per document)
## H2 for major sections
### H3 for subsections

- Use `-` for unordered lists
1. Use numbers for ordered lists

**Bold** for emphasis
*Italic* for light emphasis
`Code` for inline code

\```language
Code blocks with language specified
\```

[Links](url) with descriptive text
![Images](url) with alt text
```

**Zettelkasten Linking:**
```markdown
**Upstream:**
- `[[parent-concept]]`

**Related:**
- `[[related-concept-1]]`
- `[[related-concept-2]]`

**Downstream:**
- `[[child-concept]]`
```

**Best Practices:**
- Use sentence case for headers
- Keep lines under 120 characters
- One sentence per line (for easier diffs)
- Use relative links when possible
- Include table of contents for long docs

### Code Style

**JavaScript/TypeScript:**
```javascript
// Use descriptive variable names
const userProfile = getUserProfile(userId);

// Functions do one thing well
function calculateTotalPrice(items) {
  return items.reduce((sum, item) => sum + item.price, 0);
}

// Comment complex logic
// Calculate phi-based interval using Golden Ratio
const interval = baseTime * ((1 + Math.sqrt(5)) / 2);
```

**Python:**
```python
# Follow PEP 8
# Use descriptive names
def calculate_drift_velocity(current_drift, previous_drift, time_delta):
    """Calculate rate of ontological drift.
    
    Args:
        current_drift: Current drift measurement
        previous_drift: Previous drift measurement
        time_delta: Time elapsed between measurements
        
    Returns:
        Drift velocity in units per second
    """
    return (current_drift - previous_drift) / time_delta
```

**General Principles:**
- Clarity over cleverness
- Self-documenting code
- Comments explain "why" not "what"
- Consistent formatting
- DRY (Don't Repeat Yourself)

### Naming Conventions

**Files:**
- `kebab-case-for-files.md`
- `PascalCaseForComponents.jsx`
- `snake_case_for_python.py`

**Branches:**
- `feature/add-new-capability`
- `fix/resolve-bug-description`
- `docs/improve-documentation`

**Variables:**
- `camelCase` for JavaScript
- `snake_case` for Python
- `UPPERCASE_FOR_CONSTANTS`

---

## 🧪 Testing Guidelines

### Documentation Testing

**Before Submitting:**
- [ ] Read through entire document
- [ ] Check all links work
- [ ] Verify code examples
- [ ] Test instructions step-by-step
- [ ] Check spelling and grammar
- [ ] Ensure proper formatting

### Code Testing

**Before Submitting:**
- [ ] All existing tests pass
- [ ] New tests for new features
- [ ] Edge cases covered
- [ ] No console errors or warnings
- [ ] Performance acceptable
- [ ] Accessibility checked

**Writing Tests:**
```javascript
// Example test structure
describe('TruthAnchoringSystem', () => {
  test('should return "I don\'t know" for low confidence', () => {
    const system = new TruthAnchoringSystem();
    const result = system.assessClaim('uncertain claim', 0.60);
    expect(result).toContain('I don\'t have sufficient information');
  });
  
  test('should assert directly for high confidence', () => {
    const system = new TruthAnchoringSystem();
    const result = system.assessClaim('certain claim', 0.98);
    expect(result).toBe('certain claim');
  });
});
```

### User Testing

**Helpful Feedback:**
- What you tried to do
- What actually happened
- What you expected to happen
- Steps to reproduce
- Screenshots/videos
- Environment details

---

## 🏷️ Issue and PR Labels

### Priority Labels
- `priority: critical` - Urgent, blocks other work
- `priority: high` - Important, address soon
- `priority: medium` - Normal priority
- `priority: low` - Nice to have

### Type Labels
- `type: bug` - Something isn't working
- `type: feature` - New functionality
- `type: enhancement` - Improve existing feature
- `type: documentation` - Documentation improvements
- `type: question` - Further information requested

### Difficulty Labels
- `good first issue` - Perfect for newcomers
- `beginner friendly` - Requires basic skills
- `intermediate` - Requires moderate experience
- `advanced` - Requires deep expertise

### Status Labels
- `status: needs triage` - Needs review by maintainers
- `status: blocked` - Can't proceed (explain why)
- `status: in progress` - Someone is working on it
- `status: needs review` - Ready for review
- `status: needs testing` - Ready for testing

### Community Labels
- `help wanted` - Looking for contributors
- `discussion` - Open for community input
- `collaboration` - Great for pairing/teaming
- `mentorship available` - Mentor will guide you

---

## 🎯 Contribution Workflow Examples

### Example 1: Fix Documentation Typo

```bash
# 1. Find the typo, note location
# 2. Create branch
git checkout -b docs/fix-typo-in-readme

# 3. Fix the typo
# 4. Commit
git add README.md
git commit -m "docs: fix typo in installation section"

# 5. Push and create PR
git push origin docs/fix-typo-in-readme
# Create PR on GitHub with simple description

# 6. Done! Merges quickly
```

**Time:** 5-10 minutes

---

### Example 2: Add New Feature

```bash
# 1. Create issue describing feature
# 2. Wait for approval/discussion
# 3. Create branch
git checkout -b feature/add-ritual-timer

# 4. Implement feature
# - Write code
# - Add tests
# - Update docs
# - Test thoroughly

# 5. Commit incrementally
git add src/RitualTimer.js
git commit -m "feat: add basic ritual timer component"

git add src/RitualTimer.test.js
git commit -m "test: add tests for ritual timer"

git add docs/tools-guide.md
git commit -m "docs: document ritual timer usage"

# 6. Push and create PR
git push origin feature/add-ritual-timer
# Create detailed PR with screenshots

# 7. Address review feedback
# 8. Merge when approved
```

**Time:** Few hours to few days depending on complexity

---

### Example 3: Improve Existing Content

```bash
# 1. Identify improvement area
# 2. Create issue or discussion
# 3. Gather feedback on approach
# 4. Create branch
git checkout -b docs/enhance-onboarding-guide

# 5. Make improvements
# - Add examples
# - Improve clarity
# - Add visuals

# 6. Commit with clear messages
git commit -m "docs(onboarding): add example journeys section

- Added 4 detailed example onboarding journeys
- Included different archetype paths
- Enhanced with real community stories

Closes #87"

# 7. Push and create PR
# 8. Iterate based on feedback
# 9. Merge when ready
```

**Time:** Several hours to days

---

## 🌟 Recognition & Credit

### How We Acknowledge Contributors

**In Repository:**
- Contributors file (auto-generated)
- Credits in documentation
- Shout-outs in changelogs

**In Community:**
- Discord announcements
- X/Twitter mentions
- Round Table recognition
- Community showcases

**Roles & Badges:**
- Discord roles based on contributions
- GitHub contributor status
- Community elder recognition

### Contribution Tiers

**🌱 Seed (First Contribution):**
- Made first PR or significant contribution
- Welcomed in Discord announcement
- Added to contributors list

**🌿 Sprout (Active Contributor):**
- 5+ merged PRs or equivalent contributions
- Regular community participation
- Helping newcomers

**🌳 Root (Core Contributor):**
- 20+ merged PRs or major contributions
- Deep expertise in area
- Mentoring others
- May get write access

**🌺 Bloom (Maintainer):**
- Significant ongoing contributions
- Stewardship of community/code
- Strategic thinking
- Full commit access

---

## 📅 Contribution Rhythms

### Weekly Contribution Patterns

**Monday (#UTOideasMonday):**
- Share new ideas in discussions
- Propose features or improvements
- Open issues for feedback

**Tuesday-Wednesday:**
- Work on contributions
- Respond to reviews
- Help others

**Thursday (#TechnoHeroThursday):**
- Share progress updates
- Demo completed work
- Showcase contributions

**Friday:**
- Wrap up PRs
- Update documentation
- Plan next week

**Weekend:**
- Deep work on projects
- Learning and exploration
- Or rest! Balance is important

### Monthly Cycles

**Week 1:** Planning and issue triage
**Week 2:** Active development
**Week 3:** Review and feedback
**Week 4:** Polish and merge

---

## 🆘 Getting Help

### Where to Ask Questions

**Discord Channels:**
- `#multichat-welcomes-all` - General questions
- `#tree/uto` - Onboarding help
- `#infra-migration` - Technical setup
- Branch-specific channels - Topic questions

**GitHub:**
- Issue comments - Specific to that issue
- Discussions - General topics
- PR reviews - Code-specific

**Direct Messages:**
- DM maintainers for private questions
- Tag people in Discord for specific help
- Email for sensitive matters

### Common Questions

**Q: How do I get started?**
Read the [Onboarding Guide](docs/onboarding/), join Discord, pick a `good first issue`.

**Q: My PR hasn't been reviewed yet.**
Be patient! Maintainers are volunteers. Politely ping after 7 days if no response.

**Q: I disagree with feedback.**
Explain your reasoning respectfully. Use dialectical process. Seek synthesis.

**Q: Can I work on multiple issues?**
Sure, but finish what you start. Don't over-commit.

**Q: I made a mistake.**
It's okay! We all do. Fix it, learn from it, move forward.

**Q: I don't have time anymore.**
Life happens! Let us know. We can reassign or pause. No judgment.

---

## 🔗 Zettelkasten Links

**Upstream:**
- `[[effective-utopia-vision]]` - Overall mission
- `[[community-network]]` - Network structure

**Related:**
- `[[onboarding-guide]]` - For new members
- `[[tools-configuration-guide]]` - Development setup
- `[[code-of-conduct]]` - Community standards
- `[[channel-directory]]` - Where to communicate

**Downstream:**
- `[[issue-templates]]` - Creating good issues
- `[[pr-templates]]` - Creating good PRs
- `[[style-guides]]` - Coding standards
- `[[testing-guidelines]]` - Quality assurance

---

## 📜 License

By contributing to ê/uto, you agree that your contributions will be licensed under the Creative Commons Attribution-ShareAlike (CC BY-SA 4.0) license unless otherwise specified.

See [LICENSE](LICENSE) for details.

---

## 🙏 Thank You

Every contribution, no matter how small, makes a difference. You're helping build ethical, abundant futures for all.

**"If a civilization doesn't go extinct, it achieves everything it dreams."**

Let's build that civilization together.

---

<div align="center">

**Welcome to the forge of the future.**

🌱 Start small → 🌿 Grow steadily → 🌳 Root deeply → 🌺 Bloom fully

**Part of the ê/uto Network**

🌍 #technoheroism · #UTOideasMonday · #TechnoHeroThursday

</div>
