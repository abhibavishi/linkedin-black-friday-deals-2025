# Contributing to LinkedIn Black Friday Deals 2025

Thank you for your interest in contributing! This guide will help you add your LinkedIn tool's Black Friday deal to our curated list.

## 🎯 Eligibility Criteria

Your deal must meet these requirements:

### ✅ What We Accept:
- **LinkedIn-focused tools** (automation, analytics, content, CRM, etc.)
- **Active Black Friday/Cyber Monday deals** for 2025
- **Verified discounts** (we may test coupon codes)
- **Clear value proposition** in description
- **Valid expiration dates** (if applicable)

### ❌ What We Don't Accept:
- Generic SaaS tools (unless they have strong LinkedIn integration)
- Expired or inactive deals
- Misleading discount claims
- Referral/affiliate links (unless clearly disclosed)
- Spam or low-quality tools
- 100% free tools (unless they have a paid upgrade with a deal)

## 📝 How to Submit a Deal

### Option 1: Pull Request (Recommended)

1. **Fork this repository**
   ```bash
   # Click the "Fork" button at the top right of this page
   ```

2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR_USERNAME/linkedin-black-friday-deals-2025.git
   cd linkedin-black-friday-deals-2025
   ```

3. **Create a new branch**
   ```bash
   git checkout -b add-[your-tool-name]
   ```

4. **Add your deal to README.md**
   - Find the appropriate category
   - Add your entry **at the end of the category table**
   - Follow the exact format below

5. **Format your entry**
   ```markdown
   | [Tool Name](https://yourtool.com) | Brief description (max 150 characters) | **COUPONCODE** - X% off | Dec 2, 2025 |
   ```

6. **Commit your changes**
   ```bash
   git add README.md
   git commit -m "Add [YourTool] Black Friday deal"
   ```

7. **Push to your fork**
   ```bash
   git push origin add-[your-tool-name]
   ```

8. **Create a Pull Request**
   - Go to the original repository
   - Click "New Pull Request"
   - Select your branch
   - Fill out the PR template (see below)

### Option 2: Create an Issue

If you're not comfortable with Git:

1. Go to [Issues](../../issues/new)
2. Use the title format: `[Deal Submission] Your Tool Name`
3. Provide:
   - Tool name and URL
   - Description (150 characters max)
   - Deal details (discount code, percentage, expiration)
   - Your relationship to the tool
4. We'll add it for you!

## 📋 Pull Request Template

When creating a PR, please include:

```markdown
## Deal Submission

**Tool Name:** YourTool
**Category:** (e.g., LinkedIn Automation & Outreach Tools)
**Website:** https://yourtool.com
**Description:** (150 characters max)
**Discount Code:** BLACKFRIDAY2025
**Discount Amount:** 60% OFF
**Valid Until:** December 2, 2025
**Your Relationship:** (Founder/Employee/User/Affiliate)

### Checklist:
- [ ] I confirm this deal is active and verified
- [ ] The description is under 150 characters
- [ ] The link is NOT a referral/affiliate link (or I've disclosed it)
- [ ] I've added it to the correct category
- [ ] I've added it at the END of the category table
- [ ] The deal is LinkedIn-specific (not generic SaaS)
```

## 🎨 Formatting Guidelines

### Tool Name
- Use the official brand name (correct capitalization)
- Link to the deal landing page, not homepage
- Example: `[Reepl](https://app.reepl.io/claim-offer/BLACKFRIDAY2025)`

### Description
- **Maximum 150 characters**
- Focus on value proposition, not features
- Be specific to LinkedIn use case
- Avoid marketing fluff
- Good: "Automate LinkedIn DMs with AI trained on your writing style"
- Bad: "The best and most amazing LinkedIn tool ever created"

### Deal Details
- Format: `**CODE** - X% off` or `**CODE** - $X off`
- Always use bold for discount codes
- Be specific: "60% off annual plans" not just "Big discount!"
- Examples:
  - `**BLACKFRIDAY2025** - 60% OFF annual plan`
  - `**BF2025** - $100 off lifetime license`
  - `Up to 50% off (no code needed)`

### Valid Until
- Use format: `Dec 2, 2025`
- If no expiration: Use `-`
- If ongoing: Use `Ongoing`

## 🏷️ Category Guidelines

Choose the most appropriate category for your tool:

| Category | What Belongs Here |
|----------|-------------------|
| **🤖 Automation & Outreach** | Connection automation, message sequences, outreach campaigns |
| **📊 Analytics & Insights** | Performance tracking, analytics dashboards, engagement metrics |
| **✍️ Content Creation** | Post writers, carousel generators, video tools, schedulers |
| **👤 Profile Optimization** | Profile builders, headline generators, photo tools |
| **💼 CRM & Lead Management** | Contact management, pipeline tracking, relationship nurturing |
| **🔌 Chrome Extensions** | Browser extensions that enhance LinkedIn |
| **📚 Training & Courses** | LinkedIn courses, workshops, training programs |
| **⭐ Premium Alternatives** | Tools that replicate LinkedIn Premium/Sales Navigator |

**Not sure?** Open an issue and tag it `question`.

## ⚡ Review Process

1. **Automated Checks** (instant)
   - Link validity
   - Markdown formatting
   - Table structure

2. **Manual Review** (within 24-48 hours)
   - Deal verification
   - Quality assessment
   - Category fit
   - Description accuracy

3. **Approval & Merge**
   - PRs are typically merged within 48 hours
   - You'll be notified of any changes needed

## 🚫 Common Rejection Reasons

- **Broken links** - Test your URLs before submitting
- **Expired deals** - Verify the deal is still active
- **Wrong category** - Choose the best fit category
- **Too long description** - Keep under 150 characters
- **Not LinkedIn-specific** - Must be primarily for LinkedIn
- **Low quality tools** - We maintain quality standards
- **Affiliate links without disclosure** - Be transparent

## ✨ Pro Tips

1. **Submit early** - Black Friday is competitive!
2. **Test your coupon code** - Make sure it works
3. **Use clear descriptions** - Explain the value quickly
4. **Set realistic discounts** - Don't inflate original prices
5. **Update if needed** - If your deal changes, submit an update PR

## 📊 After Your Deal is Added

- **Share the repo** - Help others discover these deals
- **Star the repository** - Show your support
- **Update if needed** - Submit a PR if deal details change
- **Promote** - Mention the repo when promoting your deal

## 🔄 Updating Your Deal

If you need to update your deal:

1. Create a new PR with `[Update]` in the title
2. Explain what changed and why
3. We'll review and merge quickly

## 📞 Questions?

- **General questions:** Open an [Issue](../../issues)
- **Private inquiries:** Email [team@reepl.io](mailto:team@reepl.io)
- **Technical help:** Check existing issues or create a new one

---

Thank you for contributing to the LinkedIn community! 🎉

**Happy Black Friday!** 🛍️
