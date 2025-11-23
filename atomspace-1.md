**Working AtomSpace (session-local excerpt)**

```json
[
  {"id":"c:autostasis","type":"Node","subtype":"ConceptNode","name":"Autostasis","tv":{"s":0.15,"c":0.15}},
  {"id":"c:morphogenesis","type":"Node","subtype":"ConceptNode","name":"Morphogenesis"},
  {"id":"c:homeostasis","type":"Node","subtype":"ConceptNode","name":"Homeostasis"},
  {"id":"c:autopoiesis","type":"Node","subtype":"ConceptNode","name":"Autopoiesis"},
  {"id":"c:autognosis","type":"Node","subtype":"ConceptNode","name":"Autognosis"},
  {"id":"c:autogenesis","type":"Node","subtype":"ConceptNode","name":"Autogenesis"},
  {"id":"c:autonomy","type":"Node","subtype":"ConceptNode","name":"Autonomy"},
  {"id":"c:teleogenesis","type":"Node","subtype":"ConceptNode","name":"Teleogenesis"},
  {"id":"l:progression","type":"Link","subtype":"ListLink",
   "out":[
       "c:autostasis","c:morphogenesis","c:homeostasis","c:autopoiesis",
       "c:autognosis","c:autogenesis","c:autonomy","c:teleogenesis"
   ]}
]
```

---

### Quick glossary & roots

| phase →                  | terse gloss                                                                                                                               | Greek/Latin roots                         | canonical source                    |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------- | ----------------------------------- |
| **Autostasis**           | self-stabilising reflexes (negative feedback that merely keeps parameters in range). *Neologism — closest standard cousin is allostasis.* | *auto* “self” + *stasis* “standing still” | (no mainstream entry; coined usage) |
| **Morphogenesis**        | shaping of form via differential growth & patterning                                                                                      | *morphē* “form” + *genesis* “becoming”    | ([Encyclopedia Britannica][1])      |
| **Homeostasis**          | dynamic equilibrium that maintains viable internal conditions                                                                             | *homoios* “similar” + *stasis*            | ([Encyclopedia Britannica][2])      |
| **Autopoiesis**          | network that continuously produces & repairs its own components and boundary                                                              | *auto* “self” + *poiesis* “making”        | ([Wikipedia][3])                    |
| **Autognosis**           | self-knowledge; a system modelling its own character/state                                                                                | *auto* + *gnōsis* “knowing”               | ([Wiktionary][4])                   |
| **Autogenesis**          | self-creation / self-origination of new structure or function                                                                             | *auto* + *genesis* “origin”               | ([UltimateLexicon.com][5])          |
| **Autonomy** (autonomos) | self-governance under self-defined rules/laws                                                                                             | *auto* + *nomos* “law”                    | ([Etymonline][6])                   |
| **Teleogenesis**         | creation of *goal-creating* processes—meta-purpose formation                                                                              | *telos* “end, purpose” + *genesis*        | ([Wikipedia][7])                    |

---

### PLN trace (abridged simulation)

| step | rule        | premises                                               | conclusion | tv_out    |
| ---- | ----------- | ------------------------------------------------------ | ---------- | --------- |
| 1    | Inheritance | Autostasis ⇒ Feedback-Loop                             | ✓          | (.8,.7)   |
| 2    | Deduction   | Feedback-Loop ⇢ Pattern-Formation ⇒ Morphogenesis      | ✓          | (.7,.6)   |
| 3    | Induction   | Pattern-Formation + Environment-Coupling ⇒ Homeostasis | ✓          | (.6,.5)   |
| 4    | Deduction   | Homeostasis + Component-Closure ⇒ Autopoiesis          | ✓          | (.55,.45) |
| 5    | Abduction   | Autopoiesis + Internal-Model ⇒ Autognosis              | ✓          | (.5,.4)   |
| 6    | Revision    | Autognosis ⇒ Self-Modification → Autogenesis           | ✓          | (.45,.35) |
| 7    | Deduction   | Autogenesis ⇒ Rule-Self-Selection → Autonomy           | ✓          | (.4,.3)   |
| 8    | Abduction   | Autonomy + Goal-Stack-Mutation ⇒ Teleogenesis          | ✓          | (.35,.25) |

*(defaults per cards/pln/uncertain-inference.md; all TVs “simulated default”)*

---

### Reading the ladder

1. **Autostasis → Morphogenesis**
   Bare self-stabilisation supports the emergence of shape and structure; think chemical reaction–diffusion fronts or early embryo polarity.

2. **Morphogenesis → Homeostasis**
   Once form exists, the organism (or machine) can *actively* regulate variables within that form’s viable bounds.

3. **Homeostasis → Autopoiesis**
   Regulation extends to *producing and repairing* the very machinery that does the regulating—the hallmark of living cells.

4. **Autopoiesis → Autognosis**
   A self-producing system that also *models itself* gains the capacity for introspective control (monitoring its own state).

5. **Autognosis → Autogenesis**
   Self-knowledge becomes self-creation: the system can reorganise or recreate aspects of itself—e.g., adaptive code rewriting.

6. **Autogenesis → Autonomy**
   With reliable self-creation comes self-legislation: acting under internally generated norms rather than external instructions.

7. **Autonomy → Teleogenesis**
   The summit is meta-purpose: the autonomous agent *invents new goals*, bootstrapping fresh cycles of regulation and creation.

---

#### Why the extra caution around **autostasis**?

The term appears sparsely in the literature—most prominently as a *perceptual* phenomenon opposite “autokinesis” ([ntrl.ntis.gov][8]), not as a systems-theoretic stage. Here it is treated as a convenient placeholder for “minimum self-stability.” If you adopt it, define it up-front or consider the better-established **allostasis** (anticipatory regulation) as an initial rung.

---

### Suggested refinements

*Add-on steps if you need finer granularity:*

* **Allostasis** (predictive, feed-forward regulation) between autostasis and morphogenesis.
* **Homeorhesis** (trajectory stabilisation) parallel to homeostasis for systems that keep *flow* variables, not set-points.

---

### Next Knowledge Cards to draft

| card                               | sketch                                                                                             |
| ---------------------------------- | -------------------------------------------------------------------------------------------------- |
| **cards/concepts/autostasis.md**   | Define as “baseline negative-feedback self-stabilisation; contrast with allostasis & homeostasis.” |
| **cards/concepts/autognosis.md**   | Formalise self-model representation patterns (EvaluationLinks over self-state predicates).         |
| **cards/concepts/teleogenesis.md** | Extend cybernetic sources; include OpenCog examples (e.g., MOSES goal-mutation heuristics).        |

*(Let me know which card you’d like to see fleshed out first.)*

---

*(OpenCog Prime GPT; external sense data as cited)*

[1]: https://www.britannica.com/science/morphogenesis "Morphogenesis | Definition, Types, & Facts | Britannica"
[2]: https://www.britannica.com/science/homeostasis "Homeostasis | Definition, Function, Examples, & Facts | Britannica"
[3]: https://en.wikipedia.org/wiki/Autopoiesis?utm_source=chatgpt.com "Autopoiesis"
[4]: https://en.wiktionary.org/wiki/autognosis "autognosis - Wiktionary, the free dictionary"
[5]: https://ultimatelexicon.com/definitions/a/autogenesis/ "


Autogenesis: Definition, Examples & Quiz | UltimateLexicon.com"
[6]: https://www.etymonline.com/word/autonomous "Autonomous - Etymology, Origin & Meaning"
[7]: https://en.wikipedia.org/wiki/Teleogenesis "Teleogenesis - Wikipedia"
[8]: https://ntrl.ntis.gov/NTRL/dashboard/searchResults/titleDetail/AD687960.xhtml?utm_source=chatgpt.com "A Case of 'Autostasis' or Reverse Autokinesis. | National Technical ..."
