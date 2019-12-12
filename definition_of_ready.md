# The Definition of Ready

_The DoR avoids beginning work on features that do not have clearly defined completion criteria, which usually translates into costly back-and-forth discussion and rework. The DoR provides the team with an explicit agreement allowing it to “push back” on accepting ill-defined features to work on._

For each User Story (US) the following are mandatory requirements:

- The US must be documented / captured on the board / in JIRA, as a single source of truth
- The US format must capture what is required to be achieved from a business perspective. Examples:
  - As a `<user role>` I should be able to `<feature>` so that `<purpose, context>`.
  - `<Who I am>` `<What I require / would like>` `<Why I would like this feature / functionality>`.
  - The business vision on how the product is going to be used in an ideal world.
- Acceptance Criteria must be clearly defined and testable:
  - AC1, AC2, AC3 _etc_. 
- Each US should be prioritised according to the __MoSCoW__* criteria, and with a value assigned to it.
- Each US should meet the __INVEST__** criteria.
- Each US must be estimated and should be development and test complete within a two week sprint (or < 1 sprint). If it is > 1 sprint the US should be broken down into subsets of the report. By building functionality for multiple sub-reports these can lead into larger reports.
- Access to a __Subject Matter Expert__ (SME) should be made available throughout the development, to answer questions and make decisions. SMEs are empowered to guide the development team and accept work done by the development team.
- If more than one part of the business is involved (_e.g._ the functionality of two systems is being combined) there should be agreement between the business units on the content of each US prior to progressing to the development stage.
- The final, deliverable output of a US should be a report. It is useful to have reports sketched out, to see what each looks like. Attach a rough sketch of the relevant report(s) in Excel with column and row headings / sub-headings, with any default filters, table mappings or references also included where possible.
- Existing sample data which will help developers validate output during development should be made available up front. If none exists, the development team may require help from the SME in creating some.
- Data error margins and tolerances used for testing the output data should be agreed prior to progressing to the development stage.
- Any source code from existing systems which helps understand how the product currently works (if required / available) will be required up front; this should be clearly documented.
- Any existing business rules which are applied to data in existing systems are required up front; these should be clearly documented.
- Any existing lookup tables which are applied to data in existing systems are required up front; these should be clearly documented.
- Any existing data models, including source data table definitions and table join definitions, are required up front; these should be clearly documented.

 * https://en.wikipedia.org/wiki/MoSCow_method
** https://en.wikipedia.org/wiki/INVEST_(mnemonic)