## **What Satellites Can't See**

Geospatial Corroboration of Torture Testimony in Conflict Zones

Matt Harris
Former Technical Liaison Officer, UNHCR - Survivors of Torture Program 

Apr 9th - Arizona State University

---

## The Problem

**How do you build a case when you can't go to the crime scene?**

> Speaker notes: "In armed conflict, survivors of torture come forward with accounts that are vivid, specific, and deeply personal. But testimony alone — no matter how credible — isn't enough to trigger a formal investigation. You need corroboration. And the places where these things happened are active conflict zones. You can't send an investigator to knock on doors. So the question my team was trying to answer every day was: how do you corroborate a survivor's account from a distance, using data they never had access to? That's what I'm going to walk you through today. As a note, one of the slides will be very dark, I’ll warn you about it when get there again.”
> 

---

## What the Literature Says

**Edler et al. (2025) - A Systematic Review**

- Reviewed 901 articles, selected 48 with 51 empirical studies (2006–2023)
- Remote sensing is increasingly used to document conflict - damage assessment, land cover change, fire patterns
- But the field has a problem: **validation has shifted**
    - Pre-2013: RS data validated claims from ground sources (NGO networks, witnesses, local contacts)
    - Post-2013: RS data validates... other RS data
- Certain violations remain **invisible** to satellites - torture, sexual violence, forced interrogation
- The paper calls for more interdisciplinary collaboration between RS researchers and human rights practitioners

> Speaker notes: "Before I get into my own work, I want to give you some context from the current literature. This paper by Edler and colleagues came out in late 2025 — it's a systematic review of how satellite remote sensing has been used to document human rights violations in conflict zones. They reviewed over 900 articles. And they found something that concerns me. Early on, practitioners were using satellite data to corroborate what people on the ground were reporting — NGO networks, witnesses, local contacts would surface a claim, and remote sensing would help validate it. But as academic RS researchers entered the field around 2013, the methodology shifted. Remote data started validating other remote data. The ground-truth human knowledge — the testimony, the local context — got sidelined. The paper also points out that certain violations are simply invisible to satellites. You can see a bombed building from space. You cannot see torture. My work sits right in that pre-2013 window, and it represents the approach this paper argues the field is losing.”
> 

---

## My Role

**International Rescue Committee - Survivors of Torture (SOT) Program, 2009 - 2011**

**UNHCR - Survivors of Torture (SOT) Program, 2011 - 2013**

- Built the data pipeline between clinical intake and geospatial analysis.
- Limited field work in northern Iraq.
- Goal: corroborate survivor testimony using GIS and temporal data to determine which military units were likely involved in torture
- Not replacing testimony - **validating it with data the survivor could not have known**

> Speaker notes: "So who am I in all this? From 2011 to 2013 I was a Technical Liaison Officer with UNHCR, working specifically with the Survivors of Torture program. My job was to be the bridge between the clinical side and the analytical side. I wasn't the person interviewing survivors. I wasn't a field investigator. I was the person who built and operated the system that connected a survivor's words to spatial-temporal evidence. The key idea — and I want you to hold onto this phrase because it's the foundation of everything I'm going to show you — is that we were validating testimony with data the survivor could not have known. That's what makes the corroboration meaningful. They didn't have access to classified troop movements. If their account lines up with that data anyway, that tells you something.”
> 

---

## The Pipeline - Overview

**Four stages, four different skill sets, one chain of evidence**

1. **Clinical Interview** - conducted by a licensed psychologist or therapist
2. **Structured Intake Form** - designed by the SOT team, capturing the W's plus typology
3. **Geospatial Overlay** - placing testimony on the map against classified troop movement data
4. **Correlation → Investigation** - strong matches trigger formal investigation

> Speaker notes: "Here's the pipeline at a high level. Four stages, four different skill sets, one chain of evidence. I'm going to walk you through each one, but before I do, I want you to notice something about this structure: the person doing the interview is not the person reading the map. The person filling out the form is not the person running the troop movement overlay. That separation is deliberate, and it's there for a reason I'll get into on the next slide.”
> 

---

## Stage 1 - The Clinical Interview

**A licensed psychologist or therapist conducts the interview. Always.**

- The clinician's job is the survivor's wellbeing - not evidence collection
- They are trained in trauma-informed interviewing
- They have no access to maps, troop data, or prior case correlations*
- This is a **deliberate firewall against confirmation bias**

> Speaker notes: "The interview is conducted by a licensed psychologist or therapist. Their primary job is the survivor's wellbeing, not evidence collection. They're trained in trauma-informed interviewing. And critically — they have no access to our maps, our troop data, or any prior case correlations. This is a deliberate firewall against confirmation bias. The Edler paper spends a lot of time on what they call the 'seeing is believing' problem — researchers interpreting satellite images through the lens of what they expect to find. The most famous example is Colin Powell presenting aerial surveillance imagery to the UN Security Council in 2003, claiming Iraq had weapons of mass destruction. What got 'read into' those images was what the administration was most afraid of. Our pipeline prevents that at the very first step. The clinician doesn't know what the map looks like. They can't lead a survivor toward an answer that fits a spatial hypothesis someone already has. They're capturing what the survivor reports. Period.”
> 

---

## Stage 2 - The Structured Form

**The W's - plus typology and motive**

- **Who** - any identifying information about perpetrators (unit markings, uniforms, language, insignia)
- **What** - what specifically was done (the type of torture matters - more on this next)
- **When** - dates, times, duration, sequence of events
- **Where** - locations, descriptions of facilities, landmarks, surroundings
- **Why** - what was the apparent purpose?

The form was designed by the SOT team to translate clinical narrative into structured, analyzable data.

> Speaker notes: "Once the clinical interview is done, the clinician fills out a structured form that our team designed. This is the translation layer. A survivor tells their story in narrative form - it's messy, emotional, nonlinear the ways that trauma always is. The form converts that narrative into structured fields I can operationalize geospatially. Who, what, when, where, why. This is the step that most of the remote sensing studies in the Edler review skip entirely - because they never touch testimony. They go straight from satellite to conclusion. Our team built a pipeline which includes a structured form. We controlled the data schema, which means we controlled what information was captured consistently across every case that came through the program.”
> 

---

## The Typology Layer - Why "What" and "Why" Matter

**Different operators torture differently. This is a discriminator.**

- Type of torture functions as a **method signature**
- Electrical torture during interrogation looks very different from sexual violence with no intelligence objective
- Interrogation-driven torture ("we need the security rotation for this power plant") vs. gratification-driven torture - both are crimes, but they paint very different operational pictures
- Across multiple survivors, consistent method signatures help identify or narrow down which unit was operating in an area
- This is a data dimension that **no satellite will ever capture** - but it dramatically increases the confidence of a spatial-temporal match

> Speaker notes: This is probably the part that surprises you if you came in expecting a GIS talk. What I'm describing is behavioral profiling of military and para military units, built up from survivor accounts. If Unit X consistently uses a specific interrogation technique and Unit Y uses sexual violence as a terror tactic, then the type of torture a survivor describes becomes an independent variable I can cross-reference against known unit presence. Three survivors from the same region and timeframe who all describe the same method? That's a pattern. One describes something completely different? I may be looking at a second unit in the area — or a different operational phase. The "why" matters too because motive tells me something about the unit's mission profile. A unit extracting actionable intelligence is operating differently than a unit using violence to terrorize a civilian population. Both are crimes. But they have different command structures, different objectives, and potentially different accountability chains.
> 
> 
> There's another dimension here that's uncomfortable but I think it's important to be honest with you about. The typology layer also functioned as a consistency check — because not every claim was genuine. Survivors of Torture receive enhanced benefits when they resettle in the United States. That's the right policy. But limited resources mean limited slots, and that reality creates an incentive structure. Sometimes people would invent or embellish an event to qualify for those benefits. I never blamed anyone for trying — these are people in desperate circumstances doing what they can to survive. But it meant we had to watch for it constantly, because every fabricated case that moved forward was resources pulled away from someone with a legitimate claim. When a reported event was an outlier — a method signature that didn't match any known unit activity in that area, a motive that didn't track with the operational picture — sometimes the explanation wasn't a second unit. Sometimes the person was lying. The typology layer helped surface those cases too. It's dark, but pretending it didn't happen would be dishonest about how the system actually worked.
> 

---

## Stage 3 - The Geospatial Overlay

**Placing testimony on the map**

- Survivor's reported locations plotted in GIS
- Temporal window from the testimony layered against **classified estimated troop movement data**
- Looking for spatial-temporal correlation: Was the unit the survivor describes assessed to be in that location during that window?
- Cross-referencing the typology: Does the method signature match what's known about units operating in that area?

**The power of this approach: the survivor did not have access to the classified troop movement data. If their account aligns with it, that is independent corroboration.**

> Speaker notes: "This is where it all comes together. I take the structured testimony — place, time, method, motive — and overlay it against an entirely independent data source: classified estimated troop movements. The survivor didn't know where intelligence assessed Unit X to be on March 15th. But if they say 'soldiers with these markings held me at this location for three days starting around mid-March,' and the troop movement data shows that unit was assessed to be in that area during that window — that's not a coincidence I can dismiss. That's corroboration from an independent source. The Edler paper calls this triangulation, and they're right — but the key is that these are genuinely independent data streams. Clinical intake, structured survivor reporting, and classified military intelligence. No circular validation. I'm not using remote sensing to validate other remote sensing. I'm using data the survivor never had access to, to test whether their account holds up.”
> 

---

## Stage 4 - From Correlation to Investigation

**Strong correlations trigger investigations. Not conclusions.**

- A spatial-temporal match doesn't prove Unit X tortured this person
- It establishes that the survivor's account is **consistent with facts they could not have known**
- Multiple corroborated accounts pointing to the same unit, same area, same timeframe → pattern
- That pattern is what justifies committing investigative resources
- The GIS analysis opens the door. Human investigators walk through it.

> Speaker notes: "I want to be clear about what this step is and what it isn't. A spatial-temporal match does not prove that Unit X tortured this person. What it establishes is that the survivor's account is consistent with facts they could not have known without being there. That's the trigger, not the verdict. Where it gets powerful is when you start seeing multiple corroborated accounts pointing to the same unit, in the same area, during the same timeframe. That's a pattern. And that pattern is what justifies committing scarce investigative resources. Because those resources are scarce — you can't investigate everything. The geospatial pipeline helped us prioritize where the evidence was strongest. The GIS analysis opens the door. Human investigators walk through it.”
> 

---

## Content Warning

**Content Warning**

> Speaker notes: "The next slide is going to humanize what we've been talking about. It involves sexual assault and crimes against children. If that's not something you want to hear about right now, please feel free to look away or step out - no one will think anything of it. I'll give you a moment." *Take a deep breath, and count down from 8*
> 

---

## The Human Cost of the Data

**A note on what this work does to the people who do it**

You don't have to be in the room with the survivor to carry the weight.

The GIS analyst never conducts an interview. They never meet the survivor face to face. But they're the one who runs the query:

*"How many girls between the ages of 4 and 12 were raped in northern Iraq between March and April of this year?"*

And then a number comes back.

And you have to do something with that number. You have to put it on a map. You have to cross-reference it. You have to write it in a report. And then you have to go home.

**The distance that data creates is real. But it is not enough.**

> Speaker  "I want to be honest about what this work costs. There's a perception that the technical people are insulated - that because we're working with data instead of sitting across from a survivor, we're protected from the emotional weight. We're not. You carry it differently. But you carry it."  *Don't dwell*
> 

---

## Connecting the Practice to the Research

**Where my work meets the Edler et al. findings**

| Paper's Concern | Our Approach |
| --- | --- |
| Validation shifted to RS-validates-RS | We validated RS/GIS against independent clinical testimony and classified military data - three independent streams |
| Visual interpretation is subjective ("seeing is believing") | The analyst never saw the testimony before building the spatial model. The clinician never saw the map. Role separation by design. Not perfect, but decent. |
| Certain violations are "invisible" to remote sensing | Torture is invisible to satellites. But GIS + temporal data builds the evidentiary scaffolding *around* the testimony |
| Not all conflicts receive equal attention (CNN effect) | UN mandate meant working cases regardless of media coverage |
| Need for interdisciplinary collaboration | Our team *was* that collaboration - clinicians, GIS analysts, investigators, one shared pipeline |

> Speaker notes: "So let me tie this back to the paper. Each row in this table is a concern Edler and colleagues raised, matched against how our team addressed it operationally. They worry about circular validation — we had three independent data streams. They worry about subjective visual interpretation — our analysts and clinicians never saw each other's data before the overlay. They acknowledge that certain violations — they use gender-based violence as their example — remain invisible to remote sensing. Torture falls into that same category. You can't see it from space. But GIS and temporal data can build the evidentiary scaffolding around the testimony even when the violation itself leaves no satellite-visible trace. They flag the CNN effect, where media attention drives which conflicts get studied — we worked under a UN mandate, so we worked cases regardless of whether they were on the news. And they call for more interdisciplinary collaboration — our team was that collaboration. Clinicians, GIS analysts, investigators, one shared pipeline. The model the paper says the field needs existed. It worked. The question is whether these principles survive as the tools and datasets evolve."
> 

---

## Closing

**What satellites can't see, survivors can tell you.**

**What survivors can't prove, the data can corroborate.**

**Neither one works alone.**

> Speaker notes: [Read the three lines on the slide, then:] "Somehow in the most human of experiences.. we forgot to include the human who experienced it. Thank you. I'm happy to take questions.”
>
