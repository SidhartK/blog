
Is intelligence a utility: [Sam Altman seems to think so](https://www.reddit.com/r/singularity/comments/1rro8ej/sam_altman_we_see_a_future_where_intelligence_is/).

"We see a future where intelligence is a utility, like electricity or water, and people buy it from us on a meter."

If it is the case that intelligence is analogous to a utility like electricity, then what parts of the analogy are still missing?

What would it mean to buy intelligence from OpenAI on a meter. What if it turned out to be useless? Are there many types of intelligence or is there a singular unit of "intelligence". 

I have no fucking clue. 

I think it will get crazy expensive. Right now the expense is not being passed to the consumer, instead absorbed by VCs in weird schemes. 

# LLM Quotes Start Here
> ## The model
> Treat each user's monthly total as fixed-broadband traffic (shared across the household) plus their own cellular traffic. All figures GB/month, US-centric.
> **Consumed per user:**
> 
> $$C = \frac{D_{\text{fix}}}{n} + D_{\text{mob}}$$
> 
> **Produced per user:**
> 
> $$P = \frac{U_{\text{fix}}}{n} + U_{\text{mob}}$$
> 
> | Variable | Meaning | Estimate |
> |---|---|---|
> | $D_{\text{fix}}$ | household downstream (home broadband) | 700 GB |
> | $U_{\text{fix}}$ | household upstream (home broadband) | 48 GB |
> | $n$ | internet users sharing a household | 2.5 |
> | $D_{\text{mob}}$ | per-user cellular download | 18 GB |
> | $U_{\text{mob}}$ | per-user cellular upload | 2.5 GB |
> 
> (Cellular and home figures add cleanly rather than double-count: cellular numbers are off-Wi-Fi traffic only; when a phone is on home Wi-Fi it falls under $D_{\text{fix}}$.)
> 
> **Plugging in:**
> 
> $$C = \frac{700}{2.5} + 18 = 280 + 18 = \mathbf{298\ \text{GB/month}}$$
> 
> $$P = \frac{48}{2.5} + 2.5 = 19.2 + 2.5 \approx \mathbf{21.7\ \text{GB/month}}$$
> 
> ## Bottom line
> 
> In bytes per month: **consumed ≈ 3.0 × 10¹¹ B** (~300 GB), **produced ≈ 2.2 × 10¹⁰ B** (~22 GB).
> 
> Per year: **consumed ≈ 3.6 × 10¹² B** (~3.6 TB), **produced ≈ 2.6 × 10¹¹ B** (~260 GB).
> 
> $$\boxed{\dfrac{C}{P} \approx \dfrac{298}{21.7} \approx 14}$$
> 
> The average internet user consumes on the order of **14× more bytes than they produce.**
> 
> ## Two caveats worth flagging
> 
> One is definitional. I defined "produce" as *bytes pushed upstream* — the clean measurable quantity. There's a second sense: *original content a user authors that then gets replicated to many consumers.* A 3 MB photo you upload once may be downloaded a million times. Under that definition production is even tinier relative to its consumed footprint, which only sharpens the asymmetry; the 14:1 ratio is the conservative version.
> 
> The second is scope. These are US numbers (OpenVault tracks US fixed broadband). Globally, lower fixed-broadband penetration and a more mobile-centric mix would pull the absolute consumption number down — call it 50–150 GB/month consumed for a global-average user — but the *ratio* stays lopsided because mobile traffic is itself download-dominated. If you want, I can rerun the model with global-average variables, or with a distribution (light/median/power user) instead of point estimates, since the median user differs a lot from the mean that these averages report.
