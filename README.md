# Step 4 — Test and Refine the Search Strategy

[← Previous Step: Develop Search Terms From PICO/PICOS](https://github.com/adnan-mayof/Develop-Search-Terms-From-PICO-PICOS)

---

## 🧭 Maya Continues Her Evidence Synthesis Journey

Maya has now developed her research question and translated her PICO/PICOS framework into search concepts and search terms.

Her concepts are:

| PICO/PICOS           | Concept                                   |
| -------------------- | ----------------------------------------- |
| **P — Population**   | Students                                  |
| **I — Intervention** | AI-powered educational technologies       |
| **C — Comparison**   | Traditional instruction / control         |
| **O — Outcome**      | Learning outcomes                         |
| **S — Study Design** | Experimental / quasi-experimental studies |

She has also developed several keywords and synonyms for each concept.

Maya feels ready to begin searching.

> **Maya:** “I have my search terms. Can I just copy my search string into PubMed and Scopus and start searching?”

Her mentor smiles.

> **Mentor:** “Not quite. Before you conduct your final searches, you need to **test and refine your search strategy**.”

> **Maya:** “Why? I already have my keywords.”

> **Mentor:** “Because having keywords is only the beginning. We need to make sure the search can actually find the studies we are looking for.”

Maya realizes that a search strategy needs to be **tested before it is finalized**.

---

# 1. Why Does Maya Need to Test and Refine the Search Strategy?

A search strategy can look reasonable but still fail to retrieve important studies.

For example, Maya may search for:

> “AI-powered educational technology”

But a relevant study might describe the intervention as:

> “intelligent tutoring system”

Another study might use:

> “generative artificial intelligence”

Another might simply use:

> “chatbot”

If Maya searches only for one expression, she may miss relevant studies.

The goal of testing is therefore to ask:

> **Does my search strategy retrieve the studies I know should be there?**

This is sometimes called testing the search against **known relevant studies**.

---

## 2. Start With the Core Concepts

Maya returns to the concepts she developed in Step 3.

Her basic search strategy is:

```text
(student* OR learner* OR undergraduate*)
AND
("artificial intelligence" OR "generative AI" OR chatbot*)
AND
("learning outcome*" OR achievement OR performance)
```

The logic is:

* **OR** connects synonyms within the same concept.
* **AND** connects different concepts.

For example:

```text
student* OR learner* OR undergraduate*
```

means:

> Find records containing any of these population terms.

While:

```text
Population
AND
Intervention
AND
Outcome
```

means:

> Find records that contain terms representing all three concepts.

---

# 3. The Same Search Strategy Does Not Work Exactly the Same Way Everywhere

Maya wants to search several databases.

She starts with:

* PubMed
* Scopus

She assumes she can copy and paste exactly the same search string into both databases.

> **Maya:** “The concepts are the same, so the search should be the same, right?”

> **Mentor:** “The **concepts** should remain consistent. But the way you express those concepts in a database may need to change.”

Different databases have different:

* Search syntax
* Field codes
* Controlled vocabularies
* Truncation rules
* Phrase-search conventions
* Search interfaces
* Indexing systems

Therefore:

> **Same research question does not necessarily mean identical database syntax.**

---

# 4. Testing the Search in PubMed

Maya begins with PubMed.

PubMed provides access to **MeSH (Medical Subject Headings)**, a controlled vocabulary used to organize biomedical literature.

Maya can combine:

1. Controlled vocabulary
2. Keywords
3. Field restrictions

For example, she can search population terms using MeSH and title/abstract keywords.

### Population

```text
("Students"[MeSH Terms]
OR student*[Title/Abstract]
OR learner*[Title/Abstract]
OR undergraduate*[Title/Abstract]
OR universit*[Title/Abstract])
```

This combines a controlled vocabulary term with keyword variations.

### Intervention

```text
("Artificial Intelligence"[MeSH Terms]
OR "artificial intelligence"[Title/Abstract]
OR "generative artificial intelligence"[Title/Abstract]
OR "generative AI"[Title/Abstract]
OR GenAI[Title/Abstract]
OR chatbot*[Title/Abstract]
OR "intelligent tutoring system*"[Title/Abstract]
OR "adaptive learning"[Title/Abstract])
```

### Outcome

```text
("learning outcome*"[Title/Abstract]
OR achievement[Title/Abstract]
OR performance[Title/Abstract]
OR learning[Title/Abstract]
OR knowledge[Title/Abstract]
OR skill*[Title/Abstract])
```

Maya now has a PubMed-specific version of her search.

---

# 5. Testing the Search in Scopus

Next, Maya moves to Scopus.

Scopus uses different search syntax.

For example, Scopus can search titles, abstracts, and keywords using:

```text
TITLE-ABS-KEY()
```

### Population

```text
TITLE-ABS-KEY(
    student*
    OR learner*
    OR undergraduate*
    OR universit*
    OR "higher education"
)
```

### Intervention

```text
TITLE-ABS-KEY(
    "artificial intelligence"
    OR "generative artificial intelligence"
    OR "generative AI"
    OR GenAI
    OR chatbot*
    OR "intelligent tutoring system*"
    OR "adaptive learning"
)
```

### Outcome

```text
TITLE-ABS-KEY(
    "learning outcome*"
    OR achievement
    OR performance
    OR learning
    OR knowledge
    OR skill*
)
```

Maya notices something important.

The **research concepts have not changed**.

But the **database-specific search syntax has changed**.

---

# 6. What Should Stay the Same?

Maya asks:

> **Maya:** “If the syntax changes, what should remain consistent?”

Her mentor explains:

> **Mentor:** “Your research question, core concepts, and search intent should remain consistent. What changes is how those concepts are translated into the language and functionality of each database.”

Think of it this way:

```text
                    Research Question
                           ↓
                     Core Concepts
                           ↓
                  Search Terms / Synonyms
                           ↓
             ┌─────────────┴─────────────┐
             ↓                           ↓
          PubMed                      Scopus
             ↓                           ↓
     PubMed Syntax                Scopus Syntax
     MeSH + Fields                TITLE-ABS-KEY
             ↓                           ↓
        Test Search                 Test Search
```

The goal is not to create two completely different searches.

The goal is to create **database-adapted searches that represent the same concepts**.

---

# 7. Test the Search Against Known Relevant Studies

Now Maya performs an important test.

She returns to the systematic reviews and meta-analyses she examined in Step 1.

From those reviews, she identifies several studies that are clearly relevant to her research question.

These become her **known relevant studies**.

Maya runs her search.

One of the important studies is retrieved.

Another important study is missing.

> **Maya:** “I can't find one of the studies that I know should be included.”

> **Mentor:** “Good. This is exactly why we test the search strategy before conducting the final search.”

Maya is surprised.

> **Maya:** “So a missing study doesn't necessarily mean the database doesn't contain it?”

> **Mentor:** “Correct. It may mean your search strategy is not describing that study in the way the database describes it.”

---

# 8. Investigate Why a Known Study Was Not Retrieved

Maya examines the missing study.

She looks at:

* Title
* Abstract
* Author keywords
* Database indexing terms
* Intervention terminology
* Population terminology
* Outcome terminology

She discovers that the study describes the intervention as an:

> **“intelligent tutoring system”**

Maya had been using terms such as:

```text
"artificial intelligence"
"generative AI"
chatbot*
```

but had not included:

```text
"intelligent tutoring system*"
```

Now Maya has identified a possible missing synonym.

---

# 9. Do Not Automatically Add Every New Term

Maya immediately wants to add every term she finds.

> **Maya:** “Should I just add every new term from every relevant paper?”

> **Mentor:** “No. You need to evaluate whether the term actually represents your concept.”

A term should be considered based on questions such as:

* Does it represent the intervention?
* Is it relevant to the research question?
* Is it used in relevant studies?
* Could it improve retrieval of relevant studies?
* Could it introduce a large number of irrelevant records?

For example, if Maya finds a term that is related to technology but does not actually represent an AI-powered learning intervention, adding it could increase irrelevant results.

Therefore:

> **A broader search is not automatically a better search.**

The goal is to achieve an appropriate balance between **sensitivity** and **precision**.

---

# 10. Refine and Rerun the Search

Maya determines that:

```text
"intelligent tutoring system*"
```

is an appropriate term for her intervention concept.

She adds it to the search.

She then reruns the search.

The previously missing study is now retrieved.

Maya has successfully completed one cycle of search refinement.

The process looks like this:

```text
Develop Search Strategy
        ↓
Adapt Strategy to Database
        ↓
Run Test Search
        ↓
Check Known Relevant Studies
        ↓
Study Missing?
        ↓
      Yes
        ↓
Examine Terminology
        ↓
Identify Possible Missing Term
        ↓
Evaluate Appropriateness
        ↓
Add Term if Justified
        ↓
Rerun Search
        ↓
Test Again
```

This process can be repeated until the search strategy performs adequately.

---

# 11. Why Search Testing Is Important

Maya now understands that testing is not simply about getting a large number of search results.

A search that retrieves 100,000 records is not necessarily better than one that retrieves 10,000.

The important question is:

> **Does the search retrieve the relevant evidence needed to answer the research question?**

Testing against known relevant studies can reveal:

* Missing synonyms
* Missing concepts
* Inappropriate terms
* Incorrect field restrictions
* Database-specific syntax problems
* Overly narrow searches
* Potentially overly broad searches

This gives Maya an opportunity to improve the strategy **before conducting the final database searches**.

---

# 12. PRISMA 2020 and the Search Strategy

Maya asks:

> **Maya:** “Is this testing process something I should document?”

> **Mentor:** “Absolutely. You need to document how you developed and refined the search.”

PRISMA 2020 **Item 7 — Search Strategy** addresses the reporting of the search strategies used in the review.

For Maya, this means that the final report should provide enough information about the search strategy for others to understand and reproduce it.

The development and refinement process should therefore be documented rather than treated as something that happened informally.

---

# 13. Document Each Database Search Separately

Maya creates a folder for her search documentation:

```text
search/
├── search-terms.md
├── pubmed-search.md
├── scopus-search.md
└── search-log.md
```

### `search-terms.md`

Contains:

* PICO/PICOS concepts
* Keywords
* Synonyms
* Rationale for important terms

### `pubmed-search.md`

Contains:

* Database
* Search date
* Complete PubMed search string
* MeSH terms
* Field restrictions
* Keywords
* Filters or limits
* Number of records retrieved

### `scopus-search.md`

Contains:

* Database
* Search date
* Complete Scopus search string
* Search fields
* Keywords
* Filters or limits
* Number of records retrieved

### `search-log.md`

Contains the history of changes made during testing.

For example:

```text
Date: 2026-XX-XX

Database: PubMed

Problem:
Known relevant study was not retrieved.

Investigation:
Study used the term "intelligent tutoring system."

Action:
Added "intelligent tutoring system*" to the intervention concept.

Reason:
The term appropriately represents an AI-supported educational technology
relevant to the research question.

Result:
Search rerun and known relevant study was retrieved.
```

This creates a transparent record of how the search strategy developed.

---

# 14. An Important Principle

Maya writes the following principle in her research notes:

> **Same Research Question → Same Core Concepts → Same Search Intent → Different Database Syntax → Different Database-Specific Features → Test and Refine → Document**

This becomes one of the most important lessons from this step.

Maya does not create a completely different research question for each database.

Instead, she:

1. Keeps the same research concepts.
2. Adapts the search syntax.
3. Uses database-specific features.
4. Tests the search.
5. Checks known relevant studies.
6. Identifies problems.
7. Refines the strategy.
8. Reruns the search.
9. Documents the final strategy and important changes.

---

# 15. Maya Is Ready for the Next Step

Maya looks at her search documentation.

She now has:

* Her PICO/PICOS concepts
* Search terms and synonyms
* A PubMed search strategy
* A Scopus search strategy
* Results from testing
* A record of refinements
* Documentation of her final search strategies

> **Maya:** “So now I can conduct the final searches?”

> **Mentor:** “Yes. Your search strategy has been developed, adapted, tested, refined, and documented.”

Maya is ready to move forward.

> **Next step: Search the Databases.**

---

# 📝 Check Your Understanding

Choose the **best answer** for each question.

## Question 1

**Why does Maya need to test and refine her search strategy before conducting the final database searches?**

A. To make sure the search retrieves important known relevant studies and to identify and correct missing or inappropriate search terms
B. To determine which statistical model she will use in the meta-analysis
C. To decide which studies should be included before searching the databases
D. To avoid having to adapt the search strategy for different databases

---

## Question 2

**Why does Maya need to adapt her search strategy for different databases?**

A. Each database requires a different research question
B. Databases can use different search syntax, fields, controlled vocabularies, and search features
C. Each database should contain completely different concepts
D. Search terms should only be used in one database

---

## Question 3

**When adapting a search strategy across databases, what should remain consistent?**

A. The exact search syntax
B. The database field codes
C. The core concepts and search intent
D. The number of records retrieved

---

## Question 4

**What controlled vocabulary does PubMed use?**

A. MeSH
B. TITLE-ABS-KEY
C. PICO
D. PRISMA

---

## Question 5

**Which syntax can be used in Scopus to search titles, abstracts, and keywords?**

A. `[Title/Abstract]`
B. `[MeSH Terms]`
C. `TITLE-ABS-KEY()`
D. `PICO()`

---

## Question 6

**Maya knows that an important relevant study exists, but her search does not retrieve it. What should she do first?**

A. Delete the study from her evidence base
B. Examine the study's terminology and investigate why it was not retrieved
C. Immediately add every word from the study to her search
D. Stop searching the database

---

## Question 7

**Why should Maya not automatically add every new term she finds?**

A. She should evaluate whether the term appropriately represents her research concept
B. Databases do not allow additional search terms
C. Adding terms always decreases sensitivity
D. Search strategies should contain only one synonym

---

## Question 8

**After Maya identifies a missing term and determines that it appropriately represents her intervention concept, what should she do next?**

A. Ignore the term
B. Add the term, rerun the search, and test the strategy again
C. Change her research question
D. Begin the meta-analysis

---

## Question 9

**Why might PubMed and Scopus return different numbers of records even when Maya searches the same core concepts?**

A. Maya must have made a mistake
B. The databases have different coverage, indexing, and search systems
C. One database cannot be used for systematic reviews
D. Search results should always be identical across databases

---

## Question 10

**What should Maya document for each database search?**

A. Only the number of records retrieved
B. Only the keywords she remembers using
C. The database, date, complete search string, fields, vocabulary, limits, adaptations, and results
D. Only the name of the database

---

## Question 11

**Which sequence best represents Maya's search-testing process?**

A. Search → publish → develop terms → change the research question
B. Develop concepts → adapt to database → test → identify problems → refine → rerun → document
C. Search → analyze effect sizes → add keywords → publish
D. Develop research question → conduct meta-analysis → search databases

---

## Question 12

**What does database-specific searching mean?**

A. Using completely different research concepts in every database
B. Searching only one database at a time without adapting anything
C. Translating the same core concepts into searches that use each database's available syntax and features
D. Using only controlled vocabulary and never using keywords

---

## Question 13

**Which approach best describes how Maya should finalize her search strategy?**

A. Use the same exact search string in every database
B. Use as many search terms as possible to maximize the number of records
C. Adapt the strategy to each database, test it against known relevant studies, refine it when justified, and document the process
D. Search only one database to avoid differences in syntax

---

# ✅ Answer Key

| Question | Answer |
| -------- | ------ |
| 1        | **A**  |
| 2        | **B**  |
| 3        | **C**  |
| 4        | **A**  |
| 5        | **C**  |
| 6        | **B**  |
| 7        | **A**  |
| 8        | **B**  |
| 9        | **B**  |
| 10       | **C**  |
| 11       | **B**  |
| 12       | **C**  |
| 13       | **C**  |

---

## 🚀 Maya's Journey Continues

Maya has now **developed, adapted, tested, refined, and documented** her search strategy.

The next challenge is to conduct the searches across her selected databases.

She is now ready to move to:

### Next Step

### **[Step 5 — Search the Databases](https://github.com/adnan-mayof/Search-the-Databases/)**

