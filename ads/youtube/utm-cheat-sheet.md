# UTM Cheat Sheet — YouTube Ads (Rise To Thrive — Foundation)

Use these patterns for consistent naming across Google Ads, GA4, and Looker Studio.

## 1) Core Parameters

## 2) Examples
- **Hook ad (AG1, Ad1):**  
  `...?utm_source=youtube&utm_medium=cpv&utm_campaign=foundation_launch_2025-11-05&utm_content=ag1_ad1_hook`
- **Proof ad (AG2, Ad1):**  
  `...?utm_source=youtube&utm_medium=cpv&utm_campaign=foundation_launch_2025-11-05&utm_content=ag2_ad1_proof`

## 3) Google Ads Naming
**Campaign**  
`Foundation | Launch | 2025-11`

**Ad group**  
`AG1 | InMarket_BizSvcs`  
`AG2 | Topic_BusinessEducation`

**Ad**  
`AD1 | hook | 60s`  
`AD2 | proof | 30s`

## 4) QA Checklist (every URL)
- [ ] Final URL loads fast (mobile + wifi)
- [ ] UTM params present & spelled correctly
- [ ] `utm_campaign` date matches campaign name
- [ ] Test a preview ad → GA4 Real-time shows `source=youtube / medium=cpv`
- [ ] If using multiple landers, verify each has correct UTMs

## 5) Reporting Keys (Looker Studio)
- Campaign  
- Ad group  
- Ad  
- `utm_campaign`  
- `utm_content`  
- View-through conversions (incl. assisted)  
- First-time purchasers (if tracked)

> Tip: keep `utm_content` short and machine-readable to enable fast pivots by **Group** and **Ad**.
