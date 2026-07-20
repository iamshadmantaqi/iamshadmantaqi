# Graph Report - .  (2026-07-20)

## Corpus Check
- Corpus is ~990 words - fits in a single context window. You may not need a graph.

## Summary
- 49 nodes · 86 edges · 8 communities (7 shown, 1 thin omitted)
- Extraction: 70% EXTRACTED · 27% INFERRED · 3% AMBIGUOUS · INFERRED: 23 edges (avg confidence: 0.81)
- Token cost: 70,375 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Profile & Affiliations|Profile & Affiliations]]
- [[_COMMUNITY_AI & Backend Stack|AI & Backend Stack]]
- [[_COMMUNITY_Infrastructure Stack|Infrastructure Stack]]
- [[_COMMUNITY_Phoenix Products|Phoenix Products]]
- [[_COMMUNITY_Publishing & Question Banks|Publishing & Question Banks]]
- [[_COMMUNITY_Frontend Stack|Frontend Stack]]
- [[_COMMUNITY_Target Universities|Target Universities]]
- [[_COMMUNITY_Version Control|Version Control]]

## God Nodes (most connected - your core abstractions)
1. `Engineering Stack` - 18 edges
2. `Shadman Taqi` - 15 edges
3. `Phoenix Education` - 12 edges
4. `Automata One` - 7 edges
5. `Phoenix WebLMS` - 7 edges
6. `Phoenix Admission Book Series (8 titles)` - 6 edges
7. `AI Layer (multi-model)` - 6 edges
8. `Self-Hosted Infrastructure` - 6 edges
9. `North South University (NSU)` - 5 edges
10. `Private University Admission Preparation` - 5 edges

## Surprising Connections (you probably didn't know these)
- `Ads Performance Analytics` --conceptually_related_to--> `AI Layer (multi-model)`  [AMBIGUOUS]
  README.md → README.md  _Bridges community 0 → community 1_
- `Phoenix WebLMS` --conceptually_related_to--> `FastAPI`  [INFERRED]
  README.md → README.md  _Bridges community 3 → community 1_
- `Phoenix WebLMS` --conceptually_related_to--> `Next.js`  [INFERRED]
  README.md → README.md  _Bridges community 3 → community 5_
- `Shadman Taqi` --references--> `Bangladesh Mathematical Olympiad (BDMO)`  [EXTRACTED]
  README.md → README.md  _Bridges community 0 → community 4_
- `Shadman Taqi` --references--> `Self-Hosted Infrastructure`  [EXTRACTED]
  README.md → README.md  _Bridges community 0 → community 2_

## Import Cycles
- None detected.

## Communities (8 total, 1 thin omitted)

### Community 0 - "Profile & Affiliations"
Cohesion: 0.35
Nodes (12): GitHub Profile README (iamshadmantaqi), Ads Performance Analytics, Automata One, BUET National ICT Quiz, Dhaka, Bangladesh, IEEE NSU Student Branch, North South University (NSU), NSU Academics (student community) (+4 more)

### Community 1 - "AI & Backend Stack"
Cohesion: 0.29
Nodes (7): AI Layer (multi-model), Bengali Sales Call Scoring Pipeline, Claude, DeepSeek, FastAPI, Gemini, Python

### Community 2 - "Infrastructure Stack"
Cohesion: 0.48
Nodes (7): Cloudflare, Docker, Figma, Linux, Nginx, Self-Hosted Infrastructure, Engineering Stack

### Community 3 - "Phoenix Products"
Cohesion: 0.40
Nodes (6): Admission Assistant App, bKash Checkout, Flutter, Live Batches, PostgreSQL, Phoenix WebLMS

### Community 4 - "Publishing & Question Banks"
Cohesion: 0.40
Nodes (6): Private University Admission Preparation Guide, Bangladesh Mathematical Olympiad (BDMO), Per-University Model Question Books, Phoenix Admission Book Series (8 titles), English and Maths Question Banks, Rokomari (book retail channel)

### Community 5 - "Frontend Stack"
Cohesion: 0.40
Nodes (5): JavaScript, Next.js, React, Tailwind CSS, TypeScript

### Community 6 - "Target Universities"
Cohesion: 0.50
Nodes (4): Private University Admission Preparation, BRAC University (BRACU), East West University (EWU), Independent University, Bangladesh (IUB)

## Ambiguous Edges - Review These
- `Phoenix Education` → `Science Bee`  [AMBIGUOUS]
  README.md · relation: conceptually_related_to
- `Automata One` → `BUET National ICT Quiz`  [AMBIGUOUS]
  README.md · relation: conceptually_related_to
- `Ads Performance Analytics` → `AI Layer (multi-model)`  [AMBIGUOUS]
  README.md · relation: conceptually_related_to

## Knowledge Gaps
- **9 isolated node(s):** `Dhaka, Bangladesh`, `BRAC University (BRACU)`, `East West University (EWU)`, `Independent University, Bangladesh (IUB)`, `Rokomari (book retail channel)` (+4 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **1 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `Phoenix Education` and `Science Bee`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `Automata One` and `BUET National ICT Quiz`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `Ads Performance Analytics` and `AI Layer (multi-model)`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **Why does `Shadman Taqi` connect `Profile & Affiliations` to `AI & Backend Stack`, `Infrastructure Stack`, `Publishing & Question Banks`?**
  _High betweenness centrality (0.508) - this node is a cross-community bridge._
- **Why does `Engineering Stack` connect `Infrastructure Stack` to `Profile & Affiliations`, `AI & Backend Stack`, `Phoenix Products`, `Frontend Stack`, `Version Control`?**
  _High betweenness centrality (0.415) - this node is a cross-community bridge._
- **Why does `Phoenix Education` connect `Profile & Affiliations` to `Phoenix Products`, `Publishing & Question Banks`, `Target Universities`?**
  _High betweenness centrality (0.228) - this node is a cross-community bridge._
- **Are the 4 inferred relationships involving `Phoenix Education` (e.g. with `Ads Performance Analytics` and `Automata One`) actually correct?**
  _`Phoenix Education` has 4 INFERRED edges - model-reasoned connections that need verification._