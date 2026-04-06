## **What Satellites Can't See**

Geospatial Corroboration of Torture Testimony in Conflict Zones

Matthew Harris\
UNHCR/IRC\
Survivors of Torture Program (SOT)

Apr 9th, 2026 - Arizona State University

---

## The Problem

**How do you build a case when you can't go to the crime scene?**

> Speaker notes: "In armed conflict, survivors of torture come forward with accounts that are vivid, specific, and deeply personal. But testimony alone - no matter how credible - isn't enough to trigger a formal investigation. You need corroboration. And the places where these things happened are active conflict zones. You can't send an investigator to knock on doors. So the question my team was trying to answer every day was: how do you corroborate a survivor's account from a distance? That's what I'm going to walk you through today. As a note, one of the slides will be very dark, I’ll warn you about it when get there again.”


---

## What the Literature Says

**Edler et al. (2025) - A Systematic Review**

- **The Scope:** 51 empirical studies (2006–2023)
- **The Baseline:** Tracking physical damage
- **The Problem:** The "Validation Shift"
- **The Blindspot:** Invisible violations
- **The Call:** Interdisciplinary collaboration

> Speaker notes: "Before I get into my own work, I want to give you some context from the current literature. The paper by Edler and colleagues came out in late 2025 - it's a systematic review of how satellite remote sensing has been used to document human rights violations in conflict zones. They reviewed over 900 articles, narrowing it down to 48 articles containing 51 empirical studies from 2006 to 2023.
> 
> They note that remote sensing is increasingly used to document conflict-things like damage assessment, land cover change, and fire patterns. But they found something that concerns me. The field has a problem: validation has shifted. Early on, practitioners were using satellite data to corroborate what people on the ground were reporting. NGO networks, witnesses, local contacts would surface a claim, and remote sensing would help validate it.
> 
> But as academic RS researchers entered the field around 2013, the methodology shifted. Remote data started validating other remote data. The ground-truth human knowledge - the testimony, the local context - got sidelined.
> 
> The paper also points out that certain violations are simply invisible to satellites. You can see a bombed building from space. You cannot see torture, sexual violence, or forced interrogation.
> 
> The paper also surfaces something the professor asked me to touch on — who has access to this data and what that means for justice. Edler documents a heavy dependency on commercial satellite providers, especially in the early years. Companies like Maxar and Planet control the very-high-resolution imagery. They decide who gets access, and sometimes they restrict it — Planet limited access to Gaza imagery after October 2023. That creates a two-tiered system. If you have satellite access, you can document violations. If you don't, your conflict stays invisible. The countries with the satellites get to produce the evidence. The people being bombed don't get to choose whether the camera is pointed at them.
> 
> Ultimately, the paper calls for a return to interdisciplinary collaboration between RS researchers and human rights practitioners. My work sits right in that pre-2013 window, and it represents exactly the approach this paper argues the field is losing.”


---

## My Role

**IRC - SOT Program, 2010 - 2012**\
**IRC/UNHCR - SOT Program, 2012 - 2014**\
**UNHCR - SOT Program, 2022 - 2023**

- **The Role:** Building the data pipeline
- **The Goal:** Corroborating testimony via GIS &amp; RS &amp; Military Data
- **The Principle:** Independent data validation

> Speaker notes: "So who am I in all this? I've worked with the Survivors of Torture program across several stints with the IRC and UNHCR from 2010 through 2023. My job was to be the bridge between the clinical side and the analytical side. I wasn't the person interviewing survivors. I wasn't a field investigator.
> 
> I was the person who built and operated the data pipeline that connected a survivor's clinical intake to geospatial analysis. The goal of this was to corroborate their testimony using GIS and temporal data to figure out exactly which military and paramilitary units were likely involved in the torture.
> 
> The key idea - and I want you to hold onto this phrase because it's the foundation of everything I'm going to show you - is that we were not replacing testimony. We were validating it with data the survivor could not have known without being there. That's what makes the corroboration meaningful. They didn't have access to classified troop movements. If their account lines up with that data anyway, that tells you something.”


---

## The Pipeline - Overview

**Four stages, four different skill sets, one chain of evidence**

1. Clinical Interview
2. Structured Intake Form
3. Geospatial Overlay
4. Investigation Trigger

> Speaker notes: "Here's the pipeline at a high level. Four stages, four different skill sets, one chain of evidence. I'm going to walk you through each one.
> 
> First, the clinical interview, which is always conducted by a licensed psychologist or therapist.
> Second, the structured intake form, which our team designed to capture the who, what, when, where, why, and the specific torture typology.
> Third, the geospatial overlay, where we take that testimony and place it on the map against classified troop movement data.
> And finally, the investigation trigger, where strong spatial-temporal correlations are used to request a formal investigation.
> 
> Before I dive into each step, I want you to notice something about this structure: the person doing the interview is not the person reading the map. The person who manages the data is not the person running the troop movement overlay. That separation is deliberate, and it's there for a reason I'll get into on the next slide.” 

---

## Stage 1 - The Clinical Interview

- Licensed psychologist or therapist
- Wellbeing first, not evidence collection
- No access to maps, troop data, or prior correlations
- Deliberate firewall against confirmation bias

> Speaker notes: "The interview is always conducted by a licensed psychologist or therapist. Their primary job is the survivor's wellbeing, not evidence collection. They're trained in trauma-informed interviewing. And critically - they have no access to our maps, our troop data, or any prior case correlations. This is a deliberate firewall against confirmation bias. The Edler paper spends a lot of time on what they call the 'seeing is believing' problem - researchers interpreting satellite images through the lens of what they expect to find. The most famous example is Colin Powell presenting aerial surveillance imagery to the UN Security Council in 2003, claiming Iraq had weapons of mass destruction. What got 'read into' those images was what the administration was most afraid of. Our pipeline prevents that at the very first step. The clinician doesn't know what the map looks like. They can't lead a survivor toward an answer that fits a spatial hypothesis someone already has. They're capturing what the survivor reports. Period."

---

## Stage 2 - The Structured Form

- Clinical narrative → structured, analyzable data
- Captures the W's plus typology and motive
- Designed by the SOT team
- The translation layer between testimony and GIS

> Speaker notes: "Once the clinical interview is done, the clinician fills out a structured form that our team designed. This is the translation layer. A survivor tells their story in narrative form - it's messy, emotional, nonlinear the way trauma always is. The form converts that narrative into structured fields I can operationalize geospatially. Who - any identifying information about perpetrators. Unit markings, uniforms, language, insignia. What - what specifically was done, and the type of torture matters, which I'll get into on the next slide. When - dates, times, duration, sequence of events. Where - locations, descriptions of facilities, landmarks, surroundings. And why - what was the apparent purpose? Each of those becomes a field I can work with. This is the step that most of the remote sensing studies in the Edler review skip entirely - because they never touch testimony. They go straight from satellite to conclusion. Our team built a pipeline that includes this structured form. We controlled the data schema, which means we controlled what information was captured consistently across every case that came through the program."

---

## The Typology Layer - Why "What" and "Why" Matter

- Type of torture as a method signature
- Different operators torture differently - this is a discriminator
- Motive matters: interrogation vs. terror vs. gratification
- Invisible to satellites - but increases confidence of spatial-temporal match
- Also functions as a consistency check

> Speaker notes: "This is probably the part that surprises you if you came in expecting a GIS or remote sensing talk. What I'm describing is behavioral profiling of military and paramilitary units, built up from survivor accounts. Different operators torture differently. Electrical torture during interrogation looks very different from sexual violence with no intelligence objective. 'We need the security rotation for this power plant' is a very different crime than gratification-driven sexual violence. Both are crimes. But they paint very different operational pictures. If Unit X consistently uses a specific interrogation technique and Unit Y uses sexual violence as a terror tactic, then the type of torture a survivor describes becomes an independent variable I can cross-reference against known unit presence. Three survivors from the same region and timeframe who all describe the same method? That's a pattern. One describes something completely different? I may be looking at a second unit in the area - or a different operational phase. The 'why' matters too because motive tells me something about the unit's mission profile. A unit extracting actionable intelligence is operating differently than a unit using violence to terrorize a civilian population. Both are crimes. But they have different command structures, different objectives, and potentially different accountability chains. No satellite will ever capture this. But it dramatically increases my confidence in a spatial-temporal match.
> 
> There's another dimension here that's uncomfortable but I think it's important to be honest with you about. That last bullet - consistency check. The typology layer also surfaced fabrications, because not every claim was genuine. Survivors of Torture receive enhanced benefits when they resettle in the United States. That's the right policy. But limited resources mean limited slots, and that reality creates an incentive structure. Sometimes people would invent or embellish an event to qualify for those benefits. I never blamed anyone for trying - these are people in desperate circumstances doing what they can to survive. But it meant we had to watch for it constantly, because every fabricated case that moved forward was resources pulled away from someone with a legitimate claim. When a reported event was an outlier - a method signature that didn't match any known unit activity in that area, a motive that didn't track with the operational picture - sometimes the explanation wasn't a second unit. Sometimes the person was lying. The typology layer helped surface those cases too. It's dark, but pretending it didn't happen would be dishonest about how the system actually worked."

---

## Stage 3 - The Geospatial Overlay

- Testimony plotted in GIS - location and temporal window
- Overlaid against classified estimated troop movement data
- Cross-referenced against method signatures from typology
- The survivor had no access to this data - alignment is independent corroboration

> Speaker notes: This is where it all comes together. I take the structured testimony - place, time, method, motive - and overlay it against an entirely independent data source: classified estimated troop movements. The survivor didn't know where intelligence assessed Unit X to be on March 15th. But if they say 'soldiers with these markings held me at this location for three days starting around mid-March,' and the troop movement data shows that unit was assessed to be in that area during that window - that's not a coincidence I can dismiss. That's corroboration from an independent source. Then I cross-reference the typology - does the method signature match what's known about units operating in that area? If the location lines up, the timing lines up, and the method lines up, I'm looking at three independent data points converging. The Edler paper calls this triangulation, and they're right - but the key is that these are genuinely independent data streams. Clinical intake, structured survivor reporting, and classified military intelligence. No circular validation. I'm not using remote sensing to validate other remote sensing. I'm using data the survivor never had access to, to test whether their account holds up.
> 
> I want to flag something here for the folks in the room thinking about cybersecurity and data access. This pipeline works because we had access to classified troop movement data. That access enabled accountability. But flip it — the same satellite infrastructure that lets us corroborate a torture victim's story can be used by an adversary to figure out where their units were detected, which tells them where the intelligence gaps are. Open source satellite imagery has been used by armed actors to plan operations, track displacement patterns, figure out where people fled to. The tool is morally neutral. Who's holding it is what matters. And that's a question this class has been chewing on all semester.

---

## Stage 4 - From Correlation to Investigation

- Correlation is a trigger, not a verdict
- Consistent with facts they could not have known
- Multiple accounts → same unit, same area, same timeframe → pattern
- Pattern justifies committing investigative resources
- GIS opens the door - human investigators walk through it

> Speaker notes: "I want to be clear about what this step is and what it isn't. A spatial-temporal match does not prove that Unit X tortured this person. What it establishes is that the survivor's account is consistent with facts they could not have known without being there. That's the trigger, not the verdict. Where it gets powerful is when you start seeing multiple corroborated accounts pointing to the same unit, in the same area, during the same timeframe. That's a pattern. And that pattern is what justifies committing scarce investigative resources. Because those resources are scarce - you can't investigate everything. The geospatial pipeline helped us prioritize where the evidence was strongest. The GIS analysis opens the door. Human investigators walk through it."

---

## Content Warning

**Content Warning**

> Speaker notes: "The next slide is going to humanize what we've been talking about. It involves sexual assault and crimes against children. If that's not something you want to hear about right now, please feel free to look away or step out - no one will think anything of it.
> 
> There will be no visuals - just a description of a GIS query. But I think it's important you see it, because we can't understand the weight of this work without understanding what's behind the data. Behind every statistic is a real person. That's why the methodology matters. That's why the rigor matters.
> 
> I'll give you a moment." *Take a deep breath, and count down from 8*

---

## The Human Cost of the Data

I need a table where:

- the top is girls aged, 3-12
- the left is the lists of torture types
- the cells are the number of cases, split by if a caregiver was present

The torture types are: sexual assault, electrocution, beatings, hanging, burning, mock execution, waterboarding. Add any other types that have a higher count than the lowest count of the types listed above.

> Speaker notes: "I want to be honest about what this work costs. There's a perception that the technical people are insulated - that because we're working with data instead of sitting across from a survivor, we're protected from the emotional weight. We're not.
> 
> You don't have to be in the room with the survivor to carry the weight. The GIS analyst never conducts an interview. They never meet the survivor face to face. But they're the one who runs the query you see on the screen.
> 
> And then a table comes back. And you have to do something with that table. You have to put it on a map. You have to cross-reference it. You have to write it in a report. And then you have to go home.
> 
> The distance that data creates is real. But it is not enough. You carry it differently, but you carry it."

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

> Speaker notes: So let me tie this back to the paper. Each row in this table is a concern Edler and colleagues raised, matched against how our team addressed it operationally. They worry about circular validation - we had three independent data streams. They worry about subjective visual interpretation - our analysts and clinicians never saw each other's data before the overlay. They acknowledge that certain violations - they use gender-based violence as their example - remain invisible to remote sensing. Torture falls into that same category. You can't see it from space. But GIS and temporal data can build the evidentiary scaffolding around the testimony even when the violation itself leaves no satellite-visible trace. They flag the CNN effect, where media attention drives which conflicts get studied - we worked under a UN mandate, so we worked cases regardless of whether they were on the news. And they call for more interdisciplinary collaborfation - our team was that collaboration. Clinicians, GIS analysts, investigators, one shared pipeline. The model the paper says the field needs existed. It worked. 
> 
> **The question is whether these principles survive as the tools and datasets evolve.**


---

## Closing

**What satellites can't see, survivors can tell you.**

**What survivors can't prove, the data can corroborate.**

**Neither one works alone.**

> Speaker notes: What satellites can't see, survivors can tell you. What survivors can't prove, the data can corroborate. Neither one works alone.
> 
> And as satellite data becomes more accessible, the question isn't **just** whether we use it for justice — it's whether we can prevent it from being used against the people it's supposed to protect
> 
> Somehow in the most human of experiences.. we forgot to include the human who experienced it. Thank you. I'm happy to take questions.
