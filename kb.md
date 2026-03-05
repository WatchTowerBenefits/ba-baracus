# BA Baracus Knowledge Base - Complete Reference Guide

## Table of Contents
1. [NPC & Alt Overview](#npc--alt-overview)
2. [Process Guides](#process-guides)
3. [Decision Trees](#decision-trees)
4. [Troubleshooting](#troubleshooting)
5. [Q&A Library](#qa-library)
6. [Common Mistakes](#common-mistakes)
7. [Troubleshooting Flowcharts](#troubleshooting-flowcharts)
8. [Quick Reference](#quick-reference)
9. [Renewal Collection Operations](#renewal-collection-operations)

---

# NPC & Alt Overview

## What are NPCs and Alts?

**NPC (No Prior Coverage)**: Group has never offered this coverage before. Carrier listed as "none". Requires estimated premiums.

**Alt (Alternate)**: Different plan design for coverage already in place. Copied from existing coverage. Rates set to $0.

**Common Terminology**:
- **NPC**: No Prior Coverage, Virgin Coverage, Previously Uninsured Group (PUG), First Time Buyer, npc, NPC's
- **Alt**: ALT, Alternatives, Alt Treatment, Alternate Coverage, alt

## When to Use Each

### Use NPC When:
- Group doesn't currently have that product
- Broker is NOT broker of record for existing coverage
- Converting individual coverage to group coverage (STD, worksite)
- **Most common**: Employer has some benefits but adding new product (e.g., has medical/dental, adding vision)

### Use Alt When:
- Product already exists, broker wants multiple plan designs
- Group is live - brokers request through CX via Typeform
- Showing "match current" vs alternative options

### Combined NPC + Alts:
Multiple plan designs for product NOT currently in place. **Complete NPC first** (with premiums), then add alts from admin site. Only NPC needs premiums.

## NPC Can Apply To:
- **All employees, all lines** - Employer never offered any coverage
- **A certain product** - Most common (e.g., has medical/dental, adding vision)
- **A certain population** - Expanding coverage to part-time employees

---

# Process Guides

## [PROCESS-001] Principal Proposal Email Handling

### Adding Recipients in Broker Site
**Question**: When receiving Principal email, should I select "Add carrier" or "Add new recipients for existing carrier"?

**Answer**: Use "Add new recipients for existing carrier" when Principal is already invited to the marketing event.

### When to Add Recipients
**Rule**: If the person who submitted the Principal proposal email is already included in broker site, do NOT add them again.

### "On Behalf Of" Scenarios
**Question**: Email says "on behalf of [Person Name]". Add both names?

**Answer**: No need to add everyone. As long as one of the two people is listed, you don't need to add anyone additional.

### Broker Labels
**Rule**: Only use Brown & Brown labels for Brown & Brown emails. For everyone else (Unico, etc.), use Principal labels.

**Why**: Would get messy to add labels for every broker. Keep it simple: BB or Principal.

---

## [PROCESS-002] Renewal Handling

### Standard Renewal Process
**Action**: Forward to submit@threeflow.com

**When to Use**:
- Email explicitly states "renewal"
- Updated renewal rates received
- Carrier site shows event type as "Renewal"
- Renewal chained email received

### Renewal + New Coverage
**Scenario**: Renewal email includes new line of coverage (e.g., Hospital Indemnity)

**Action**: 
1. Forward renewal attachment/email to submit@threeflow.com
2. Forward new coverage proposal to support@threeflow.com with message:
   > "Principal sent over a quote for a [Product] product attached to a renewal. However, the broker does not currently have an active marketing event on ThreeFlow for [Product]. Can you please check with the Broker to see if they want to start a marketing event to have this added?"

### Updated Renewal Rates
**Action**: Forward to submit@threeflow.com even if rates differ from currently submitted values

### Renewal with Alt Plans
**Scenario**: Receive alternate proposals for products that are renewals

**Action**: Upload via "Update Renewal" to use AI (may go to ThreeFlow Assist) OR manually input if AI routes incorrectly

**Example**: Broker asks to submit "low plan" from proposal into regular dental (non-alt). Manually enter rates and submit.

---

## [PROCESS-003] Document Upload Strategy

### When to Use AI Upload ("Update Quote")
**Use when**:
- Alt products only in proposal (won't override other coverages)
- Products are in "Not Started" status
- No other lines of coverage would be affected
- Worksite products that can go through ThreeFlow Assist
- All products in proposal are the ONLY products you want to update

**How**: Select "Update quote" → Enable checkbox to rerun through smart proposal

**Warning**: AI may override existing submissions if other products are in the proposal. Use manual entry if uncertain.

### When to Manually Enter
**Use when**:
- Multiple coverage options exist and you only want to update specific ones
- Other products already submitted that shouldn't be touched
- Avoiding override of already-entered attributes
- Rate-only updates
- Commission-only updates
- Products with specific plan design changes (not just rate updates)

**Process**:
1. Upload new proposal to "My Documents" section
2. Manually update rates/plan design in carrier site
3. Spot-check other attributes for changes
4. Submit or resubmit as needed

### Document Upload Only (No Submission)
**Use when**:
- Marketing event is closed
- Documents already uploaded/submitted with same rates
- Carrier provided docs proactively (worksite not requested)
- Group is complete but want documentation saved

**Action**: Upload to "My Documents" folder only

### Re-uploading Same Document
**Scenario**: Receive updated proposal with changes to STD/LTD but only need to upload for specific products

**Action**: 
1. Upload to "My Documents"
2. Use "Update Quote" with AI checkbox ONLY if updating lines not yet submitted
3. Manual entry for products already submitted to avoid overriding

---

## [PROCESS-004] Declination Handling

### Decline Reason Code Mapping

| Carrier Statement | Reason Code to Use |
|-------------------|-------------------|
| "Rates uncompetitive" / "Current carrier fairly priced" | Rates Uncompetitive |
| "SIC code" / "Nature of business" / "Due to industry" | Non-preferred (or unfavorable) industry |
| "We don't offer self-insured in this group size" | Size segment outside carrier min/max threshold |
| "Unable to quote" (rate-related) | Rates Uncompetitive |
| "No pricing tied to..." (worksite proactively quoted) | Don't decline - upload docs, submit only requested lines |
| "Declined by UW" but only certain options | Decline only those specific options |

### When NOT to Decline
**Scenario**: Carrier asks for more information (e.g., "need updated census with occupations/salaries", "need additional details to quote")

**Action**: Leave in ambiguous status until you either:
- Receive updated proposal, OR
- Get specific decline information

**This is NOT a decline** - It's a request for more info.

### Multiple Products, Multiple Reasons
**Question**: Email states declining multiple products for different reasons. Individual reasons or single reason?

**Answer**: Use single reason that comes up most often for the declined lines. Can decline all at once.

### Undo Decline
**Scenario**: Product showing as declined but received proposal

**Action**: Can undo decline in carrier site and upload as normal

---

## [PROCESS-005] NPC/Alt Build Workflow

### Standard Turnaround
**SLA**: Complete within 1 business day

**Rush Requests**: Priority 1 (ASAP) - Tag CX when complete

### Request Process
1. Request comes through #npcaltrequest Slack channel
2. User mentions next available underwriter analyst
3. UA completes request
4. UA tags @npcqa2 in thread
5. QA2 confirms reviewing
6. QA2 notifies user when finalized

### NPC Setup Steps
1. Identify NPC (carrier = "none")
2. Keep carrier as "None"
3. Use appropriate NPC template
4. Rename plan/class descriptions:
   - **Plan Based** (Dental, Vision, Stop Loss)
   - **Worksite**: High Plan, Low Plan
   - **Class Based**: All Eligible Employees
5. Complete all plan design values (use template recommendations, adjust per broker notes in ClickUp/Slack)
6. Set appropriate rate structures
7. **Enter estimated premiums** (REQUIRED for NPCs)

### Alt Setup Steps
1. **Alts are copied from current coverage** (never built from scratch)
2. Rename base product to "[Product] - Match Current"
   - **Stop Loss**: "$XX,XXX - Match Current" (e.g., $80,000 - Match Current)
   - **Note**: Product name uses this convention. Plan name should be "Stop Loss" unless differentiators needed
3. Rename alternate product per conventions:
   - **Non-med**: "[Product] - [variation]" (e.g., "STD - ER Paid", "LTD - 60% schedule")
   - **Stop Loss**: $XX,XXX only (e.g., $65,000)
   - **Multiple changes**: Use | to separate (e.g., "LTD: 60% | $2,500 | 26 week")
4. Make plan design changes based on broker notes
5. **Enter $0 for rates** (rate structure should match base, change if needed)
6. Add from admin site

### Product Abbreviations
- Basic Life/AD&D = BL/ADD
- Short Term Disability = STD
- Long Term Disability = LTD
- Critical Illness = CI
- Accident = Acc
- Hospital Indemnity = HI

### Combined NPC + Alts Process
1. Complete NPC first (with premiums)
2. Rename NPC to match alt conventions  
3. Add alts from admin site
4. **Alts do NOT need premiums**

### Important Notes
- **Do NOT upload broker documentation to admin**
- Always use templates and adjust per broker notes
- Rename plan/class descriptions as needed
- Check for broker-specific templates (e.g., SCOTT Insurance Vision requirements)

---

## [PROCESS-006] Commission Updates

### Commission Listed in Email Only
**Action**: Enter commission value from email into carrier site manually

**Don't**: Reupload proposal via AI - would override other attributes

### Commission Not Listed Anywhere
**Action**: Leave commission field blank

### Commission Update Only (No Rate Changes)
**Process**:
1. Update commission attribute manually in carrier site
2. Verify rates still accurate
3. Upload new proposal document to "My Documents" (if provided)
4. Do NOT use "Update Quote" - would override everything

---

## [PROCESS-007] Email Classification & Labeling

### Email Labels to Use

| Label | When to Use |
|-------|-------------|
| Principal_Proposal | Direct from Principal rep (may need to add recipients) |
| Principal_Renewal | Renewal from Principal → Forward to submit@threeflow.com |
| BB_Proposal | From Brown & Brown rep |
| BB_Renewal | Brown & Brown renewal → Forward to submit@threeflow.com |
| Complete | No action needed (notifications, already processed, duplicate) |
| Escalated | Needs team attention (wrong carrier, unclear, missing info) |

### Determining Original Sender in Chained Emails
**Rule**: Label based on **original sender** of the chain (usually the Principal rep), not the most recent person

**Example**: Email from bbrown@brownandbrowninsurance.com but original Principal rep sent it → Label as "Principal_Proposal"

### Forwarded Through Google Group
**Issue**: "From" field shows group address (proposals@threeflow.com) not original sender

**Solution**: Check `reply-to` field or email headers to identify original sender's domain for proper labeling

### ThreeFlow System Notifications
**Types**:
- "Comment Received" → Mark as Complete
- "Ready to Review" → Process as normal workflow
- Auto-generated notifications on closed products → Mark as Complete

---

## [PROCESS-008] Multi-Carrier Scenarios

### Proposal for Non-Invited Carrier
**Scenario**: Received Delta Dental proposal but Delta not invited to marketing event

**Action**: 
1. Escalate to UC/CX to add carrier to marketing event
2. Wait for confirmation carrier added
3. Proceed with upload once carrier appears in broker site

### Proposal for Different Carrier (Not Delta)
**Examples**: Cigna, Prudential, Mutual of Omaha when not invited

**Action**: 
- If completed by another ThreeFlow associate → Mark as Complete
- If needs processing → Mark as "Escalated" (NOT just complete)
- Note: Still needs to be addressed by team

### Undeliverable Carrier Contact
**Scenario**: Delta Dental invited but need to add recipient, no contact email available

**Action**: Enter carrier contact as "undeliverable@threeflow.com"

---

## [PROCESS-009] Renewal Collection - Rate Entry Rules

### Rate Pass / Rate Hold / Rate Guarantee Scenarios

**Rule**: Rate pass = rate hold = no change renewal. Copy current rates forward and enter the rate guarantee duration in months.

**Variations that all mean the same thing**:
- "Rate pass"
- "Rate hold"
- "Rate lock" (for remaining duration)
- "No change renewal"
- "0% rate action"
- "Rates will remain the same"
- Document states "no changes to plan design or carrier"

**ASO / Self-Funded Exception**: If you see "COBRA rates" or "premium equivalent" language on a dental or vision renewal, the plan is likely ASO or self-funded. These plans typically have composite rates under $11 PEPM. Do not treat as a standard rate pass — enter the composite admin/network fee.

### Rate Guarantee Duration Defaults

| Scenario | Rate Guarantee to Enter |
|---|---|
| Standard, not specified | 12 months |
| Document specifies 24-month guarantee | 24 months |
| Document specifies 12-month and 24-month options | Use 12 months unless directed otherwise |
| "Rate guarantee through [date]" stated explicitly | Calculate months from renewal date to that date |
| NY DBL — "rate pass for 24 months" language | 24 months |

### Which Rates to Use When Multiple Sets Exist

| Scenario | Use These Rates |
|---|---|
| "Renewal rates" vs "Revised renewal rates" | Always use the most recent revision |
| "Original renewal" vs "Revised renewal" | Use "Revised" |
| Rates labeled "Final negotiated" in email | Use final negotiated rates, not renewal document |
| Rates highlighted in yellow in proposal | Use highlighted rates |
| "One Year Renewal Rates" vs "Two Year Renewal Rates" | Match rate guarantee period to rate option |
| "Renewal rates including agent fees" vs "excluding" | Use rates including agent fees |
| Monthly premium rows vs contribution rows | Use "monthly premium" rows; do not use "contribution" rows |
| Column labeled "Total Costs" | Use Total Costs column for renewal rates |
| Current rates and new rates in same column | Column F / "new rate" column is renewal |

### Products to Process vs Skip

**Process only products shown in the renewal document.** Carriers may issue separate renewals for additional products.

**Always skip / do not process**:
- Alt plans (unless explicitly instructed to process a specific alt)
- Absence Management (unless specifically included in renewal scope)
- Medical (not processed by this team)
- NJ TDB ("set by the state, no renewal")
- Voluntary AD&D (different workflow — ignore unless separate instructions given)
- Products in an active rate guarantee period (skip until guarantee expires)
- New business quotes embedded in renewal documents (these are not renewals)

**Enter $0 for**:
- Missing child rates when no rate is provided
- Missing AD&D rates when no rate is provided
- Plans where carrier explicitly shows $0
- Class 2 fields when only Class 1 rates are documented (unless instructed otherwise)

**Do NOT enter $0 for**:
- Products where rates simply weren't received — skip or escalate instead
- Basic/Dependent Life child rates when the product should be ignored entirely

### NY DBL / PFL Specific Rules

**PFL rate for 2026 renewals**: Use **0.432**

**If current PFL rate shows "--" on carrier site**: Enter **0** (not 0.432)

**If any other PFL rate is present**: Enter **0.432**

**DBL composite rate**: Enter the same rate for both male and female fields when rates match across gender (e.g., $0.500 for both).

**PFL male/female split**: PFL is a composite rate. Enter 0.432 for the composite PFL field. DBL male and female fields should reflect the DBL rates separately.

---

## [PROCESS-010] Renewal Collection - Carrier & Employer Lookup

### Employer Not Found on Carrier Site

**Lookup order**:
1. Try exact name from Asana task
2. Try DBA name or alternate name from renewal document
3. Search broker site for confirmed employer name
4. Search admin site
5. If still not found → Send back to original UA and escalate

**Known name variations to check**:
- DBA names (e.g., "AeroSafe Global" instead of legal entity name)
- Shortened names (e.g., "Gravity IT" = "Michael Clarke LLC DBA Gravity IT Resources")
- Parent company names
- Names with/without LLC, Inc, Corp

### Carrier Credential Lookup (1Password)

**If credentials not found**:
1. Check for alternate broker name spelling (e.g., "HUB INTERNATIONAL" covers "HUB INTERNATIONAL INSURAN")
2. Check if broker is excluded (see Scenario Classification below)
3. Request credentials from SME if broker is active but credentials missing

**Known credential mappings**:

| Broker / Carrier | Login / Note |
|---|---|
| Delta Dental (general) | Use Delta Dental Insurance Company (DDIC) |
| Marsh McLennan - DC | readyrenewal+marshmclennandc@threeflow.com |
| MMA - GA / McGriff - Blue Ridge | Same broker, use McGriff Insurance - Blue Ridge |
| Alliant Insurance Services | readyrenewal+alliantinsuranceservices@threeflow.com |
| UNICO / UNICO - Nebraska | Same, proceed as one |
| Brown & Brown (Southern CA) - Non-Medical GA | Treat like other B&B locations; credentials in 1Password |
| The Baldwin Group - Southwest | Find state in admin site; "Outsourced" suffix = do not process |
| HUB INTERNATIONAL INSURAN | Use HUB INTERNATIONAL as reference |

### Carrier Site UI Issues

| Issue | Resolution |
|---|---|
| "Update Quote" instead of "Start Renewal" | Same destination — proceed as normal |
| "Review Plan Design" instead of "Submit" | Enter `--` in any missing plan design fields to unlock Submit |
| "There was an error loading the product" | Reassign to UA; technical issue |
| "There was an error creating your market event" | SME collects renewal manually |
| Document stuck in "Processing" state | Reassign to UA and escalate |
| Rate fields blank in admin site after update | Check that plan description field is filled in; blank plan name blocks rate changes |
| Unable to submit — only "Collect Files" tab visible | Upload blank workbook to bypass; reuse same blank workbook for each Stop Loss product |

---

## [PROCESS-011] Renewal Collection - Scenario Classification

### Scenario Color Guide

| Scenario | Condition | Action |
|---|---|---|
| **Red** | Excluded broker, BOR lost, employer not found anywhere | Tag "excluded broker" or "BOR lost"; close Asana task |
| **Orange** | Broker active but specific handling required | Follow broker-specific instructions |
| **Yellow** | Employer exists, product exists, needs collection | Collect renewal as normal |
| **Light Green** | Employer exists, product on platform, renewal already in progress | Verify and complete |
| **Dark Green** | Renewal already submitted | Tag "renewal already submitted"; close task |

### Excluded Broker Rules
- If broker not found in Broker Renewal Instructions → Assume excluded broker
- Tag: **"excluded broker"**
- Scenario: **Red**
- Action: Close Asana task

**Known excluded broker patterns**:
- "Outsourced" in broker name (e.g., "The Baldwin Group SW - Outsourced") → Do not process
- NFP Illinois → Excluded; use Totalis group if present for same employer
- Any broker where instructions explicitly say "do not process"

### Churned Broker
- Tag: **"churned broker"**
- Scenario: **Light Green**
- Action: Close Asana task

### Guardian 100+ Lives
- Tag: **"guardian o100 lives"**
- Scenario: **Dark Green**
- Action: Close Asana task

### Totalis Groups
- Always reassign to SME
- Never processed by vendor team
- Place on hold and assign back

### Employer in "Closed Projects" or "Completed Projects" in Admin
- Tag: **"BOR lost"**
- Scenario: **Red**
- Action: Close Asana task

### Renewal Already Submitted
- Verify rates in document match what's on carrier/broker site
- If rates match → Tag "renewal already submitted"; close task
- If rates differ → Update to match document, then close

### Next Initiative Workbook Lookup Failures

**Standard lookup order**:
1. Search Next Initiative Workbook
2. Search admin site
3. Search broker site
4. If still not found → Red scenario; follow broker instructions

**If found in admin but not workbook**: Proceed based on what admin site shows.

**Note on headcount**: Basic Life/AD&D is the most reliable product for headcount. Dental and Vision enrollment is not 100% of employees and should not be used as headcount source. If no reliable headcount is available, use LinkedIn company size as a conservative estimate.

---

## [PROCESS-012] Renewal Collection - Asana Task Management

### Tags Reference

| Tag | When to Apply |
|---|---|
| excluded broker | Broker not in instructions or explicitly excluded |
| churned broker | Broker no longer a client |
| BOR lost | Employer found in Closed/Completed Projects in admin |
| guardian o100 lives | Guardian group with 100+ lives |
| renewal already submitted | Renewal confirmed submitted on carrier/broker site |
| document upload | Task requires document upload only, no rate entry |
| duplicate | Same employer/product assigned twice |
| missing broker contact | Broker contact not found; add to UW notes with date |
| support issue | Forward to support team for technical resolution |

### Pending Status — When to Use

Set task to **Pending** and add a UW note (with today's date) when:
- Broker approval required before processing
- Waiting for carrier contact to be confirmed
- CS team needs to assist with complex setup
- Missing rates that require broker outreach
- Product structure requires SME review before vendor can proceed

**UW Note format**: `[Date] - [reason]`
Example: `2/19 - missing broker contact`

### Closed / Submitted Status Tasks

If a task's due date is active but status shows Closed on carrier site:
- Verify if renewal was already processed
- If yes → Tag "renewal already submitted" and close Asana task
- If unclear → Send back to UA with note

---

# Decision Trees

## [DECISION-001] Rate Selection - Multiple Plans in Proposal

### Single Plan in Proposal, Multiple Plans in Carrier Site

**Scenario**: Proposal has 1 plan, carrier site has "Low Plan" and "High Plan" (or "Plan 1" and "Plan 2")

**Options**:
1. Enter same plan info for both options, OR
2. Enter plan info for one option, leave other blank with $0 rates

**Default**: Option 2 (fill one, leave other at $0)

**When to Use Option 1**: Class-based products like STD where both classes should have same plan

### Multiple Plans in Proposal, Single Plan in Carrier Site

**Decision Framework**:
1. **Check email first** - Does it specify which plan?
2. **Check proposal** - Is one option highlighted/checked/marked with asterisk?
3. **Match current plan design** - Choose plan that most closely resembles current/requested
4. **Match funding type** - For Dental: ASO/composite vs fully-insured/4-tier
5. **Match tier structure** - If current carrier was 3-tier, use 3-tier rates from proposal

### Multiple Rate Guarantees in Same Proposal

**Decision Process**:
1. **Check email for direction** - Broker may specify
2. **If no direction**: Either is acceptable, just ensure rates and guarantee period match the same option
3. **Default to 12 months** if nothing specified
4. **Use rates that match already submitted** - If one option already submitted, use that guarantee period

**Common Error**: Mixing 12-month rates with 24-month guarantee (or vice versa) - Don't do this!

---

## [DECISION-002] Rate Guarantee Defaults

### When Rate Guarantee Not Listed

**Default**: Use **12 months**

**Exceptions**:
| Scenario | Rate Guarantee to Use |
|----------|----------------------|
| "4-years for first contract, then 1-year or 2-years to match dental" | **48 months** |
| "Does not impact renewal or rate guarantee period" | **12 months** |
| Delta Vision proposals without listed guarantee | **12 months** |
| "First Renewal date: January 1, 2030" (received Dec 2024) | **48 months** |
| "Rate guarantee through [end date]" | Calculate months from renewal date to end date |
| Document says 24-month guarantee but renewal is short-term | Use 12 months; 1/2026–3/2026 is not a renewal period |

---

## [DECISION-003] Commission Handling

### Commission Not Listed in Proposal
**Action**: Leave blank

**Exception**: Email lists commissions separately → Enter from email

### Commission Updates
**Action**: 
1. Manually update commission attribute only
2. Verify rates still accurate
3. Upload document to "My Documents" if new doc provided
4. **Do NOT reupload via AI** - would override other attributes

### Commission Types in Proposal
- **Rate field** = "Total Fee"
- **Commission field** = "Broker Fee"

---

## [DECISION-004] When to Update vs Upload Only

### Document Already Submitted, New Document Received

**If Rates Match**: Upload to "My Documents" only → Mark email as complete

**If Rates Differ**: 
1. Upload to "My Documents"
2. Manually update rates (and spot-check plan design attributes)
3. Resubmit coverage

### Revised Proposal Received
1. Upload new proposal to "My Documents"
2. Manually update rates for each affected product
3. Spot-check plan design attributes
4. Note: Attributes shouldn't change in revisions, but always verify

---

## [DECISION-005] Multiple Plans - Matching Logic

### Employer Contribution Scenarios
**Check Current**: Review current carrier contribution structure → Match that structure

### Age-Banded vs Composite Rates
**Decision**: Match current carrier's structure

### Class-Based Products
**Scenario**: Carrier site has multiple classes, proposal has single plan

**Action**: Enter same plan/rates for all classes based on class descriptions matching the proposal

---

## [DECISION-006] Tier Structure Mismatches

### DIVE Extracted Wrong Tier Structure
**Action**: Update to whatever tier structure current carrier used

### Composite to 4-Tier (or vice versa)
1. Check if broker requested tier structure change
2. If NO change requested: Keep current structure
3. If change requested: Use new tier structure from proposal

---

## [DECISION-007] Product Coverage Decisions

### Proposal Contains More Products Than Requested
1. Upload proposal to carrier site
2. Submit ONLY the requested products
3. Upload full proposal to "My Documents" for documentation
4. Do NOT submit worksite products unless specifically requested

### Products Without Proposals
- Leave in "Action Needed" or "Not Started" status
- Do NOT submit with $0 rates unless carrier explicitly declined

### Voluntary vs Non-Contributory
1. Check email — Are they ADDING voluntary or REPLACING non-contributory?
2. If ADDING: Escalate to add new voluntary product
3. If REPLACING: Update existing product to voluntary

---

## [DECISION-008] Package Pricing & Discounting

**Default**: Standalone pricing unless directed otherwise

**Critical**: Rates must match the pricing type selected:
- Standalone = "Not included"
- Package pricing = "Included"

---

## [DECISION-009] Absence Management Scenarios

**Action Required**:
1. **Rates** - Critical, must be accurate
2. **Plan design** - Enter what you can from proposal
3. **Missing attributes** - Can request help from UC if needed

**When to Escalate**: If proposal missing key information for Absence Management entry

---

## [DECISION-010] Renewal Rate Structure Complexity

### Age-Banded vs Composite Mismatch
- Carrier site shows composite, document shows age-banded (or vice versa) → Escalate; do not guess
- Single rate in document, carrier site shows age-banded → Enter single rate across all age bands unless told otherwise
- Age-banded document, composite carrier site → Escalate to SME

### Multi-Class Rate Handling
- Document has Class 1 only, carrier site has Class 1 and Class 2 → Enter Class 1 rates; enter 0 for Class 2 unless instructed otherwise
- Document has different rates per class → Match each class to its corresponding document rates
- Document has composite, carrier has Class 1 Composite and Class 2 Age-Banded → Escalate

### ASO Dental Rate Calculation
- Admin fee + network/access fee = composite rate
- Enter that single composite value for all plan tiers unless plan-specific fees are given
- "COBRA rates" or "premium equivalent" on dental/vision = likely ASO; use composite under $11 PEPM

### Plan Name Mismatches (Carrier vs Document)
| Carrier Site Shows | Document Shows | Rule |
|---|---|---|
| Dental Carrier 2 | Dental | Confirm carrier identity; proceed if same carrier |
| Dearborn Group | BCBS IL | Same carrier family; proceed as normal |
| VLTD / Buy-Up | LTD | Core rate = LTD; buy-up = VLTD. Check circled rate in carrier screenshot |
| Absence Management | Leave Services | Same product; proceed |
| Class 1 / Class 2 | M / F (male/female) | Class 1 = Male rates; Class 2 = Female rates |
| Non-preferred | Tobacco | Tobacco = non-preferred; Non-tobacco = preferred |
| Smoker / Non-Smoker | Preferred / Non-Preferred | Smoker = Non-preferred; Non-smoker = Preferred |

---

# Troubleshooting

## [TROUBLE-001] Employer Not Found

### Check Carrier Site Spelling Variations
- Exact spelling required (no abbreviations)
- Check alternate names in proposal vs carrier site
- Check DBA ("Doing Business As") names
- Check parent company names

### Delta Dental Entity Confusion
**Solution Process**:
1. Search employer in Broker Site first
2. Check which Delta entity was invited
3. Use that Delta login

**Most Common Mistake**: Assuming Delta of Michigan when it's actually Delta of Great Lakes

### No Marketing Event Found

| Scenario | Action |
|----------|--------|
| Only renewal exists (no RFP/marketing event) | Forward to support@threeflow.com with context |
| Group still in build status | Mark as complete, no marketing event started yet |
| Broker closed event | Upload to "My Documents" only, mark complete |
| Wrong year showing (e.g., 2022 event) | Do NOT touch old event. Escalate to confirm correct event |

---

## [TROUBLE-002] Upload/Processing Issues

### DIVE Failed to Extract Values
**Action**: Manually update rates and plan design from proposal

**Common with**: Absence Management, some Vision proposals, complex dental plan structures, certain worksite products

### Document Uploaded but Still "Processing"
**Normal Wait Time**: 2-5 minutes

**If stuck longer than 10 minutes**:
1. Refresh carrier site page
2. If truly stuck: Submit IT ticket via support@threeflow.com

### Smart Proposal Didn't Pull Anything
**Action**: Proceed with manual entry — normal for some document types

---

## [TROUBLE-003] Status Confusion

### "Action Needed" Status
- **If proposal exists**: Review flagged items, correct, and submit
- **If NO proposal and NO explicit decline**: Leave as-is until proposal/decline received

### "Closed" Status but Received Proposal
- If carrier site technically allows: Upload/submit normally
- Minimum: Upload to "My Documents" to save in system

### "Submitted" Status but Receiving Updates
1. Compare rates first
2. If same rates: Upload to "My Documents" only
3. If different rates: Update and resubmit

### Carrier Site Status → Asana Action Mapping

| Carrier Site Status | Meaning | Asana Action |
|---|---|---|
| Submitted / Selected / Sold | Already processed | Verify rates match; tag "renewal already submitted"; close |
| Closed | Event ended | If reopenable: process; otherwise upload docs only |
| Declined | Carrier declined | Can undo decline if proposal received |
| In Progress | Partially completed | Continue from where left off |
| Not Started | Nothing entered yet | Proceed with collection |
| RFP | Marketing / RFP event type | If renewal doc received: enter renewal rates as normal |

---

## [TROUBLE-004] Email Classification Issues

### ThreeFlow Notifications

| Notification Type | Action |
|-------------------|--------|
| "Comment Received" | Mark as complete |
| "Ready to Review" | Process as normal workflow |
| "Status Changed" | Review change, take action if needed |
| Auto-generated on closed products | Mark as complete |
| Duplicate notifications | Check for x-slack-retry-num header, mark duplicate complete |

---

## [TROUBLE-005] Product Coverage Gaps

### Carrier Not Invited to Marketing Event
**Escalation Message**: "Received [Carrier] proposal for [Employer]. [Carrier] not invited to [Product] marketing event. Can you add?"

### Products in Proposal Don't Match Carrier Site
1. Identify which products are missing from carrier site
2. Request Principal be added for missing coverages (escalate to UC/CX)
3. Wait for UC to add products before uploading

---

## [TROUBLE-006] ThreeFlow Assist Routing

**When Routing Fails**: 
1. Don't wait for Assist routing
2. Manually enter alt products
3. Submit directly
4. Upload proposal to "My Documents"

---

## [TROUBLE-007] Rate Calculation Issues

### Total Fee vs Component Fees
- **Rate field** = Total Fee
- **Commission field** = Broker Fee

### Composite Rate from 4-Tier
1. Check if employer census available
2. Calculate weighted average if census exists
3. If no census: Ask UC for guidance

---

## [TROUBLE-008] Credential & Access Issues

### Missing Carrier Credentials
1. Check shared credentials document first
2. If not there: Request from UC/CX
3. Wait for credentials before proceeding

**Escalation**: "@UC - Need login credentials for [Carrier Name] to upload proposal for [Employer]"

---

# Q&A Library

## Broker Site Questions

### Q: How do I add a carrier contact in broker site?
**A**: Under Principal section → "Invite new carriers or recipients" → "Add new recipients for existing carrier"

### Q: Recipient already listed in broker site. Add again?
**A**: No. If person who submitted email is already included, do not add again.

### Q: Trying to add recipient but no products shown for recent event, only old 2022 event visible?
**A**: Group still in build status within ThreeFlow. No marketing event started yet. Mark email as complete.

### Q: Broker site shows "Principal (In-Force)" when trying to add recipient?
**A**: Principal only invited to some coverages, not all. Request Principal be added for missing coverages. Escalate to UC/CX.

### Q: Name mismatch between broker site and proposal (e.g., "619 Recruiting" vs "619 Recruiting LLC")?
**A**: Proceed with name visible in Carrier Site. Minor variations (LLC, Inc) are acceptable.

---

## Carrier Site Questions

### Q: Uploaded document but status still "Not Started"?
**A**: Check if correct document uploaded. If document only includes different coverage, need to upload correct document.

### Q: Can't find employer in carrier site?
**A**: Check exact spelling. For Delta, verify which Delta entity. Search in Broker Site to see which Delta was invited.

### Q: Delta Vision - rate guarantee not in proposal?
**A**: Default to **12 months**.

### Q: Carrier site has 2 plans, proposal has 1 plan?
**A**: Enter same plan in both, OR enter in one and leave other at $0 rates.

### Q: Product status shows "Closed" - can I still upload?
**A**: If carrier site allows, you can upload/submit. At minimum, upload to "My Documents".

### Q: Smart Proposal processing for 10+ minutes, is it stuck?
**A**: Refresh page first. If still processing after 15 minutes, submit IT ticket via support@threeflow.com.

---

## Renewal Collection Questions

### Q: What does "rate pass" mean and how do I enter it?
**A**: Rate pass = rate hold = no change renewal. Copy current rates forward. Enter the rate guarantee duration in months. Also applies to: "rate lock," "rate hold," "no-change renewal," "0% rate action."

### Q: Document says "Rate Hold" — is that the same as a rate pass?
**A**: Yes. Rate hold = rate pass. Copy current rates and enter the appropriate rate guarantee duration.

### Q: There's no renewal document, but the email says rates are the same / "no change." Can I proceed?
**A**: If no rates are available at all, send back to the original UA. If the email provides specific rates or confirms a rate pass, you can proceed using the email as the source document.

### Q: Which rates do I use when the document has "Renewal Rates" and "Revised Renewal Rates"?
**A**: Always use the most recent revision. If labeled "Revised," those supersede the original renewal rates.

### Q: The renewal document shows rates "including agent fees" and "excluding agent fees." Which do I use?
**A**: Use rates **including** agent fees.

### Q: The document has multiple rate columns. How do I know which is renewal?
**A**: Look for columns labeled "new rate," "proposed rate," "renewal rate," or highlighted in yellow. "Monthly premium" rows are rates. Do not use "contribution" rows.

### Q: The carrier site shows "Update Quote" instead of "Start Renewal." What do I do?
**A**: "Update Quote" leads to the same place as "Start Renewal." Proceed normally. If needed, there is also an option in the upper right corner to upload the document manually.

### Q: The "Submit" button isn't showing — only "Review Plan Design." What do I do?
**A**: Enter `--` in any missing plan design fields. This unlocks the Submit button.

### Q: The carrier site shows the employer as "Submitted," "Selected," or "Sold." Do I still need to process?
**A**: Verify the rates match the renewal document. If they match, tag "renewal already submitted" and close the Asana task. If they differ, update the rates and close.

### Q: The task shows "Closed" in the carrier site. Can I close it in Asana?
**A**: Verify the context first. If the renewal was already correctly processed, close the task. If it appears closed in error, escalate to the UA.

### Q: I can't find broker credentials in 1Password. What do I do?
**A**: Check for alternate spellings of the broker name. If the broker is excluded (not in Broker Renewal Instructions), tag "excluded broker" and close the task. If the broker is active, escalate to the SME to create credentials.

### Q: I can't find the employer in the Next Initiative Workbook. What do I do?
**A**: Search the admin site next. If not there, search the broker site. If not found anywhere, treat as a Red scenario and follow broker instructions.

### Q: What do I do with a Totalis group?
**A**: Always reassign to SME. Never process Totalis groups — place on hold and assign back.

### Q: What does it mean if the broker name contains "Outsourced"?
**A**: Do not process. "Outsourced" in the broker name means this group should not be processed by the vendor team. Close and tag accordingly.

### Q: The carrier site has both "High" and "Low" plans, but the document only has one set of rates. What do I do?
**A**: Escalate and send back to the original UA noting that the missing plan rates were not received.

### Q: The document doesn't mention the renewal date. The carrier site shows one date. Can I use the carrier site date?
**A**: Generally yes, if the carrier site date is consistent with the due date. Confirm with the SME if there is any uncertainty.

### Q: What is the PFL rate for NY DBL 2026 renewals?
**A**: Use **0.432**. If the current PFL rate on the carrier site shows "--", enter **0** instead. For DBL, if rates are the same for male and female, enter the same composite value for both (e.g., $0.500 for both).

### Q: The document shows "Male" and "Female" rates, but the carrier site shows "Class 1" and "Class 2."
**A**: Class 1 = Male rates. Class 2 = Female rates. Proceed accordingly.

### Q: There's no renewal document but the email says "no change" or "all policies renew as-is." Can I treat this as a rate pass?
**A**: If the email provides specific rates or explicitly confirms rate pass, you can proceed using the email as the renewal document. If no rates are provided at all, send back to the UA.

### Q: The renewal document has rates for Absence Management. Should I process it?
**A**: Generally no — do not process Absence Management unless it is specifically included in the renewal scope. Move forward with the other products.

### Q: Should I process a product that the document says is in a rate guarantee period?
**A**: No. If a product is in an active rate guarantee, skip it. Process only the products that are actually up for renewal.

### Q: I found the employer under a different name (DBA name) on the carrier site. Can I proceed?
**A**: Yes, if the carrier and broker information aligns and the SME or prior documentation confirms it's the same company. Proceed with the name shown on the carrier site.

### Q: There are two duplicate tasks for the same employer. What do I do?
**A**: Confirm the products and due dates are truly identical. If yes, add "Duplicate" to the notes and close the duplicate task. If the products or dates differ, they may be legitimate separate tasks — escalate to confirm.

### Q: The document has ASO Dental rates listed as admin fee + network/access fee. How do I enter them?
**A**: Add the two fees together to get one composite rate. Enter that single composite value. This applies to all plan tiers unless specific per-plan fees are provided.

---

## Document Handling Questions

### Q: Email attachment is .eml format. Upload?
**A**: No, don't upload .eml files. Upload other attachments (PDF, Excel) only.

### Q: Received same document multiple times?
**A**: If already submitted with matching rates, mark email as complete. If rates differ, need to update manually.

### Q: Updated proposal received with rate changes?
**A**: Upload to "My Documents" AND manually update rates/attributes in carrier site. Resubmit coverage.

### Q: Should I upload proposal if carrier proactively quoted worksite products we didn't request?
**A**: Upload proposal to "My Documents" for documentation. Submit ONLY products actually requested in email.

---

## Rate Entry Questions

### Q: Proposal has Plan A and B with 4 options each. Which to choose?
**A**: Look for checked/highlighted option in proposal. That's the plan to upload.

### Q: Commission not listed in proposal, only in email?
**A**: Enter commission from email if provided. If not mentioned anywhere, leave blank.

### Q: Proposal shows "Administration Fee", "Broker Fee", "Total Fee". Which is the rate?
**A**: Rate field = "Total Fee". Commission field = "Broker Fee".

### Q: Composite rates in one proposal, 4-tier rates in another. Which to use?
**A**: Match current carrier's rate structure.

### Q: Rate guarantee not listed anywhere in proposal or email?
**A**: Default to **12 months**.

---

## Declination Questions

### Q: Email says "unable to quote disability for this SIC code". Decline? Which reason?
**A**: Yes, decline STD/LTD. Use "Non-preferred (or unfavorable) industry."

### Q: Email says "rates uncompetitive" or "current carrier fairly priced". Which decline reason?
**A**: Use "Rates Uncompetitive."

### Q: Carrier asking for more info (census, occupations). Should I decline?
**A**: Not yet. Leave in ambiguous status until you get actual decline or updated proposal.

### Q: Product showing as declined but now received proposal. Can I undo?
**A**: Yes, undo decline in carrier site and upload proposal as normal.

---

## Product-Specific Questions

### Q: LTD shows as voluntary option not yet submitted, no proposal. What to do?
**A**: Leave in "Action Needed" status. Wait for carrier to provide proposal or explicit decline.

### Q: Absence Management - DIVE can't extract. Need to enter manually?
**A**: Yes, manually enter rates (critical) and plan design attributes from proposal. Ask UC for help if needed.

### Q: Hospital Indemnity - proposal has Low/High plans, carrier site has one?
**A**: Use "High" plan if it better aligns with requested hospital benefits.

### Q: Dental has Alt 1 and Alt 2, but only received one proposal?
**A**: Submit the alt with the proposal. Leave other alt in "Not Started" or "Action Needed" until additional proposal received.

---

## Special Scenarios

### Q: Renewal email but carrier site shows RFP event type?
**A**: Trust the email. If it says "renewal", it's a renewal. Forward to submit@threeflow.com.

### Q: Received proposal for carrier we don't have login for (Cigna, Prudential, etc.)?
**A**: Mark as "Complete" if handled by another ThreeFlow associate. Otherwise mark as "Escalated" for team to address.

### Q: Two different Delta entities for same employer (Ohio and Great Lakes). Which to use?
**A**: Check proposal header for Delta entity name. Use that carrier login. If unclear, check broker site for which was invited.

---

## NPC/Alt Specific Questions

### Q: Broker asks for Critical Illness NPC with no other notes?
**A**: Use only the "high" Critical Illness plan template.

### Q: Are premiums required for NPCs and Alts?
**A**: Premiums ONLY required for NPCs, NOT for Alts.

### Q: Dental alts - Current: $2K max/$1.5K ortho. Alt 1: $2K/$2K ortho. Alt 2: $2.5K/$2K ortho. How to name?
**A**:
- "Dental - Match Current"
- "Dental - $2,000 | $2,000 ortho"
- "Dental - $2,500 | $2,000 ortho"

### Q: Stop Loss - Current: $50K. Alts: $65K and $75K. How to name?
**A**:
- "$50,000 - Match Current"
- "$65,000"
- "$75,000"

---

# Common Mistakes

## Mistake 1: Using AI Upload When Manual Entry Needed
**Prevention**: Check what's already submitted before using AI. If ANY products already submitted, use manual entry.

## Mistake 2: Wrong Rate Guarantee from Multi-Option Proposal
**Prevention**: Choose one option (12-month OR 24-month) and use BOTH rate and guarantee from that same option. Never mix-and-match.

## Mistake 3: Declining When Carrier Requested More Info
**Prevention**: Look for explicit decline language. Requests for info = Leave in ambiguous status.

## Mistake 4: Not Checking Employer Name Variations
**Prevention**: Try multiple spelling variations, DBA names, parent company names before reporting not found.

## Mistake 5: Uploading to Wrong Delta Entity
**Prevention**: Check proposal header for Delta entity name. Verify in broker site which Delta was invited.

## Mistake 6: Missing Commission Field vs Rate Field
**Prevention**: Rate field = "Total Fee". Commission field = "Broker Fee".

## Mistake 7: Submitting Products Not Requested
**Prevention**: Read email carefully for requested products. Submit ONLY products explicitly requested.

## Mistake 8: Not Uploading New Proposal to "My Documents"
**Prevention**: Always upload to "My Documents" when receiving new/updated proposal, even when manually entering rates.

## Mistake 9: Ignoring Rate Structure Mismatch
**Prevention**: Check current carrier's rate structure first. Match that structure unless broker explicitly requested a change.

## Mistake 10: Marking Email Complete Without Taking Action
**Prevention**: Only mark complete when work is truly done or belongs to someone else. Use "Escalated" for items needing team attention.

## Mistake 11: Not Updating Package Pricing Attribute
**Prevention**: Standalone rates → "Not included". Package rates → "Included". Always match.

## Mistake 12: Entering Same NPC Setup for Alt
**Prevention**: Alt must show a DIFFERENT option from NPC. Verify broker notes for what should differ.

## Mistake 13: Processing a Product in an Active Rate Guarantee
**Prevention**: Check rate guarantee status before entering any renewal rates. If a product is in a rate guarantee period, skip it and process only products that are up for renewal.

## Mistake 14: Using Dental/Vision Enrollment as Headcount
**Prevention**: Use Basic Life/AD&D for headcount. Dental and vision enrollment is not 100% of employees. If unavailable, use LinkedIn company size as a conservative estimate.

## Mistake 15: Entering 0.432 for PFL When Current Rate Shows "--"
**Prevention**: If current PFL rate on carrier site shows "--", enter 0. Only enter 0.432 if another rate is already present.

---

# Troubleshooting Flowcharts

## Flowchart 1: Email Received - What Do I Do?


START: Email received
    ↓
Is it a ThreeFlow system notification?
    YES → Mark as Complete
    NO → Continue
    ↓
Does email explicitly say "renewal"?
    YES → Forward to submit@threeflow.com → Mark Complete
    NO → Continue
    ↓
Can you find employer in carrier site?
    NO → Check broker site for exact spelling
          → Check Delta entity confusion
          → Still not found? → Escalate to UC
    YES → Continue
    ↓
Does email request decline?
    YES → Is this request for more info OR actual decline?
          → Request for info → Leave in ambiguous status
          → Actual decline → Use correct reason code → Mark Complete
    NO → Continue
    ↓
Are products already submitted with same rates?
    YES → Upload to "My Documents" only → Mark Complete
    NO → Continue
    ↓
Are there other products already submitted that shouldn't be touched?
    YES → Manual entry required
    NO → Can use AI upload
    ↓
Upload proposal & Submit → Mark email Complete


---

## Flowchart 2: Can't Find Employer - What to Check


START: Employer not found in carrier site
    ↓
Check exact spelling from proposal
    ↓
Try variations: LLC/Inc/Corp, DBA name, parent company, broker site name
    ↓
Still not found? Is this a Delta Dental proposal?
    YES → Check broker site for invited Delta entity
          → Try: Great Lakes, Ohio, Indiana, Illinois, Michigan
    NO → Continue
    ↓
Still not found? Check broker site
    ↓
Does employer exist in broker site?
    YES → Is there an active marketing event?
          YES → Different carrier? → Escalate
          NO → Mark as Complete (no marketing event)
    NO → Escalate to UC (employer doesn't exist in system)


---

## Flowchart 3: Renewal Rate Entry Decision


START: Ready to enter renewal rates
    ↓
Is this a rate pass / rate hold?
    YES → Copy current rates forward
          → Enter rate guarantee in months
          → Submit
    NO → Continue
    ↓
Are there multiple rate sets in the document?
    YES → Is one labeled "Revised"?
          YES → Use revised rates
          NO → Is one highlighted or marked?
               YES → Use marked rates
               NO → Check email for direction
                   → Default to rates matching the rate guarantee period
    NO → Continue
    ↓
Is the rate structure different from carrier site?
    YES → ASO dental? Add admin + network fee = composite rate
          Age-banded vs composite? → Escalate if unclear
          Plan name mismatch? → Check mapping table (DECISION-010)
    NO → Enter rates as shown
    ↓
Missing rates for some fields?
    YES → Is it a missing class? → Enter 0
          Is it a missing product? → Skip or escalate
          Is it PFL NY DBL? → Enter 0.432 (or 0 if current shows "--")
    NO → Continue
    ↓
Submit renewal


---

## Flowchart 4: Upload Strategy Decision


START: Received proposal to upload
    ↓
Are there products already submitted?
    NO → Can use AI upload ("Update Quote")
    YES → Are the already-submitted products in this proposal?
          NO → Can use AI upload (won't affect them)
          YES → Will this proposal update those products?
                YES (intentional) → Manual entry safer for complex; AI ok for simple rates
                NO (don't want to touch) → MUST use manual entry
    ↓
Manual Entry: Upload to "My Documents" → Update rates manually → Submit
AI Upload: "Update Quote" → Check rerun smart proposal → Review → Submit or fix manually


---

## Flowchart 5: NPC vs Alt Decision


START: Request for coverage setup
    ↓
Does group currently have this product?
    NO → Single plan or multiple?
         SINGLE → NPC only (use template, enter premiums)
         MULTIPLE → NPC + Alts (NPC first with premiums, then add alts at $0)
    YES → Alts only
          → Copy from current coverage
          → Rename base "Match Current"
          → Rename alts with variation using | for multiple changes
          → Set rates to $0
          → Add from admin site


---

## Flowchart 6: Status Confusion Resolution


START: Confused about product status
    ↓
NOT STARTED → Upload and process
IN PROGRESS → Update/add products; proceed normally
ACTION NEEDED → Proposal exists? Fix and submit. No proposal? Leave as-is.
SUBMITTED → Rates match new doc? Upload docs only. Different? Update and resubmit.
CLOSED → Can upload? Process normally. Can't? Upload to "My Documents" only.


---

## Flowchart 7: Decline Decision Tree


START: Email mentions not quoting
    ↓
"Rates uncompetitive" / "Current carrier fairly priced" → Rates Uncompetitive
"SIC code" / "Nature of business" / "Due to industry" → Non-preferred industry
"Group size" / "Don't offer in this size" → Size segment outside min/max
"Need census" / "Need more information" → DON'T DECLINE YET → Leave in ambiguous status
"Unable to quote" → Check if rate-related → YES: Rates Uncompetitive / NO: Escalate
"Declined by UW" / "DTQ" → Check context → Use appropriate code
    ↓
Execute decline → Mark email Complete


---

## Flowchart 8: Renewal Collection Scenario Classification


START: New Asana task received
    ↓
Is broker in Broker Renewal Instructions?
    NO → Tag "excluded broker" → Red scenario → Close task
    YES → Continue
    ↓
Does "Outsourced" appear in broker name?
    YES → Do not process → Close task
    NO → Continue
    ↓
Is employer found in Next Initiative Workbook?
    NO → Search admin site → Search broker site
         Still not found? → Red scenario → Follow broker instructions
    YES → Continue
    ↓
Is this a Totalis group?
    YES → Reassign to SME → Place on hold
    NO → Continue
    ↓
Is this a Guardian group with 100+ lives?
    YES → Tag "guardian o100 lives" → Dark green → Close task
    NO → Continue
    ↓
Is renewal already submitted on carrier site?
    YES → Verify rates match → Tag "renewal already submitted" → Close task
    NO → Continue
    ↓
Is employer in "Closed" or "Completed Projects" in admin?
    YES → Tag "BOR lost" → Red scenario → Close task
    NO → Proceed with collection (Yellow/Light Green/Dark Green as appropriate)

---

# Quick Reference

## Must-Know Defaults

| Item | Default Value |
|------|---------------|
| Rate Guarantee (not listed) | 12 months |
| Delta Vision Rate Guarantee | 12 months |
| Commission (not listed) | Leave blank |
| NPC Premiums | Required (estimated annual) |
| Alt Rates | $0 |
| NY DBL PFL Rate (2026) | 0.432 (enter 0 if current shows "--") |
| DBL Male/Female (same rates) | Enter same composite value for both |
| Missing child/AD&D rates | Enter $0 |
| Missing product rates (not provided) | Skip or escalate — do NOT enter $0 |
| Wellness rate not in document | Enter $0 |
| ASO Dental rate | Admin fee + network fee = composite; typically under $11 PEPM |
| Rates including vs excluding agent fees | Always use rates including agent fees |
| "Revised" vs "Original" renewal rates | Always use revised |
| Rate pass = rate hold = rate lock | Copy current rates forward |

## Scenario Tag Quick Reference

| Condition | Tag | Scenario | Action |
|---|---|---|---|
| Broker not in instructions | excluded broker | Red | Close task |
| "Outsourced" in broker name | excluded broker | Red | Close task |
| Broker no longer client | churned broker | Light Green | Close task |
| BOR lost / Closed in admin | BOR lost | Red | Close task |
| Guardian 100+ lives | guardian o100 lives | Dark Green | Close task |
| Renewal already submitted | renewal already submitted | Dark Green | Close task |
| Doc upload only needed | document upload | — | Upload; close |
| Same employer assigned twice | duplicate | — | Verify; close duplicate |
| Broker contact missing | missing broker contact | Pending | Add UW note; pending |
| Technical / support issue | support issue | — | Reassign to support |

## Always Escalate — Do Not Attempt

- Employer not found after exhausting all lookup sources
- Rate structure interpretation requiring calculation or actuarial judgment
- Admin site access issues (blank rate fields after update, can't update current rates)
- Multi-class or multi-carrier complexity beyond standard mapping
- Carrier/technical errors ("error loading product")
- Totalis groups
- Any task already set to Pending by SME
- Broker approval required before processing
- Missing carrier contact on broker site
- Products requiring plan alternatives or structural changes
- Stop Loss alternate quotes (enter main renewal, then assign back to UA for alts)
