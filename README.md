# Vultr vs Hetzner 2026: After the June Price Hike, Which Cloud VPS Actually Wins on Value? — Plans, Specs, Performance & Free Credit Guide (Post June 15 Adjustment)

On June 15, 2026, Hetzner pushed a price list that turned a quiet Sunday into a small emergency for thousands of self-hosters. CCX13, the 2 vCPU / 8 GB dedicated plan that used to cost €15.99, jumped to €42.99 — a 169% increase overnight. Reddit's r/hetzner filled up within hours with migration threads. So if you're running a **vultr vs hetzner 2026** comparison today, you're not just weighing specs against specs anymore. You're weighing specs against a price list that quietly changed the math.

**Vultr vs Hetzner 2026** is the showdown between two of the most popular independent cloud VPS providers this year — Vultr, the US-based provider with 31 data centers across 5 continents, against Hetzner, the German provider famous for aggressive pricing that just got 30% to 192% more expensive on most cloud SKUs. This guide lays out the post-June-15 pricing on both sides, the benchmark gaps, and where each one still makes sense.

## What actually changed on June 15, 2026

According to Hetzner's official price adjustment documentation, the new prices apply to all new orders and instance rescales from June 15, 2026 onward. The CPX shared-vCPU series and CCX dedicated-vCPU series took the biggest hits. CCX plans rose between 113% and 173%, CPX plans between 144% and 192%. The shared CX and CAX (ARM) lines rose more modestly, between 30% and 38%.

What that means in plain numbers: a Hetzner CCX23 (4 vCPU / 16 GB dedicated) in Falkenstein used to be €31.49. It's now €85.99. The same money that previously bought you a 4-core dedicated box now barely covers the entry-level 2-core CCX13.

This is the single biggest reason the vultr vs hetzner 2026 conversation shifted.

## Vultr's full 2026 plan lineup at a glance

Vultr's published Cloud Compute pricing hasn't seen a comparable adjustment in 2026, and they added a new VX1 generation that VPSBenchmarks flagged as their best-performing tier. Here's every current Cloud Compute plan as listed on Vultr's official pricing page, in US dollars and including IPv4.

### Cloud Compute — Regular Performance (shared vCPU, regular SSD)

| vCPU | RAM | Bandwidth | Storage | Monthly | Hourly |
|---|---|---|---|---|---|
| 1 | 0.5 GB | 0.50 TB | 10 GB | $2.50 (IPv6 only) / $3.50 | $0.004 / $0.005 |
| 1 | 1 GB | 1.00 TB | 25 GB | $5 | $0.007 |
| 1 | 2 GB | 2.00 TB | 55 GB | $10 | $0.015 |
| 2 | 2 GB | 3.00 TB | 65 GB | $15 | $0.022 |
| 2 | 4 GB | 3.00 TB | 80 GB | $20 | $0.030 |
| 4 | 8 GB | 4.00 TB | 160 GB | $40 | $0.060 |
| 6 | 16 GB | 5.00 TB | 320 GB | $80 | $0.119 |
| 8 | 32 GB | 6.00 TB | 640 GB | $160 | $0.238 |
| 16 | 64 GB | 10.00 TB | 1280 GB | $320 | $0.476 |
| 24 | 96 GB | 15.00 TB | 1600 GB | $640 | $0.952 |

👉 [Pick a Regular Performance plan sized to your workload](https://www.vultr.com/?ref=9738262-9J)

### Cloud Compute — High Performance (AMD EPYC / Intel Xeon + NVMe)

| vCPU | RAM | Bandwidth | Storage | Monthly |
|---|---|---|---|---|
| 1 | 1 GB | 2 TB | 25 GB | $6 |
| 1 | 2 GB | 3 TB | 50 GB | $12 |
| 2 | 2 GB | 4 TB | 60 GB | $18 |
| 2 | 4 GB | 5 TB | 100 GB | $24 |
| 4 | 8 GB | 6 TB | 180 GB | $48 |
| 4 | 12 GB | 7 TB | 260 GB | $72 |
| 8 | 16 GB | 8 TB | 350 GB | $96 |
| 12 | 24 GB | 12 TB | 500 GB | $144 |

👉 [Start on a High Performance NVMe instance from $6/mo](https://www.vultr.com/?ref=9738262-9J)

### Cloud Compute — High Frequency (3GHz+ Intel Xeon, NVMe)

| vCPU | RAM | Bandwidth | Storage | Monthly |
|---|---|---|---|---|
| 1 | 1 GB | 1 TB | 32 GB | $6 |
| 1 | 2 GB | 2 TB | 64 GB | $12 |
| 2 | 2 GB | 3 TB | 80 GB | $18 |
| 2 | 4 GB | 3 TB | 128 GB | $24 |
| 3 | 8 GB | 4 TB | 256 GB | $48 |
| 4 | 16 GB | 5 TB | 384 GB | $96 |
| 6 | 24 GB | 6 TB | 448 GB | $144 |
| 8 | 32 GB | 7 TB | 512 GB | $192 |
| 12 | 48 GB | 8 TB | 768 GB | $256 |

### Optimized Cloud Compute — General Purpose (dedicated AMD EPYC vCPU)

| vCPU | RAM | Bandwidth | Storage | Monthly |
|---|---|---|---|---|
| 1 | 4 GB | 4 TB | 30 GB | $30 |
| 2 | 8 GB | 5 TB | 50 GB | $60 |
| 4 | 16 GB | 6 TB | 80 GB | $120 |
| 8 | 32 GB | 7 TB | 160 GB | $240 |
| 16 | 64 GB | 8 TB | 320 GB | $480 |
| 24 | 96 GB | 9 TB | 480 GB | $720 |
| 32 | 128 GB | 9 TB | 640 GB | $960 |
| 40 | 160 GB | 10 TB | 768 GB | $1,200 |
| 64 | 192 GB | 11 TB | 960 GB | $1,920 |
| 96 | 256 GB | 12 TB | 1280 GB | $3,840 |

👉 [Compare every Vultr Optimized plan side by side](https://www.vultr.com/?ref=9738262-9J)

For the dedicated-vCPU fans: Vultr's CPU Optimized tier starts at $28/mo (1 vCPU / 2 GB), Memory Optimized at $40/mo (1 vCPU / 8 GB), Storage Optimized at $75/mo (1 vCPU / 8 GB / 150 GB NVMe). Vultr also rents NVIDIA GH200 instances at $2,913/mo and 8-GPU H100 boxes at $13,432/mo — Hetzner has no equivalent hourly GPU cloud product.

## Hetzner's full 2026 plan lineup (post-June 15 prices)

All Hetzner prices below are ex VAT and ex IPv4 (add roughly €0.50/mo for an IPv4 address), sourced from Hetzner's official price-adjustment documentation for the Germany / Finland region. USA (ASH/HIL) and Singapore (SIN) run slightly higher — Singapore CCX13 is €53.99 vs €42.99 in Falkenstein.

### Cost-Optimized (shared, older hardware, limited availability)

| Plan | vCPU | RAM | Storage | Monthly (ex VAT) |
|---|---|---|---|---|
| CX23 | 2 (Intel/AMD) | 4 GB | 40 GB | €5.49 |
| CAX11 | 2 (Ampere ARM) | 4 GB | 40 GB | €5.99 |
| CX33 | 4 (Intel/AMD) | 8 GB | 80 GB | €8.49 |
| CAX21 | 4 (Ampere ARM) | 8 GB | 80 GB | €10.49 |
| CX43 | 8 (Intel/AMD) | 16 GB | 160 GB | €15.99 |
| CAX31 | 8 (Ampere ARM) | 16 GB | 160 GB | €20.99 |
| CX53 | 16 (Intel/AMD) | 32 GB | 320 GB | €29.49 |
| CAX41 | 16 (Ampere ARM) | 32 GB | 320 GB | €40.99 |

### Regular Performance (shared, current-gen AMD)

| Plan | vCPU | RAM | Storage | Monthly (ex VAT) |
|---|---|---|---|---|
| CPX11 (USA only) | 2 | 2 GB | 40 GB | €17.49 |
| CPX21 (USA only) | 3 | 4 GB | 80 GB | €31.99 |
| CPX22 | 2 | 4 GB | 80 GB | €19.49 |
| CPX31 (USA only) | 4 | 8 GB | 160 GB | €62.49 |
| CPX32 | 4 | 8 GB | 160 GB | €35.49 |
| CPX41 (USA only) | 8 | 16 GB | 240 GB | €120.49 |
| CPX42 | 8 | 16 GB | 320 GB | €69.49 |
| CPX51 (USA only) | 16 | 32 GB | 360 GB | €237.99 |
| CPX52 | 12 | 24 GB | 480 GB | €100.49 |
| CPX62 | 16 | 32 GB | 640 GB | €129.99 |

### General Purpose (dedicated AMD EPYC vCPU)

| Plan | vCPU | RAM | Storage | Monthly (ex VAT) |
|---|---|---|---|---|
| CCX13 | 2 | 8 GB | 80 GB | €42.99 |
| CCX23 | 4 | 16 GB | 160 GB | €85.99 |
| CCX33 | 8 | 32 GB | 240 GB | €138.49 |
| CCX43 | 16 | 64 GB | 360 GB | €275.99 |
| CCX53 | 32 | 128 GB | 600 GB | €533.49 |
| CCX63 | 48 | 192 GB | 960 GB | €853.49 |

If you're comparing the dedicated tier head to head, CCX13's new €42.99 monthly cap works out to roughly $46 at recent exchange rates. Vultr's General Purpose 2 vCPU / 8 GB runs $60/mo. Vultr is pricier here, but the gap closed substantially when Hetzner raised its price by 169%.

## Side-by-side: where the value sits now

Here's where the post-June-15 reality gets interesting. The table below compares apples-to-apples at similar specs, taking the cheapest available option on each side. Hetzner figures are converted to USD at roughly €1 = $1.07 and exclude the ~€0.50 IPv4 surcharge.

| Workload | Vultr plan | Vultr price | Hetzner plan | Hetzner price (USD) | Cheaper option |
|---|---|---|---|---|---|
| 1 vCPU / 1 GB / NVMe | High Frequency 1GB | $6/mo | CX23 (2 vCPU / 4 GB) | ~$5.90 | Hetzner (more cores + RAM) |
| 2 vCPU / 4 GB / NVMe | High Performance 2C/4G | $24/mo | CPX22 (2 vCPU / 4 GB) | ~$21 | Hetzner |
| 2 vCPU / 8 GB / dedicated | Optimized GP 2C/8G | $60/mo | CCX13 (2 vCPU / 8 GB) | ~$46 | Hetzner |
| 4 vCPU / 8 GB / shared | Regular 4C/8G | $40/mo | CPX32 (4 vCPU / 8 GB) | ~$38 | Hetzner |
| 4 vCPU / 16 GB / dedicated | Optimized GP 4C/16G | $120/mo | CCX23 (4 vCPU / 16 GB) | ~$92 | Hetzner |
| 8 vCPU / 32 GB / dedicated | Optimized GP 8C/32G | $240/mo | CCX33 (8 vCPU / 32 GB) | ~$149 | Hetzner |
| 16 vCPU / 64 GB / dedicated | Optimized GP 16C/64G | $480/mo | CCX43 (16 vCPU / 64 GB) | ~$296 | Hetzner |

Even after the hikes, Hetzner is still cheaper at every spec point — usually by 25% to 40%. The vultr vs hetzner 2026 verdict on raw price/performance still tilts Hetzner. But there are real reasons to pick Vultr anyway, and they live outside the price column.

## Where Vultr pulls ahead (and it's not price)

**Data center coverage.** According to VPSBenchmarks' June 15, 2026 dataset, Vultr runs 31 data centers across 5 continents, including locations in Chile, South Africa, Israel, India, South Korea, and Poland. Hetzner operates 6 data centers in 3 continents: Germany (FSN, NBG), Finland (HEL), USA (ASH, HIL), and Singapore (SIN). If your users sit in São Paulo, Mumbai, or Seoul, Hetzner simply isn't an option.

**Performance ceilings at the high end.** VPSBenchmarks' June 2026 results graded Vultr's VX1 GP 2C 8G 120S ($55.48/mo) at B for web performance, A for performance stability, and A for disk IO. The same lab graded the Hetzner CCX13 at E for web performance, E for raw CPU, and E for stability. Vultr's newest generation sits a noticeable tier above Hetzner's CCX13 in the metrics that matter for production web workloads.

**Performance consistency.** VPSBenchmarks gives Hetzner a 71 consistency score versus Vultr's 61 — Hetzner wins here, ironically, because their hardware is more homogeneous across the small fleet. Vultr's per-instance variance has improved markedly with the VX1 line, but the older Regular Performance and High Frequency tiers still show wider swings.

**Provisioning speed.** VPSBenchmarks clocked Hetzner at an average 25 seconds from order to accepting connections, against Vultr's 85 seconds. Hetzner wins this round, though both numbers are well under the "is my server up yet?" pain threshold.

**Trust signals — split verdict.** Hetzner's European data centers are ISO/IEC 27001 certified and BSI C5 certified, with full GDPR compliance and a 99.9% uptime SLA. The company reports 400,000+ customers on its official cloud pages. Vultr, founded in 2014, sits at a 1.7/5 Trustpilot score as of mid-2026 — reviewers praise the high-frequency compute performance but repeatedly cite support responsiveness issues. Neither company is universally loved, but Hetzner's compliance posture is materially stronger if you're running anything regulated in the EU.

## How to register Vultr and claim your free credit

If you've decided Vultr's global reach is worth the premium, the signup flow takes about five minutes and the new-user credit is the fastest way to test before committing.

1. **Open the Vultr signup page** through a referral link so the free-credit promo attaches to your account automatically.
2. **Create your account** with email + password, or sign in with GitHub / Google.
3. **Verify your email** and complete the KYC step — Vultr requires a card on file to issue the promotional credit, even though the card won't be charged during the trial window.
4. **Enter a promo code on the billing page** — the two currently active codes from Vultr's official coupons page are `FLYTWOHUNDRED` ($200 credit) and `FLY300VULTR` ($300 credit). Both are valid for new customers only and the credit expires 30 days after issue.
5. **Spin up your first instance** from the Cloud Compute menu; the hourly billing draws down from the promo credit first.

👉 [Claim the $300 free credit and launch your first Vultr instance](https://www.vultr.com/?ref=9738262-9J)

A quick note on the credit math: $300 covers roughly 6,250 hours of a $48/mo High Performance 4C/8G instance, which is more than enough for a serious benchmark run against your existing Hetzner box before you commit to migration.

## When you should pick Hetzner anyway

Despite the price hikes, Hetzner is still the right call in three specific situations.

First, when your users are in Europe and you need predictable per-hour billing on dedicated cores. CCX13 at €42.99 is a 169% jump but still 23% cheaper than Vultr's equivalent GP 2C/8G at $60. The arithmetic still favors Hetzner for EU-bound traffic.

Second, when you need ARM. Hetzner's CAX line (Ampere Altra) starts at €5.99/mo for a 2-core / 4 GB box. Vultr does not currently offer native ARM cloud compute at comparable prices in 2026.

Third, when compliance matters. The ISO 27001 and BSI C5 certifications matter for healthcare, finance, and German public-sector work — Vultr's compliance portfolio is thinner and its data centers are not all ISO certified.

## When you should pick Vultr anyway

Pick Vultr when your audience is outside Europe and the US East / US West corridor. Pick Vultr when you need GPU compute — the GH200 and H100 instances are rentable by the hour, while Hetzner's GPU options are essentially limited to dedicated server rentals with monthly commitment. Pick Vultr when you want the newer VX1 generation, which VPSBenchmarks grades measurably better than Hetzner's CCX line on disk IO and stability. And pick Vultr when you want the $300 free credit to test the migration before paying a cent.

👉 [Get the $300 free credit and benchmark Vultr against your current Hetzner setup](https://www.vultr.com/?ref=9738262-9J)

## FAQ: Vultr vs Hetzner 2026 questions people actually ask

**Is Hetzner still cheaper than Vultr in 2026?**
Yes, but the gap narrowed significantly. After Hetzner's June 15, 2026 price adjustment, the CCX dedicated line rose by 113% to 173% and the CAX ARM line rose by 30% to 33%. Hetzner remains 25% to 40% cheaper at equivalent specs, but the days of "Hetzner at a quarter of the price" are over.

**Which is faster, Vultr or Hetzner?**
On raw CPU at the dedicated tier, Hetzner's CCX line wins on price/performance. On the high-end shared tier, VPSBenchmarks' June 2026 results grade Vultr's VX1 GP 2C 8G 120S at B for web performance and A for stability and disk IO, ahead of Hetzner's CCX13 at E across the board. Vultr also offers 3GHz+ High Frequency instances with single-thread performance Hetzner can't match.

**Can I run Vultr in Asia / Africa / South America?**
Yes — according to VPSBenchmarks, Vultr has 31 data centers across 5 continents including Singapore, Tokyo, Mumbai, Seoul, São Paulo, Santiago, Johannesburg, and Sydney. Hetzner has only 6 locations (Germany, Finland, US East, US West, Singapore), with no presence in South America, Africa, India, or East Asia outside Singapore.

**Does Vultr offer a free trial?**
Yes. Vultr's official coupons page currently lists two promo codes for new customers: `FLYTWOHUNDRED` for $200 in credit and `FLY300VULTR` for $300 in credit. Both expire 30 days after issue and require a valid payment method on file.

**Should I migrate from Hetzner to Vultr after the price hike?**
It depends on workload. For European users on shared vCPU plans, the math still favors Hetzner — the CX/CAX/CPX lines only rose 30% to 38%. For users on dedicated CCX plans, especially outside Europe, Vultr's General Purpose tier is now within 25% of Hetzner's price with better global coverage. Use the $300 free credit to benchmark your actual workload before deciding.

**Does Hetzner have an SLA?**
Yes — Hetzner publishes a 99.9% uptime SLA with clearly defined service credits in case of malfunction. Vultr also publishes a 100% uptime SLA. Both meet typical production requirements.

## The bottom line

The vultr vs hetzner 2026 comparison is no longer a blowout. Hetzner's June 15 price adjustment erased most of its 3:1 pricing advantage on the dedicated tier and turned its previous "obviously cheaper" positioning into "still cheaper, but you have to weigh it now." If your workload is Europe-bound and price-sensitive, Hetzner still wins. If your users are global, you need GPU, or you want the newest VX1 silicon, Vultr is the safer bet — and the $300 free credit makes the test essentially free.

👉 [Open a Vultr account with $300 in free credit and decide for yourself](https://www.vultr.com/?ref=9738262-9J)
