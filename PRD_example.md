>  [!NOTE]
> This is just an example of a PRD that I generated from a quick chat. You can continue with this one as your "save point", but I'd recommend starting one from scratch instead (see the instructions in readme.md) to help better capture whatever unique thoughts and vision you might have.

### `docs/PRD.md`

**Overview**

A location-based, mission-aligned marketplace platform connecting religious institutions with community-centric organizations (schools, non-profits, hobbyists). Born from the real-world friction of manually scouting and "door-knocking" to find suitable school campuses, this app digitizes individual church rooms into a searchable database. It bridges the gap between underutilized religious infrastructure and local community needs through a low-risk, success-based partnership model.

**Solution**

The platform serves as a specialized directory and lease-management tool. Instead of generic building rentals, it functions as a **granular inventory marketplace**, treating each room (sanctuary, classroom, hall) as a unique listing. By utilizing an "Activity Compatibility Matrix," the app matches organizations with churches that share similar community values. It simplifies the discovery process with high-quality, standardized accessibility photos and facilitates long-term, recurring leases without the burden of commercial real estate friction.

**Goals & Success Metrics**

* **3 Months:** 50+ active, verified church listings in a pilot region; $0 upfront cost for providers; 10+ successful recurring/one-off bookings.
* **12 Months:** Consistent monthly revenue through a high-volume, low-friction booking system; integrated payment/ledger tracking.
* **Scaling Moat:** Maintain a "Community First" reputation where the majority of revenue stays with the church and local missions.

**Users & Personas**

* **The Provider (Church Administrator/Trustee):** Wants to generate revenue for building upkeep and support the neighborhood without managing complex marketing, unvetted strangers, or heavy logistics.
* **The Searcher (School Scout, Non-Profit Lead, Organizer):** Needs to find a compliant, affordable, and stable venue (from a single Saturday market to a 9-month school lease) without the friction of cold-calling.

**User Stories**

* **As a Searcher**, I want to filter a map by my neighborhood and "Educational Use" so I can find a satellite campus within walking distance.
* **As a Searcher**, I want to see mandatory photos of the entrance, restrooms, and parking so I know if the space is accessible for my community group before I visit.
* **As a Searcher**, I want to see a "Verified Institution" badge so I can trust that my organization's deposit is going to a legitimate, registered church.
* **As a Provider**, I want to list my "Church Hall" and "Classroom A" as separate entities with different rates and customization rules (e.g., storage availability) to maximize occupancy.
* **As a Provider**, I want to require an organizational mission statement with every booking request so I can ensure their activity aligns with our congregation’s values.
* **As a Provider**, I want to view a "Lease Ledger" that tracks whether a tenant has paid their security deposit directly to us, keeping our board's financial reporting clean.

**Competitive Analysis**

* **Direct Competitors:** Peerspace, Splacer. (They focus heavily on high-cost commercial, party, or photo-shoot rentals with no mission-alignment filters).
* **Indirect Competitors:** Facebook Groups, Craigslist, manual scouting. (Highly unorganized, zero vetting, massive time-friction).
* **Our Advantage:** We are building a "Trust Engine." By focusing specifically on community/educational compliance, long-term recurring leases, and mission alignment, we become the definitive, safe social infrastructure layer that commercial sites ignore.

**In Scope (v1)**

* **Sub-listing Architecture:** Support for multiple distinct "Rooms" under one "Parent Church."
* **Activity Compatibility Matrix:** A standardized whitelist of community activities (e.g., "Youth Education," "Support Groups") to act as a mutual pre-filter.
* **Recurring Lease Engine:** Support for complex scheduling (one-off, weekly, or block months) with a generated Memorandum of Understanding (MOU).
* **Digital Verification Waterfall:** Automated checks against non-profit/charity registries (e.g., ACNC/EIN) and domain verification to prevent fraudulent listings.
* **Standardized Visuals:** Mandatory photo uploads for core accessibility areas (Entrance, Parking, Restrooms, Main Space).
* **Deposit & Payment Ledger:** A dashboard to record and acknowledge offline security deposits and recurring rent payments.
* **Community Review System:** Post-booking ratings focusing on amenity accuracy and mission alignment.

**Out of Scope**

* Platform-held Escrow (v1 will not act as a bank holding security deposits).
* Campus-wide unified bookings (Users must book specific rooms to keep calendar logic clean).
* Sub-leasing capabilities for tenants.
* In-app verification of a tenant's liability insurance or background checks (handled via platform messaging but executed offline).

**Constraints**

* **Hyper-local Density:** The map-based search requires a critical mass of listings in a specific city/suburb to be useful; a scattered national launch will fail.
* **Manual Verification:** Independent or newly planted churches not in standard tax databases will require manual admin review.
* **Legal Buffer:** Platform must clearly state in its Terms of Service that it is a matchmaking and ledger tool, and that liability/insurance falls entirely on the two connecting parties.

**Open Questions**

* Does the platform's 10% service fee apply only to the recurring rental rate, or does it also take a cut of the initial security deposit?
* How should the platform handle or penalize late recurring monthly payments logged in the ledger?
