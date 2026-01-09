# SEO Guide for Watson Laser Lab Website

This guide provides best practices for optimizing content on the Watson Laser Lab website for search engines.

## Table of Contents
- [Quick Reference](#quick-reference)
- [Page Frontmatter](#page-frontmatter)
- [Content Writing Tips](#content-writing-tips)
- [Images and Media](#images-and-media)
- [Analytics Setup](#analytics-setup)
- [Monitoring](#monitoring)

---

## Quick Reference

### Essential SEO Fields for All Content

```yaml
---
title: "Your Page Title (50-60 characters)"
description: "Compelling 150-160 character description with keywords"
date: 2026-01-09
tags:
  - spectroscopy
  - physical-chemistry
  # Add 3-5 relevant keywords
---
```

---

## Page Frontmatter

### Publications

```yaml
---
title: "Descriptive Paper Title"
authors:
  - admin
  - Author Two
date: "2026-01-09"
publishDate: "2026-01-09"

# Publication type (article-journal, preprint, conference-paper, etc.)
publication_types: ["article-journal"]

# Publication name
publication: "Journal Name"
publication_short: "J. Name"

# Abstract - use full abstract for best SEO
abstract: "Detailed abstract with key terms..."

# Summary for listings (1-2 sentences)
summary: "Brief summary highlighting main findings and methods."

# Tags for categorization
tags:
  - laser-spectroscopy
  - physical-chemistry
  - molecular-dynamics

# Featured publication?
featured: false

# Links
url_pdf: "path/to/pdf"
url_code: "https://github.com/..."
url_dataset: "https://doi.org/..."

# Featured image
image:
  caption: 'Descriptive caption with keywords'
  focal_point: "Smart"
  preview_only: false
  alt_text: 'Detailed description of what the image shows'

# DOI
doi: "10.xxxx/xxxxx"
---
```

### Blog Posts

```yaml
---
title: "Engaging Blog Post Title"
subtitle: "Optional subtitle for context"
summary: "Compelling 1-2 sentence summary with keywords"
date: 2026-01-09
lastmod: 2026-01-09

# Authors
authors:
  - admin

# Tags
tags:
  - research-update
  - spectroscopy
  - lab-news

# Categories
categories:
  - Research
  - News

# Featured post?
featured: false

# Featured image
image:
  caption: "Image description"
  focal_point: "Smart"
  preview_only: false
  alt_text: "Descriptive alt text"

# Projects (link to research projects)
projects:
  - project-slug
---
```

### Research Projects

```yaml
---
title: "Project Name"
summary: "One-line project summary"
description: "Detailed 2-3 sentence description including key methodologies and objectives. Include relevant keywords naturally."

# Tags
tags:
  - liquid-jets
  - spectroscopy
  - instrumentation

# Date
date: "2024-01-01"

# Featured image
image:
  caption: "Equipment or results image caption"
  focal_point: Smart
  alt_text: "Descriptive text explaining the image"

# Links
links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/GetResearchDev
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional)
slides: ""
---
```

### Author/Team Member Pages

```yaml
---
title: "Dr. First Last"
role: "Position/Title"

# Organizations
organizations:
  - name: Curtin University
    url: "https://www.curtin.edu.au/"

# Short bio (appears in author lists)
bio: "Brief 1-2 sentence bio focusing on expertise and research interests."

# Research interests (displayed on profile)
interests:
  - Laser Spectroscopy
  - Physical Chemistry
  - Molecular Dynamics

# Education
education:
  courses:
    - course: PhD in Chemistry
      institution: University Name
      year: 2020
    - course: BSc in Chemistry
      institution: University Name
      year: 2015

# Social/Academic networks
social:
  - icon: envelope
    icon_pack: fas
    link: 'mailto:email@example.com'
  - icon: twitter
    icon_pack: fab
    link: https://twitter.com/username
  - icon: google-scholar
    icon_pack: ai
    link: https://scholar.google.com/citations?user=XXXXX
  - icon: orcid
    icon_pack: ai
    link: https://orcid.org/0000-0000-0000-0000
  - icon: github
    icon_pack: fab
    link: https://github.com/username

# User groups (for team page organization)
user_groups:
  - PhD Students

# For alumni
# user_groups:
#   - Alumni
# alumni_year: 2024
---
```

---

## Content Writing Tips

### 1. Title Optimization
- **Length**: 50-60 characters (displays fully in search results)
- **Keywords**: Include primary keyword near the beginning
- **Clarity**: Make it clear what the page is about
- **Examples**:
  - ✅ "Liquid Jet Spectroscopy Research | Watson Lab"
  - ❌ "Our Amazing Research"

### 2. Meta Descriptions
- **Length**: 150-160 characters
- **Content**: Compelling summary that encourages clicks
- **Keywords**: Include 1-2 main keywords naturally
- **Call-to-action**: Consider adding action words
- **Examples**:
  - ✅ "Discover our liquid jet spectroscopy research using advanced laser techniques to study molecular dynamics. Learn about our methods and recent publications."
  - ❌ "This is our research page."

### 3. Content Structure
- **Headings**: Use H2, H3 hierarchy (H1 is auto-generated from title)
- **First paragraph**: Include main keywords in opening 100 words
- **Length**: Aim for 300+ words on main pages
- **Readability**: Short paragraphs, bullet points, clear language
- **Internal links**: Link to related publications, projects, team members

### 4. Keyword Strategy

**Primary Keywords** (use in titles, H2s, first paragraph):
- Laser spectroscopy
- Physical chemistry
- Molecular dynamics
- Chemical physics

**Secondary Keywords** (use throughout content):
- Liquid jet spectroscopy
- Laser ablation synthesis
- High-resolution spectroscopy
- Infrared spectroscopy
- Cluster chemistry
- Gas-phase spectroscopy

**Long-tail Keywords** (use in blog posts, detailed pages):
- "liquid microjet spectroscopy methods"
- "laser ablation synthesis of nanoparticles"
- "high-resolution infrared spectroscopy techniques"

### 5. Writing for Both Humans and Search Engines
- Write naturally - don't force keywords
- Focus on providing value to readers
- Answer common questions in your field
- Use keywords in context, not in lists
- Maintain academic credibility while being accessible

---

## Images and Media

### Image Optimization
1. **File names**: Use descriptive names with keywords
   - ✅ `liquid-jet-spectroscopy-setup.jpg`
   - ❌ `IMG_1234.jpg`

2. **Alt text**: Describe what's in the image (for accessibility and SEO)
   - ✅ `"Liquid microjet system with laser alignment and detection optics"`
   - ❌ `"Lab equipment"`

3. **Captions**: Add context and keywords when relevant
   ```yaml
   image:
     caption: 'High-resolution infrared spectrum showing vibrational bands'
     alt_text: 'Graph displaying infrared absorption spectrum with labeled peaks'
   ```

4. **File size**: Compress images before uploading (aim for <500KB)
   - Use tools like TinyPNG, ImageOptim, or Squoosh

5. **Format**:
   - Use WebP for best compression (with JPEG fallback)
   - PNG for diagrams/screenshots
   - JPEG for photos

---

## Analytics Setup

### Google Analytics 4

1. **Create GA4 Property**:
   - Go to [Google Analytics](https://analytics.google.com)
   - Admin → Create Property
   - Follow setup wizard

2. **Get Measurement ID**:
   - Admin → Data Streams → Your web stream
   - Copy Measurement ID (format: `G-XXXXXXXXXX`)

3. **Add to Config**:
   - Edit `config/_default/params.yaml`
   - Add under `marketing.analytics.google_analytics`

4. **Key Metrics to Track**:
   - Page views by section (Research, Publications, Team)
   - Most viewed publications
   - Traffic sources
   - User engagement (time on page, bounce rate)
   - Geographic distribution

### Google Search Console

Already configured with verification code: `orxzTq-XVc4sbtFuu86twhe0LgLg-o_fzpFPUP07l5U`

**What to Monitor**:
1. **Performance**:
   - Click-through rates (CTR)
   - Average position for keywords
   - Impressions and clicks

2. **Coverage**:
   - Indexed pages
   - Crawl errors
   - Sitemap status

3. **Enhancements**:
   - Mobile usability
   - Core Web Vitals
   - Structured data validation

**Action Items**:
- Submit sitemap: `https://watsonlaserlab.com/sitemap.xml`
- Monitor weekly for crawl errors
- Check keyword performance monthly
- Review mobile usability quarterly

---

## Monitoring

### Monthly Checklist

#### Search Performance
- [ ] Review Search Console performance reports
- [ ] Check for crawl errors
- [ ] Monitor keyword rankings for main terms
- [ ] Review most clicked pages
- [ ] Check mobile usability issues

#### Analytics
- [ ] Review GA4 traffic trends
- [ ] Identify top-performing content
- [ ] Analyze user engagement metrics
- [ ] Check bounce rates by page type
- [ ] Review traffic sources

#### Content
- [ ] Update stale content (>1 year old)
- [ ] Add new publications promptly
- [ ] Ensure all images have alt text
- [ ] Check for broken internal/external links
- [ ] Review and update meta descriptions

#### Technical
- [ ] Test site speed (aim for <3s load time)
- [ ] Validate structured data with [Schema Markup Validator](https://validator.schema.org/)
- [ ] Check sitemap is current
- [ ] Review Core Web Vitals in Search Console
- [ ] Test on mobile devices

### Quarterly Goals

1. **Q1 Goals**:
   - Improve organic traffic by 15%
   - Publish 4+ blog posts
   - Update all research project pages
   - Add alumni achievements

2. **Q2 Goals**:
   - Increase keyword rankings for top 5 terms
   - Build 10+ quality backlinks
   - Create 2+ detailed methods pages
   - Expand publication database

3. **Q3 Goals**:
   - Achieve page 1 ranking for "laser spectroscopy Perth"
   - Launch research highlight series
   - Video content optimization
   - Social media integration

4. **Q4 Goals**:
   - Year-end review and strategy planning
   - Update all team member profiles
   - Create annual report page
   - Audit all content for freshness

---

## Link Building Strategies

### Internal Linking
- Link new publications to relevant research projects
- Cross-reference related blog posts
- Link team members to their publications
- Create topic clusters (hub and spoke model)

### External Backlinks
- Submit to academic directories
- Register with university department
- List on research networking sites (ResearchGate, Academia.edu)
- Engage with science communication platforms
- Write guest posts for related research blogs
- Present at conferences and link presentations
- Collaborate with other research groups

### Quality Criteria
- Prioritize .edu and .org domains
- Focus on relevant, high-authority sites
- Natural, editorial links (not link schemes)
- Diverse anchor text
- Links from content, not sidebars/footers

---

## Quick Wins

### Immediate Actions (Do Now)
1. ✅ Google Search Console verification (completed)
2. ✅ Enhanced site descriptions (completed)
3. ✅ Structured data added (completed)
4. Set up Google Analytics
5. Add meta descriptions to all publications
6. Optimize image alt text across site

### Short-term (This Month)
1. Create 2 blog posts about recent research
2. Update all research project pages with detailed descriptions
3. Add ORCID links for all team members
4. Submit site to academic directories
5. Review and fix any broken links
6. Optimize 5 oldest publication pages

### Medium-term (This Quarter)
1. Build backlinks from 5 quality sources
2. Create comprehensive methods/techniques pages
3. Develop content calendar for regular updates
4. Implement blog content strategy
5. Create video content for key research areas
6. Expand about/history section

---

## Resources

### SEO Tools
- **Google Search Console**: [search.google.com/search-console](https://search.google.com/search-console)
- **Google Analytics**: [analytics.google.com](https://analytics.google.com)
- **Schema Markup Validator**: [validator.schema.org](https://validator.schema.org)
- **PageSpeed Insights**: [pagespeed.web.dev](https://pagespeed.web.dev)
- **Mobile-Friendly Test**: [search.google.com/test/mobile-friendly](https://search.google.com/test/mobile-friendly)

### Keyword Research
- **Google Scholar**: See what terms are used in your field
- **Google Trends**: Track search interest over time
- **Answer The Public**: Find question-based queries
- **Competitor analysis**: See what keywords similar labs rank for

### Image Optimization
- **TinyPNG**: [tinypng.com](https://tinypng.com)
- **Squoosh**: [squoosh.app](https://squoosh.app)
- **ImageOptim**: [imageoptim.com](https://imageoptim.com)

### Learning Resources
- **Moz Beginner's Guide to SEO**: [moz.com/beginners-guide-to-seo](https://moz.com/beginners-guide-to-seo)
- **Google Search Central**: [developers.google.com/search](https://developers.google.com/search)
- **Schema.org Documentation**: [schema.org](https://schema.org)

---

## Support

For questions about SEO implementation or issues with the site, contact:
- **Technical**: Review this guide and Hugo Blox documentation
- **Analytics**: Check Google Analytics and Search Console help centers
- **Strategy**: Consider consulting with digital marketing or SEO specialists for academic websites

---

**Last Updated**: January 2026
**Maintained By**: Watson Laser Lab
