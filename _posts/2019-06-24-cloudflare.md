---
layout: post
title: "Cloudflare Outage – June 2019: A BGP Route Leak Takes Down Major Websites"
date: 2019-06-24
---

### Overview
On June 24, 2019, a significant internet outage impacted services worldwide, including major websites like Discord, Facebook, and Reddit. The outage was caused by a BGP (Border Gateway Protocol) route leak, which created a ripple effect across the global internet, affecting approximately 15% of Cloudflare's traffic.

### Technical Details
The outage was triggered when **DQE Communications**, a regional ISP, accidentally advertised incorrect routes to Cloudflare’s services due to a BGP optimization mishap. These faulty routes were propagated by Verizon, further amplifying the issue and affecting a large swath of internet traffic. The routing error caused significant disruptions to Cloudflare’s Content Delivery Network (CDN), affecting services like Discord, AWS, and Nintendo Life.

### Impact
- **Global Disruption**: Popular platforms such as Discord and Reddit were inaccessible for nearly two hours, affecting millions of users worldwide.
- **Service Recovery**: Cloudflare worked quickly to correct the routing error, and services were restored after about two hours of downtime.

### Lessons Learned
This incident highlighted the fragility of the internet’s routing system and the far-reaching effects that even a small routing error can cause. Enterprises need visibility into the internet infrastructure they depend on, especially when relying on cloud services.

**Sources**:
- [ThousandEyes](https://www.thousandeyes.com/blog/biggest-internet-outages-2019)
- [World Economic Forum](https://www.weforum.org)
