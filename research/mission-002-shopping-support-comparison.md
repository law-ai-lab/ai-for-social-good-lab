# Mission #002 — Shopping Support Comparison: Koshigaya City

**AI for Social Good Lab | Rie Nakahara**  
**Reviewed:** 2026-10-19  
**Stage:** Desk research, not a user study or validated product finding.

## 1. Objective

Compare two official grocery-access support approaches in Koshigaya, Saitama. Investigate whether older adults who value choosing their own groceries can reach shops and return home with purchases. Preserve joy, independence, privacy, safety and dignity. Distinguish official descriptions (**E**), hypotheses (**H**), unknowns (**U**) and research decisions (**D**).

## 2. Confirmed support options

| Dimension | A. Mobile retail (移動販売) | B. 越谷げんき de MaaS |
|---|---|---|
| Model (E) | Mobile retailers sell fresh and daily-use items, under arrangements with Welcia and Kasumi. | The wider program includes route search; this comparison focuses on its separate bus/taxi fare subsidy [S2–S3]. |
| Coverage (E) | Some areas within six districts [S1]: 桜井・出羽・増林・大相模・新方・荻島. Not citywide. The page does not state a 75+ eligibility rule for mobile retail. | Koshigaya residents 75+, including those turning 75 within the fiscal year; participating operators/routes only [S2]. |
| Times (E) | Monday–Friday, including most public holidays; year-end/New Year excluded. Actual stops/times vary; weather may cause cancellations. | Actual vehicle schedule and availability depend on operators. A subsidy does not create transportation. |
| Cost (E) | Specific product prices and conditions at a stop not verified here. | Bus: ¥100 discount per eligible ride without frequency cap. Taxi: ¥500 discount per eligible ride, up to 12 per fiscal year [S2]. Not free rides. |
| Access rules (E) | Confirm exact stop and any retailer conditions before directing users there. | Advance registration and transit IC card; bus subsidy excludes cash payment and requires nonzero card balance. Bus discounts start the day after registration. Participating taxis display a sticker; IC-card identification does not itself complete taxi payment. Smartphone self-registration and assisted registration are described [S2, S4]. |
| What it may help with (H) | Bringing products closer to the person's neighborhood. | Lowering some transport costs while allowing a chosen in-person shopping trip. |
| What's not established (U) | Whether a given stop is accessible, stock matches preferences, or chosen food is available. | Actual workable round trip, bag assistance, walking distance, boarding feasibility and final cost. |
| Joy/independence (H) | Choosing nearby products may preserve discovery and informal social contact. | Visiting a preferred shop might preserve browsing and personal choices. Neither benefit was measured here. |

## 3. Original municipal sources

1. **S1.** [越谷市：移動販売をご利用ください](https://www.city.koshigaya.saitama.jp/kurashi_shisei/fukushi/koureisha/chiikinosasaeai/idouhanbai.html) — updated 2026-04-01; six-area coverage, retailers, timetable principles and cancellations.
2. **S2.** [越谷市：越谷げんき de MaaS 運賃補助](https://www.city.koshigaya.saitama.jp/kurashi_shisei/kurashi/sumai/koukyokoutsu/koshigayagenkidemaasunnchinhojo.html) — updated 2026-08-06; age, benefit levels, IC use, operators.
3. **S3.** [越谷市：越谷げんき de MaaS overview](https://www.city.koshigaya.saitama.jp/kurashi_shisei/kurashi/sumai/koukyokoutsu/koshigayagenkidemaas.html) — updated 2025-10-01; separates route search and subsidy.
4. **S4.** [越谷市：自分で登録する方向け](https://www.city.koshigaya.saitama.jp/kurashi_shisei/kurashi/sumai/koukyokoutsu/genkidemaastouroku.html) — updated 2026-08-06; smartphone self-registration.
5. **S5. Historical context only.** [越谷市広報 2026年4月（PDF）](https://www.city.koshigaya.saitama.jp/kurashi_shisei/shisei/koho/koho_kosigaya/2026/files/1472_R080401_12.pdf) — described assisted registration for people without an easy smartphone process. Use the current subsidy page (S2), rather than this older newsletter, for current arrangements.

**Current assisted registration (E, S2):** City Hall main building, 6th floor, weekdays 09:00–15:00; arrangements changed on 2026-08-03. A transit IC card and identity documents are required; a smartphone is listed only if held. This challenges the assumption that smartphone ownership is always required for subsidy access. Recheck arrangements before visiting. Our prototype must never collect identity-document or IC-card numbers.

**Verification method:** Read the five municipal sources on 2026-10-19. Page update dates are not proof that every timetable or operational detail is current. S1 includes old year-end notices; do not reuse those as the 2026–27 holiday schedule. No exact stop, route or operator availability was checked for a specific trip.

Official descriptions verify published program rules, **not** satisfaction, real-time availability, individual suitability or measured effectiveness. No users, staff or providers were interviewed for this comparison.

## 4. Hypothetical shopping journey (not a real participant)

An independently living older adult wants to pick seasonal vegetables for a favorite meal and enjoy browsing. Reaching a distant supermarket and returning with bags is difficult **in this fictional example**.

- **Option A — mobile retail:** Potentially shorter travel, but actual nearby stop, food selection, affordability and timing remain unknown.
- **Option B — MaaS subsidy:** May preserve a preferred physical shopping trip, but does not establish a feasible return connection, safe boarding with groceries, or doorstep help.
- **Alternative:** Existing delivery or chosen human assistance might work better; we have not compared the full local market.

**D — provisional product question:** Could a plain-language comparison of verified local options help someone choose *how they want to shop* without hiding costs, access conditions, or unknowns? This is not evidence an AI system is needed.

## 5. Joy, accessibility and ethical safeguards

Shopping is more than food acquisition: the founder prioritizes excitement, discovery, recipes, independence, social connection and choosing to shop alone or together. These are **design values**, not empirically validated local preferences.

- Adult-to-adult language and multiple choices; never assume age implies incapacity.
- No compulsory AI friend, memory sharing, account or special device.
- No identifiable addresses, clinical information, purchase histories or interviews in public GitHub.
- Clearly distinguish official provider information from a prototype's fictional demonstration.
- Do not promise transport, zero-cost delivery, availability or booking until verified.
- Sponsored offers, if ever used, must be clearly labeled.

## 6. Limitations and open questions

1. Which specific mobile-retail stop, hours and products would fit one fictional area-level scenario?
2. Is there a practical outbound *and return* itinerary to a chosen supermarket, with acceptable total remaining fare?
3. Are bag carrying, waiting conditions and transfer-to-home help available?
4. Can a resident practically reach the documented assisted-registration venue and complete registration? The published support route exists; actual usability has not been tested.
5. Which residents prefer store visits, mobile retail, or delivery, and why?
6. Does a new comparison screen improve decisions relative to existing municipal pages?
7. Is AI necessary, or would a well-maintained static interface work better?

## 7. Provisional implications for Prototype v0.1 (D)

The working gap is **understanding whether an option fits a desired shopping trip, including getting home with bags**. Service absence, information difficulty and physical barriers are different problems; this comparison has not established which is dominant.

Start with a small Japanese-language comparison for one fictional area-level journey. Let the person choose nearby mobile shopping or a preferred store visit, see remaining costs and access conditions, and review the return journey before deciding. Offer an obvious route to official information and human enquiry. Mark unverified steps explicitly; a subsidy must never be labeled a guaranteed ride or bag-carrying service.

Use readable text, keyboard access and a printable summary. Any enjoyable fictional store or character demonstration should be optional and clearly separated from real provider information. No accounts, sensitive data, real ordering, booking, live availability claims or medical claims are needed for this scope. A maintained static interface is the first approach to evaluate; AI is not a prerequisite.

**Validation needed:** Compare comprehension with the existing city pages, then use a separately consented process to learn whether older adults find the choices understandable, useful and enjoyable. A fictional walkthrough cannot validate user demand or safety.

## 8. Mission #002 result and next step

- [x] Compare two official options from one locality.
- [x] Record sources, dates, uncertainties and possible user decisions.
- [x] Preserve joy, autonomy, accessibility and research ethics.
- [ ] Verify exact stop/itinerary and participant preferences in follow-on work.

**Next 30–60-minute task:** Select one *fictional* area-level shopping journey (without a residential address), confirm one current mobile-retail stop and one possible round-trip transport arrangement using official schedules, and mark every unverified step. Sketch one optional joy-focused interface screen that does not imply real services have been booked.

**Long-term milestone:** Public Japanese-language browser prototype v0.1 by 2026-12-31, with documented limitations and no false real-world fulfillment claims.
