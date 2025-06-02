**Document: Consideration Factors for Property Buyers and Investors**

**Purpose**
This document outlines the comprehensive set of factors considered during property evaluation, relevant to both **home buyers** and **property investors**. The structure is intended to support both a product design framework and potential implementation logic, such as AI-based recommendation or evaluation tools.

---

## 1. Core Structure

The considerations are grouped into two major dimensions:

### 1.1 Micro: Attributes Specific to the Property

These are characteristics tied to the individual dwelling and land parcel.

* **Type of Dwelling**

  * Verification against actual structure (may be mislabeled)
  * Categories: House, Townhouse, Duplex, Apartment

* **Construction Quality & Material**

* **Style & Aesthetic**

  * E.g., Match with modern/classic style preference

* **Layout and Orientation**

  * Room positioning (e.g., north-facing bedroom)
  * Living area flow (e.g., open-plan kitchen)

* **Features**

  * Number of bathrooms, storage, air-con, solar, garage, etc.
  * Check against specific user requirement

* **Privacy**

  * Overlooking neighbors, fencing, window alignment

* **Size**

  * Internal living area, number of rooms

* **Land Attributes**

  * Lot size
  * Shape and gradient (slope, corner block)
  * Front yard / backyard utility
  * Zoning (e.g., R2, R3, mixed use)
  * Fire / flood risk (mapped overlays)
  * Elevation profile (Google map lookup or elevation API)

---

### 1.2 Macro: Neighbourhood Attributes

These describe the characteristics of the surrounding area and broader planning context.

* **Neighbourhood Profile**

  * Suburb & LGA layers
  * Reputation
  * Demographic summary & trend
  * Crime & safety
  * Median price trends

* **Noise and Pollution Sources**

  * Proximity to major roads
  * Construction sites
  * Airports or industrial areas

* **Development Activity**

  * Nearby DAs and rezoning
  * Council development pipeline

* **Suburb Dynamics & Investment Indicators**

  * Gentrification signals:

    * Demographic shift (e.g., more professionals)
    * Cafe/opening trends
    * Renovation and flip frequency
    * Infrastructure investment (light rail, TOD)
  * Rental yield and vacancy rate
  * Investor vs. owner-occupier mix

---

## 2. Location and Proximity

Assesses ease of access to practical and lifestyle-oriented amenities:

* **Life Essentials**

  * Closest public transport
  * Shopping and grocery
  * Restaurants

* **Lifestyle Amenities**

  * Public parks
  * Beaches
  * Gyms and cafes

* **Schools**

  * Government or private, primary/secondary
  * Catchment considerations

* **Other Locations of Interest**

  * Work, family, community centers

---

## 3. Affordability

* **Personal Affordability**

  * Calculator/simulation of capacity to pay
  * Match to individual goals (budget, loan serviceability)

* **Housing Affordability Schemes**

  * FHB programs
  * Shared equity, stamp duty relief
  * Web search and AI agent to assess eligibility

* **Bank Lending Constraints**

  * Loan-to-Value Ratio (LVR)
  * Lending buffer rates

---

## 4. Enabling Product Logic (Design Notes)

* **Personalisation Layer**

  * Tagging user priorities: e.g., natural light, future development potential
  * Deal-breaker and must-have logic

* **Matching Engine**

  * Compare user preferences to property attributes
  * Score mismatch or alignment

* **Automation & Enhancement Features**

  * Image-based detection (dwelling type, backyard size)
  * Map overlay features (flood zones, TOD, vegetation, elevation)
  * Free text parsing + AI summarisation for listings

* **Gentrification Signal Score (planned feature)**

  * Composite score using property, planning, and socio-demographic data

---

**Next Steps**
This document is intended as a living foundation for ongoing feature planning, prioritisation, and technical architecture alignment. Future iterations may include user persona weightings, scoring logic per factor, and backend schema alignment.
